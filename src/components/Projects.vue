<script setup>

</script>

<template>
     
    
    <section>
        <p> ~/ PROJECTS</p>
        <div class="projects">
            <!-- project 1 -->
            <div class="project-container">
                <div class="project-title">
                    <h3>Expense Tracker</h3>
                    <p class="project-stack">VueJs, Tailwind, TS, Vue-Icon</p>

                    <p class="project-details">Expense Tracker App</p>
                    <div class="flex">
                        <a href="">Visit Site</a>
                        <a href="">Github</a>
                    </div>
                </div>
            </div>
            <div class="project-container">
                <div class="project-title">
                    <h3>Expense Tracker</h3>
                    <p class="project-stack">VueJs, Tailwind, TS, Vue-Icon</p>

                    <p class="project-details">Expense Tracker App</p>
                    <div class="flex">
                        <a href="">Visit Site</a>
                        <a href="">Github</a>
                    </div>
                </div>
            </div>
            <div class="project-container">
                <div class="project-title">
                    <h3>Expense Tracker</h3>
                    <p class="project-stack">VueJs, Tailwind, TS, Vue-Icon</p>

                    <p class="project-details">Expense Tracker App</p>
                    <div class="flex">
                        <a href="">Visit Site</a>
                        <a href="">Github</a>
                    </div>
                </div>
            </div>
            <div class="project-container">
                <div class="project-title">
                    <h2>Expense Tracker</h2>
                    <p class="project-stack">VueJs, Tailwind, TS, Vue-Icon</p>

                    <p class="project-details">Expense Tracker App</p>
                    <div class="flex">
                        <a href="">Visit Site</a>
                        <a href="">Github</a>
                    </div>
                </div>
            </div>
            <div class="project-container">
                <div class="project-title">
                    <h3>Expense Tracker</h3>
                    <p class="project-stack">VueJs, Tailwind, TS, Vue-Icon</p>

                    <p class="project-details">Expense Tracker App</p>
                    <div class="flex">
                        <a href="">Visit Site</a>
                        <a href="">Github</a>
                    </div>
                </div>
            </div>
            
        </div>
    </section>
 
</template>

<style scoped>

p{
    padding: 0;
    margin: 0;
}

a{
    text-decoration: none;
    color: #fff;
    font-size: 12px;
}

section{
    width: 50%;
    margin: auto;
}

p{
    padding: 1em;
    font-weight: bold;
    font-size: 12px;
}
.projects{
    color: #fff;
    
    /* background-color: black; */
    height: 100vh;
    
    padding: 3em;

    
    
    overflow-y: scroll;
   
    
    
    
    
    
    
}

.project-container{
    background-color: #212122;
    padding: 2em;
    margin-bottom: 2em;
    line-height: 2em;
    transition: .3s ease-in-out;
    cursor: pointer;
}

.project-stack{
    font-size: 10px;
    text-transform: uppercase;
    letter-spacing: .4px;
    padding: 0;
}

.project-details{
    
    font-size: 14px;
    color: grey;
    padding: 0;
}

.flex{
    width: 50%;
    justify-content: space-between;
}

.project-container:hover{
    transform: scale(1.2);
}
</style>
