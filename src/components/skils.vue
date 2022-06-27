<template>
    <div class="skill">
        <div>
            <div class="imgsk">
                <img src="@/assets/logo.png" alt="">
            </div>
            <h6>Vue.JS</h6>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aliquam vitae sem non nibh fringilla maximus porttitor sagittis est. Suspendisse accumsan ex eget lobortis consectetur. Morbi eget nunc elementum, eleifend lacus vitae</p>
            <div class="bar"></div>
        </div>
    </div>
</template>
<script>
import btnPrimary from '@/components/btnPrimary.vue'

export default {
      components: {
          btnPrimary
      }
}
</script>
<style scoped>
.skill{
    width: 360px;
    display: flex;
    justify-content: left;
    margin: 40px 16px;
    border-radius: 16px;
    background-color: #F80040;
    box-shadow: 0 0 0px #F80040;
    padding: 12px 8px 0px 8px;
    transition: all 0.3s ease-in-out;
}
.skill:hover{
    box-shadow: 0 0 32px #F80040;
}
.imgsk{
    margin-top:-52px;
    margin-left: 32px;
    width: 40px;
    height: 40px;
    display: flex;
    background-color: #150941;
    padding: 16px;
    border-radius: 50px;
    box-shadow: 0 0 0px #F80040;
    transition: all 0.3s ease-in-out;
    }
.skill:hover .imgsk{
    box-shadow: 0 0 32px #F80040;
    width: 50px;
    height: 50px;
    margin-top:-52px;
    margin-bottom: -10px;
    margin-left: 27px;

}
.bar{
    background-color: #150941;
    height: 0px;
    width: 80px;
    margin-left: 27px;
    border-radius: 16px 16px 0px 0px;
    margin-top: 16px;
    transition: all 0.2s ease-in-out;
}
.skill:hover .bar{
    height: 10px;
    margin-top: 6px;
}
h6{
    font-size: 21px;
    margin: 4px 0px 0px 0px;
}
p{
    margin: 4px 0px 0px 0px;
    text-align: left;
    padding: 0px 12px;
    
}
</style>