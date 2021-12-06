# ionic-sqlite-app - Plugin de cordova

git clone https://github.com/josefandino/ionic-sqlite-app.git

# ingresar a la carpeta
cd ionic-sqlite-app

# instalar las libririas
npm i

# Agregar cordova

### Se debe tener instalado android Studio, ya que este plugin no funciona en el navegador

### Para agregar la platforma de cordova en el proyecto pude utilizar los siguientes comandos:
ionic build --prod
ionic cordova run android

ionic cordova platform add android

ionic cordova resources --force
ionic cordova build android

### Para correr el proyevto en Android Studio
ionic cordova run android 

### Si le diice que tiene instalado capacitor, puede utilizar esta línea  de comandos:
ionic integrations disable capacitor

## Si llegas a tener una duda, me pudes escribir:




