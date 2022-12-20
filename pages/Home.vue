<template>
    <div>
        <!------main image showcase-->
        <div class="h-screen mx-8 rounded-2xl bg-no-repeat bg-center bg-cover " :style="{ 'background-image': `url(${require('@/static/images/Frame.png')})` }"> 
            <div class="pl-32 pt-40">
                <div>
                    <h1 class="font-mono text-white text-4xl font-extrabold w-1/4"> Modern Urban Apartment with
                        <span> Modern</span>
                
                        Amenities
                    </h1>
                </div>
                <div> 
                    <img src="images/hero-shape-2.png.png" />
                </div>
                
                <div class="w-2/4 text-white">
                    <p> Congue nisi, pretium in suspendisse. Enim accumsan ad, ligula pulvinar cursus porttitor nostra. Dictum ipsum
                        augue,venenatis rhoncus, amet inceptos dolor
                        venenatis rhoncus, amet inceptos dolor</p>
                </div>


                <div> 
                    <p class="py-4 w-36 bg-red-600 text-white text-center rounded text-xs"> Learn More</p>
                </div>



            </div>
            

        </div>

        <!----------------------main three steps section-->
        <div> 
            
        </div>
        <!----------------------main three steps section-->
  <div class="text-center "> 
    <!-- our main cities -->
    <h1 class="text-center text-4xl font-bold">Our Hottest Nearby Cities</h1>
       <p class=" text-center"> cum quos eveniet, corrupti architecto error repellat porro veritatis hic aspernatur debitis,</P>
        <p >Lorem ipsum dolor, sit amet consectetur adipisicing elit.</P>
        <P> Autem mollitia consequatur debitis fugiat quia! Laudantium,</P> 
       <p>illo iure voluptate?</p>

  </div>
  <section
		class="w-full h-screen flex justify-center items-center bg-gradient-to-r from-purple-400 via-pink-500 to-red-500"
	>
		<article class="w-full h-screen">
			<div
				id="flippable-carousel-title"
				class="absolute left-1/2 transform -translate-x-1/2 top-28"
			>
				<div class="text-3xl lg:text-7xl neon-title whitespace-nowrap">Flippable Card Carousel</div>
			</div>
			<div
				v-if="flippableCardInfos && flippableCardInfos.length"
				id="flippable-carousel"
				ref="flippableCarousel"
				class="w-full h-screen flex items-center"
			>
				<!-- SECTION cards -->
				<div
					id="flippable-carousel-flip"
					class="w-full absolute overflow-hidden flex items-center mt-24"
				>
					<FlippableCard
						v-for="(card, cardIndex) in flippableCardInfos"
						:key="cardIndex"
						:card="card"
						:cardIndex="cardIndex"
						:slideToSelectedCard="slideToSelectedCard"
					/>
				</div>

				<!-- SECTION navigation -->
				<div
					id="flippable-carousel-navigator"
					class="absolute left-1/2 transform -translate-x-1/2 z-50 flex items-center h-card-mobile lg:h-card-web mt-24"
					v-touch:swipe.lefe="($e) => slideToSelectedCard($e, 'NEXT')"
					v-touch:swipe.right="($e) => slideToSelectedCard($e, 'PREV')"
				>
					<div :class="`w-full justify-between ${isSliding ? 'hidden' : 'flex'}`">
						<button @click="($e) => slideToSelectedCard($e, 'PREV')" class="w-6 transform">
							<font-awesome-icon icon="fa-solid fa-chevron-left" size="2x" color="#fff" beat />
						</button>
						<button @click="($e) => slideToSelectedCard($e, 'NEXT')" class="w-6">
							<font-awesome-icon icon="fa-solid fa-chevron-right" size="2x" color="#fff" beat />
						</button>
					</div>
					<div
						id="flippable-carousel-navigator-fakeface"
						class="absolute left-1/2 transform -translate-x-1/2 w-card-mobile h-card-mobile lg:w-card-web lg:h-card-web"
						@mouseenter.prevent="() => flipCardHandler('ENTER')"
						@mouseleave.prevent="() => flipCardHandler('LEAVE')"
						v-touch:tap="() => flipCardHandler('ENTER')"
						v-touch:end="() => flipCardHandler('LEAVE')"
					></div>
				</div>
			</div>
		</article>
	</section>

    </div>
</template>

<script>
// 

</script>

<style>

</style>