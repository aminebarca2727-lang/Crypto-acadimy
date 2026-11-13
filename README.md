# Crypto Academy — projet Flutter

Application Android éducative en français, thème noir futuriste / bleu électrique.

## Fonctionnalités incluses
- Accueil et progression (session locale en mémoire)
- 20 leçons de sensibilisation aux cryptoactifs
- Mini-quiz pédagogique
- Graphique entièrement fictif dessiné dans l'application
- Simulateur avec solde fictif de départ de 10 000 $
- Historique de simulations pendant la session

## Important
Cette version est un prototype pédagogique. Elle ne récupère aucun cours en direct, ne stocke pas les données après fermeture, ne connecte aucun portefeuille et ne passe aucun ordre réel. Le bouton de simulation utilise des variations fictives pour illustrer l'interface, pas pour représenter un marché.

## Ouvrir le projet
Ce dossier contient le code source Flutter minimal. Pour générer un APK, il faut un environnement Flutter/Android SDK (ordinateur ou service de compilation cloud). Sur un téléphone seul, l'éditeur FlutterFlow peut être plus pratique, mais ce code n'est pas un projet FlutterFlow importable directement.

1. Installer Flutter et Android Studio sur un ordinateur.
2. Dans un terminal : `flutter create crypto_academy`
3. Remplacer `lib/main.dart` par le fichier `lib/main.dart` fourni ici.
4. Remplacer `pubspec.yaml` par celui fourni ici.
5. Dans le dossier du projet : `flutter pub get`
6. Tester : `flutter run`
7. Générer un APK : `flutter build apk --release`
8. APK attendu : `build/app/outputs/flutter-apk/app-release.apk`

## Évolutions avant publication
- Persistance locale des progrès et du portefeuille simulé
- Authentification facultative et politique de confidentialité
- Tests sur plusieurs tailles d'écran
- Accessibilité et localisation
- Revue de sécurité et conformité aux règles Google Play
