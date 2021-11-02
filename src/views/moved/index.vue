<template>
    <div id="page-list" class="device">
        <header class="header">
            <h1>111</h1>
        </header>
        <div class="main">
            <h1>222</h1>
        </div>
        <footer class="footer">
            <h1>333</h1>
        </footer>
        
    </div>
    
</template>
<style lang="scss">

.device {
    position: relative;
    float: left;
    width: 100%;
    height: 1000px;
    background-color: #eee;
    // border-radius: 40px;
    overflow: hidden;
    display: flex;

    header{
        height: 1rem;
        line-height: 1rem;
        width: 100%;
        background-color: red;
        top: 5px;
        margin:10px;
    }
    .main{
        width: 100%;
        height: 10rem;
        background-color: pink;
        top: 2.5rem;
    }
    footer{
        height: 1rem;
        width: 100%;
        background-color: skyblue;
        bottom: 10px;
    }

}

</style>