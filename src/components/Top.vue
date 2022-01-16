<template>
    <section class="hero">
        <section class="container">
            <div class="title" style="font-size:1vw">The Wedding of</div>
            <div class="name">Teguh & Shelvy</div>
            <div>Minggu, 07 November 2021</div>
            <br/>
            <br/>
            <div class="div">Kepada Yth:</div>
            <h1>Ratbi</h1>
        </section>
    </section>
</template>
<script>

export default {
    name: 'Top',
    data: () => ({

    })
    
}
</script>

<style scoped>
.hero {
    background: url('../assets/bg-top-web.jpg') no-repeat center center;
    -webkit-background-size: cover;
    -moz-background-size: cover;
    -o-background-size: cover;
    background-size: cover;
    display: table;
    width: 100%;
}
.blur {
  -webkit-filter: blur(2px);
  -moz-filter: blur(2px);
  -o-filter: blur(2px);
  -ms-filter: blur(2px);
  filter: blur(2px);
}
.centered {
    position: absolute;
    top: 30%;
    left: 43%;
    transform: translate(-50%, - 50%);
}
.hero .container {
    display: table-cell;
    text-align: center;
    vertical-align: middle;
    height: 700px
}
.hero .container .title {
    size: 6rem;
}
.hero .container .name {
    font-size: xx-large;
    font-weight: 600;
    line-height: 1em;
}
</style>