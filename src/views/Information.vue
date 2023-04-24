<template>
    <v-container class="pa-8">
        <v-row class=" d-flex justify-center">
            <v-col>
                <v-card variant="text">
                    <v-card-item>
                        <v-card-title class="text-left text-cyan-accent-3">
                            Why AzDev.Space?
                        </v-card-title>
                    </v-card-item>
                    <v-card-text class="text-teal-accent-4">
                        <p class="text-subtitle-1">AzDev is a mash up of Azure and Developer</p>
                        <p class="my-2">
                            This website was initially intended to be a space for me to choose a set of web and Cloud
                            technologies to create a custom Event Based Microservices Architecture Framework that
                            I can use for future projects. The initial use case is a responsive website that allows me to
                            collate and present information relating to my career history and future ambitions in a
                            modern layout. My current thinking is that I will expand this to allow for other job seekers to
                            create their own profiles and for recruiters to be able to search for suitable candidates.
                        </p>
                        <p class="text-subtitle-1">
                            The Theory
                        </p>
                        <p class="text-subtitle-2 my-2">
                            I intend to use Pulumi to deploy the required Azure Cloud infrastructure, code, data and other
                            artifacts required for this website.
                        </p>
                        <p>The first version of this will include:</p>
                        <ul class="pl-3 my-2">
                            <li>Azure Cloud: [ "App Configuration Service" , "Keyvault", "Container Registry", "Cosmos DB",
                                "App Service", "SQL", "Storage" ]</li>
                            <li>Front End: [ "Vue 3", "Vite", "Pinia", "Axios", "GraphQL", "Vuetify", "Typescript",
                                "Vitest", "Playwright" ]</li>
                            <li>Back End: [".Net 8", "C#", "Web API", "EF Core", "Curity", "FluentValidation", "XUnit", "Moq"]</li>
                            <li>Devops: ["Pulumi", "Git", "GitKraken", "Azure Devops", "Powershell", "Docker"]</li>
                        </ul>
                    </v-card-text>
                </v-card>
            </v-col>
        </v-row>
    </v-container>
</template>