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
                <a href="/loyalty"><img  class="small" src="https://cdn1.iconfinder.com/data/icons/arrows-vol-1-5/24/Forward2-512.png"></a>
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
                <ion-label >Order Now!</ion-label>
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
                <ion-label >My Account</ion-label>
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
        <ion-title class="ion-text-center">
          <div class="content-center">
            <img class="small" src="https://cdn-icons-png.flaticon.com/512/2385/2385865.png">
            <a href="/loyalty"><p>0 points</p></a>
            <img class="extra-small" src="https://cdn1.iconfinder.com/data/icons/arrows-vol-1-5/24/Forward2-512.png">
          </div>
        </ion-title>
        <ion-buttons slot="end">
          <ion-avatar class="small ion-margin-end">
            <img src="https://b.thumbs.redditmedia.com/1dTxU-YsMCMGxfijoARgpfBhjc7YKxF6Nu8RrUUZCvc.png" alt="Avatar">
          </ion-avatar>
        </ion-buttons>
      </ion-toolbar>
    </ion-header>
    <ion-content class="ion-padding">
      <div class="content-center">
        <div class="ion-margin-end">
          <ion-img class="medium" src="https://cdn-icons-png.flaticon.com/512/3703/3703377.png"></ion-img>
        </div>
        <div>
          <p>Anneoyong, Chou!</p>
          <h2>What do you want to eat?</h2>
        </div>
      </div>
      <ion-searchbar placeholder="try our new Steak Fries Veggies"></ion-searchbar>
      <div class="ion-margin-top horizontal-container">
        <b><ion-text>Special Offers!</ion-text></b>
        <div class="horizontal-container">
          <p class="ion-margin-end">View All</p>
          <img class="extra-small" src="https://cdn1.iconfinder.com/data/icons/arrows-vol-1-5/24/Forward2-512.png">
        </div>
      </div>
      <div class="wrapper">
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
          <ion-img class="item-custom" src="https://couponswala.com/blog/wp-content/uploads/2022/09/Food-Combo-Offers-696x392.jpg.webp"></ion-img>
      </div>
      <b><ion-text>Category</ion-text></b>
      <div class="wrapper">
        <ion-card class="ion-margin-top item-custom ion-card-custom">
          <ion-img class="ion-img-custom" src="https://media.timeout.com/images/105881603/750/562/image.jpg"></ion-img>
          <ion-card-content class="ion-card-content-custom">
            <ion-card-title class="ion-card-title-custom">Chicken</ion-card-title>
            <ion-card-subtitle class="ion-card-subtitle-custom">9 recipes</ion-card-subtitle>
          </ion-card-content>
        </ion-card>
        <ion-card class="ion-margin-top item-custom">
          <ion-img class="ion-img-custom" src="https://media.timeout.com/images/105881603/750/562/image.jpg"></ion-img>
          <ion-card-content class="ion-card-content-custom">
            <ion-card-title class="ion-card-title-custom">Chicken</ion-card-title>
            <ion-card-subtitle class="ion-card-subtitle-custom">9 recipes</ion-card-subtitle>
          </ion-card-content>
        </ion-card>
        <ion-card class="ion-margin-top item-custom">
          <ion-img class="ion-img-custom" src="https://media.timeout.com/images/105881603/750/562/image.jpg"></ion-img>
          <ion-card-content class="ion-card-content-custom">
            <ion-card-title class="ion-card-title-custom">Chicken</ion-card-title>
            <ion-card-subtitle class="ion-card-subtitle-custom">9 recipes</ion-card-subtitle>
          </ion-card-content>
        </ion-card>
        <ion-card class="ion-margin-top item-custom">
          <ion-img class="ion-img-custom" src="https://media.timeout.com/images/105881603/750/562/image.jpg"></ion-img>
          <ion-card-content class="ion-card-content-custom">
            <ion-card-title class="ion-card-title-custom">Chicken</ion-card-title>
            <ion-card-subtitle class="ion-card-subtitle-custom">9 recipes</ion-card-subtitle>
          </ion-card-content>
        </ion-card>
        <ion-card class="ion-margin-top item-custom">
          <ion-img class="ion-img-custom" src="https://media.timeout.com/images/105881603/750/562/image.jpg"></ion-img>
          <ion-card-content class="ion-card-content-custom">
            <ion-card-title class="ion-card-title-custom">Chicken</ion-card-title>
            <ion-card-subtitle class="ion-card-subtitle-custom">9 recipes</ion-card-subtitle>
          </ion-card-content>
        </ion-card>
      </div>
      <div>
        <b><ion-text>What's New?</ion-text></b>
        <ion-img class="ion-margin-top" src="https://i.ytimg.com/vi/KW4rNKdaPq0/maxresdefault.jpg"></ion-img>
      </div>
      <div class="ion-margin-top">
        <b><ion-text>Most Popular</ion-text></b>
        <ion-grid>
          <ion-row>
            <ion-col>
              <ion-card class="ion-padding gray-background">
                <ion-img src="https://freepngimg.com/thumb/salad/9-2-salad-png-image.png"></ion-img>
                <ion-card-content>
                  <b><p>Salad</p></b>
                  <p>Appetizer</p>
                </ion-card-content>
                <div>
                 <ion-text color="danger">P 175</ion-text>
                </div>
            </ion-card>
            </ion-col>
            <ion-col>
              <ion-card class="ion-padding gray-background">
                <ion-img src="https://freepngimg.com/thumb/salad/9-2-salad-png-image.png"></ion-img>
                <ion-card-content>
                  <b><p>Salad</p></b>
                  <p>Appetizer</p>
                </ion-card-content>
                <div>
                 <ion-text color="danger">P 175</ion-text>
                </div>
            </ion-card>
            </ion-col>
          </ion-row>
          <ion-row>
            <ion-col>
              <ion-card class="ion-padding gray-background">
                <ion-img src="https://freepngimg.com/thumb/salad/9-2-salad-png-image.png"></ion-img>
                <ion-card-content>
                  <b><p>Salad</p></b>
                  <p>Appetizer</p>
                </ion-card-content>
                <div>
                 <ion-text color="danger">P 175</ion-text>
                </div>
            </ion-card>
            </ion-col>
            <ion-col>
              <ion-card class="ion-padding gray-background">
                <ion-img src="https://freepngimg.com/thumb/salad/9-2-salad-png-image.png"></ion-img>
                <ion-card-content>
                  <b><p>Salad</p></b>
                  <p>Appetizer</p>
                </ion-card-content>
                <div>
                 <ion-text color="danger">P 175</ion-text>
                </div>
            </ion-card>
            </ion-col>
          </ion-row>
        </ion-grid>
      </div>
     
    </ion-content>
    <ion-fab vertical="bottom" horizontal="end" class="fab-container">
    <button class="ion-fab-button-custom">
      <p>Order Now!</p> <!-- Use the imported icon -->
    </button>
  </ion-fab>
  </ion-page>
</template>

<script lang="ts">
  import { IonButtons, IonContent, IonHeader, IonMenu, IonMenuButton, IonPage, IonTitle, IonToolbar, IonAvatar, IonRow, IonCol, IonImg, IonFab, IonFabButton, IonIcon, IonSearchbar, IonRouterOutlet, IonList, IonButton, IonItem, IonLabel, IonBadge, IonCard, IonCardContent, IonText, IonGrid, IonCardSubtitle, IonCardTitle } from '@ionic/vue';
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
      IonRow,
      IonCol,
      IonImg,
      IonAvatar,
      IonFab, IonFabButton, IonIcon, IonSearchbar,
      IonRouterOutlet, IonList, IonButton, IonItem, IonLabel, IonBadge,
      IonCard, IonCardContent, IonText, IonGrid, IonCardSubtitle, IonCardTitle
    }, 
    setup() {
      const router = useRouter();
      return { router };
    },
  });
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

.content-center{
  display: flex;
  align-items: center;
  justify-content: center;
}

.horizontal-container {
  display: flex;
  align-items: center; /* Vertically center-align the content */
  justify-content: space-between;
}

.wrapper{
  max-height: 320px;
  display: flex;
  overflow-x: auto;
}
.item-custom{
  min-width: 120px;
  height: 90px;
  margin-right: 5px;
  text-align: center;
}

.ion-card-custom {
  position: relative;
}

.ion-img-custom {
  width: 100%;
  height: auto;
}

.ion-card-content-custom {
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  color: white;
  padding: 16px;
  box-sizing: border-box;
}

.ion-card-title-custom {
  color: white;
  font-size: 16px; /* Adjust the font size as needed */
}

.ion-card-subtitle-custom {
  color: white;
  font-size: 8px; /* Adjust the font size as needed */
}

.gray-background{
  background-color: #EEEEEE;
}

.fab-container {
  position: fixed;
  bottom: 20px; /* Adjust the distance from the bottom as needed */
  right: 20px; /* Adjust the distance from the right as needed */
  z-index: 999; /* Adjust the z-index as needed to ensure it's above other elements */
}

/* Style for the FAB button */
.ion-fab-button-custom {
  width: 100px; /* Adjust the width as needed */
  height: 50px; /* Adjust the height as needed */
  border-radius: 10px; /* Adjust the border-radius to make it rectangular */
  background-color: #CD1818; /* Set the background color */
  color: white; /* Set the text color */
}
</style>