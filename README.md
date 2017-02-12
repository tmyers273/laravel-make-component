# laravel-make-component

The `php artisan make:component` you didn't know you were missing.

The package will create a new .vue file for you, based off a template. It will then proceed to register the component using the common snake case convention in the root Vue instance.

I originally created this package in order to help streamline my Laravel & Vue workflow. Having to break flow to type out boilerplate was having a major impact on my productivity. So the laravel-make-comonent package was born!

# Usage

1. `php artisan make:component`  
1. There is no step 2

# Config

In `/config/components.php` by default:

```json
{
  
  componentTemplate: '/resources/views/layousts/component.vue',

  entryPoint: '/resources/js/app.js',
  
  email: 'tmyers273@gmail.com',
  
  author: 'Tom M'
  
}
```
