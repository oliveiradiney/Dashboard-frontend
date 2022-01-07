<template>
    <div class="navbar">
        <h3 class="logo">Dashboard</h3>
        <a href="#" @click.prevent="logout" class="logout">Sair <i class="fa fa-sign-out-alt"></i></a>
    </div>
</template>

<script>
export default {
    name: 'NavBarComponent',
    methods: {
        logout(){
            this.$router.push({name: 'login'})
        }
    }
}
</script>

<style lang="scss">
.navbar{

    .logo{
        color: #fff;
    }

    .logout{
        color: #fff;
    }
    .logout{
        color: #fff;
        text-decoration: none;
    }
}

</style>