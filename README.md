# ApplyBridge Android starter

Projet Android compilable par GitHub Actions. L'application embarque une première interface web dans `app/src/main/assets/index.html` via WebView.

## GitHub
Pousse tout le dossier dans un dépôt GitHub. Le workflow `.github/workflows/build-apk.yml` compile automatiquement `app-debug.apk` et le publie dans les Artifacts de l'exécution.

## V3 production
Ce projet est le socle Android. Pour les services V3 complets, il faudra ensuite connecter Supabase/Auth/Storage, une API IA côté serveur, parsing PDF/DOCX, paiements Stripe/Paddle, notifications, emails et analytics. Les clés privées ne doivent jamais être embarquées dans l'APK.
