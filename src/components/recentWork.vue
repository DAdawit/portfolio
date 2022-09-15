<template>
    <div>
        <div class="my-15">
            <v-row>
                <v-col cols="12" class="d-flex justify-center">
                    <h1 class="display-1">Our Recent work</h1>
                </v-col>
            </v-row>
            <h4 class="grey--text text-center subtitle-1">You can relay on our amazing features list and also our
                customer services will be great</h4>
            <h4 class="grey--text text-center subtitle-1">experience for you without doubt and in no-time</h4>
        </div>

        <v-item-group>
            <v-container>

                <v-row>
                    <v-col v-for="work in works" :key="work.id" cols="12" xs="12" sm="6" md="4" lg="4">
                        <v-item cols="12" xs="12" sm="6" md="4" lg="4">
                            <v-card max-width="350">
                                <v-img src="https://cdn.vuetifyjs.com/images/cards/sunshine.jpg" height="300px"></v-img>

                                <v-card-title>
                                    Top western road trips
                                </v-card-title>

                                <v-card-subtitle>
                                    1,000 miles of wonder
                                </v-card-subtitle>

                                <v-card-actions>
                                    <v-btn color="orange lighten-2" text>
                                        Explore
                                    </v-btn>

                                    <v-spacer></v-spacer>

                                    <v-btn icon @click="show = !show">
                                        <v-icon>{{ show ? 'mdi-chevron-up' : 'mdi-chevron-down' }}</v-icon>
                                    </v-btn>
                                </v-card-actions>

                                <v-expand-transition>
                                    <div v-show="show">
                                        <v-divider></v-divider>
                                        <v-card-text>
                                            {{work.description}}
                                        </v-card-text>
                                    </div>
                                </v-expand-transition>
                            </v-card>

                        </v-item>
                    </v-col>
                </v-row>
            </v-container>
        </v-item-group>

        <!-- <v-row class="d-flex justify-space-around">
            <v-col cols="12" lg="4" md="4" sm="6" xs="12">

            </v-col>
        </v-row> -->

        <template>

        </template>
    </div>
</template>
<script>
    export default {
        data: () => ({
            show: false,
            works: [{
                    id: 1,
                    titile: 'hello world',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, debitis? Dolorum ullam sed quasi officiis expedita possimus autem ratione cum, officia vero praesentium asperiores necessitatibus obcaecati ipsum dolor enim optio!',
                },
                {
                    id: 2,
                    titile: 'hello world',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, debitis? Dolorum ullam sed quasi officiis expedita possimus autem ratione cum, officia vero praesentium asperiores necessitatibus obcaecati ipsum dolor enim optio!',
                },
                {
                    id: 3,
                    titile: 'hello world',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, debitis? Dolorum ullam sed quasi officiis expedita possimus autem ratione cum, officia vero praesentium asperiores necessitatibus obcaecati ipsum dolor enim optio!',
                },
                {
                    id: 4,
                    titile: 'hello world',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, debitis? Dolorum ullam sed quasi officiis expedita possimus autem ratione cum, officia vero praesentium asperiores necessitatibus obcaecati ipsum dolor enim optio!',
                },
                {
                    id: 5,
                    titile: 'hello world',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, debitis? Dolorum ullam sed quasi officiis expedita possimus autem ratione cum, officia vero praesentium asperiores necessitatibus obcaecati ipsum dolor enim optio!',
                },
                {
                    id: 6,
                    titile: 'hello world',
                    description: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Amet, debitis? Dolorum ullam sed quasi officiis expedita possimus autem ratione cum, officia vero praesentium asperiores necessitatibus obcaecati ipsum dolor enim optio!',
                },
            ]
        }),
    }
</script>