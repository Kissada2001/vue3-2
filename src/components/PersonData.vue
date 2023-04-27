<template>
    <div>{{ message }}</div>
</template>

<script>
export default {
    name: "PersonData",
    data(){
        return{
            message:"ข้อมูลพนักงาน"

        }
    }
}
</script>

<style scoped>
    div{
        color: rgb(240, 6, 6);
    }
</style>