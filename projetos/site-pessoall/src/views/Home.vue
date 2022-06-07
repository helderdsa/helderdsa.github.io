<template>
  <div class="home">
    <navbar/>
    <quemsou/>
    <cases/>
    <div  class="skillsection">
      <skills/>
      <skills/>
      <skills/>
      <skills/>
      <skills/>
      <skills/>
    </div>
    <btnPrimary btnText="Primário"/>
    <btnSecondary btnText="Secundário"/>
  </div>
</template>

<script>
// @ is an alias to /src
import btnPrimary from '@/components/btnPrimary.vue'
import btnSecondary from '@/components/btnSecondary.vue'
import skills from '@/components/skils.vue'
import navbar from '@/components/navBar.vue'
import quemsou from '@/components/quemSou.vue'
import cases from '@/components/cases.vue'
export default {
  name: 'Home',
  components: {
    btnPrimary,
    btnSecondary,
    skills,
    navbar,
    quemsou,
    cases
  }
}
</script>
<style scoped>
.home{
  background-color: #150941;
  overflow-x:hidden;
}
.skillsection{
  display: flex;
  justify-content: center;
  margin-top: 50px;
  flex-wrap: wrap;
  padding-top: 50px;
}
</style>
