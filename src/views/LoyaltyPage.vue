<template>
    
    <ion-menu content-id="main-content">
      <ion-header>
        <ion-toolbar>
            <div class="horizontal-container">
                <ion-avatar class="medium ion-margin">
                    <img src="https://b.thumbs.redditmedia.com/1dTxU-YsMCMGxfijoARgpfBhjc7YKxF6Nu8RrUUZCvc.png" alt="Avatar">
                </ion-avatar>
                <img class="medium" src="https://cdn-icons-png.flaticon.com/512/2385/2385865.png">
                <a href="/loyalty"><p>0 Points</p></a>
                <img  class="small" src="https://cdn1.iconfinder.com/data/icons/arrows-vol-1-5/24/Forward2-512.png">
            </div>
           <div class="ion-margin-start">
                <div> 
                    <b><ion-text>Chou Tzuyu</ion-text></b>
                </div>
                <ion-text>+63 912 345 6789</ion-text>
           </div>
          
        </ion-toolbar>
      </ion-header>
      <ion-content class="ion-padding">
        <ion-list lines="none">
            <ion-item>
                <a href="/home"><ion-label>Home</ion-label></a>
                
            </ion-item>
            <ion-item>
                <ion-label>Order Now!</ion-label>
            </ion-item>
            <ion-item>
                <ion-label>Notifications</ion-label>
                <ion-badge color="warning" slot="end">4</ion-badge>
            </ion-item>
            <ion-item>
                <ion-label>Store Locator</ion-label>
            </ion-item>  
        </ion-list>
        <ion-item>
            <ion-label>FAQ's</ion-label>
        </ion-item>
        <ion-list lines="none">
            <ion-item>
                <ion-label>My Orders</ion-label>
                <ion-badge  color="warning" slot="end">2</ion-badge>
            </ion-item>
            <ion-item>
                <ion-label>My Account</ion-label>
            </ion-item>
            <ion-item>
                <ion-label>My Favorites</ion-label>
            </ion-item>
            <ion-item>
                <ion-label>Order Tracker</ion-label>
            </ion-item>  
            <ion-item>
                <ion-label>Order History</ion-label>
            </ion-item>  
        </ion-list>
        <ion-button class="ion-margin-top" color="danger">Logout</ion-button>
      </ion-content>
    </ion-menu>
    <ion-page id="main-content">
      <ion-header>
        <ion-toolbar>
          <ion-buttons slot="start">
            <ion-menu-button></ion-menu-button>
          </ion-buttons>
          <b><ion-text>Loyalty Points</ion-text></b>
        </ion-toolbar>
      </ion-header>
      <ion-content class="ion-padding">

        <div class="ion-margin-top horizontal-container">
            <b><ion-text class="horizontal-container">
                <ion-img class="medium" src="https://cdn-icons-png.flaticon.com/512/2385/2385865.png"></ion-img>
                Beginner Tier
            </ion-text></b>
            <div class="horizontal-container">
            <p class="ion-margin-end">View All</p>
            <img class="extra-small" src="https://cdn1.iconfinder.com/data/icons/arrows-vol-1-5/24/Forward2-512.png">
            </div>
        </div>
        <p>
            Earn points by purchasing from our store. Vestibulum ante ipsum primis in faucibus orci luctus et.
        </p>
        <div class="progress-bar-container">
      <div class="circular-progress">
        <div class="progress-ring">
          <div class="progress-circle"></div>
        </div>
        <div class="progress-text">0/160</div>
      </div>
    </div>
        <div class="ion-margin-top horizontal-container">
            <b><ion-text class="horizontal-container">Rewards</ion-text></b>
            <div class="horizontal-container">
                <p class="ion-margin-end">How it Works</p>
                <img class="extra-small" src="https://cdn1.iconfinder.com/data/icons/arrows-vol-1-5/24/Forward2-512.png">
            </div>
        </div>

        <div>
            <ion-chip class="custom-chip">
                <ion-label>All</ion-label>
            </ion-chip>
            <ion-chip>Beginner</ion-chip>
            <ion-chip>Intermediate</ion-chip>
            <ion-chip>Loyal</ion-chip>
        </div>
        <ion-card>
           
            <div class="horizontal-container-custom ion-margin-start">
                <div>
                    <ion-img  class="medium" src="https://freepngimg.com/thumb/salad/9-2-salad-png-image.png"></ion-img>
                </div>
                <div>
                    <ion-card-header>
                        <ion-text>Meat</ion-text>
                        <b><ion-text>Steak Fries Veggies</ion-text></b>
                    </ion-card-header>
                </div>
            </div>
            <ion-card-content>
                <div class="horizontal-container">
            <b><ion-text class="horizontal-container">
                <ion-img class="small" src="https://cdn-icons-png.flaticon.com/512/2385/2385865.png"></ion-img>
                20 points
            </ion-text></b>
            </div>
            </ion-card-content>
        </ion-card>
      </ion-content>
    </ion-page>
  </template>
  
  <script lang="ts">
    import { IonButtons, IonContent, IonHeader, IonMenu, IonMenuButton, IonPage, IonTitle, IonToolbar, IonText, IonImg, IonProgressBar, IonChip, IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle, IonAvatar, IonList, IonButton, IonRouterOutlet, useIonRouter } from '@ionic/vue';
    import { defineComponent } from 'vue';
    import { useRouter } from 'vue-router';

    export default defineComponent({
      components: {
        IonButtons,
        IonContent,
        IonHeader,
        IonMenu,
        IonMenuButton,
        IonPage,
        IonTitle,
        IonToolbar,
        IonText,
        IonImg,
        IonProgressBar,
        IonChip,
        IonCard, IonCardHeader, IonCardSubtitle, IonCardTitle,
        IonAvatar, IonList, IonButton, IonRouterOutlet, 
    },
    setup() {
      const router = useRouter();
      return { router };
    },});
  </script>

  <style scoped>
    a{
        text-decoration: none;
        color: black;
    }
    .extra-small{
    width: 15px; /* Adjust the width to your desired size */
    height: 15px; /* Adjust the height to your desired size */
    }

    .small{
    width: 23px; /* Adjust the width to your desired size */
    height: 23px; /* Adjust the height to your desired size */
    }
    .medium{
    width: 50px; /* Adjust the width to your desired size */
    height: 50px; /* Adjust the height to your desired size */
    }

    .horizontal-container {
    display: flex;
    align-items: center; /* Vertically center-align the content */
    justify-content: space-between;
    }

    .horizontal-container-custom{
        display: flex;
        align-items: center;
        justify-content: flex-start;
    }

    .custom-chip {
    background: #CD1818; /* Set the background color to red */
    color: white; /* Set the overall color to white (this affects the border color) */
    }
    
    .progress-bar-container {
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 20px; /* Adjust the margin-top as needed */
  }

  .circular-progress {
    position: relative;
  }

  .progress-ring {
    width: 300px; /* Adjust the size of the progress ring */
    height: 300px; /* Adjust the size of the progress ring */
    border: 4px solid #007bff; /* Adjust the progress ring color */
    border-radius: 60%;
    position: relative;
  }

  .progress-text {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    font-weight: bold;
    font-size: 18px; /* Adjust the font size */
  }
    </style>