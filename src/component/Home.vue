<template>
    <div>
        <Vtopbar></Vtopbar>
         <div class="activeimg">
             <img src="../../static/temp/activeimg.png"/>
         </div>
        <Vhomecontent></Vhomecontent>
    </div>
</template>

<script type="text/ecmascript-6">
    import Vtopbar from "./TopBar.vue"
    import Vhomecontent from "./HomeContent.vue"
    export default {
        name:"home",
        components:{Vtopbar:Vtopbar,Vhomecontent:Vhomecontent},
        data () {
            return {}
        },
        methods:{}
    }
</script>
<style>

</style>
