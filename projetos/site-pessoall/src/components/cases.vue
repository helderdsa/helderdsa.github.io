<template>
  <div class="cases">
    <div class="items">
      <div>
        <img :src="caseimg" alt="" class="item" />
      </div>
      <div>
        <img :src="caseimg" alt="" class="item" />
      </div>
      <div>
        <img :src="caseimg" alt="" class="item" />
      </div>
      <div>
        <img :src="caseimg" alt="" class="item" />
      </div>
      <div>
        <img :src="caseimg" alt="" class="item" />
      </div>
    </div>
    <div class="descricaoCase">
      <p>
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis pharetra
        tristique diam hendrerit sollicitudin. Cras fringilla non sem rhoncus
        tincidunt. Curabitur mollis ultricies erat ac gravida. Suspendisse
        laoreet consectetur odio, sit amet ullamcorper arcu egestas id.
        Curabitur id nunc non lacus iaculis rutrum in ut lacus. Donec ante orci,
        fringilla eu arcu et, suscipit vestibulum ipsum. Duis vitae icitudin mi.
        In a erat tellus. Pellentesque vitae sollicitudin orci. Proin ac varius
        nisi. In a orci ultricies, interdum leo vitae, sodales urna. Sed
        tristique mi massa, vitae hendrerit nisi hendrerit et. Class aptent
        taciti sociosqu ad litora torquent per conubia nostra, per inceptos
        himenaeos. Donec egestas rhoncus lectus tempus facilisis. Cras facilisis
        et neque et euismod. Integer in mattis nulla, nec pellentesque mauris.
      </p>
      <btnSecondary btnText="Primário" />
    </div>
  </div>
</template>
<script>
import cases from "../../public/fotos/case.jpg";
import btnSecondary from '@/components/btnSecondary.vue'

export default {
  data() {
    return {
      caseimg: cases,
    };
  },
  components: {
    btnSecondary,
  },
};
</script>
<style scoped>
.cases {
  background-color: #f80040;
  display: flex;
  justify-content: center;
  height: 600px;
}
.item {
  height: 180px;
  width: 360px;
  margin: 20px;
  box-shadow: -15px 15px 16px #1509419f;
}
.items{
    width: 500px;
    overflow: hidden;
    transform: skew(15deg);
}
.descricaoCase{
  width: 500px;
  text-align: justify;
  padding-top: 100px;
}
</style>