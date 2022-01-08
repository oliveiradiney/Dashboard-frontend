<template>
    <DashboardComponent>
        <div slot="slot-pages" class="content-pages">
            <header class="title_pages">
                <p>Inicio</p>
            </header>

            <CardsComponent />
        </div>
    </DashboardComponent>
</template>
<script>
import DashboardComponent from '../Dashboard/DashboardComponent';
import CardsComponent from '../../components/CardsComponent';

export default {
    components:{
        DashboardComponent,
        CardsComponent
    }
}
</script>

<style lang="scss" src="./style.scss" scoped />