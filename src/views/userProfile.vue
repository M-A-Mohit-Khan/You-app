<template>
 <ion-page>
    <ion-header>
        <ion-toolbar>
            <div class="header">
            <div><svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" width="1.5em" height="1.5em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><path d="M21 11H6.414l5.293-5.293l-1.414-1.414L2.586 12l7.707 7.707l1.414-1.414L6.414 13H21z" fill="white"/></svg></div>
            <div><ion-title class="login">Profile</ion-title></div>
            </div>

            <div class="profileimg">
          <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" width="7em" height="7em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 48 48"><g fill="none"><path fill-rule="evenodd" clip-rule="evenodd" d="M14.809 34.714c6.845-1 11.558-.914 18.412.035A2.077 2.077 0 0 1 35 36.818c0 .48-.165.946-.463 1.31A61.165 61.165 0 0 1 32.941 40h2.641c.166-.198.333-.4.502-.605A4.071 4.071 0 0 0 37 36.819c0-2.025-1.478-3.77-3.505-4.05c-7.016-.971-11.92-1.064-18.975-.033c-2.048.299-3.52 2.071-3.52 4.11c0 .905.295 1.8.854 2.525c.165.214.328.424.49.63h2.577a57.88 57.88 0 0 1-1.482-1.85A2.144 2.144 0 0 1 13 36.845c0-1.077.774-1.98 1.809-2.131z" fill="white"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 25a6 6 0 1 0 0-12a6 6 0 0 0 0 12zm0 2a8 8 0 1 0 0-16a8 8 0 0 0 0 16z" fill="white"/><path fill-rule="evenodd" clip-rule="evenodd" d="M24 42c9.941 0 18-8.059 18-18S33.941 6 24 6S6 14.059 6 24s8.059 18 18 18zm0 2c11.046 0 20-8.954 20-20S35.046 4 24 4S4 12.954 4 24s8.954 20 20 20z" fill="white"/></g></svg>
          
          </div>
           
           <div class="profileimg">
         <svg xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" aria-hidden="true" role="img" width="1.5em" height="1.5em" preserveAspectRatio="xMidYMid meet" viewBox="0 0 24 24"><g fill="none"><path d="M16.474 5.408l2.118 2.117m-.756-3.982L12.109 9.27a2.118 2.118 0 0 0-.58 1.082L11 13l2.648-.53c.41-.082.786-.283 1.082-.579l5.727-5.727a1.853 1.853 0 1 0-2.621-2.621z" stroke="#f8f8f8" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/><path d="M19 15v3a2 2 0 0 1-2 2H6a2 2 0 0 1-2-2V7a2 2 0 0 1 2-2h3" stroke="#f8f8f8" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"/></g></svg>
          
          </div>
          
          
        </ion-toolbar>    
    </ion-header>

    <ion-content>
      <ion-card>

       
      <p class="details">
        <ul>
          Name :
        </ul>
        <ul>
         
        </ul>
      </p>

      <p class="details">
        <ul>
          Email :
        </ul>
        <ul>
          
        </ul>
      </p>

      <p class="details">
        <ul>
          Password :
        </ul>
        <ul>
          
        </ul>
      </p>

      
      
       
      </ion-card>
    </ion-content>
  
  
</ion-page>
  
</template>
<script>
import { 
    IonPage,
    IonContent,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonCard,
    
     } from '@ionic/vue';
import { defineComponent } from 'vue';

export default defineComponent({
    
  components: { 
    IonPage,
    IonContent,
    IonHeader,
    IonToolbar,
    IonTitle,
    IonCard,
    
     
    }
  
});



</script>

<style scoped>


  ion-header{
    height:28%;
  }

  ion-toolbar{
  --ion-background-color:#FE8A87;
  color:white;
  height: 100%;

  
}

.header{
    display: flex;
    margin-top:2% ;
}

.profileimg{
  text-align: center;
}

  .login{
    font-weight: bold;
  }

p{
    margin: 2% 3%;
    font-size: 16px;
}

.details{
  display: flex;
} 
 
 
</style>


