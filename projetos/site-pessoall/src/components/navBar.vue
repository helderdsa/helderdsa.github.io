<template>
    <div class="nav">
        <a href="">Quem sou eu</a>
        <a href="">cases</a>
        <a href="">skills</a>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.nav{
    background-color: #150941;
    display: flex;
    justify-content: right;
    padding: 16px 24px;
    box-shadow: 0 0 16px #150941;
    position: fixed;
    width: 100%;
    top: 0;
    right: 0;
}
a{
    margin-left: 16px;
    text-decoration: none;
    transition: all 0.3s ease-in-out;
    font-weight: bold;
    text-transform: uppercase;
}
a:link {
    color: #F80040;
}

/* visited link */
a:visited {
    color: #F80040;
}

/* mouse over link */
a:hover {
  color: #F80040;
  box-shadow: 0 16px 8px -6px #F80040;
}

/* selected link */
a:active {
  color: #F80040;
  box-shadow: 0 16px 8px -6px #F80040;
}
</style>