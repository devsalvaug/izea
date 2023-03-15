<script setup lang="ts">
import { PowerIcon } from 'vue-tabler-icons';
</script>

<template>
    <div class="container">
        <div class="centrado">



            <v-avatar size="140">
                <img class="avatar-image"
                    src="https://izea-marketplace-prod.imgix.net/34oplig4kdgo2jnz5cjdp3wz79ds?ixlib=rails-4.2.0&w=126&h=126&auto=format&mask=ellipse&dpr=1&q=75"
                    height="100" width="100" alt="avatar">
            </v-avatar>
            <br>
            <br>
            <div class="container">
                <p class="text-h4">
                    Braxton Miller
                </p>


            </div>
            <div class="container">

                <p style="margin-top: -15%;" class="text-caption
                                                                                        ">
                    882.6k Followers
                </p>
            </div>

            <div class="avatar-group">
                <div class="container">
                    <v-avatar class="avatar avatar-1" size="30">

                    </v-avatar>
                    <v-avatar class="avatar avatar-2" size="30">

                    </v-avatar>
                    <v-avatar class="avatar avatar-3" size="30">
                    </v-avatar>
                </div>
            </div>

            <v-divider height="1" />
        </div>
    </div>
</template>

<style lang="scss">
.container {
    justify-content: center;
    height: 7vh;

}


.avatar-image {
    width: 100%;
    height: auto;
}

.avatar-group {
    position: relative;
    margin-top: -10%;
    margin-left: 15%;
    /* Hace que la posición absoluta de los avatares sea relativa a este contenedor */
}

.avatar {
    position: absolute;
    /* Hace que los avatares sean posicionados de forma absoluta */
    border: 2px;
    /* Añade un borde blanco para resaltar cada avatar */
    box-shadow: 0px 0px 4px 0px rgba(0, 0, 0, 0.75);
    /* Añade una sombra para dar profundidad */
}

.avatar-1 {
    top: 0;
    left: 0;
}

.avatar-2 {
    top: 0px;
    left: 25px;
}

.avatar-3 {
    top: 0px;
    left: 50px;
}
</style>
