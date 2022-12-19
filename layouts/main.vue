<template>
    <div>
        <div>
           
            <RealHeader />

        </div>
        
       

        <div>      
        <Nuxt />
        </div>
        <hr>

            
        <div>
            <RealFooter />
        </div>
    </div>

</template>

<script>
import RealHeader from '~/components/RealHeader.vue';
import RealFooter from '~/components/RealFooter.vue';

export default {
    name: 'MainLayout',
    components: {
    RealHeader,
    RealFooter
}

}
</script>

<style>

</style>
