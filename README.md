# fiarahamiasa

## Installation du projet Laravel 11 + Vue.js 3 + TypeScript + Bun

### Prérequis

Avant de commencer, assure-toi d'avoir installé **Bun** et PHP 8.2+ (nécessaire pour Laravel 11) :
```sh
curl -fsSL https://bun.sh/install | bash
```

Vérifie l'installation :
```sh
bun -v
php -v  # Assurez-vous d'avoir PHP 8.2 ou plus
```

### Installation du projet

1. **Cloner le projet**
```sh
git clone <repo_url>
cd <nom_du_projet>
```

2. **Installer les dépendances PHP**
```sh
composer install
```

3. **Installer les dépendances front-end avec Bun**
```sh
bun install
```

4. **Installer Vue.js et les plugins nécessaires**
```sh
bun add vue
bun add -d @vitejs/plugin-vue typescript vue-tsc @vue/runtime-core
```

5. **Lancer le projet**

### Démarrer le serveur Laravel
```sh
php artisan serve
```

### Lancer le serveur Vite avec Bun
```sh
bun run dev
```
