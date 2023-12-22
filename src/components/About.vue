<script setup>

</script>


<template>
    <section>
        <h1>Hello , i'm <br> Adetunji Adetayo </h1>
        <div>
            <p>I'm a software engineer focused on solving problems using frontend technology. I am interested in user experience, accessibility, design engineering, gaming, web3, web animations, cloud engineering and golang.</p>
        </div>
        <div class="links">
            <ul>
                <li><a href="">00 . PROJECTS </a></li>
                <li><a href="">01 . ARTICLES </a></li>
                <li><a href="">02 . RESUME </a></li>
            </ul>
        </div>
        <div class="quick-links">
            <ul>
                <li><a href="">Github </a></li>
                <li><a href="">Twitter </a></li>
                <li><a href="">Linkdin </a></li>
                <li><a href=""> Email </a></li>
            </ul>
        </div>


    </section>
</template>



<style  scoped>

a{
    text-decoration: none;
    color: black;
}

section{
    width: 50%;
    height: 80vh;
}

h1{
    font-family: 'Montserrat', sans-serif;
  font-size: 2.5rem;
  margin-bottom: .5em;
}
p{
    font-family: 'Montserrat', sans-serif;
  font-size: 14px;
  letter-spacing: .7px;
}

.links{
    margin-top: 2em;
    line-height: 4em;
}

.links li a, .quick-links li a{
    font-size: 14px;
    font-weight: 500;
    font-family: 'Montserrat', sans-serif;;
}

.quick-links{
    width: 50%;
  
    margin-top: 2em;
}
.quick-links ul{
    display: flex;
    justify-content: space-between;
    
    

}
</style> 