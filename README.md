# laravel-vue 
This repository contains a full-stack scaffolding project using Laravel for the backend and Vue.js for the frontend. It's designed to provide a robust starting point for web applications that require a dynamic, reactive frontend powered by Vue.js, alongside the powerful features of the Laravel framework.


## Installation

1. Install laravel
```bash
composer create-project laravel/laravel example-app
```

2. Install laravel ui

```bach
composer require laravel/ui
```

3. Install vue 
```bash
php artisan ui vue
```

- INFO  Vue scaffolding installed successfully.

- WARN  Please run [npm install && npm run dev] to compile your fresh scaffolding.

4. install npm
```bash
npm install
```

5. To check
```bash
npm run dev
```

5.1 inside the body tab of welcome.blade.php
```html
<div id="app">
    <example-component></example-component>
</div>
```
for load the example component of vue js.

5.3 inside the head tag
```bash
@vite(['resources/js/app.js', 'resources/css/app.css']);
```


### Congratulations you are successfully scafolding
