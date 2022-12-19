<template>
    <div>
        <div>
           
            <Navbar />

        </div>
        
       

        <div>      
        <Nuxt />
        </div>
        <hr>

            
        <div>
            <Footer />
        </div>
    </div>

</template>

<script>
import RealHeader from '~/components/RealHeader.vue';
import Footer from '~/components/Footer.vue';

export default {
    name: 'MainLayout',
    components: {
        RealHeader,
    Footer
}

}
</script>

<style>

</style>
