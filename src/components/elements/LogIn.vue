<template>
    <div class="log-in">
        <img src="../../assets/img/insider_short_logo.png" alt="Insider Short Logo">
        <a class="text-uppercase fw-bold text-decoration-none">sign in</a>
        <a class="text-uppercase fw-bold text-decoration-none">i</a>
        <a class="text-uppercase fw-bold text-decoration-none">join</a>
    </div>
</template>

<script>
export default {
    name: 'LogIn'
}
</script>

<style lang="scss" scoped>
@import 'bootstrap';
@import '../../assets/style/partials/variables.scss';
    .log-in{
        border-left: 1px solid #373737;
        border-right: 1px solid #373737;
        display: flex;
        align-items: center;
        justify-content: center;
        height: 100%;
        padding: 0 25px;
        cursor:pointer;
        img{
            width: 20px;
        }
        a{
            padding: 0 5px;
            color:$primary-txt-color-light;
            font-size: $lower-font-size;
        }
    }
</style>