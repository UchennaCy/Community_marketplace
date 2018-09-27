<template>
    <v-app id="home">
        <v-navigation-drawer app>
        ...
        </v-navigation-drawer>
        <v-toolbar>
        ...
        </v-toolbar>
        <v-content>
            <v-container fluid xfill-height>
                <v-layout row wrap>
                    <v-flex xs12>
                        <post-grid :posts="posts"></post-grid>
                    </v-flex>
                </v-layout>
            </v-container>
        </v-content>
    </v-app>
</template>