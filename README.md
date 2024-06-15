# Theme Wordpress - Blog (La Minute De Code)

Ce repository contient un thème WordPress développé en PHP. Il comprend trois dossiers principaux :
1. `static` : Développement du thème en HTML, CSS et JavaScript.
2. `integration` : Intégration du thème avec WordPress en PHP.
3. `childtheme` : Thème enfant.

## Contenu du Repository

### Static
Ce dossier contient tous les fichiers statiques (HTML, CSS, JavaScript) utilisés pour développer le thème avant l'intégration avec WordPress.

### Integration
Ce dossier contient l'intégration du thème statique avec WordPress en utilisant PHP. Vous y trouverez les fichiers de template WordPress, les fonctions PHP, et les hooks nécessaires pour faire fonctionner le thème avec WordPress.

### Childtheme
Ce dossier contient le thème enfant, permettant de personnaliser le thème parent sans modifier directement ses fichiers.

## Installation

1. Clonez ce repository :
    ```bash
    git clone https://github.com/votre-utilisateur/MonThèmeWordPress.git
    ```
2. Copiez les dossiers `integration` et `childtheme` dans le répertoire `wp-content/themes` de votre installation WordPress.
3. Activez le thème parent (dossier `integration`) puis le thème enfant (dossier `childtheme`) depuis l'interface d'administration de WordPress.

## Utilisation

Vous pouvez maintenant utiliser et personnaliser votre thème WordPress comme bon vous semble. Pour toute modification majeure, il est recommandé de le faire dans le thème enfant.

## Contribuer

Les contributions ne sont actuellement pas acceptées car ce repository est destiné à un usage spécifique dans le cadre de la formation "Développer un thème avec WordPress de A à Z" sur [laminutedecode.com](https://laminutedecode.com).

## Licence

Ce projet est la propriété de LaMinuteDeCode. Il est strictement interdit de copier ou de vendre ce thème. Voir le fichier `LICENSE` pour plus de détails.
