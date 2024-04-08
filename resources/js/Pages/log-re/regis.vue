<template>
    <form class="sign-up">
        <h2>Sign Up</h2>
        <p>Please enter your personal details</p>
        <div class="login-box">
            <input type="text" placeholder="Name">
            <input type="email" placeholder="Email" />
            <input type="password" placeholder="Password" />
            <input type="password" placeholder="Comfirm password">
            <span class="spacer"></span>
            <button>Sign Up</button>
            <div style="color: #081f5c; font-size: 13px; margin-top: 10px;">Have an ready account ? <a href="/signin">Sign in</a></div>
        </div>
    </form>
</template>

<style>
body {
    margin: 0;
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
}

.sign-up {
    width: 450px; /* Adjust width as needed */
    height: 450px;
    padding: 20px;
    border-radius: 15px;
    background: linear-gradient(to bottom, #efefef, #ccc);
    box-shadow: 0 15px 30px rgba(0, 0, 0, .2), 0 10px 10px rgba(0, 0, 0, .2);
    text-align: center;
}

h2 {
    margin-top: 13px;
    margin-bottom: 10px;
    color: #081f5c;
    font-size: 30px;
}
p{
    margin-bottom: 15px;
    color: #081f5c;
}
a {
    color: #081f5c;
    text-decoration: none;
    font-size: 13px;
}

button {
    border-radius: 20px;
    border: 1px solid #081f5c;
    background-color: #213e60;
    color: #fff;
    font-size: 16px;
    font-weight: bold;
    padding: 10px 40px;
    letter-spacing: 1px;
    text-transform: uppercase;
    cursor: pointer;
    transition: transform .1s ease-in;
    margin-top: 15px;
    box-shadow: inset 0 1px 2px rgba(0, 0, 0, .4),
                            0 -1px 1px #fff,
                            0 1px 0 #fff;
}

button:active {
    transform: scale(.9);
}

button:focus {
    outline: none;
}

.sign-up form {
    display: flex;
    flex-direction: column;
    align-items: center;
}

.sign-up .login-box input {
    width: 100%;
    max-width: 350px;
    border-radius: 15px;
    margin: 6px 0;
    padding: 8px 15px;
    border: none;
    border-bottom: 1px solid #ddd;
    background-color: #eee;
    box-shadow: inset 0 1px 2px rgba(0, 0, 0, .4),
                            0 -1px 1px #fff,
                            0 1px 0 #fff;
}

.sign-up .login-box input:focus {
    background-color: #fff;
}
.spacer{
    margin-top: 10px;
}
</style>
