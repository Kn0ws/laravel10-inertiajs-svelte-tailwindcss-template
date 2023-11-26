### テンプレートについて
Laravel10アプリケーション上にInertiaJS, Svelte, TailwindCSSを設定したテンプレート

### インストール手順

1. `cp .env.example .env`
2. `composer install`
3. `php artisan key:generate`
4. `yarn install`
5. `yarn run build`
   ホットリロードする為、別コンソールで以下を実行
6. `php artisan serve`
