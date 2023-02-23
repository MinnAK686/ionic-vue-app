<template>
    <div>
        <ion-grid>
            <ion-row>
                <ion-col size="2">
                    <ion-avatar size="sm">
                        <img
                            alt="Silhouette of a person's head"
                            src="https://images.unsplash.com/photo-1440589473619-3cde28941638?ixlib=rb-4.0.3&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=387&q=80"
                        />
                    </ion-avatar>
                </ion-col>
                <ion-col>
                    <div class="tweets">
                        <div class="tweets-header">
                            <ion-text color="dark">
                                <span>
                                    <strong>BSC News</strong>
                                </span>
                            </ion-text>
                            <ion-text color="medium">
                                <span> @BSCNews </span>
                            </ion-text>
                            &middot;
                            <ion-text color="medium">
                                <span> 50m </span>
                            </ion-text>
                        </div>
                        <div class="tweets-body">
                            <ion-text>
                                <p>
                                    "Love is the master key that opens the gates
                                    of happiness."- Oliver Holmes
                                </p>
                            </ion-text>
                        </div>
                        <div class="tweets-footer"></div>
                    </div>
                </ion-col>
            </ion-row>
        </ion-grid>
    </div>
</template>

<script setup lang="ts">
import { IonGrid, IonRow, IonCol, IonAvatar, IonText } from "@ionic/vue";
</script>
<style scoped>
ion-avatar img {
    width: 3rem;
    height: 3rem;
}
.tweets .tweets-header {
}
</style>
