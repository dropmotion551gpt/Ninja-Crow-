NINJA CROW BRAND ASSETS
Theme: Midnight navy + antique gold, matching the supplied Ninja Crow game title screen.
Character: original stylized hooded crow-ninja artwork.

FILES
- ninja-crow-app-icon-1024.png : master square app icon
- ninja-crow-logo.png : logo on navy background
- ninja-crow-logo-transparent.png : transparent-background logo
- *.svg : editable vector versions
- android-mipmap/ : Android launcher icon sizes

ANDROID / CAPACITOR
After `npx cap add android`, copy the five mipmap-* folders into:
android/app/src/main/res/
Allow merge/overwrite if prompted. Then run:
npx cap sync android
Build the signed release APK using your GitHub Actions release workflow.

IMPORTANT
This asset pack contains visual assets only. It does not itself change the APK build workflow or create a signing key.
