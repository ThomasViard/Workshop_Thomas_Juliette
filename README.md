# Workshop_Thomas_Juliette

Objectif: Découvrir Flutter.

**INSTALATION**:

pour installer: https://docs.flutter.dev/get-started/install

**PROJET**: Créez une application Flutter avec authentification à l'aide de firebase.

**Etape 1: Initialisation**

0- Installez Android Studio et accepter tous ce qui y sera demandé.

1- Ouvrez votre terminal ou votre invite de commandes et créez un nouveau dossier pour votre projet.​

2- Rendez-vous sur https://firebase.google.com/ où vous créerez un projet. Sous "Lancez-vous en ajoutant Firebase à votre application", cliquez sur le logo flutter et suivez les étapes. Vous pouvez rencontrer un problème dans la localisation du bin flutterfire, ce qui vous empècherai de l'utiliser.

**Etape 2: L'appli**

Tout d'abord il faut savoir que vous pouvez trouver n'importe quel widget sur internet. Si il ne sont pas natifs vous pouvez récuperer des packages sur https://pub.dev/. Il suffit d'effectuer flutter pub get package_name et vous aurez le package qui vous fais envie.

Dans le que je fournis, il y a une interface graphique simple, mais vous êtes libre de la changer

Dans le fichier authenticate_screen.dart, il y'a les methodes d'authentifications qui ne sont pas encore créés, et nous allons le faire dans le fichier authentication.dart

Retourner sur firebase dans la partie authentication, vous pouvez choisir une methode de connexion (sign-in method), et nous commencons avec l'email et le mot de passe
