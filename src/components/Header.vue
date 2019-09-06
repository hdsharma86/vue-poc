<template>
    <v-app-bar app>
        <v-toolbar-title class="headline text-uppercase">
            <span @click.stop="drawer = !drawer" class="bars">
                <v-icon>mdi-view-headline</v-icon>
            </span>
            <span class="font-weight-light">Maropost</span>
        </v-toolbar-title>
        <v-spacer></v-spacer>
        <v-btn
            text
            href="https://github.com/vuetifyjs/vuetify/releases/latest"
            target="_blank"
            >
        </v-btn>
    </v-app-bar>
</template>
<style>
    .bars .v-icon{
        font-weight: bold;
        font-size: 40px;
        padding: 0px 17px 0 7px;
    }
</style>
