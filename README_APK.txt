WALL-E / EVE  -  Android app (APK)
==================================
Eta PC chara, shudhu phone-e cholo. Gemini API phone theke shorashori call hoy.

PHONE-E KI KI KAJ KORE
  Chat, voice (mic), 3D WALL-E / EVE, office background, hat nara, sound, weather,
  timer (app khola thakle), notes, routine, file/docx/chobi toiri, Word/PPT/Excel poRa.
PHONE-E KAJ KORE NA
  PC command (open notepad, battery, screenshot, run command). Character voice effect
  (robot voice) nai: phone-er nijer voice bole.

APK BANANOR 2TA UPAY
-----------------------------------------------------------
UPAY A: GitHub diye (PC-te kichu install lagbe na)
  1. github.com-e free account, notun private repository banan.
  2. Ei folder-er shob file (node_modules chara) repository-te upload korun
     ("Add file" > "Upload files"). .github folder-ta-o dite hobe.
  3. Repository-r "Actions" tab > "Build APK" > build shesh hole
     "WallE-apk" artifact download korun (zip), bhitore app-debug.apk.
  4. APK phone-e pathan, tap kore install korun ("Install unknown apps" allow korte hobe).

UPAY B: Android Studio diye
  1. Android Studio install korun.  2. File > Open > ei folder-er "android" folder.
  3. Gradle sync shesh hole  Build > Build Bundle(s)/APK(s) > Build APK(s).
  4. app-debug.apk ta android/app/build/outputs/apk/debug/ folder-e pabena.

PROTHOM BAR CHALANO
  * App khulle Gemini API key chabe: aistudio.google.com/apikey theke free key niye paste korun.
    Key shudhu phone-e thake. Pore bodlate bottom bar-er "Key" button.
  * Mic permission "Allow" korun. Start chapun, tarpor character-e tap korle sunbe.
  * Bangla bolte "EN" button chepe BN korun. Phone-e Bangla voice thaka chai
    (Settings > Text-to-speech output).
  * Mouse-er bodole angul diye drag korle character ghure.

CHARACTER BODLATE: www/assets/ er walle.glb, eve.glb, office.glb bodle nin
(same nam), tarpor abar build korun.
