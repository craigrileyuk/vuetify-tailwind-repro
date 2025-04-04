<template>
    <VApp>
        <VAppBar title="Some Application">ASDF</VAppBar>
        <VNavigationDrawer>
            <v-list nav>
                <v-list-item title="Navigation drawer" link></v-list-item>
            </v-list>
        </VNavigationDrawer>
        <VMain>
            <v-container>
                <v-sheet
                    border="dashed md"
                    color="surface-light"
                    height="200"
                    rounded="lg"
                    width="100%"
                >
                    <h1>This is home</h1>
                </v-sheet>
            </v-container>
        </VMain>
    </VApp>
</template>

<script setup></script>
