<template>
  <div class="quemSou">
    <img :src="eu" alt="" class="heroImg" />
    <div class="texto">
      <h3 class="cta">
        OLÁ!!
        <br />
        HELDER DANIEL AQUI
      </h3>
      <h5 class="ctaSec">UX DESIGNER E DEV FRONT-END</h5>
      <btnPrimary btnText="fale comigo" 
      style="
      font-size: 28px;
      border-radius: 50px;
      padding: 16px 24px;
      "/>
    </div>
  </div>
</template>
<script>
import image from "../../public/fotos/ftsite.png";
import btnPrimary from '@/components/btnPrimary.vue'
export default {
  data() {
    return {
      eu: image,
    };
  },
  components: {
    btnPrimary,   
  }
};
</script>
<style scoped>
.quemSou {
  margin-top: 50px;
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  text-align: left;
}
.texto {
  padding-top: 90px;
}
.heroImg {
  height: 500px;
  width: 500px;
}
.cta {
  margin-bottom: 0px;
}
.ctaSec {
  margin-top: 0px;
  margin-bottom: 16px;
}
</style>