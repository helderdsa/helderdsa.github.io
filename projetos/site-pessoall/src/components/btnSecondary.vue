<template>
    <button class="btn">{{btnText}}</button>
</template>
<script>
export default {
    props:['btnText']
}
</script>
<style scoped>
.btn{
    margin: 8px;
    text-transform: uppercase;
    background-color: #150941;
    border-radius: 32px;
    padding: 8px 16px 8px 16px;
    border: none;
    color: #F80040;
    font-weight: bold;
    font-size: 16px;
    box-shadow: 0 0 16px #F80040;
    transition: all 0.3s ease-in-out;
}
.btn:hover{
    box-shadow: 0 0 32px #F80040;
}
</style>