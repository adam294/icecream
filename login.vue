<template>
    <section class="login-section">
        <div class="login-div">
            <title>Hello world!</title>
            <h1>Welcome to boring page</h1>
            <div class="login-form">
                <form>
                    Email:<br>
                    <input type="text"><br>
                    Password:<br>
                    <input type="text"><br>
                </form>
                <button type="button"><a href="map.vue">Log in</a></button>
                <button type="button">Sign up</button>
            </div>
        </div>
    </section>
</template>


<style scoped>
body {
    background-color: cornflowerblue;
    width: 480px;
}

.login-div {
    background-color: cornflowerblue;
    width: 480px;
}

.login-form {
    display: inline-block;
    position: fixed;
    top: 60%;
    margin: auto;
    width: 35%;
}

</style>
