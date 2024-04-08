<template>
    <Head title="Welcome" />
    <div class="head">
        <h1 class="logo">Food Recipes</h1>
        <div class="nav-log">
            <a href="/signin">Sign In</a>
            <span class="spacer"></span>
            <a href="/signup">Sign Up</a>
        </div>
    </div>
</template>
<style>
@import url('https://fonts.googleapis.com/css2?family=Lora:ital,wght@0,400..700;1,400..700&display=swap');

.head{
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 10px;

}
.logo {
    font-family: 'Lora', serif;
    font-size: 35px;
    letter-spacing: 1px; /* ระยะห่างของตัวอักษร */
    text-align: center;
    color: black;
    margin: 15px;

}
.spacer {
    margin-left: 10px; /* Adjust the margin as needed */
    margin-right: 10px; /* Adjust the margin as needed */
}
.login{

}
.regis{

}
</style>
