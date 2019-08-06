sudo apt-get install php-common php-mbstring php-xml php-zip php-curl
//adding path laravel
composer global config bin-dir —absolute
export PATH="/path/to/composer/bin:$PATH"
source ~/.bashrc
//settings laravel
php artisan key:generate
php artisan make:auth
php artisan preset none
php artisan preset vue
//tailwindcss
npm install vue-router tailwindcss —save-dev