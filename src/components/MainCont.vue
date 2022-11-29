<template>

    <div class="main-container">
     
        <aside class="aside-main">
            <div class="left-side">
                    <p id="hi">
                        He11o !! I'm
                    </p>
                    <p id="rafael">
                        Rafael Henrique
                    </p>
                    <p id="full"> 
                        Full-Stack Developer
                    </p>
                <section class="section-main">
                    <div class="btn-group btn-group-lg" role="group" aria-label="Large button group" >
                        <a type="button" class="btn btn-outline-light" href="https://www.linkedin.com/in/rafael-henrique-b84b15110/" target="_blank">GitHub</a>
                        <a type="button" class="btn btn-outline-light" href="https://www.linkedin.com/in/rafael-henrique-b84b15110/" target="_blank">Linkedin</a>
                    </div>
                </section>
            </div>
        </aside>
        <div class="right-side">
            <img src="../assets/Code typing-pana.png">
        </div>
    </div>


</template>

<script>

import '../styles/components/maincont.sass'

export default {
    name: "MainCont"
}
</script>

<style scoped>




img {
    width: 70%;
}


</style>