# Invoice Ninja
## Simple, Intuitive Invoicing

### Live demo: [http://sketch-out.com/ninja/public/](http://sketch-out.com/ninja/public/)
### Introduction

Most online invoicing sites are expensive. They shouldn't be. The aim of this project is to provide a free, open-source alternative. Additionally, the hope is this codebase will serve as a sample site for Laravel as well as other JavaScript technologies. 

If you'd like to get involved please send an email to hillelcoren at gmail.

### Features
* Core application built using Laravel 4
* Invoice PDF generation directly in the browser
* Integrates with many payment providers

### Remaining Work
* Recurring invoices
* Internationalization
* Home dashboard
* Reports

### Steps to setup

Clone the Github project

    git clone git@github.com:hillelcoren/invoice-ninja.git ninja

Install packages using Composer

    cd ninja
    composer install

Configure config/database.php and then initialize the database

    php artisan migrate
    php artisan db:seed


### Frameworks/Libraries
* [laravel/laravel](https://github.com/laravel/laravel) - A PHP Framework For Web Artisans
* [twbs/bootstrap](https://github.com/twbs/bootstrap) - Sleek, intuitive, and powerful front-end framework for faster and easier web development.
* [patricktalmadge/bootstrapper](https://github.com/patricktalmadge/bootstrapper) - Laravel Twitter Bootstrap Bundle
* [danielfarrell/bootstrap-combobox](https://github.com/danielfarrell/bootstrap-combobox) - A combobox plugin 
* [jquery/jquery](https://github.com/jquery/jquery) - jQuery JavaScript Library
* [eternicode/bootstrap-datepicker](https://github.com/eternicode/bootstrap-datepicker) - A datepicker for @twitter bootstrap
* [jquery/jquery-ui](https://github.com/jquery/jquery-ui) - The official jQuery user interface library
* [knockout/knockout](https://github.com/knockout/knockout) - Knockout makes it easier to create rich, responsive UIs with JavaScript
* [rniemeyer/knockout-sortable](https://github.com/rniemeyer/knockout-sortable) - A Knockout.js binding to connect observableArrays with jQuery UI sortable functionality
* [MrRio/jsPDF](https://github.com/MrRio/jsPDF) - Generate PDF files in JavaScript. HTML5 FTW.
* [FortAwesome/Font-Awesome](https://github.com/FortAwesome/Font-Awesome) - The iconic font designed for Bootstrap that works with twitter bootstrap
* [jasonlewis/basset](https://github.com/jasonlewis/basset) - A better asset management package for Laravel
* [Zizaco/confide](https://github.com/Zizaco/confide) - Confide is a authentication solution for Laravel 4
* [Anahkiasen/former](https://github.com/Anahkiasen/former) - A powerful form builder, for Laravel and other frameworks (stand-alone too)
* [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) - Laravel debugbar
* [DataTables/DataTables](https://github.com/DataTables/DataTables) - Tables plug-in for jQuery
* [Chumper/Datatable](https://github.com/Chumper/Datatable) - This is a laravel 4 package for the server and client side of datatables
* [omnipay/omnipay](https://github.com/omnipay/omnipay) - A framework agnostic, multi-gateway payment processing library for PHP 5.3+
* [Intervention/image](https://github.com/Intervention/image) - PHP Image Manipulation