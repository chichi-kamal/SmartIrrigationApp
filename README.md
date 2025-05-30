# Smart Irrigation - Application Flutter

## Description
Smart Irrigation est une application mobile Flutter pour gérer intelligemment l’irrigation agricole.  
Elle collecte des données de capteurs et permet de contrôler l’arrosage à distance, optimisant la consommation d’eau.

## Prérequis
- Windows 10+ (ou macOS/Linux avec adaptations)
- Git ([https://git-scm.com/](https://git-scm.com/))
- Android Studio (SDK Android et émulateur) : [https://developer.android.com/studio](https://developer.android.com/studio)
- Flutter SDK

## Installation et utilisation

### 1. Installer Flutter SDK sous Windows
- Téléchargez Flutter : https://flutter.dev/docs/get-started/install/windows  
- Extrayez dans `C:\flutter`  
- Ajoutez `C:\flutter\bin` au PATH système (via Variables d’environnement)  
- Redémarrez votre terminal  
- Vérifiez avec `flutter doctor`  
- Acceptez les licences Android : `flutter doctor --android-licenses`

### 2. Cloner le projet et installer les dépendances
```bash
git clone https://github.com/TON-UTILISATEUR/smartirrigation.git
cd smartirrigation
flutter pub get

###Pour lancer l’application en debug
flutter run

###Pour générer une apk
flutter build apk --release
