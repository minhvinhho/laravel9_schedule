# project setup
01. `composer install`
02. `cp .env.example .env`
03. `php artisan key:generate`
04. `php artisan migrate`
05. `php artisan db:seed`
06. `php artisan storage:link`
07. `php artisan serve`
08. `npm install`
09. `npm run dev`

# clear up
01. `php artisan config:cache`
02. `php artisan cache:clear`
03. `php artisan route:clear`
04. `php artisan view:clear`
05. `composer dump-autoload`

# fix error SSL
`set NODE_OPTIONS=--openssl-legacy-provider`

# check routes
`php artisan optimize`
