# bootcamp2017santacruz
Pasos para hacer funcionar aplicaciones con Angular 4

Pre Requisitos
 # 1 nodej:v6.10.0
 https://nodejs.org/dist/v6.10.0/
 # 2 Angular cli: 1.2.4 
  npm install --g @angular/cli@1.2.4
 # 3 Ionic 
 npm install -g ionic cordova
 # 4 Gradle 3.5
   https://gradle.org/releases/ 
   
   *pasos para configurar gradle 
   
     https://ionicframework.com/docs/developer-resources/platform-setup/windows-setup.html 
     https://ionicframework.com/docs/developer-resources/platform-setup/mac-setup.html 
 
 ***************************************
 # Herramienta de desarrollo
 # visual code
        https://code.visualstudio.com/download
 
 # PASOS PARA CREAR UN PROYECTO WEB CON ANGULAR CLI
 
 # *Crear proyecto
        ng new nombreproyecto

 # *Compilar
        ng build 

 # *Ejecutar proyecto
        ng serve
        ng serve --port 1234
 
 # PASOS PARA CREAR UN PROYECTO IONIC CON ANGULAR 4
 
   # *Crear proyecto
      ionic start nombreproyecto

   # *Compilar
     ionic build

   # * Ejecutar proyecto
      ionic serve
      ionic serve  lab android
 
 # * Adicionar plataforma  android  / ios
   ionic cordova platform add android	  
   ionic cordova platform add ios	
 
 # * compilar por plataforma
   ionic cordova build android  
   ionic cordova build ios
 
 # *ejecutar en un dispotivo android
   ionic cordova run android --device 
 
 
 ***************************************
 # *Paso  para ejecutar los demos
   npm install
   
  # *Adicionales 
    Ionic=>  https://ionicframework.com  
    Angular=> https://angular.io/

