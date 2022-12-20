<template>
    <div>
        <!------main image showcase-->
        <div class="h-screen mx-8 rounded-2xl bg-no-repeat bg-center bg-cover " :style="{ 'background-image': `url(${require('@/static/images/Frame.png')})` }"> 
            <div class="pl-32 pt-44 relative">
                <div>
                    <h1 class="leading-relaxed text-white text-6xl font-extrabold w-2/4 absolute "> Modern Urban Apartment with
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
        <div> 

            
        </div>
        <!----------------------main three steps section-->


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