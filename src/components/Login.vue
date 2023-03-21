<template>
    <h2>Login</h2>
    <form>
        <label>email:</label>
        <input type="email" v-model="email" placeholder="email">

        <label>password:</label>
        <input type="password" v-model="password" placeholder="password">
        <button type="button">Submit</button>
    </form>
</template>

<script>
export default {
name:'Login',
data() {
    return {
        input: {
            email: "",
            password:""
        }
    }
}
}
</script>

<style>
h2 {
    margin-top: 200px;
    margin-bottom: 30px;
    font-weight: normal;
}
form {
    display: flex;
    flex-direction: column;
    align-items: center;
}
label {
    text-align: left;
    margin-top: 10px;
}
input{
    width: 300px;
    height: 25px;
    border: 1px solid gray;
    border-radius: 5px;
}
button {
    
    width: 300px;
    height: 40px;
    margin-top: 20px;
    border-radius: 5px;
    border: none;
    background-color: #1FC69E;
    color: white;
    font-weight: bold;
    font-size: 17px;
}
</style>