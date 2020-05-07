<template>
    <div>
        <div id="leftBar">
            <div id="nav">
                <a href="#main"><h3>About me</h3></a>
                <a href="#skills"><h3>My skills</h3></a>
                <a href="#projects"><h3>Projects</h3></a>
            </div>
        </div>
    </div>
</template>

<script>

    export default {
        name:'LeftNav',
    }
    
</script>

<style scoped>
#leftBar {
    background-color: #4B9F88;
    text-align: center;
    position: fixed;
    top: 0;
    left: 0;
    display: flex;
    justify-content: center;
    flex-direction: column;
    width: 20%;
    height: 100%;

}

#nav h3{
    padding: 1em;
    color: #FFFFFF;
    text-transform: uppercase;
}
a {
        text-decoration: none;
}
</style>