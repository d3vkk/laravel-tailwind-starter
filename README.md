# Laravel 7 + Tailwind CSS Template

![Laravel + Tailwind Logo](https://github.com/d3vkk/laravel+tailwind-template/blob/master/laravel+tailwind-logo.png)

Laravel 7 + Tailwind CSS Template. With zero bloat dependencies

[What is Laravel?](https://laravel.com/)

[What is Tailwind CSS?](https://tailwindcss.com/)

## Set up

```
git clone https://github.com/d3vkk/laravel+tailwind-template.git
```

Install dependencies with npm
```
npm install
```

Or yarn
```
yarn install
```

Compile the css file
```
npm run dev
```

Link the css file a blade file e.g. `resources/views/welcome.blade.php`
```php
<link href = {{ asset('css/main.css') }} rel = "stylesheet" />
```

© 2020 Donald K • Under MIT License