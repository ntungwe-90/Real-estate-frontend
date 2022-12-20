<template>
    <div>
        <!------main image showcase-->
        <div class="h-screen mx-8 rounded-2xl bg-no-repeat bg-center bg-cover " :style="{ 'background-image': `url(${require('@/static/images/Frame.png')})` }"> 
            <div class="pl-32 pt-44 ">
                <div>
                    <h1 class="leading-relaxed text-white text-6xl font-extrabold w-2/4"> Modern Urban Apartment with
                        <span class="text-red-600"> Modern</span>
                
                        Amenities
                    </h1>
                </div>
                <div> 
                    <img src="images/hero-shape-2.png.png" />
                </div>
                
                <div class="w-1/3 text-gray-50 text-sm leading-7 text-justify">
                    <p> Congue nisi, pretium in suspendisse. Enim accumsan ad, ligula pulvinar cursus porttitor 
                        augue,venenatis rhoncus, amet inceptos venenatis </p>
                </div>


                <div> 
                    <p class="py-4 w-36 bg-red-600 text-white text-center rounded text-base mt-8"> Learn More</p>
                </div>



            </div>
            

        </div>

        <!----------------------main three steps section-->
        <div class="flex justify-center mt-36"> 
            <h1 class="font-extrabold text-4xl text-neutral-900">3 Steps To Book Your Home</h1>   
        </div>
        <div class="flex justify-center" > 
            <p class="text-gray-500 w-2/5 pt-4 leading-8 text-sm">Congue nisi, pretium in suspendisse. Enim accumsan ad, ligula pulvinar cursus porttitorCongue nisi, pretium in suspendisse. Enim accumsan ad, ligula pulvinar cursus porttito </p>
        </div>

        <div class=" flex justify-between mx-20"> 
            <div> 
                <div> 
                    <img src="images/Pin Location.png" />

                </div>
                <div>
                    <h1 class="font-extrabold text-xl text-neutral-700"> Pick a Home</h1> 
                    <p class="w-2/4 text-sm"> Select A Location That Is Preferred by You</p>

                </div>
           
            </div>
            <div> 
                <div> 
                    <img src="images/Home.png" />

                </div>
                <div>
                    <h1 class="font-extrabold text-xl text-neutral-700"> Confirm your book</h1> 
                    <p class="w-2/4 text-sm"> Select A Location That Is Preferred by You</p>

                </div>
           
            </div>
            <div> 
                <div> 
                    <img src="images/Frame 82.png" />

                </div>
                <div>
                    <h1 class="font-extrabold text-xl text-neutral-700"> Choose a location</h1> 
                    <p class="w-2/4 text-sm"> Select A Location That Is Preferred by You</p>

                </div>
           
            </div>
        </div>
        <!----------------------main three steps section-->

        <!----------------------main image and card section-->
        
        <!----------------------main image and card section-->
    


    </div>
</template>

<script>
export default {
    name: "HomePage",
    layout: "main"

};
</script>

<style>
body {
    font-family: 'Poppins', sans-serif;
}
</style>