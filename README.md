# MyCordovaApp

$ng new myCorovaApp
$ng build --prod

$Cordova create mobile
$cd mobile
/mobile $Cordova platform add android
/mobile $ Cordova run android

index.html 
Add . in href like below
<base href="./">

Add Cordova link in the body
<script type="text/javascript" src="cordova.js"></script>

$ng build --prod

Angular.json
"architect" node, change the following from - to

"outputPath": "dist/myCordovaApp",
"outputPath": "dist",

$ng build --prod

Now go to /mobile/www folder 
Delete folders css, img, js and index.html file

Copy all files from Dist and copy it to /mobile/www

Connect your mobile and run below command

/mobile $ Cordova run android
