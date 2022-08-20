<template>
    <div>
        <div class="input">
            <input type="text" placeholder="add details">
            <button class="btn">Add</button>
        </div>
        <div class="container">
            <div><input type="checkbox"><p>Do coding challenges</p></div>
            <div><input type="checkbox"><p>Do coding challenges</p></div>
        </div>
    </div>
</template>

<script>
    export default {
        name: "All"
    }
</script>

<style scoped>
    .input{
        display: flex;
        align-items: center;
        justify-content: center;
        flex-direction: row;
        margin-left: 50px;
    }
    input[type=text]{
        border: 1px solid #BDBDBD;
        border-radius: 12px;
        width: 476px;
        height: 56px;
        margin-right: 20px;
    }
    .btn{
        /*padding: 20px 40px;*/
        width: 109px;
        height: 56px;
        left: 915px;
        top: 184px;
        background: #2F80ED;
        box-shadow: 0px 2px 6px rgba(127, 177, 243, 0.4);
        border-radius: 12px;
        border: none;
        color: #FFFFFF;
    }
    .container{
        margin-top: 20px;
        margin-left: 515px;
    }
    .container div{
        display: flex;
        align-items: center;
        flex-direction: row;
    }
    .container div input{
        border: 1px solid #828282;
        border-radius: 4px;
        width: 24px;
        height: 24px;
    }
    .container div p{
        font-style: normal;
        font-weight: 500;
        font-size: 18px;
        line-height: 22px;
        color: #000000;
    }
</style>