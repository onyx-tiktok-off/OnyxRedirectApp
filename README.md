# OnyxRedirectApp

Application Android qui ouvre automatiquement :  
https://onyx-tiktok-off.github.io/OnyxBudgetV2/

## Utilisation

1. Extraire le ZIP à la racine de ton dépôt GitHub.
2. Commit + push.
3. Va dans l’onglet **Actions** du repo.
4. Télécharge l’APK généré dans les artifacts.

## Build local

- Ouvrir avec Android Studio (JDK 17).
- Lancer `Run > Run 'app'`.

## Personnalisation

- L’URL est dans `MainActivity.kt` (variable `startUrl`).
- Icônes modifiables dans `app/src/main/res/mipmap-*`.
