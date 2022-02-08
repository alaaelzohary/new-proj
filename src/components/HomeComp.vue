<template>
<section class="Slider position-relative">
    <div class="caption position-absolute top-50 start-50 translate-middle">
    <h4>Design / Development / Photography</h4>
    <h1> CREATIVITY HAVE MEN LEVEL</h1>
    <a class="btn career me-4">Preview</a>
    <a class="btn career">Get Theme</a>
    </div>
    </section>  
</template>


<style>
.Slider{
    background: url("../assets/imgs/header.jpg");
    background-size: cover;
    background-color: var(--second-color);
    background-blend-mode: multiply;
    color: var(--white);
    height: 85vh;
}
.Slider .caption .career{
    color: var(--white);
    font-size: bold;
    font-size: calc(var(--default-font-size) + 2px );
    border: 1px solid var(--white);
}
.Slider .caption .career:hover{
    background-color: var(--mainColor);
    border: 1px solid var(--mainColor);
}


</style>


<script>

export default{
name:"Slider"        
}
</script>
