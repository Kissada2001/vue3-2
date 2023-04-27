<template>
    <div>{{ message }}</div>
    <PersonData></PersonData>
</template>

<script>
import PersonData from './PersonData.vue'
export default {
    name:"ListData",
    components:{
        PersonData
    },
    data(){
        return{
            message:"แสดงรายชื่อพนักงานทุกคน"
        }
    }
}
</script>

<style>

</style>