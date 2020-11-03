Awesome Laravel
===============

A curated list of delightful [Laravel](http://laravel.com/) PHP framework [packages](#packages) and [resources](#resources).  Inspired by other [awesome lists](https://github.com/bayandin/awesome-awesomeness).

## Table of Contents

- [Essentials](#essentials)
- [Packages](#packages)
- [Popular Packages](#popular-packages)
- [Development Setup](#development-setup)
- [Application Hosting](#application-hosting)
- [Application Deployment](#application-deployment)
- [Code Snippets](#code-snippets)
- [Tutorials & Blogs](#tutorials--blogs)
- [Videos](#videos)
- [Conferences](#conferences)
- [Books](#books)
- [Starter Projects](#starter-projects)
- [Codebases for Reference](#codebases-for-reference)
- [Content Management Systems](#content-management-systems)
- [Podcasts](#podcasts)
- [Community](#community)
- [Jobs](#jobs)
- [Hosted Development Tools](#hosted-development-tools)
- [Miscellaneous](#miscellaneous)     
     
## Essentials

* [Laravel](https://laravel.com) ([Documentation](https://laravel.com/docs))
* [Laravel API Reference](https://laravel.com/api/master/)
* [Lumen](https://lumen.laravel.com) ([Documentation](https://lumen.laravel.com/docs))
* [Laracasts](https://laracasts.com)
* [Laravel News](https://laravel-news.com) ([Archive](https://laravel-news.com/archive/))

## Packages

* [Packagist](https://packagist.org/)
* [Laravel Collective](https://laravelcollective.com/)
* [Packalyst](http://packalyst.com/)
* [Spatie](https://spatie.be/en/opensource/laravel)

## Popular Packages

> This is a list of well-documented, tested packages that are frequently used in Laravel projects. If you're looking for an exhaustive list of PHP packages, then check out the Package Repositories mentioned above.

##### Developer Tools

* [Scaffold Interface](https://github.com/amranidev/scaffold-interface) - A Smart CRUD Generator For Laravel
* [IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - Generates a helper file for IDE auto-completion
* [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) - Extends built-in file generators
* [Laravel API/Scaffold/CRUD Generator](https://github.com/InfyOmLabs/laravel-generator) - Generator for APIs, CRUD scaffolds etc.
* [Laravel Tinx](https://github.com/furey/tinx) - Reload your Laravel Tinker session from inside Tinker
* [Laravel API Documentation Generator](https://github.com/mpociot/laravel-apidoc-generator) - Automatically generate your API documentation
* [Laravel Packager](https://github.com/Jeroen-G/Laravel-Packager) - A CLI tool for creating Laravel packages
* [Workbench Export to Migrations](https://github.com/beckenrode/mysql-workbench-export-laravel-5-migrations) - Workbench plugin for exporting Models to Laravel migrations
* [Laravel Decomposer](https://github.com/lubusIN/laravel-decomposer) - List all installed packages, their dependencies, app & server details
* [LaRecipe](https://github.com/saleem-hadad/larecipe) - Write gorgeous documentations for your products using Markdown inside your Laravel app.
* [Prequel](https://github.com/Protoqol/Prequel/) - A clear and concise database management GUI tweaked for Laravel.

##### Testing & Debugging

* [Laravel TestTools](https://chrome.google.com/webstore/detail/laravel-testtools/ddieaepnbjhgcbddafciempnibnfnakl) - Chrome extension to generate Laravel integration tests while using your app
* [Laravel Test Factory Generator](https://github.com/mpociot/laravel-test-factory-helper) - Generate Laravel test factories from your existing models
* [Clockwork](https://github.com/itsgoingd/clockwork) - Integrates Clockwork Chrome extension for debugging and profiling apps
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates PHP Debug Bar with Laravel
* [Ignition](https://github.com/facade/ignition) - A beautiful error page for Laravel apps
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log viewer
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - Provides a log viewer
* [LERN](https://github.com/tylercd100/lern#lern-laravel-exception-recorder-and-notifier) - Record exceptions into a database and will send you a notification
* [Mail Preview](https://github.com/themsaid/laravel-mail-preview) - Preview sent mail in a web browser or mail client
* [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - A Laravel Package to integrate Nette Tracy Debugger
* [Laravel Terminal](https://github.com/recca0120/laravel-terminal) - run artisan in a web browser
* [Laravel API Tester](https://github.com/asvae/laravel-api-tester) - Postman-like tool with Laravel routes
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command
* [Laravel Telescope](https://github.com/laravel/telescope) - Laravel Telescope is an elegant debug assistant for the Laravel framework

##### Authentication & Authorization

* [Bouncer](https://github.com/JosephSilber/bouncer) - Roles & Permissions
* [Laratrust](https://github.com/santigarcor/laratrust) - Roles, Permissions and teams
* [Entrust](https://github.com/Zizaco/entrust) - Role-based Permissions
* [JWT Auth](https://github.com/tymondesigns/jwt-auth) - JSON Web Token authentication for APIs
* [Laravel Permission](https://github.com/spatie/laravel-permission) - Associate users with roles and permissions
* [Defender](https://github.com/artesaos/defender) - Roles & Permissions
* [OAuth2 Server Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - OAuth 2.0 authorization server and resource server
* [Socialite](https://github.com/laravel/socialite) - OAuth authentication with Facebook, Google, Twitter etc.
* [Socialite Providers 2.0](http://socialiteproviders.github.io/) - 100+ social authentication providers for Socialite with Lumen support
* [Google2FA](https://github.com/antonioribeiro/google2fa) - Google Two-Factor Authentication Module
* [Laravel User Verification](https://github.com/jrean/laravel-user-verification) - Handle the user verification flow and validate email
* [Adldap2 Laravel](https://github.com/Adldap2/Adldap2-Laravel) - LDAP authentication and Active Directory management
* [Doorman](https://github.com/clarkeash/doorman) - Limit access to your Laravel applications by using invite codes
* [Laravel Heyman](https://github.com/imanghafoori1/laravel-heyman) - Heyman continues where the above role-permission packages left off

##### Utilities

* [Awes.io](https://github.com/awes-io/awes-io) - boilerplate for CRM, SaaS, ERP based on Vue (Nuxt.js), TailwindCSS plus Laravel as a backend.
* [Artisan View](https://github.com/svenluijten/artisan-view) - Manage the views in Laravel projects via artisan
* [Bootstrapper](https://github.com/patricktalmadge/bootstrapper/) - Set of classes to create Bootstrap 3 markup
* [Captcha](https://github.com/mewebstudio/captcha) - An anti-bot image captcha system
* [Charts](https://github.com/ConsoleTVs/Charts) - Multi-library chart package to create interactive charts
* [Lavacharts](https://github.com/kevinkhill/lavacharts) - Charts and Graphs for PHP Powered by the Google Chart API
* [Eloquent Filter](https://github.com/Tucker-Eric/EloquentFilter) - Filter models and their Relationships
* [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Create slugs for Eloquent models
* [Eloquent Sortable](https://github.com/spatie/eloquent-sortable) - Sortable behaviour for Eloquent models
* [HTML](https://github.com/LaravelCollective/html) - HTML and Form Builders for Laravel
* [Multi-tenant](https://github.com/hyn/multi-tenant) - Flexible multi tenancy with secure separation of routes, assets and databases
* [Laravel Form Builder](https://github.com/kristijanhusak/laravel-form-builder) - Form builder inspired by Symfony's form builder
* [Laravel Activitylog](https://github.com/spatie/laravel-activitylog) - Log activity inside your Laravel app
* [Laravel Auditing](https://github.com/owen-it/laravel-auditing) - Audit for Eloquent models
* [Laravel Breadcrumbs](https://github.com/davejamesmiller/laravel-breadcrumbs) - Create and manage breadcrumbs
* [Laravel Collection Macros](https://github.com/spatie/laravel-collection-macros) - A set of handy collection macros
* [Laravel Cookie Consent](https://github.com/spatie/laravel-cookie-consent) - Make your Laravel app comply with the crazy EU cookie law
* [Laravel Datatables](https://github.com/yajra/laravel-datatables) - jQuery DataTables API
* [Laravel GeoIP](https://github.com/Torann/laravel-geoip) - Determine the location of website visitors based on their IP addresses
* [Laravel Hashids](https://github.com/vinkla/laravel-hashids) - Generate unique, non-sequential ids using [Hashids](http://hashids.org/php/)
* [Laravel Impersonate](https://github.com/404labfr/laravel-impersonate) - A package to authenticate as one of your users
* [Laravel Mailbox](https://github.com/beyondcode/laravel-mailbox) - A package to handle incoming emails
* [Laravel Markdown](https://github.com/GrahamCampbell/Laravel-Markdown) - CommonMark markdown parser
* [Laravel Menu](https://github.com/spatie/laravel-menu) - Html menu generator for Laravel
* [Laravel Talk](https://github.com/nahid/talk) - Realtime User messaging system
* [Laravel Messenger](https://github.com/cmgmyr/laravel-messenger) - User messaging system
* [Laravel Moderation](https://github.com/hootlex/laravel-moderation) - Approve or reject resources like posts, comments, users, etc.
* [Laravel Tags](https://github.com/spatie/laravel-tags) - Add tags and taggable behaviour
* [Laravel Stats Tracker](https://github.com/antonioribeiro/tracker) - Gather information from requests to identify and store
* [Listify](https://github.com/lookitsatravis/listify) - Add sorting/ordering capabilities to any Eloquent model
* [noCAPTCHA](https://github.com/ARCANEDEV/noCAPTCHA) - Helper for Google's new noCAPTCHA (reCAPTCHA)
* [Purifier](https://github.com/mewebstudio/purifier) - HTML filter
* [Revisionable](https://github.com/VentureCraft/revisionable) - Create a revision history for Eloquent models
* [SEOTools](https://github.com/artesaos/seotools) - Helpers for some common SEO techniques
* [Page Cache](https://github.com/JosephSilber/page-cache) - Caches responses as static files on disk for lightning fast page loads
* [Laravel Setting](https://github.com/anlutro/laravel-settings) - Persistent configuration settings that are stored in JSON files
* [Friendship](https://github.com/hootlex/laravel-friendships) - Friendship management system
* [Teamwork](https://github.com/mpociot/teamwork) - User to team associations with an invite system
* [Validating](https://github.com/dwightwatson/validating) - Trait for validating Eloquent models
* [VAT Calculator](https://github.com/mpociot/vat-calculator) - Handle all the hard stuff related to EU MOSS vat regulations
* [Laravel UUID](https://github.com/webpatser/laravel-uuid) - Generate a UUID according to the RFC 4122 standard
* [Laravel Installer](https://github.com/RachidLaasri/LaravelInstaller) - Allow users to install your application just by following the setup wizard, like WordPress
* [Laravel Modules](https://github.com/nWidart/laravel-modules) - Easy module management
* [Laravel Phone](https://github.com/Propaganistas/Laravel-Phone) - Phone number validator and formatter
* [Laravel Ban](https://github.com/cybercog/laravel-ban) - Simplify blocking and banning Eloquent models
* [Laravel Proxy](https://github.com/fideloper/TrustedProxy) - Handling sessions when behind load balancers or other intermediaries.
* [Laravel Video Chat](https://github.com/PHPJunior/laravel-video-chat) - Video Chat using Socket.IO and WebRTC
* [Widgets for Laravel](https://github.com/arrilot/laravel-widgets) - A powerful alternative to view composers.
* [Secure Headers](https://github.com/BePsvPT/secure-headers) - Add security related headers to HTTP response
* [Laravel Nova](https://nova.laravel.com/) - Nova is a beautifully designed administration panel for Laravel
* [Laravel Love](https://github.com/cybercog/laravel-love) - It lets people express how they feel about the content. React on Eloquent models with Likes or Dislikes.
* [stancl/tenancy](https://github.com/stancl/tenancy) - Automatic tenancy for your Laravel app. No code changes needed.

##### Media & Document Management

* [Intervention Image](https://github.com/Intervention/image) - Image handling library for creating, editing and composing images
* [Laravel ImageUp](https://github.com/qcod/laravel-imageup) - Yet another image manipulation package, adds tons of extra functionality
* [Laravel Glide](https://github.com/spatie/laravel-glide) - Easily convert images with Glide
* [Laravel MediaLibrary](https://github.com/spatie/laravel-medialibrary) - Associate files with Eloquent models
* [Laravel Snappy](https://github.com/barryvdh/laravel-snappy) - HTML to PDF generator using wkhtmltopdf
* [Laravel DOMPDF](https://github.com/barryvdh/laravel-dompdf) - HTML to PDF generator using [dompdf](https://github.com/dompdf/dompdf)
* [Laravel Stapler](https://github.com/CodeSleeve/laravel-stapler) - ORM-based file upload manager
* [Laravel Excel](https://github.com/Maatwebsite/Laravel-Excel) - Import and export Excel and CSV files
* [Fast Excel](https://github.com/rap2hpoutre/fast-excel) - Fast XLSX, CSV and ODT import and export for Laravel
* [Laravolt Avatar](https://github.com/laravolt/avatar) - Plug n play avatar, turn name, email, and any other string into beautiful avatar (or gravatar), effortless.
* [Laravel FFmpeg](https://github.com/pascalbaljetmedia/laravel-ffmpeg) - This package provides an integration with FFmpeg for Laravel 5.8.

##### Integration with Javascript

* [Laroute](https://github.com/aaronlord/laroute) - Generate Laravel route URLs from JavaScript
* [PHP Vars to JavaScript Transformer](https://github.com/laracasts/PHP-Vars-To-Js-Transformer) - Pass server-side string/array/collection/whatever to JavaScript
* [Javascript Validation](https://github.com/proengsoft/laravel-jsvalidation) - Use validation rules, messages, FormRequest and validators to validate forms in client-side
* [Laravel Pjax](https://github.com/spatie/laravel-pjax) - A Pjax middleware
* [Laravel Blade Javascript](https://github.com/spatie/laravel-blade-javascript) - A Blade directive to export variables to JavaScript
* [Ziggy](https://github.com/tightenco/ziggy) - Use your Laravel named routes in JavaScript
* [LiveWire](https://github.com/livewire/livewire) - A magical front-end framework for Laravel

##### Databases, ORMs, Migrations & Seeding

* [Backup Manager](https://github.com/backup-manager/laravel) - Backup and restore databases from S3, Dropbox, SFTP etc.
* [Laravel Nestedset](https://github.com/lazychaser/laravel-nestedset) - Nested Sets pattern implementation
* [ClosureTable](https://github.com/franzose/ClosureTable) - Closure table pattern implementation
* [Eloquence](https://github.com/kirkbushell/eloquence) - Extra features for Eloquent models
* [iSeed](https://github.com/orangehill/iseed) - Generate a new seed file from an existing database table
* [Laravel OCI8](https://github.com/yajra/laravel-oci8) - Oracle DB driver via OCI8
* [Laravel Backup](https://github.com/spatie/laravel-backup) - Backup your app
* [Laravel Doctrine](https://github.com/laravel-doctrine/orm) - Doctrine 2 ORM implementation
* [Laravel MongoDB](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder with support for MongoDB
* [Migrations Generator](https://github.com/Xethron/migrations-generator) - Generate migrations from an existing database
* [Sofa/Eloquence](https://github.com/jarektkaczyk/eloquence) - Extensions for the Eloquent ORM
* [Tenanti](https://github.com/orchestral/tenanti) - Multi-tenant database schema manager
* [Laravel Repository](https://github.com/andersao/l5-repository) - Repositories to abstract the database layer
* [Lada Cache](https://github.com/spiritix/lada-cache) - A Redis based, fully automated and scalable database cache layer
* [Laravel MySQL Spatial extension](https://github.com/grimzy/laravel-mysql-spatial) - easily work with MySQL Spatial Data Types and MySQL Spatial Functions

##### Search

* [Algolia Search](https://github.com/algolia/algoliasearch-laravel) - Integrates the Algolia Search API to the Laravel Eloquent ORM
* [Elasticquent](https://github.com/elasticquent/Elasticquent) - Elasticsearch for Eloquent models
* [Plastic](https://github.com/sleimanx2/plastic) - Fluently mapping and searching Elasticsearch
* [Laravel Search](https://github.com/mmanos/laravel-search) - Unified API for Elasticsearch, Algolia, and ZendSearch
* [SearchIndex](https://github.com/spatie/searchindex) - Store and retrieve objects from Algolia or Elasticsearch
* [Searchable](https://github.com/nicolaslopezj/searchable) - Trait that adds a simple search function to Eloquent models
* [TNTSearch](https://github.com/teamtnt/tntsearch) - A fully featured full text search engine written in PHP
* [TNTSearch driver](https://github.com/teamtnt/laravel-scout-tntsearch-driver) - Driver for [Laravel Scout](https://github.com/laravel/scout) search package based on TNTSearch
* [Laravel-Searchy](https://github.com/TomLingham/Laravel-Searchy) - Fuzzy search, basic string matching, Levenshtein Distance

##### APIs

* [ApiGuard](https://github.com/chrisbjr/api-guard) - Allow API authentication with API keys
* [Dingo API](https://github.com/dingo/api) - Multi-purpose toolkit for developing RESTful APIs
* [Laravel CORS](https://github.com/barryvdh/laravel-cors) - Add CORS (Cross-Origin Resource Sharing) headers support
* [Laravel Fractal](https://github.com/spatie/laravel-fractal) - Output complex, flexible, AJAX/RESTful data structures with Fractal
* [Laravel GraphQL](https://github.com/rebing/graphql-laravel) - Supports Relay, eloquent models, validation and GraphiQL
* [Lighthouse](https://github.com/nuwave/lighthouse) - An up and coming GraphQL library for Laravel
* [Laravel Responder](https://github.com/flugger/laravel-responder) - Build custom API responses with Fractal

##### Tasks, Commands and Scheduling

* [Dispatcher](https://github.com/indatus/dispatcher) - Scheduler for Artisan commands
* [Elixir](https://github.com/laravel/elixir) - Node (NPM) package to run Gulp tasks
* [Mix](https://github.com/JeffreyWay/laravel-mix) - Fluent API for defining basic webpack build steps
* [Envoy](https://github.com/laravel/envoy) - SSH Task Runner

##### Payments

* [Cashier](https://github.com/laravel/cashier) - Subscription billing with Stripe
* [Omnipay for Laravel](https://github.com/ignited/laravel-omnipay) - Integrate the [Omnipay](https://github.com/thephpleague/omnipay) PHP library

##### Optimization

* [Intervention Image Cache](https://github.com/Intervention/imagecache) - Caching extension for the Intervention Image Class
* [Laravel HTMLMin](https://github.com/GrahamCampbell/Laravel-HTMLMin) - Blade/HTML/CSS/javascript minifier
* [Rememberable](https://github.com/dwightwatson/rememberable) - Query caching for Eloquent
* [Widgetize](https://github.com/imanghafoori1/laravel-widgetize) - Page Partial caching
* [Laravel Responsecache](https://github.com/spatie/laravel-responsecache) - Speed up app by caching the entire response

##### Monitoring

* [Horizon](https://github.com/laravel/horizon) - Monitor and configure queues with a simple web UI
* [Laravel Failed Job Monitor](https://github.com/spatie/laravel-failed-job-monitor) - Get notified when a queued job fails
* [Laravel Uptime Monitor](https://github.com/spatie/laravel-uptime-monitor) - A powerful and easy to configure uptime and ssl monitor
* [Larametrics](https://github.com/aschmelyun/larametrics) - A self-hosted metrics and notifications platform for Laravel apps

##### Localization

* [Language Files](https://github.com/caouecs/Laravel-lang) - Validation, Pagination and Reminders language lines in 37 languages
* [Laravel Localization](https://github.com/mcamara/laravel-localization) - Add i18n support via routes
* [Laravel Translatable](https://github.com/spatie/laravel-translatable) - Making Eloquent models translatable by storing translations as JSON
* [Laravel Translatable](https://github.com/dimsav/laravel-translatable) - Retrieve and store translatable Eloquent model instances
* [Laravel Translator](https://github.com/vinkla/laravel-translator) - Translate Eloquent models into multiple languages
* [Laravel Date](https://github.com/jenssegers/date) - A library to help you work with dates in multiple languages, based on Carbon
* [Laravel Langman](https://github.com/themsaid/laravel-langman) - Manage language files from Artisan Console
* [Laravel Translation](https://github.com/waavi/translation) - Translation and localization management
* [Linguist](https://github.com/keevitaja/linguist) - i18n localization support for Laravel

##### Third-party Service Integration

* [Laravel Analytics](https://github.com/spatie/laravel-analytics) - Retrieve pageviews and other data from Google Analytics
* [Laravel DigitalOcean](https://github.com/GrahamCampbell/Laravel-DigitalOcean) - DigitalOceanV2 bridge
* [Laravel GitHub](https://github.com/GrahamCampbell/Laravel-GitHub) - PHP GitHub API bridge
* [Laravel Instagram](https://github.com/vinkla/laravel-instagram) - Instagram API bridge
* [Laravel Newsletter](https://github.com/spatie/laravel-newsletter) - Send newsletters with Mailchimp
* [Laravel Pusher](https://github.com/vinkla/laravel-pusher) - Pusher API bridge

## Development Setup

* [Homestead](https://laravel.com/docs/master/homestead) - Official Vagrant box for Laravel
* [Valet](https://laravel.com/docs/master/valet) - Development environment for Mac users
* [Valet Linux](https://github.com/cpriego/valet-linux) - Development environment for Linux users
* [LaraDock](https://github.com/LaraDock/laradock) - Run Laravel on Docker (Like Homestead but for Docker instead of Vagrant)
* [LaraEdit Docker](https://github.com/laraedit/laraedit-docker) - Homestead environment in a single Docker container
* [Laragon](https://laragon.org/) -  Isolated development environment on Windows
* [Stacker](https://github.com/Maxlab/stacker) - The environment for local web development on Docker
* [Devilbox](https://github.com/cytopia/devilbox) - A dockerized and general-purpose LAMP/MEAN stack for every PHP version
* [Vessel](https://vessel.shippingdocker.com) - Simple Docker development environments for Laravel
* [Lando](https://docs.lando.dev/config/laravel.html) - A local development environment tool built on Docker

## Application Hosting

* [Vapor](https://vapor.laravel.com)
* [Forge](https://forge.laravel.com/) ([ForgeRecipes](https://forgerecipes.com/))
* [FortRabbit](https://www.fortrabbit.com/laravel-hosting)
* [Heroku](https://www.heroku.com/) ([Documentation](https://devcenter.heroku.com/articles/getting-started-with-laravel))
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) ([Tutorial](http://docs.aws.amazon.com/elasticbeanstalk/latest/dg/php-laravel-tutorial.html))
* [Cloudways](https://www.cloudways.com/en/laravel-hosting.php)
* [Ploi](https://ploi.io/)
* [CodePier](https://codepier.io?ref=awesome-laravel)
* [RunCloud](https://runcloud.io/)

## Application Deployment

* [Deployer](https://deployer.org/) - A deployment tool with support for Laravel out of the box
* [Envoyer](https://envoyer.io/) - Zero down-time Deployer for PHP & Laravel projects
* [Rocketeer](https://github.com/rocketeers/rocketeer) - Task runner and deployment package

## Code Snippets

* [Laravel LTS Cheat Sheet ](https://summerblue.github.io/laravel5-cheatsheet/) ([Chinese version](https://cs.phphub.org/))
* [Laravel Tricks](http://laravel-tricks.com/)

## Tutorials & Blogs

* [Taylor Otwell](http://taylorotwell.com/)
* [Tuts+](https://code.tutsplus.com/categories/laravel)
* [Medium](https://medium.com/tag/laravel/latest)
* [Laravel Daily](https://laraveldaily.com/)
* [Scotch](https://scotch.io/tag/laravel)
* [Digital Ocean](https://www.digitalocean.com/community/search?q=laravel&primary_filter=newest&type=tutorials)
* [Matt Stauffer](https://mattstauffer.co/blog)
* [Vegi Bit](https://vegibit.com/tag/laravel/)
* [Neon Tsunami](https://www.neontsunami.com/tags/laravel)
* [Dor.ky](https://dor.ky/tag/laravel/)
* [Stillat](https://stillat.com/explore/categories/laravel-5)
* [Easy Laravel Book Blog](http://www.easylaravelbook.com/blog/)
* [Laraveles](http://laraveles.com/blog/) (ES)
* [Styde](https://styde.net/category/laravel-5/) (ES)
* [Cloudways Laravel Blog](http://cloudways.com/blog/laravel)
* [Laravel Best Practices](https://github.com/alexeymezenin/laravel-best-practices)
* [Pusher Laravel Tutorials](https://pusher.com/tutorials?tag=Laravel)
* [LaraShout](https://larashout.com/)

## Videos

* [Laracasts](https://laracasts.com/)
* [Codecourse](https://www.codecourse.com/) ([YouTube](https://www.youtube.com/user/phpacademy/playlists))
* [Tuts+](http://code.tutsplus.com/categories/laravel/courses)
* [Servers for Hackers](https://serversforhackers.com/laravel-perf)
* [Test-Driven Laravel](https://course.testdrivenlaravel.com/)
* [Duilio Palacios](https://www.youtube.com/user/silencedsg/videos) (ES)
* [CodigoFacilito](https://codigofacilito.com/courses/laravel) (ES)
* [DevDojo](https://devdojo.com/search?value=laravel)
* [Amitav Roy](https://www.youtube.com/channel/UC4gijXR8cM4gmEt9Olse-TQ/videos)
* [Laracademy](https://laracademy.co/)
* [Dev Marketer](https://www.youtube.com/channel/UC6kwT7-jjZHHF1s7vCfg2CA/playlists)
* [Udemy](https://www.udemy.com/courses/search/?q=laravel)
* [Lynda](https://www.lynda.com/search?q=laravel)
* [Pluralsight](https://www.pluralsight.com/search?q=laravel&categories=course)
* [Bitfumes](https://www.youtube.com/bitfumes)
* [ConfidentLaravel](https://confidentlaravel.com/)

## Conferences

* [Laracon US](http://laracon.us/)
* [Laracon EU](http://laracon.eu/)
* [Laracon Online](https://laracon.net/)
* [Laraconf Brasil](http://laraconfbrasil.com.br/)
* [Laracon Australia](https://laracon.com.au/)
* [Laravel Live UK](https://laravellive.uk/)
* [Laravel Live India](https://laravellive.in/)
* [Laravel Nigeria](https://laravelnigeria.com)

##### Videos

* [Laracon EU 2018](https://www.youtube.com/playlist?list=PLMdXHJK-lGoC64wnqvm6v1R5dsuAV-MpS)
* [Laracon US 2018](https://www.youtube.com/playlist?list=PL-yJve--iT5oM2LgF37VXsBb8Os4ZulIc)
* [Laracon EU 2017](https://www.youtube.com/playlist?list=PLMdXHJK-lGoBFZgG2juDXF6LiikpQeLx2)
* [Laracon US 2017](https://www.youtube.com/playlist?list=PL-yJve--iT5oaLQA6OI8TWLVSOBP1qhs3)
* [Laracon EU 2016](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCMkOxqe82hOC8tgthqhHCN)
* [Laracon US 2016](https://www.youtube.com/playlist?list=PL-yJve--iT5o9fH_cRY0u6P751pcF59GK)
* [Laracon EU 2015](https://www.youtube.com/playlist?list=PLMdXHJK-lGoA9SIsuFy0UWL8PZD1G3YFZ)
* Laracon US 2015
* [Laracon EU 2014](https://www.youtube.com/playlist?list=PLMdXHJK-lGoCYhxlU3OJ5bOGhcKtDMkcN)
* [Laracon US 2014](https://www.youtube.com/channel/UCRawXmZv30Vf_MivyPYb_GQ/videos)
* [Laracon EU 2013](https://www.youtube.com/playlist?list=PLMdXHJK-lGoB-CIVsiQt0WU8WcYrb5eoe)
* [Laracon US 2013](https://www.youtube.com/playlist?list=PLkwAlZpjHQbLcox_S_AgGU24QUfKgXayN)

## Books

* [Laravel Starter](https://www.amazon.com/Laravel-Starter-Shawn-McCool-ebook/dp/B00ABFQ0AS) by Shawn McCool
* [Laravel: Code Happy](https://leanpub.com/codehappy) by Dayle Rees
* [Laravel: Code Bright](https://leanpub.com/codebright) by Dayle Rees
* [Laravel: Code Smart](https://leanpub.com/codesmart) by Dayle Rees
* [Laravel: From Apprentice To Artisan](https://leanpub.com/laravel) by Taylor Otwell
* [Laravel 4 Cookbook](https://leanpub.com/laravel4cookbook) by Christopher Pitt and Taylor Otwell
* [Laravel Testing Decoded](https://leanpub.com/laravel-testing-decoded) by Jeffrey Way
* [Refactoring to Collections](https://adamwathan.me/refactoring-to-collections/) by Adam Wathan
* [Implementing Laravel](https://leanpub.com/implementinglaravel) by Chris Fidao
* [Getting Stuff Done with Laravel 4](https://leanpub.com/gettingstuffdonelaravel) by Chuck Heintzelman
* [Laravel Application Development Blueprints](https://www.packtpub.com/web-development/laravel-application-development-blueprints) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Build APIs You Won't Hate](https://leanpub.com/build-apis-you-wont-hate) by Phil Sturgeon
* [Integrating Front end Components with Web Applications](https://leanpub.com/frontend) by Maksim Surguy
* [Laravel Design Patterns and Best Practices](https://www.packtpub.com/web-development/laravel-design-patterns-and-best-practices) by Arda Kılıçdağı and Halil İbrahim Yılmaz
* [Learning Laravel 4 Application Development](https://www.packtpub.com/web-development/learning-laravel-4-application-development) by Hardik Dangar
* [Getting Started with Laravel 4](https://www.packtpub.com/web-development/getting-started-laravel-4) by Raphaël Saunier
* [Laravel Application Development Cookbook](https://www.packtpub.com/web-development/laravel-application-development-cookbook) by Terry Matula
* [Building Web Applications Using Parse REST API](https://leanpub.com/building-web-applications-using-parse-rest-api) by Mhd Zaher Ghaibeh
* [Laravel - My First Framework](https://leanpub.com/laravel-first-framework) by Maksim Surguy
* [Easy Laravel 5](https://leanpub.com/easylaravel/) by W. Jason Gilmore
* [Laravel 5 Essentials](https://www.packtpub.com/web-development/laravel-5-essentials) by Martin Bean
* [Easy E-Commerce Using Laravel and Stripe](https://leanpub.com/easyecommerce) by W. Jason Gilmore and Eric L. Barnes
* [Laravel 5.1 Beauty](https://leanpub.com/l5-beauty) by Chuck Heintzelman
* [Design Patterns with PHP and Laravel](https://leanpub.com/larasign) by Kelt Dockins
* [Mastering Laravel](https://www.packtpub.com/web-development/mastering-laravel) by Christopher John Pecoraro
* [How to Build Real-Time Laravel Apps with Pusher](http://pusher-community.github.io/real-time-laravel/) by Pusher
* [Learning Laravel's Eloquent](https://www.amazon.com/Learning-Laravels-Eloquent-Francesco-Malatesta-ebook/dp/B00YSILQ6C) by Francesco Malatesta
* [Laravel 5 Learn Easy](https://leanpub.com/laravel5learneasy) by Sanjib Sinha
* [Laravel and AngularJS](https://leanpub.com/laravel-and-angularjs) by Daniel Schmitz and Daniel Pedrinha Georgii
* [Laravel Collections Unraveled](https://leanpub.com/laravelcollectionsunraveled) by Jeff Madsen
* [Writing APIs With Lumen](https://leanpub.com/lumen-apis) by Paul Redmond
* [The Laravel Survival Guide](https://leanpub.com/laravelsurvivalguide) by Tony Lea
* [Laraboot: Laravel 5 For Beginners](https://leanpub.com/laravel-5-for-beginners-laraboot) by Bill Keck
* [Laravel 5.4 For Beginners](https://leanpub.com/laravel-5-4-for-beginners) by Bill Keck
* [Laravel Up & Running](https://www.amazon.com/gp/product/1491936088) by Matt Stauffer
* [Laravel Companion](https://leanpub.com/laravelcompanion-secondedition) by Johnathon Koster
* [Deploy Laravel on AWS with CloudFormation](https://leanpub.com/laravel-aws) by Lionel Martin
* [React Native and Laravel for Future Mobile Development](https://leanpub.com/rn_laravel) by Ega Radiegtya
* [Servers for Hackers](https://book.serversforhackers.com) by Chris Fidao
* [Full-Stack Vue.js 2 and Laravel 5](https://www.amazon.com/Full-Stack-Vue-js-Laravel-frontend-together/dp/1788299582) by Anthony Gore
* [Build an API with Laravel](https://buildanapi.com) by Wacky Studio

## Starter Projects

* [Spark](https://spark.laravel.com/)
* [LaraAdmin](https://github.com/dwijitsolutions/laraadmin)
* [Grafite Builder](https://github.com/GrafiteInc/Builder)
* [Laravel Boilerplate](https://github.com/rappasoft/laravel-5-boilerplate)
* [Laravel Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter)
* [AdminLTE Laravel](https://github.com/acacha/adminlte-laravel)
* [Laravel Hackathon Starter](https://github.com/unicodeveloper/laravel-hackathon-starter)
* [Laravel API Starter Kit](https://github.com/joselfonseca/laravel-api)
* [Backpack for Laravel](https://github.com/Laravel-Backpack/Base)
* [SomelineStarter](https://github.com/someline/someline-starter)
* [Laravel Admin](https://github.com/z-song/laravel-admin)
* [Voyager](https://github.com/the-control-group/voyager)
* [Orchid](https://github.com/TheOrchid/Platform)
* [Laravel REST API Boilerplate](https://github.com/francescomalatesta/laravel-api-boilerplate-jwt)
* [Hello API](https://github.com/Porto-SAP/Hello-API)
* [REST API With Lumen](https://github.com/hasib32/rest-api-with-lumen)
* [Laravel Zero - Console application](https://github.com/laravel-zero/laravel-zero)
* [Apiato](https://github.com/apiato/apiato)
* [Laravel Adminpanel](https://github.com/viralsolani/laravel-adminpanel)
* [Laravel Vue Boilerplate](https://github.com/alefesouza/laravel-vue-boilerplate)
* [Laravel Enso](https://github.com/laravel-enso/enso)
* [Laravel Template with Vue](https://github.com/wmhello/laravel_template_with_vue)

## Codebases for Reference

* [Cachet](https://github.com/cachethq/Cachet) - Status page system for websites and APIs
* [Deployer](https://github.com/REBELinBLUE/deployer) - Application deployment system
* [GitScrum](https://github.com/renatomarinho/laravel-gitscrum) - Task management with Git and Scrum
* [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) - Invoicing, expenses, & time-tracking application
* [Koel](https://github.com/phanan/koel) - Personal music streaming server
* [Laravel.io](https://github.com/laravelio/portal) - Source for the Laravel.io Community Portal
* [Attendize](https://github.com/Attendize/Attendize) - Ticket selling and event management platform
* [Antvel](https://github.com/ant-vel/App) - Ecommerce platform
* [Jigsaw](https://github.com/tightenco/jigsaw) - Static site generator
* [Canvas](https://github.com/cnvs/canvas) - A Laravel Publishing Platform
* [Vuedo](https://github.com/Vuedo/vuedo) - Vuedo is blog platform, built with Laravel and Vue.js
* [Screeenly](https://github.com/stefanzweifel/screeenly) - Create website screenshots through an API
* [Voten](https://github.com/voten-co/voten) - A real-time social bookmarking for the 21st century
* [Monica](https://github.com/monicahq/monica) - Personal relationship management system
* [Snipe-IT](https://github.com/snipe/snipe-it) - IT asset/license management system
* [Akaunting](https://github.com/akaunting/akaunting) - Accounting software for small businesses and freelancers
* [Torch](https://github.com/mattstauffer/Torch) - Examples of using each Illuminate component in non-Laravel applications
* [Pixelfed](https://github.com/pixelfed/pixelfed) - A free and ethical photo sharing platform, powered by ActivityPub federation


## Content Management Systems

* [OctoberCMS](https://github.com/octobercms/october)
* [SleepingOwlAdmin](https://github.com/LaravelRUS/SleepingOwlAdmin)
* [PyroCMS](https://github.com/pyrocms/pyrocms)
* [Lavalite](https://github.com/LavaLite/cms)
* [TypiCMS](https://github.com/typicms/base)
* [Asgard CMS](https://github.com/AsgardCms/Platform)
* [Microweber](https://github.com/microweber/microweber)
* [Coaster CMS](https://github.com/web-feet/coastercms)
* [Statamic](https://statamic.com/)
* [Borgert CMS](https://github.com/odirleiborgert/borgert-cms/)
* [PJ Blog](https://github.com/jcc/blog/)
* [Laralum](https://github.com/Laralum/Laralum)
* [Twill](https://github.com/area17/twill)

## Podcasts

* [The Laravel Podcast](http://www.laravelpodcast.com/)
* [The Laravel News Podcast](https://laravel-news.com/podcast/ )
* [The Laracasts Snippet](https://laracasts.simplecast.fm/)
* [Hecho en Laravel (Spanish)](http://hechoenlaravel.com)

## Community

* [Laracasts Forum](https://laracasts.com/discuss)
* [Laravel.io Forum](http://laravel.io/forum)
* [Larachat Slack](https://larachat.slack.com/) ([Signup](https://larachat.co/register))
* [Gitter](https://gitter.im/laravel/laravel)
* [IRC Channel](http://laravel.io/chat)
* [StackOverflow](http://stackoverflow.com/questions/tagged/laravel)
* [Twitter](https://twitter.com/laravelphp)
* [Google+](https://plus.google.com/communities/106838454910116161868)
* [Reddit](https://www.reddit.com/r/laravel)
* [Quora](https://www.quora.com/topic/Laravel)
* [Facebook](https://www.facebook.com/LaravelCommunity)
* [LinkedIn](https://www.linkedin.com/groups/4419933/profile)

##### Local User Groups

* [Laravel Global Community](https://www.facebook.com/groups/group.laravel/)
* [LaravelES Slack](https://laraveles.slack.com) ([Signup](http://laraveles.com/blog/wp-login.php?action=slack-invitation))
* [Laravel India](https://laravellive.in/), [Slack Signup](https://laravelliveindia.slack.com/join/shared_invite/enQtNjQyMDE4NDA3MDQzLWMyZmIxNGZkNGVkNGFmMzE1MTgyOGNiZGY1ZmU1ZDQ3Mzk2ODBlZGJlODk3ZmI0OWNlZmI5MzQyZDJhYzg1NjE), [Twitter](https://twitter.com/LaravelLiveIN), [Facebook](https://www.facebook.com/laravellive/), [Youtube](https://www.youtube.com/channel/UC6TxYSHI7g9FMJ7VlHk72Yg)
* [Laravel UK](https://laravelphp.uk/), [Slack Signup](https://laravelphp.uk/login/slack)
* [Laravel Russia](https://laravel.ru/) ([VK group](http://m.vk.com/laravel_rus))
* [Laravel France](https://laravel.fr/)
* [Laravel Bangladesh](https://www.facebook.com/groups/LaravelBanglaDesh/)
* [Laravel Indonesia](http://id-laravel.com/) ([Facebook](https://www.facebook.com/groups/laravel/), [Telegram](https://t.me/laravelindonesia))
* [Laravel Brasil](http://www.laravel.com.br/) ([Facebook](https://www.facebook.com/groups/laravelbrasil/), [Slack](http://slack.laravel.com.br), [Telegram](https://telegram.me/laravelbr), [GitHub](https://github.com/laravelbrasil), [Discord](https://discord.gg/9dpuWeZ))
* [Laravel Turkey](http://www.laravel.gen.tr/) ([Facebook](https://www.facebook.com/groups/laravelturkiye/))
* [Laravel Nigeria](http://www.laravelnigeria.com/) ([Facebook](https://www.facebook.com/groups/laravelnigeria/))
* [Laravel China](https://phphub.org/)
* [Laravel Taiwan](https://laravel.tw/) ([Facebook](https://www.facebook.com/groups/laravel.tw/))
* [Laravel Spanish](http://laraveles.com/foro/)
* [Laravel Korea](https://www.laravel.co.kr/) ([Facebook](https://www.facebook.com/groups/laravelkorea/))
* [Laravel Japan](http://laravel.jp/) ([Facebook](https://www.facebook.com/groups/laravel.jp/))
* [Laravel Malaysia](https://www.facebook.com/groups/laravel.my/)
* [Laravel Algeria](https://www.facebook.com/groups/LaravelAlgeria/)
* [Laravel Greece](http://www.laravel.gr) ([Facebook](https://www.facebook.com/laravelgr))
* [Laravel Middle East](http://laravelme.com/) ([Facebook](https://www.facebook.com/laravelme))
* [Laravel Georgia](https://www.facebook.com/groups/laravel.georgia/)
* [Laravel Italy](http://laravel-italia.it)
* [Laravel Vietnam](https://www.facebook.com/groups/vietnam.laravel/)
* [Laravel Slovenia](https://www.facebook.com/groups/laravelslovenija/)
* [Laravel Hungary](https://laravel.hu)
* [Laravel Cameroon](https://laravelcm.com/) ([Slack](https://laravelcm.slack.com), [GitHub](https://github.com/laravelcm), [Facebook](https://www.facebook.com/laravelcm), [Twitter](https://twitter.com/laravelcm))
* [Laravel Philippines](https://www.facebook.com/groups/laravelph)

##### Meetups

* [All Meetups](http://www.meetup.com/topics/laravel/)
* [London Meetup](https://www.meetup.com/London-Laravel/)
* [Buenos Aires Meetup](https://www.meetup.com/Laravel-Buenos-Aires/)
* [Athens-Greece Meetup](https://www.meetup.com/athens-laravel-meetup/)
* [Copenhagen Meetup](https://www.meetup.com/Copenhagen-Laravel-Meetup/)
* [Detroit Meetup](https://www.meetup.com/Laravel-Detroit/)
* [Paris Meetup](https://www.meetup.com/fr-FR/Paris-Laravel-Meetup/)
* [Melbourne Meetup](https://www.meetup.com/Melbourne-laravel-Meetup/)
* [Budapest Meetup](https://www.meetup.com/Laravel-Hungary-Meetup/)

## Jobs

* [LaraJobs](https://larajobs.com/)
* [Laravel Gurus](https://laravelgurus.com/)

## Hosted Development Tools

* [Laravel Shift](https://laravelshift.com/) - Automated upgrade tool for Laravel projects
* [Laravel Schema Designer](http://laravelsd.com/) - Create, export and share database schemas
* [StyleCI](https://styleci.io) - PHP Coding Style Service

## Miscellaneous

* [CodeCanyon](https://codecanyon.net/tags/laravel?term=laravel) - Paid scripts and plugins
* [Laravel Collections](https://laravelcollections.com) - Every Laravel Developers Goto Resource Site
* [LaravelLinks](https://telegram.me/laravellinks) - A Telegram Channel dedicated to sharing great Laravel Resources
     
## Packages
- [DuckDuckGo Packagist Search](https://duck.co/ia/view/packagist) - Search for Laravel packages from [DuckDuckGo](https://duckduckgo.com/) by including 'packagist' as first search term. \[06/29/2015\]
- [Laravel Collective](http://laravelcollective.com/) - Maintainers of components removed from core Laravel framework, including annotations, remote (SSH), and forms/HTML.
- [Packagist](http://packagist.com/) - Official directory of Laravel (and other Composer-installable) packages.
- [Packagist](https://packagist.org/)
- [Packalyst](http://packalyst.com/) - Directory of Laravel packages (semi-official).
- [Packanalyst](http://packanalyst.com/) - Search engine and source-code browser for any PHP class, interface, or trait in [Packagist](http://packagist.org/).
- [Spatie](https://spatie.be/en/opensource/laravel) - A large collection of Laravel specific quality packages made by Spatie.
*

### Admin Tools/Panels
- [Backpack for Laravel](https://backpackforlaravel.com/) - Set of modular packages for building admin interfaces for Laravel based on [Admin LTE](https://github.com/almasaeed2010/AdminLTE/). \[10/01/2016\]
- [Laralum](https://github.com/ConsoleTVs/Laralum) - Simple admin panel with database CRUD support and built-in support for Laravel Auth. \[09/06/2016\]
- [Laravel Admin](https://github.com/jordanbardsley7/laravel-admin) - Provides a new Artisan `admin` command set for generation and management of administration routes, controllers, views, and configuration. \[08/30/2016\]
- [Laravel Admin Panel](https://github.com/appzcoder/laravel-admin) - Laravel tool for managing users, roles, permissions, and CRUD generation. \[04/12/2016\]
- [Laravel Admin Starter](https://github.com/jamesmills/laravel-admin) - Minimalist admin panel for managing users, roles, and permissions.
- [Laravel Administrator](https://github.com/FrozenNode/Laravel-Administrator/) - An administrative interface builder for Laravel that allows you to visually manage your Eloquent models and their relations and create stand-alone settings pages for storing site data and performing site tasks.
- [Laravel Totem](https://github.com/codestudeo/laravel-totem) - A nice dashboard for managing Laravel scheduler tasks. \[08/25/2017\]
- [Orchid](https://theorchid.github.io/en/) - A package for Laravel which helps with the administration of the application on Laravel, allowing you to write code as you want, control of routing/themes/plugins/etc - none of this and will not be! The package only gives a good set of tools that will be in demand in almost every project. \[07/13/2017\]
- [UserFrosting](http://www.userfrosting.com) - A web framework and fully implemented user management application that uses Laravel's ORM and cache components.  The Sprinkle system allows you to easily and cleanly extend the core codebase with the custom features that your application requires.
- [Voyager](https://github.com/the-control-group/voyager) - Comprehensive Laravel admin package with support for CRUD administration of database, menu editor, media manager and more. \[11/01/2016\]


### Algorithms/Data Structures

- [Laravel NestedSet](https://github.com/lazychaser/laravel-nestedset) - An implementation of a tree data structure in a relational database. \[03/16/2017\]
- [HashIDs](https://github.com/mitchellvanw/hashids) - Laravel wrapper for the [HashIDs](http://hashids.org/) tool to generate short, unique hashes for any integer (e.g., surrogate key ID).

### Authentication/Security
- [Acacha Laravel Social](https://github.com/acacha/laravel-social) - OAuth Social Login/Register implementation with Github, Facebook, Google, Twitter... using Laravel Socialite and (optionally) [AdminLTE Laravel package](https://github.com/acacha/adminlte-laravel) . \[23/02/2017\]
- [Active Directory LDAP Authentication](https://github.com/strebl/ldap-auth) - LDAP authentication package for Active Directory. \[07/27/2015\]
- [Botscout protection](https://github.com/nicolasbeauvais/laravel-botscout) - Block malicious scripts using botscout.com protection for your laravel app. \[03/03/2017\]
- [Bouncer](https://github.com/JosephSilber/bouncer) - Powerful package for handling roles and abilities in the Laravel [ACL](http://laravel.com/docs/authorization). \[07/27/2016\]
- [Captcha](https://github.com/infinity-next/brennan-captcha) - An anti-bot image captcha system written by Frederick Brennan and ported to Laravel for Infinity Next by Joshua Moon.
- [Captcha](https://github.com/mewebstudio/captcha) - Captcha for Laravel 5 - An anti-bot image captcha system.
- [Confide](https://github.com/zizaco/confide) - An authentication solution for Laravel with features like  account creation, login, logout, confirmation by e-mail, password reset, etc.
- [Dingo](https://github.com/dingo) - Laravel package/API for using [JWT Authentication](http://jwt.io/). \[11/06/2015\]
- [EasyAdmin](https://github.com/Laravelish/EasyAdmin) - An advanced Laravel login and user management package with support for [two-factor authentication](https://twofactorauth.org/). \[03/26/2016\]
- [Eloquent OAuth](https://github.com/adamwathan/eloquent-oauth) - Easy-to-use package for [OAuth](http://oauth.net/) authentication in Laravel 4.
- [jwt-auth](https://github.com/tymondesigns/jwt-auth) - [JSON Web Token](http://en.m.wikipedia.org/wiki/JSON_Web_Token) authentication package for Laravel. \[06/11/2015\]
- [Laravel ACL](https://github.com/kodeine/laravel-acl) - Lightweight role-based permissions system for Laravel 5's built-in Auth system. \[06/15/2016\]
- [Laravel Impersonate](https://github.com/404labfr/laravel-impersonate) - A package to authenticate as one of your users. [03/08/2016]
- [Laravel Password Exposed Validation Rule](https://github.com/DivineOmega/laravel-password-exposed-validation-rule) - Adds validation rule to Laravel to check if user password has been compromised in data breach. \[06/25/2018\]
– [Laravel 5 Very Basic Auth](https://github.com/olssonm/l5-very-basic-auth) – HTTP Basic Authentication without the need for a database \[09/07/2017\]
- [LDAP-Auth](https://github.com/krenor/ldap-auth) - Very basic read-only LDAP authentication driver for Laravel 5.1+. \[11/23/2015\]
- [Libsodium for Laravel](https://github.com/scrothers/libsodium-laravel) - Laravel package wrapper for the [libsodium](https://download.libsodium.org/doc/) library which allows it to be a drop-in replacement for the Laravel native [encryption](http://laravel.com/docs/encryption) and [hashing](http://laravel.com/docs/hashing) classes/services. \[09/14/2015\]
- [OAuth-4-Laravel](https://github.com/artdarek/oauth-4-laravel) - Laravel package wrapper for [PHPoAuthLib](https://github.com/Lusitanian/PHPoAuthLib) with support for OAuth 1 and OAuth 2 providers.
- [OAuth-5-Laravel](https://github.com/andrewxtsang/oauth-5-laravel) - Laravel **5.x** package wrapper for [PHPoAuthLib](https://github.com/Lusitanian/PHPoAuthLib) with support for OAuth 1 and OAuth 2 providers. \[07/20/2015\]
- [PropAuth](https://github.com/psecio/propauth) - Package that supports property-based security policy evaluation. See tutorial [here](https://websec.io/2015/10/07/Security-Policy-Evaluation-Laravel-PropAuth.html). \[01/04/2015\]
- [Purifier](https://github.com/mewebstudio/purifier) - HTMLPurifier for Laravel 5 - HTML filter
- [ReplayPHP Auth](https://github.com/replayphp/auth) - Enhancements to the Laravel 5 Auth module. \[11/07/2016\]
- [Roles](https://github.com/romanbican/roles) - Powerful package for handling roles and permissions in Laravel. \[07/16/2015\]
- [Sentinel](https://github.com/cartalyst/sentinel) - Fully-featured, framework-agnostic (works great with Laravel!) authentication and authorization system.  (Successor to [Cartalyst](https://cartalyst.com/)'s [Sentry](https://github.com/cartalyst/sentry) library.) \[07/02/2015\] 
- [SleepingOwl Admin](http://sleeping-owl.github.io/) - An administrative interface builder for Laravel models that supports customization. \[04/27/2015\]
- [Socialite Providers](http://socialiteproviders.github.io/) - Collection of 70+ OAuth 1 and 2 provider packages for [Socialite](https://github.com/laravel/socialite) package. \[05/15/2015\]
- [URL Signer](https://github.com/spatie/laravel-url-signer) - Improve Laravel security by creating URLs with limited lifetime (similar to AWS signed URLs). \[08/16/2015\]
- [Laravel Security Checker](https://github.com/Jorijn/laravel-security-checker) - Added Laravel functionality to SensioLabs Security Checker. Adds a command to check for, and optionally emails you, vulnerabilities when they affect you. \[07/24/2017\]

### Boilerplate/Customized Configurations
- [Laravel Code Generator](https://github.com/CrestApps/laravel-code-generator) - A clean code generator for Laravel framework that will save you time! This awesome tool will help you generate resources like views, controllers, routes, migrations, languages or request-forms! It is extremely flexible and customizable to cover many on the use cases. It is shipped with cross-browsers compatible template, along with a client-side…
- [Acacha adminlte-laravel](https://github.com/acacha/adminlte-laravel) - A Laravel 5 package that switches default Laravel scaffolding/boilerplate to AdminLTE template with Bootstrap 3.0 and [Pratt Landing Page](http://blacktie.co/demo/pratt/). \[02/02/2016\]
- [Antares Project](https://github.com/antaresproject) - Custom re-packaging of Laravel, Vue.JS, and more as a starting point for building new applications quickly. \[06/27/2017\]
- [Base Laravel Admin](https://github.com/alexdover/laravel-base-admin) - A basic Laravel 4.x install with a admin site/dashboard using Bootstrap 3. \[04/13/2015\]
- [Bootstrapper for Laravel](http://bootstrapper.eu1.frbit.net/) - Laravel package that provides fluent interface for using [Bootstrap](http://getbootstrap.com/) CSS framework in Laravel. \[11/09/2015\]
- [Enso](https://github.com/laravel-enso/Enso) - Boilerplate for building single-page apps (SPA) with Laravel and Vue.JS using [Bulma](https://bulma.io/) CSS framework. \[09/17/2018\]
- [esensi](http://esen.si/) - Laravel boilerplate application with enhancements for loaders and models.
- [Fountain](https://darovi.co/fountain) - Comprehensive application builder for Laravel 5 including ecommerce, invoicing and more. \[10/17/2016\]
- [Gold Standard](https://github.com/dwightwatson/gold-standard) - Boilerplate template for clean, [resourceful](https://laravel.com/docs/controllers#resource-controllers), testable Laravel applications. \[03/31/2017\]
- [Hexavel](https://github.com/peterfox/hexavel) - Restructured version of Laravel framework to provide streamlined workflows and simplify development process. \[12/30/2015\]
- [HTG Laravel](https://github.com/euperia/htg-laravel) - Basic Laravel boilerplate with [AdminLTE](https://almsaeedstudio.com/AdminLTE) focused on rapid prototyping. \[07/28/2016\]
- [L4 Core](https://github.com/anlutro/laravel-4-core) - Laravel 4 application boilerplate built from author's other packages; includes Bootstrap. \[06/11/2015\]
- [LaraAdmin](http://laraadmin.com/) - LaraAdmin is a Open source Laravel Admin Panel / CMS which can be used as Admin Backend, Data Management Tool or CRM boilerplate for Laravel with features like Advanced CRUD Generation, Module Manager, Backups and many more. \[12/13/2016\]
- [Laracogs](http://laracogs.com/) - Package that includes helpers for Bootstrap, CRUD, notifications, billing via Cashier, and form generation. \[04/26/2016\]
- [LaraLTE2](https://github.com/kossa/laralte2) - Laravel PHP Framework with [AdminLTE2](https://almsaeedstudio.com/AdminLTE) and other packages and JavaScript tools. \[06/04/2016\]
- [Laramen](https://github.com/laurencei/laramen) - Customized configuration of Laravel that uses Lumen-powered API routes. \[09/26/2017\]
- [Larafolio](https://github.com/zachleigh/larafolio) - Web design portfolio management tool built with Laravel. \[06/28/2018\]
- [LaraProto](https://github.com/taviroquai/laraproto) - Laravel web site prototype with built-in user management and Bootstrap styling. \[08/06/2015\]
- [Laravel Angular Admin](https://github.com/silverbux/laravel-angular-admin) - Laravel, AngularJS, Bootstrap, and AdminLTE with OAuth and JWT authentication. \[10/18/2016\]
- [Laravel 5 Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter) - Laravel 5 and [Angular Material](https://material.angularjs.org/) with sample config for ui-router, Restangular, theming, etc. See tutorial on use [here](http://www.sitepoint.com/flexible-and-easily-maintainable-laravel-angular-material-apps/).
- [Laravel 5 Boilerplate](https://github.com/repeater09/Laravel-5-Boilerplate) - Laravel 5 application boilerplate built with [Skeleton](http://getskeleton.com/), [Sidr](http://www.berriart.com/sidr/), and [Fontastic](http://fontastic.me/).
- [Laravel 5 Boilerplate](https://github.com/rappasoft/Laravel-5-Boilerplate) - Responsive Laravel 5 application template with [Bootstrap 3](http://www.getbootstrap.com/), [HTML 5 Boilerplate](http://www.html5boilerplate.com/), [Font Awesome](http://fortawesome.github.io/Font-Awesome/), and more.
- [Laravel 5 Bootstrap 3 Starter Site](https://github.com/mrakodol/Laravel-5-Bootstrap-3-Starter-Site) - Laravel 5 site template using [Bootstrap 3](http://www.getbootstrap.com/) with built-in support for managing videos, pictures, and news, [DataTables](https://datatables.net/), and much more. \[04/30/2015\]
- [Laravel 5 on Shared Hosting](https://github.com/onerciller/laravel5-on-shared-hosting) - Custom directory structure for Laravel to separate the ''public'' directory from code directories. \[05/06/2016\]
- [Laravel 5 Scaffold Generator](https://github.com/laralib/l5scaffold) - Artisan extension package to build scaffolding.  Single command creates model, controller, migration, seeder, and RESTful views. \[04/27/2015\]
- [Laravel 5 Starter](https://github.com/Imaginarydesign/laravel-5-admin-starter) - A complete Laravel starter configuration using Bootstrap and [AdminLTE](https://www.almsaeedstudio.com/) for admin functions. \[03/26/2016\]
- [Laravel 5 Starter Package](https://github.com/andyjessop/laravel5-starter-package) - A starter package for Laravel 5 with boilerplate views, configs, and routes. \[07/22/2015\]
- [Laravel Boilerplate with EMail Verification on Registration](https://github.com/lubusIN/laravel-email-verification-app-boilerplate) - Basic Laravel configuration that supports e-mail verification when user registers. \[02/06/2017\]
- [Laravel and AngularJS Starter Application Boilerplate](https://github.com/Zemke/starter-laravel-angular) - Single-page application starter configuration with Laravel 5 and [Angular.JS](https://angularjs.org/) 1.3.  \[04/07/2015\]
- [Laravel Enterprise Starter Kit (LESK)](https://github.com/sroutier/laravel-enterprise-starter-kit) - Comprehensive boilerplate configuration that cleanly integrates many popular packages for quick start to new projects. \[03/26/2017\]
- [InfyOm Laravel Generator](https://github.com/InfyOmLabs/laravel-generator) - API, Scaffold, CRUD Laravel Generator \[05/01/2016\]
- [Laravel Hackathon Starter](https://github.com/unicodeveloper/laravel-hackathon-starter) - Laravel boilerplate configuration with lots of built-in API support. \[02/23/2016\]
- [Laravel Kickstart](https://github.com/samrap/lks) - Laravel starter configuration with an Elixir configuration, the latest versions of Bootstrap and JQuery, a Blade wrapper template, debug tools, and much more. \[03/09/2016\]
- [Laravel React Typescript Boilerplate](https://github.com/georgewritescode/Laravel-React-Typescript-Boilerplate) - Boilerplate configuration for starting projects based on Laravel, React, and Typescript. \[07/16/2018\]
- [Laravel React Webpack Starter Kit](https://github.com/bezunakarmi/laravel-react-webpack) - Package for quickly configuring Laravel with React.JS, Webpack, and PostCSS/SASS. \[04/17/2017\]
- [Laravel Skeleton Application](https://github.com/rdehnhardt/skeleton) - Basic Laravel application template with dashboard, user management, and more. \[07\26\2017\]
- [Laravel Vue Boilerplate](https://github.com/alefesouza/laravel-vue-boilerplate) - A Laravel 5.5 single-page application (SPA) boilerplate using [Vue.js](https://vuejs.org/) 2.5, [Bootstrap 4](https://getbootstrap.com/docs/4.0/), [TypeScript](https://www.typescriptlang.org/), Sass, Pug and [Jest](https://facebook.github.io/jest/). \[05/08/2018\]
- [Laravel Zero](https://github.com/laravel-zero/laravel-zero) - Customized version of Laravel optimized for building console/shell/command-line applications. \[06/27/2017\]
- [Laravel-Auth](https://github.com/jeremykenedy/laravel-auth) - Laravel 5.4 configuration with email registration verification, social authentication, user roles and permissions, user profiles, and user management system. \[08/19/2017\]
- [Laravel/Angular Material Starter](https://github.com/jadjoubran/laravel5-angular-material-starter) - Complete project starter template for building application with Laravel 5 and [Angular Material](https://material.angularjs.org/). \[08/20/2015\]
- [Owl](https://github.com/kjdion84/owl) - Laravel 5.5 configuration with CRUD generator, roles/permissions, Bootstrap 4, DataTables, and much more. \[09/05/2017\]
- [React-Redux-Laravel](https://github.com/onerciller/react-redux-laravel#react-redux-laravel) - Boilerplate blog application for a Laravel JWT Backend and a React/Redux Front-End with Bootstrap 4. \[06/06/2016\]
- [Scafold](https://github.com/bestmomo/scafold) - Adds back some of the boilerplate/scaffolding removed in Laravel 5.1. \[07/20/2015\]
- [Skeletor](https://github.com/pixelfusion/skeletor) - Interactive shell tool for creating a new Laravel/Lumen project that automates several common steps. Learn more [here](https://medium.com/pixel-fusion/skeletor-the-laravel-skeleton-generator-f02a14ff2b4b). \[10/05/2017\]
- [Support](https://github.com/iolson/support) - Adds some nice features and other third-party packages to your Laravel installation. \[10/05/2015\]
- [Turtle](https://github.com/kjdion84/turtle) - Laravel 5.5 package with front & backend scaffolding including a CRUD generator, auth integration, roles, permissions, contact forms, reCAPTCHA, activity logs, demo mode, user timezones, AJAX CRUD/validation, Bootstrap 4, DataTables, & more. \[09/18/2017\]
- [UIkit UI preset](https://github.com/Torrix/laravel-ui-uikit) - UI preset for Laravel 6 that bundles UIkit and Vue.js \[09/16/2019\]
- [Watts](https://github.com/YABhq/Watts) - Custom configuration with tools for developing microservices using Lumen. \[05/10/2016\]

### Database/Eloquent/Models
- [Analogue](https://github.com/analogueorm/analogue) - Intuitive, fluent data mapper ORM for Laravel and PHP. \[07/15/2015\]
- [Apify](https://github.com/ConsoleTVs/Apify) - API generator for Laravel that allows JSON access to any model/table. \[01/07/2017\]
- [belongsToThrough](https://github.com/znck/belongs-to-through) - Adds trait to Eloquent models to support ''belongsToThrough'' relationship. \[10/21/2015\]
- [Computed Properties for Eloquent](https://github.com/n7olkachev/laravel-computed-properties) - Improved accessors for Laravel 5.4+ models. \[08/22/2017\]
- [CRUD Generator](https://github.com/appzcoder/crud-generator) - Simple Artisan command to generate CRUD commands for database interaction of your model in Laravel 5. \[08/30/2015\]
- [CRUDBooster](https://github.com/crocodic-studio/crudbooster) - Customization of Laravel framework for auto-generation of CRUD (Create, Read, Update, Delete) methods for your model. \[08/30/2016\]
- [CSV](https://github.com/wilgucki/csv) - Package that supports reading and writing CSV (or other token-delimited) files. \[03/20/2017\]
- [CSV Seeder](https://github.com/Flynsarmy/laravel-csv-seeder) - If you have your seed data for your database in a spreadsheet, use this package to load it directly from a [CSV file](https://en.wikipedia.org/wiki/Comma-separated_values). \[05/11/2015\]
- [Datagrid](https://github.com/aginev/datagrid) - Self-contained (no external dependencies) data grid package for Laravel 5 with support for filtering, sorting, and Bootstrap. \[07/20/2015\]
- [Datatable](https://github.com/Chumper/Datatable) - Alternate Laravel 4 package wrapper for [Datatables](http://datatables.net/).
- [Elasticquent](https://github.com/elasticquent/Elasticquent) - Package for mapping Laravel Eloquent models to [Elasticsearch](http://www.elasticsearch.org/) types. \[03/15/2017\]
- [Eloquence](https://github.com/kirkbushell/eloquence) - Adds some very useful extensions to base Eloquent models, such as camel-case attributes, sluggable and UUID keys, etc. \[04/22/2015\]
- [Eloquent Encryption/Decryption for Laravel](https://github.com/delatbabel/elocryptfive) - Automatic encryption/decryption of model attributes when stored/retrieved. \[08/17/2017\] 
- [Eloquent Filter](https://github.com/Tucker-Eric/EloquentFilter) - Provides customized filtering capability for Eloquent models via a Filterable attribute. \[03/05/2016\]
- [Eloquent MongoDB Repository](https://github.com/PHPRepository/php-eloquent-mongodb-repository) - Implementation of [repository](http://code.tutsplus.com/tutorials/the-repository-design-pattern--net-35804) [design pattern](http://www.sitepoint.com/repository-design-pattern-demystified/) for MongoDB using Eloquent. \[03/09/2016\]
- [Eloquent Populator](https://github.com/guidocella/eloquent-populator) - Populate Laravel's Eloquent ORM's models by guessing the best Faker formatters for their attributes from their columns' names and types. \[02/16/2017\]
- [Eloquent Sortable](https://github.com/spatie/eloquent-sortable) - Adds a sortable [trait](http://php.net/manual/en/language.oop5.traits.php) to Eloquent models for Laravel 4/5. \[05/25/2015\]
- [Eloquent Versioned](https://github.com/sbarre/eloquent-versioned) - Adds transparent versioning to Eloquent models, which persists an entirely new row in database when updating a model instance. \[06/08/2015\]
- [Eloquent Preferences](https://github.com/klaude/eloquent-preferences) - Allows binding of multiple key-value pair preferences to your Eloquent models. \[12/29/2015\]
- [glmdev/search](https://github.com/glmdev/search) - Adds relevance-based keyword search capability to any fields of Eloquent models. \[07/26/2017\]
- [Lada Cache](https://github.com/spiritix/lada-cache) - A Redis based, automated and scalable database caching layer for Laravel 5.1+. \[21/09/2016\]
- [Laracadamy Generators](https://github.com/laracademy/generators) - Extends Artisan `generate` command to automatically build model directly from database table. \[09/02/2016\]
- [Laradump](https://github.com/yadakhov/laradump) - A Laravel wrapper package for the MySQL [mysqldump](http://dev.mysql.com/doc/refman/5.7/en/mysqldump.html) tool to allow exporting of your database and reloading via Laravel [Artisan](https://laravel.com/docs/artisan) commands. \[08/03/2016\]
- [Laraformer](https://github.com/kamranahmedse/laraformer) - Laravel package to add a transformation layer to your Eloquent model. \[03/05/2016\]
- [Laravel DataTables](https://github.com/bllim/laravel4-datatables-package) - Laravel 4 server-side handler package for [DataTables](https://datatables.net/) jQuery plug-in.
- [Laravel Doctrine](http://laraveldoctrine.org/) - A package that tightly integrates the [Doctrine](http://www.doctrine-project.org/) ORM with Laravel. \[09/10/2015\]
- [Laravel Firebird](https://github.com/jacquestvanzuydam/laravel-firebird) - [Firebird](http://firebirdsql.org/) Illuminate package for Laravel 5. \[04/27/2015\]
- [Laravel Media Library](https://github.com/spatie/laravel-medialibrary) - Package for associating files (including those hosted on Amazon S3) with Eloquent model. \[07/15/2015\]
- [Laravel Normalizer](https://github.com/nWidart/laravel-normalizer) - Simple package to allow model-independent normalization (i.e., capitalization, numeric formatting, etc.) of data before persisting. \[07/28/2016\]
- [Laravel Property Bag](https://github.com/zachleigh/laravel-property-bag) - Add settings or other properties to Laravel models simply and easily. \[06/28/2018\]
- [Laravel 5 Repository](https://github.com/prettus/l5-repository) - Package for the implementing the [repository design pattern](http://www.sitepoint.com/repository-design-pattern-demystified/) to abstract database layer of your application. \[08/16/2015\]
- [Laravel 5 Model Factory Generator](https://github.com/rymanalu/factory-generator) - Create a new model factory file using Artisan command. \[03/27/2017\]
- [Laravel References](https://github.com/jameslkingsley/laravel-references) - Provides a simple way to add unique references to models that can be resolved via route model binding without exposing primary keys. \[10/09/2017\]
- [Laravel Searchy](https://github.com/TomLingham/Laravel-Searchy) - Easy-to-use database searching package for Laravel 4 with support for fuzzy searching and sensitivity configuration. \[04/30/2015\]
- [Laravel Value Objects](https://github.com/redcrystalcode/laravel-value-objects) - Cast Eloquent model attributes to [value objects](https://en.wikipedia.org/wiki/Value_object) with ease. \[12/07/2015\]
- [LODM](https://github.com/wolfy-j/lodm) - ODM package for Laravel with native support for MongoDB that supports inheritance, composition, and aggregation, as well as hierarchical data. \[10/12/2015\]
- [MySQL to Laravel](https://github.com/dachusa/MySQLToLaravel) - Script to generate Laravel migrations from an existing MySQL database. \[02/20/2016\]
- [MySQL Workbench Export Laravel 5 Migrations Plugin](https://github.com/beckenrode/mysql-workbench-export-laravel-5-migrations) - Plugin for [MySQL Workbench](http://dev.mysql.com/downloads/workbench/) to export data models to Laravel 5 migrations. \[09/24/2016\] 
- [ODBC Driver](https://github.com/garylocke/odbc-driver) - Laravel 5.x package which provides support for using **any** database via [ODBC](https://en.m.wikipedia.org/wiki/Open_Database_Connectivity). \[07/20/2015\]
- [PHP Eloquent Repository](https://github.com/nilportugues/php-eloquent-repository) - Repository package for Eloquent for use with Eloquent or plain PHP. \[02/15/2016\]
- [Query Dumper](https://github.com/sarfraznawaz2005/querydumper) - Output query SQL and results to your view page for debugging. \[09/18/2017\]
- [Revisionable](https://github.com/VentureCraft/revisionable) - Adds simple (and, optionally, [trait](http://php.net/manual/en/language.oop5.traits.php)-based) support for keeping revision history of models in your Laravel applications.
- [Rinvex Repository](https://github.com/rinvex/repository) - Comprehensive and well-documented [repository](https://www.sitepoint.com/repository-design-pattern-demystified/) package (specifically [Active Repository](https://blog.omranic.com/active-repository-is-good-awesomely-usable-6991cfd58774) pattern) for abstracting storage/persistence. \[08/31/2016\]
- [Searchable](https://github.com/nicolaslopezj/searchable) - a trait for Laravel 4.2+ and Laravel 5.0 that adds a simple search function to Eloquent Models to prioritize fields for searching. \[12/04/2016\]
- [Single-Table Inheritance](https://github.com/phaza/single-table-inheritance) - Adds a [trait](http://php.net/manual/en/language.oop5.traits.php) to Eloquent models to allow multiple models to be stored in the same database table. \[07/12/2015\]
- [Unique With Validator](https://github.com/felixkiss/uniquewith-validator) - Provides support for composite unique indexes, such as combination of first and last name.
- [QueryBuilderParser](https://github.com/timgws/QueryBuilderParser) - A Laravel package that builds SQL queries based on input from a jQuery QueryBuilder.


### Design Pattern Tools
- [Laravel Context](https://github.com/rtroncoso/Laravel-Context) - Provides application contextual support for using different service providers, such as the case of admin functionality versus regular functionality. \[07/07/2015\]
- [Repositories Maker](https://github.com/abdelrahmanrafaat/repositories-maker) - Adds Artisan command to auto-generate repositories for all Eloquent models. \[10/01/2016\]
- [Laravel Widgetize](https://github.com/imanghafoori1/laravel-widgetize) - Helps you have clean controller methods + easy caching. \[4/4/2017\]

### Development Tools

- [Scaffold Interface](https://github.com/amranidev/scaffold-interface) - A Smart CRUD Generator For Laravel
- [Laravel 5 Extended Generators](https://github.com/laracasts/Laravel-5-Generators-Extended) - Extends built-in file generators
- [Laravel Tinx](https://github.com/furey/tinx) - Reload your Laravel Tinker session from inside Tinker
- [Laravel API Documentation Generator](https://github.com/mpociot/laravel-apidoc-generator) - Automatically generate your API documentation
- [Laravel Packager](https://github.com/Jeroen-G/Laravel-Packager) - A CLI tool for creating Laravel packages
- [LaRecipe](https://github.com/saleem-hadad/larecipe) - Write gorgeous documentations for your products using Markdown inside your Laravel app.
- [Prequel](https://github.com/Protoqol/Prequel/) - A clear and concise database management GUI tweaked for Laravel.
- [Acacha llum](https://github.com/acacha/llum) - Llum illuminates your Laravel projects speeding up your Github/Laravel development workflow. \[23/02/2017\]
- [Artisan Menu](https://github.com/DivineOmega/artisan-menu) - Provides menu-driven front-end for Artisan, including custom Artisan commands and prompting for arguments. \[07/16/2018\]
- [Artisan View](https://github.com/svenluijten/artisan-view) - Adds a `make:view` [Artisan](https://laravel.com/docs/artisan) command for generating a Blade view file. \[07/27/2016\]
- [Best Artisan](https://github.com/bestmomo/nice-artisan) - Adds a clean web interface to [Artisan](https://laravel.com/docs/artisan) commands. \[01/08/2017\]
- [Blacksmith](https://github.com/Indatus/blacksmith) - Independent code-generation tool that works closely with Laravel to generate models, views, controllers, seeds, forms, and much more.
- [Candela](https://github.com/jenssegers/candela) - A [Silex](http://silex.sensiolabs.org/)/[Slim](http://www.slimframework.com/) style version of Laravel's Lumen microframework. \[05/16/2015\]
- [Debug Window](https://github.com/andersmandersen/laravel-debugwindow) - Extension of popular DebugBar tool that displays variables sent to view in easy-to-read format. \[07/20/2015\]
- [Env Providers](https://github.com/svenluijten/env-providers) - Load service providers based on the application's current environment. \[03/07/2017\]
- [Inspector](https://github.com/tajawal/inspector) - Utility that checks installed [Composer](https://getcomposer.org/) project dependencies and notifies you of any updates (not Laravel specific). \[04/26/2016\]
- [Interactive Make](https://github.com/laracademy/interactive-make) - Turns Artisan `make` command into fully-interactive wizard for all options. \[04/26/2017\]
- [Lambo](https://github.com/tightenco/lambo) - Simple shell script that speeds the process of creating and configuring a new Laravel project. \[07/24/2017\]
- [Laraquick](https://github.com/ezra-obiwale/laraquick) - Collection of classes to help speed Laravel development. \[04/23/2018\]
- [Larastan](https://github.com/nunomaduro/larastan) - Wrapper package for [PhpStan](https://github.com/phpstan/phpstan) static-analysis tool. \[07/23/2018\]
- [Larasupport](http://irazasyed.github.io/larasupport/) - Provides some missing helpers to [Lumen](http://lumen.laravel.com/) and allows Laravel packages to be used with Lumen. \[06/08/2015\]
- [Laravel API Generator](https://github.com/mitulgolakiya/laravel-api-generator) - Another independent code-generation tool for creating project boilerplate, including migrations, models, controllers, various views, etc. \[05/14/2015\]
- [Laravel Backup](https://github.com/freekmurze/laravel-backup) - Artisan extension that allows you to backup your application and database into a ZIP archive.
- [Laravel Console](https://github.com/darsain/laravel-console) - An in-browser console for running Laravel commands (or any PHP code!).  Like a browser-based version of [Artisan](http://laravel.com/docs/4.2/artisan). \[04/22/2015\]
- [Laravel Decomposer](https://github.com/lubusIN/laravel-decomposer) - Generates a list of all of the packages used by your Laravel application, including dependencies, and displays them in the browser. \[02/20/2017\]
- [Laravel Environment](https://github.com/Brunty/laravel-environment) - Artisan extension to create and edit environment-specific configuration files in the shell.
- [Laravel Environment Manager](https://github.com/tommyku/laravel5_env) - Artisan command for managing multiple environments (`.env`) for a Laravel 5 application.
- [Laravel Feature Flag/Switch](https://github.com/jonathan-bird/feature-switch) - Simple tool for adding [feature flag](https://en.wikipedia.org/wiki/Feature_toggle) capability to your Laravel applications. \[06/16/2016\]
- [Laravel IDE Helper](https://github.com/barryvdh/laravel-ide-helper) - Adds auto-complete support for Laravel syntax to a variety of IDEs and text editors, including [Aptana Studio](http://aptana.com/), [Eclipse](http://eclipse.org/), [PHP Storm](http://www.jetbrains.com/phpstorm/), and more.
- [Laravel Identify](https://github.com/unicodeveloper/laravel-identify) - Package to identify client configuration, such as browser, device, operating system and more. \[01/07/2017\]
- [Laravel Inspector](https://github.com/lsrur/inspector/) - Comprehensive debugging and profiling tool with full logging capabilities that outputs errors and logged actions to browser JavaScript console. \[08/03/2016\]
- [Laravel Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Add on which allows you to view your Laravel 4.2/5.0 log file within the application itself by opening the `logs` (or other) route.
- [Laravel Make-Me](https://github.com/HydrefLab/laravel-make-me) - Extendable interactive Artisan `make` command. \[03/03/2018\]
- [Laravel PackMe](https://github.com/ptondereau/laravel-packme) - A shell/command-line starter kit for developing pakcages for Laravel 5. \[06/16/2016\]
- [Laravel Permission](https://github.com/spatie/laravel-permission) - A simple package to manage users, roles, and permissions in Laravel. \[09/22/2015\]
- [Laravel Tracer](https://github.com/appstract/laravel-tracer) - Displays the full path of each Blade view, including partials, loaded into template at place it is applied. \[06/22/2017\]
- [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - Package for integrating the excellent [Nette Tracy](https://tracy.nette.org/) debugging library as a replacement for [Laravel's standard error handling functions](https://laravel.com/docs/errors). \[09/02/2016\]
- [Laravel UUID](https://github.com/webpatser/laravel-uuid) - Laravel 4.x/5.x package to generate a UUID according to the RFC 4122 standard. See [here](https://medium.com/@steveazz/setting-up-uuids-in-laravel-5-552412db2088) for example usage as database key. \[04/29/2016\]
- [Laravel View Xray](https://github.com/beyondcode/laravel-view-xray) - Provides capability to show which Blade template rendered various portions of page in a view. \[07/24/2018\]
- [Laravel Web Installer](https://github.com/RachidLaasri/LaravelInstaller) - Package helps you design an installer/setup wizard to allow users to install Laravel application without using Composer, SSH, etc. \[09/14/2015\]
- [Laravel-4-Generators](https://github.com/JeffreyWay/Laravel-4-Generators) - Package for speeding up development by generating classes, migrations, database seeds, and more.
- [Laroute](https://github.com/aaronlord/laroute) - Package of helper functions for "porting" Laravel routes over to JavaScript for use on front end of application.
- [Laravel Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates Laravel with [PHP Debug Bar](http://phpdebugbar.com/) to display debugging during application testing.
- [Laravel Resourceful](https://github.com/remoblaser/laravel-resourceful) - Generates full complement of CRUD resource Laravel code, including migrations, seeds, requests, controllers, models, and views. \[04/20/2015\]
- [Links](https://github.com/ConsoleTVs/Links) - Package for link statistics and tracking, including browser type, OS, language, and more. \[11/04/2016\]
- [Llum](https://github.com/acacha/llum) - Command-line utility to perform common configuration tasks for Laravel framework. \[08/12/2017\]
- [Lumen Generators](https://github.com/webNeat/lumen-generators) - Adds several Artisan commands for generating controllers, models, migrations, resources, routes and more. (For Lumen and Laravel) \[09/03/2017\]
- [Make:User](https://github.com/laracademy/commands.make-user) - Adds an Artisan command for generating a new user account based on e-mail address with optional name. \[11/15/2016\]
- [Migrations Generator](https://github.com/Xethron/migrations-generator) - Generate database migrations from existing database schema.
- [Open on Make](https://github.com/ahuggins/open-on-make) - Simple package to open new file created by `artisan make` command in editor of your choice. \[06/25/2018\]
- [PHP Console](https://github.com/barbushin/php-console-laravel) - Laravel package wrapper/service provider to handle PHP errors, dump variables, execute PHP code remotely, etc. in Google Chrome with [PHP Console extension](https://chrome.google.com/webstore/detail/php-console/nfhmhhlpfleoednkpnnnkolmclajemef).
- [Potion](https://github.com/Classy-Geeks/laravel-potion) - Asset management tool for Laravel 5 based off of Assetic with only PHP dependencies.  \[04/05/2015\]
- [Pretty Routes](https://github.com/garygreen/pretty-routes) - Adds a `/routes` URL to your application for a nice visualization of all of the routes, including HTTP methods, middleware used, and more. \[08/31/2016\] 
- [SmartSeeder](https://github.com/slampenny/SmartSeeder) - SmartSeeder extends database seeding beyond development to allow to use different seed data depending on the environment.
- [sqli](https://github.com/antonioribeiro/sqli) - Laravel 4 Artisan SQL REPL (interactive tool), similar to *tinker* for SQL queries.
- [Environment](https://github.com/jpcercal/environment) - A simple library to increase the power of your environment variables.
- [TNT Search](https://github.com/teamtnt/tntsearch) - Full-featured full-text search engine. \[10/01/2016\]
- [Translation.io for Laravel](https://github.com/translation/laravel) - Package that integrates support for [Translation.io](https://translation.io/) to allow localization of Laravel applications using [GetText](https://www.gnu.org/software/gettext/). \[05/01/2018\]
- [Laravel UI http logger](http://apideveloper.io) - Laravel package to log every request/response app handled and UI to analyze it

### E-commerce
- [Aimeos](http://aimeos.org/project/laravel-shop-package/) - Complete e-commerce/web shop package with support for product catalogs, shopping, checkout, payment, and order management. \[04/29/2015\]
- [Antvel](https://github.com/ant-vel/antVel) - Package for building e-commerce applications with Laravel. \[12/16/2016\]
- [Amazon ECS (E-Commerce Services)](https://github.com/JoeDawson/amazon-ecs) - Package to allow searching the Amazon product catalog. \[12/18/2015\]
- [AvoRed](https://github.com/avored/laravel-ecommerce) - Full-featured e-commerce platform built on Laravel. \[07/09/2018\]
- [Grafite Commerce](https://github.com/GrafiteInc/Commerce) - Full-fledged e-commerce package that includes support subscriptions, electronic downloads, and more. \[06/25/2018\]
- [LaraCart](https://github.com/lukepolo/laracart/) - Fully-featured shopping cart package for Laravel. \[03/30/2017\]
- [Laragento](https://github.com/develpr/laragento) - A Laravel + [Magento](http://magento.com/) mashup, for directly accessing Magento data via RESTful API provided by Laravel. \[10/12/2015\]
- [Laravel PayPal](https://github.com/srmklive/laravel-paypal) - Laravel package for PayPal payment processing, which can also be used outside of Laravel. \[07/14/2020\]
- [Laravel PayPal Payment](https://github.com/xroot/laravel-paypalpayment) - Package for processing credit card or PayPal account payments using [PayPal REST API](https://developer.paypal.com/docs/api/).
- [Mage2](https://github.com/mage2/laravel-ecommerce) - Laravel e-commerce package with built-in Paypal support. \[12/16/2016\]
- [Paypal IPN](https://github.com/logicalgrape/paypal-ipn-laravel) - Package for a listener and processor for [Paypal IPN](https://developer.paypal.com/docs/classic/ipn/gs_IPN/) responses.
- [Vanilo](https://vanilo.io/) - Basic (catalog, clients, cart, orders) e-commerce toolkit/framework for Laravel [built along the principles of Laravel itself](https://medium.com/@attilafulop/e-commerce-platform-for-laravel-c09a2bcfe8c6). \[08/17/2017\] 

### GIS/Mapping
- [GeocoderLaravel](http://geocoder-php.org/GeocoderLaravel/) - Laravel package for the well-documented and supported [GeocoderPHP](http://geocoder-php.org/Geocoder/) library.
- [GeoIP for Laravel](http://www.darwinbiler.com/laravel-4-freegeoip/) - Laravel package with fluent API for getting location information from IP address. \[06/01/2015\]
- [GooglMapper](https://github.com/bradcornford/Googlmapper) - Package for integrating Google Maps into your Laravel application. \[06/25/2018\]
- [LaraGeo](https://github.com/Fuhrmann/larageo-plugin) - Laravel package wrapper for [geoPlugin](http://www.geoplugin.com/webservices/json) IP address-to-locality web service.
- [Laravel Google Maps](https://github.com/farhanwazir/laravelgooglemaps) - Package to provide full Google Maps support to Laravel. \[07/30/2016\]
- [Laravel IP Service](https://github.com/dimsav/laravel-ip-service) - A Laravel package for [ip2nation.com](http://ip2nation.com/) to get the user's country by IP address.
- [Laravel MySQL Spatial](https://github.com/grimzy/laravel-mysql-spatial) - Package to easily work with [MySQL Spatial Data Types](https://dev.mysql.com/doc/refman/5.7/en/spatial-datatypes.html) and [MySQL Spatial Functions](https://dev.mysql.com/doc/refman/5.7/en/spatial-function-reference.html). \[09/11/2017\]
- [Laravel PostGIS](https://github.com/njbarrett/laravel-postgis) - Package to simplify use of [PostGIS](http://postgis.net/) geometry data in Laravel. \[09/11/2017\]
- [Postcode](https://github.com/garygreen/Postcode) - Simple searching by postal codes for geographic information, including latitude/longitude. \[09/24/2016\]

### Helpers/General
- [Alerts](https://github.com/prologuephp/alerts) - Package for handling global site messages in Laravel. \[07/30/2015\]
- [Beautymail](https://github.com/Snowfire/Beautymail) - Send responsive HTML emails from Laravel Blade views. \[11/03/2016\]
- [Blade](https://github.com/duncan3dc/blade) - Allows you to use Laravel Blade templates as standalone components outside of Laravel. \[10/17/2016\]
- [Blade on Steroids](https://github.com/antonioribeiro/steroids) - Several enhancements to the standard Blade syntax, including sub-templating and much more.
- [Bruno](https://github.com/esbenp/bruno) - A Laravel base controller class and a trait that will enable to add filtering, sorting, eager loading and pagination to your resource URLs. \[12/31/2016\]
- [Captain Hook](https://github.com/mpociot/captainhook) - Adds support for [web hooks](https://en.wikipedia.org/wiki/Webhook) (a.k.a. callback functions) in Laravel  Package supporting multiple JavaScript charting libraries, including ChartJS, Highcharts, Chartist, and more. \[10/15/2016\]driven by Laravel's [Event](http://laravel.com/docs/5.1/events) system. \[11/04/2015\]
- [Charts](https://github.com/ConsoleTVs/Charts) - Package supporting multiple JavaScript interactive charting libraries, including [ChartJS](http://www.chartjs.org/), [Highcharts](http://www.highcharts.com/), [Chartist](https://github.com/gionkunz/chartist-js), and more. \[10/15/2016\]
- [CSS Colors](https://github.com/SoapBox/css-colors) - Tool to automatically produce color variations/gradients for foreground and background based on input CSS hex color (wrapper for [this PHP class](http://www.barelyfitz.com/projects/css-color/)).  \[04/05/2015\] 
- [dd](https://github.com/marktopper/dd) - Laravel 4 helper similar to [new `dd` from Laravel 5](https://laravel-news.com/2014/12/laravel-5-dd-gets-upgrade/).
- [Eloquent Sluggable](https://github.com/cviebrock/eloquent-sluggable) - Extends Eloquent to include a "sluggable" trait for easy generation of [slugs](http://en.wikipedia.org/wiki/Semantic_URL#Slug).
- [Ekko](https://github.com/laravelista/Ekko) - Laravel helper package that detects active Bootstrap navigation menu (navbar) item and applies `'active'` class. \[07/18/2015\]
- [CSV/XLS File Validator](https://github.com/mdcass/file-validator) - Package for applying validation rules to CSV and XLS files to ensure they conform to your schema. \[12/16/2016\]
- [Flashy](https://github.com/mercuryseries/flashy) - Easy flash notifications for Laravel. \[01/21/2016\]
- [Full Calendar Helper](https://github.com/maddhatter/laravel-fullcalendar) - Package to simplify interaction with [FullCalendar.io](http://fullcalendar.io/) in Laravel. \[09/08/2015\]
- [Gazatem DbLogger](http://www.gazatem.com/) - Package for saving Monolog log output to database using the existing Laravel API. \[03/01/2016\]
- [Graham Campbell's Packages](https://grahamjcampbell.co.uk/) - Variety of excellent packages for extending Laravel 4/5 functionality.
- [HTML5 Inputs](https://github.com/smalldogs/html5inputs/) - Extends Laravel [Form class](http://laravel.com/docs/4.2/html) to support [HTML5 form controls](http://diveintohtml5.info/forms.html), including `color`, `date`, `datetime`, `datatime-local`, `month`, `number`, `range`, `search`, `tel`, `time`, and `week`. \[04/27/2015\]
- [HTML5 Forms for Laravel](https://github.com/Braunson/laravel-html5-forms) - Another package to extend Laravel FormBuilder to support HTML5 form elements. \[06/11/2015\]
- [Intervention Image](http://image.intervention.io/) - An open-source PHP image handling and manipulation library with Laravel facades and service providers. \[02/11/2016\]
- [iSeed](https://github.com/orangehill/iseed) - Inverse seed generator to create a database seed file using existing data in database table.
- [Ixudra Curl](https://github.com/ixudra/curl) - Laravel package for fluent curl support. \[01/23/2016\]
- [Kint](http://kint-php.github.io/kint/) - A replacement for [`var_dump()`](http://php.net/manual/en/function.var-dump.php), [`print_r()`](http://php.net/manual/en/function.print-r.php), and [`dd()`](http://laravel.com/docs/4.2/helpers#miscellaneous) for pretty printing debugging data.
- [Laracurl](https://github.com/zjango/Laracurl) - Laravel wrapper package for [PHP cURL](https://github.com/anlutro/php-curl) class that provides OOP interface to [cURL](https://en.wikipedia.org/wiki/CURL). \[10/27/2015\]
- [LaraOCR](https://github.com/alimranahmed/LaraOCR) - Adds integrated support for optical character recognition (OCR) engines like [Tesseract](https://github.com/tesseract-ocr/tesseract). \[12/04/2017\]
- [Larastrap](https://github.com/memphisphp/larastrap) - Laravel base site configuration based on Laravel 4.1, [Bootstrap 3](https://github.com/twbs/bootstrap/releases), [jQuery](https://jquery.com/), [FontAwesome](http://fontawesome.io/), and [HTML5 Shiv](https://github.com/aFarkas/html5shiv/).
- [Laravel Achievements](https://github.com/gstt/laravel-achievements) - Implements an achievement system in Laravel, based on Notifications. \[02/20/2017\]
- [Laravel Annotations](https://github.com/adamgoose/laravel-annotations) - Provides support for annotating Controller methods with the corresponding route, including route naming.
- [Laravel Auto Presenter](https://github.com/ShawnMcCool/laravel-auto-presenter) - Automatically decorates (applies formatting to) model objects bound to views during the view render process.
- [Laravel Calendar](https://github.com/makzumi/laravel-calendar) - A comprehensive calendar package with built-in support for events. \[04/22/2015\]
- [Laravel Config Writer](https://github.com/daftspunk/laravel-config-writer) - Augments the [Laravel Configuration class](https://laravel.com/docs/configuration) to include support for writing configuration parameters. \[08/17/2017\]
- [Laravel DOMPDF Wrapper](https://github.com/barryvdh/laravel-dompdf) - Laravel 4/5 package wrapper around [DOMPDF](http://dompdf.github.io/) for generating PDFs from Laravel views.
- [Laravel Email Database Log](https://github.com/shvetsgroup/laravel-email-database-log) - Simple pakcage that logs all out-going e-mails sent from Laravel to `email_log` table in application database. \[10/12/2015\]
- [Laravel Enqueue](https://github.com/php-enqueue/laravel-queue) - Open-source Laravel wrapper for the PHP Enqueue queue library with support for [several queue transport technologies](https://github.com/php-enqueue/enqueue-dev/tree/master/docs/transport), including AMQP and Redis. \[07/24/2017\]
- [Laravel Excel](http://www.maatwebsite.nl/laravel-excel/docs) - An Eloquent way of importing and exporting Excel and CSV files for Laravel 4.* with the power of PHPOffice's [PHPExcel](https://github.com/PHPOffice/PHPExcel).
- [Laravel File Generator](https://github.com/skyronic/laravel-file-generator) - Tools for helping you create your own [`artisan`](https://laravel.com/docs/artisan) commands to generate file templates. \[04/11/2017\]
- [Laravel File Manager](https://github.com/tsawler/laravel-filemanager) - File upload manager and editor for Laravel that integrates with [CKEditor](http://ckeditor.com/). \[12/31/2016\]
- [Laravel Formatter](https://github.com/SoapBox/laravel-formatter) - Port of [FuelPHP](http://fuelphp.com/) formatter library for formatting JSON, XML, YAML, and CSV data.
- [Laravel Forum](https://github.com/Riari/laravel-forum) - A complete forum package designed for easy integration into any Laravel 4 application.
- [Laravel Handlebars](https://github.com/ProAI/laravel-handlebars) - Provides support for using [Handlebars](http://handlebarsjs.com/) and [Mustache](https://github.com/bobthecow/mustache.php) templates with Laravel, including in conjunction with Blade. \[08/02/2016\]
- [Laravel HTML](https://github.com/spatie/laravel-html) - Provides fluent interface for creating HTML in Blade templates or any HTML/frontend file. \[04/17/2017\]
- [Laravel Javascript Routes](https://github.com/fedeisas/laravel-js-routes) - Package to allow simple matching of Laravel routes to JavaScript/jQuery on client side.
- [Laravel Kint](https://github.com/rtconner/laravel-kint) - Package wrapper for [Kint](http://raveren.github.io/kint/) debugging library that includes native service provider. \[08/10/2015\]
- [Laravel Medium Editor](http://www.codeforest.net/laravel-wysiwyg-editor) - Laravel package for using the [Medium WYSIWYG JavaScript Editor](http://daviferreira.github.io/medium-editor/) with Laravel 4.x.
- [Laravel Menu](http://lavary.github.io/laravel-menu/) - Package that provides fluent, Laravel-esque method for building menus.
- [Laravel Menu (Murze)](https://github.com/spatie/laravel-menu) - Laravel package for generating hierarchical HTML menus for your application. \[03/28/2016\]
- [Laravel 5 Nestable](https://github.com/atayahmet/laravel-nestable) - Provides trait support for nestable/hierarchical menus and categories in Laravel. \[11/02/2016\]
- [Laravel Options](https://github.com/appstract/laravel-options) - Provides a key-value store table named `options` for storing application configuration data. \[03/20/2017\]
- [Laravel Paginate Route](https://github.com/spatie/laravel-paginateroute) - Extension to use built-in [Laravel paginator](http://laravel.com/docs/pagination) feature without the query string. \[07/12/2015\]
- [Laravel Panel](http://laravelpanel.com/) - Clean, Bootstrap-based admin panel for Laravel 5.x. \[07/13/2015\]
- [Laravel Report Generator](https://github.com/Jimmy-JS/laravel-report-generator) - Package that simplifies generating reports in PDF, CSV, and Excel formats.
- [Laravel SASS](https://github.com/panique/laravel-sass) - Automatic SASS-to-CSS compiling for Laravel 4 (and any other framework too), config-free, in pure PHP.
- [Laravel Taggable Trait](https://github.com/rtconner/laravel-tagging) - Trait and library to support managing tags on your models. \[10/15/2016\] 
- [Laravel Talk](https://github.com/nahid/talk) - Real-time messaging package for integration with any Laravel 5 application.  See [complete tutorial](https://medium.com/@nahid/laravel-talk-a-realtime-messaging-system-d42abb8ba10a) for more information. \[12/22/2017\]
- [Laravel Tenancy](https://github.com/tenancy/tenancy) - Allows multiple sites to use same Laravel installation with client- or application-specific code to be segregated. \[07/24/2018\]
- [Laravel Transactional Events](https://github.com/fntneves/laravel-transactional-events) - Adds a transactional layer to the Laravel [Event Dispatcher](https://laravel.com/docs/events#dispatching-events). \[09/06/2017\]
- [Laravel Validation Rules](https://github.com/laravel-validation-rules) - Collection of drop-in, Composer-enabled validation rules that integrate with built-in [validation engine](https://laravel.com/docs/5.5/validation). \[09/21/2017\]
- [MailThief](https://github.com/tightenco/mailthief) - A fake mailer for Laravel applications that makes it easy to test mail without actually sending any emails. \[07/07/2016\]
- [PDF Laravel 5](https://github.com/vsmoraes/pdf-laravel5) - Package wrapper for [DOMPDF](http://dompdf.github.io/) HTML-to-PDF conversion library. \[08/16/2015\] 
- [PHP Curl](https://github.com/anlutro/php-curl) - A simple PHP wrapper class for [cURL](http://curl.haxx.se/), including Laravel [service provider](http://laravel.com/docs/ioc#service-providers) and facade.
- [Prestissimo](https://github.com/hirak/prestissimo) - [Composer](https://getcomposer.org/) plugin which allows parallel downloads (via [cURL](https://curl.haxx.se/)) to speed up installation of packages. \[05/20/2019\]
- [Quarx](https://quarx.info/) - [Open-source](https://github.com/YABhq/Quarx/) package to add CMS capabilities to your Laravel application. \[05/04/2016\]
- [Rapyd](https://github.com/zofe/rapyd-laravel) - A Laravel 4 package for building simple CRUD functions using data grids (tables) and forms.
- [Registry Manager](https://github.com/Torann/laravel-registry) - Complete package for managing application configuration settings in database with cache support for better performance. \[05/20/2015\]
- [Settings](https://github.com/edvinaskrucas/settings) - A persistent setting package for Laravel that includes encrypting/decrypting values, caching, events, and more. \[10/06/2015\]
- [Socieboy Forum](https://github.com/socieboy/forum) - Forum package for use with any Laravel 5 application. \[09/24/2016\]\
- [sudo-su](https://github.com/viacreative/sudo-su) - Handy package to allow impersonation of other users during development. \[03/15/2017\]
- [Syntara](http://mrjuliuss.github.io/syntara/) - Comprehensive user administration system for Laravel 4, including authentication, groups/permissions management, and more.
- [Throttle](https://github.com/AltThree/Throttle) - A request rate-limiter for Laravel. \[11/19/2016\]
- [Tuxedo](https://github.com/tomirons/tuxedo) - send transactional emails with Laravel's Mail classes, with the templates already done for you. \[01/14/2017\]
- [Virtuoso](https://github.com/coderabbi/virtuoso) - Extension to the built-in [View Composers](http://laravel.com/docs/4.2/responses#view-composers) functionality that provides composability of composers themselves.
- [Laravel TinyPNG API Support](https://github.com/yasmuru/ys-tinify-laravel) - Tinify API support with laravel

### JavaScript Framework Support
- [Laravel and AngularJS](https://github.com/danielschmitz/laravel_and_angularjs_codes) - Source code to go with [book](https://leanpub.com/laravel_and_angularjs) on building applications with Laravel and [AngularJS](https://angularjs.org/). \[09/02/2016\]
- [Laravel GraphQL](https://github.com/Folkloreatelier/laravel-graphql) - Adds support for [GraphQL](https://facebook.github.io/graphql/) to Laravel/Lumen. \[09/02/2017\]
- [Laravel ReactJS](https://github.com/Cohros/laravel-reactjs) - Package to simplify sending data from Laravel back-end to front-end built to [Facebook ReactJS](http://facebook.github.io/react/). \[07/18/2015\]
- [Laravue](https://github.com/laravue/laravue) - Package that integrates [Vue.JS](http://vuejs.org/) JavaScript framework for single-page web applications. \[07/27/2015\]
- [react-laravel](https://github.com/talyssonoc/react-laravel) - Package to allow using ReactJS components directly in Laravel Blade views. \[07/18/2015\]
- [React/Laravel API Starter Application](https://github.com/TomKeyte/laravel-api-react-redux-starter-app) - Starter configuration of Laravel with React and Redux to build applications with Laravel REST API backend. \[06/27/2017\]
- [React Laravel Boilerplate](https://github.com/huwcarwyn/react-laravel-boilerplate) - Custom boilerplate template for building applications with Laravel and React/Redux. \[04/17/2018\]
- [Sweet Alert](https://github.com/uxweb/sweet-alert) - Package wrapper for the stylish [Sweet Alert](http://t4t5.github.io/sweetalert/) JavaScript `alert` replacement window utility.  See this [excellent tutorial on how to use the package](http://www.askjong.com/howto/notify-like-a-boss-with-sweet-alert-and-laravel). \[07/20/2015\] 
- [vue-starter Backend API](https://github.com/layer7be/vue-starter-laravel-api) - Adds Laravel backend support, including [JWT Authentication](http://jwt.io/) using the [Dingo](https://github.com/dingo) package, to [vue-starter](https://github.com/layer7be/vue-starter). \[11/06/2015\]
- [Webpack Laravel](https://github.com/dolbex/webpack-laravel) - A full-featured Webpack + Vue.JS-loader setup for Laravel with hot reload, linting, testing & CSS extraction. \[04/30/2016\]

### Third-Party API Support
- [API for Laravel](https://github.com/dingo/api) - Package to simplify creation of RESTful API for your Laravel application.
- [AWS Service Provider for Laravel 4](https://github.com/aws/aws-sdk-php-laravel) - Official Laravel service provider to integrate [AWS SDK for PHP](http://aws.amazon.com/sdk-for-php/) with Laravel.
- [CloudConvert Laravel API](http://robbiepaul.github.io/cloudconvert-laravel/) - A Laravel package wrapper for the [CloudConvert API](https://cloudconvert.com/apiconsole).
- [Google API for Laravel](https://github.com/jadulled/googleapi-laravel) - Laravel 4 wrapper for Google APIs, including support for OAuth/Log in via Google.
- [Laravel Dropbox](https://github.com/GrahamCampbell/Laravel-Dropbox) - Package providing a fluent API to Dropbox for Laravel. \[09/26/2016\]
- [Laravel Google Calendar](https://github.com/spatie/laravel-google-calendar) - Manage events on Google Calendar via Laravel. \[05/26/2016\]
- [laravel-ratchet](https://github.com/Askedio/laravel-ratchet) - Package that provides artisan command `ratchet:serve` which starts a [Ratchet](http://socketo.me/) IO, Web Socket, or WAMP server using the class provided. \[05/16/2016\]
- [Laravel SMS](https://github.com/matthewbdaly/laravel-sms) - SMS service provider package for Laravel for sending SMS notifications via Nexmo or Clockwork. \[09/26/2017\]
- [PHP OAuth 2.0 Server for Laravel](https://github.com/lucadegasperi/oauth2-server-laravel) - [OAuth 2.0](http://oauth.net/2/) authorization server and resource server for the Laravel 4 framework.
- [Telegram Bot SDK](https://github.com/irazasyed/telegram-bot-sdk) - Unofficial Laravel package for developing bots for the [Telegram](https://telegram.org/) messenger application. \[12/30/2015\]
- [Fluent-Facebook](https://github.com/iluminar/fluent-facebook) - A laravel 5 package for reading and writing to facebook graph object with ease in laravelish syntax. \[03/06/2017\]

### REST/Web Services
- [Apiato](http://apiato.io/) - [Open-source package](https://github.com/apiato/apiato), with comprehensive documentation, to help build APIs with Laravel. \[07/26/2017\]
- [Brainsocket](http://brainsocket.brainboxmedia.ca/) - Package for supporting real-time event-driven PHP apps using WebSockets.
- [DreamFactory](https://github.com/dreamfactorysoftware/dreamfactory) - An open-source REST API backend for mobile and web applications built on Laravel. \[11/19/2016\]
- [Dingo API](https://github.com/dingo/api) - Toolkit for building RESTful API with Laravel including API versioning, rate limiting, error handling, and more.
- [Laravel API Boilerplate (JWT Edition)](https://github.com/francescomalatesta/laravel-api-boilerplate-jwt) - Package for API boilerplate to build REST API/web service quickly, including support for JWT. \[04/23/2018\]
- [Laravel GraphQL](https://github.com/studio-net/laravel-graphql) - Laravel package wrapper for [GraphQL PHP](https://github.com/webonyx/graphql-php) to support use of [GraphQL](https://facebook.github.io/graphql/) for data access with Eloquent. \[08/03/2017\]
- [Laravel JSON API](https://github.com/cloudcreativity/laravel-json-api) - Package wrapper for standardizing JSON API requests/responses according to [JSON API](http://jsonapi.org/). \[04/12/2017\]
- [Laravel Scene](https://github.com/AeonAxan/laravel-scene) - Transformer which converts Laravel models into API responses. \[12/05/2017\]
- [Laravel OpenAPI](https://github.com/jeandormehl/openapi-gen) - Laravel wrapper for OpenAPI Documentation for [OpenApi/Swagger](https://github.com/OAI/OpenAPI-Specification). \[23/10/2019\]

### Views
- [Themevel](https://github.com/shipu/themevel) - Theme and Assets Management for Laravel 5
- [AmaranJS Laravel Package](https://github.com/hakanersu/amaran-laravel) - Package wrapper for Laravel support to use excellent [AmaranJS notification jQuery plugin](http://ersu.me/amaranjs-en). \[07/13/2015\]
- [Bones Flash](https://github.com/GeneaLabs/bones-flash) - Enhanced version of built-in "flash" messages/notifications for Laravel, which includes modal popups and various levels of message. \[03/26/2017\]
- [Cursor Pagination](https://github.com/juampi92/cursor-pagination) - Pagination package to return results based on cursor value, which always returns same values. \[03/03/2018\]
- [Illuminate Menu](https://github.com/lazychaser/illuminate-menu) - A simple menu builder for Laravel using Bootstrap. \[11/04/2016\]
- [LaraTheme](https://github.com/codeWithTony/larathemes) - Simple/minimal theme manager for Laravel 5+. \[03/09/2016\]
- [Laravel API Response](https://github.com/lykegenes/laravel-api-response) - A wrapper package for [The PHP League](http://thephpleague.com/)'s [Fractal](http://fractal.thephpleague.com/) package. \[09/30/2015\]
- [Laravel Grid](https://github.com/adam-boduch/laravel-grid) - Package for displaying tabular data with support for filtering, sorting, and data from Eloquent model, collections, or arrays. \[03/09/2018\]
- [Laravel Theme](https://github.com/karlomikus/theme) - Package for adding theme support via [ViewServiceProvider](https://laravel.com/api/5.1/Illuminate/View/ViewServiceProvider.html) API. \[05/01/2016\]
- [Laravel View Themes](https://github.com/alexwhitman/laravel-view-themes) - Specify custom themes for your views in simple manner. \[05/25/2015\]
- [SwitchBlade](https://github.com/awkwardideas/SwitchBlade) - Add several useful directives to Laravel Blade templates, including support for [`switch`](http://php.net/manual/en/control-structures.switch.php), variable and debugging output, and empty/null variable checks. \[03/06/2017\]

### Web Forms
- [Bootforms](https://github.com/adamwathan/bootforms) - Package which simplifies and streamlines the process of specifying forms in Laravel with [Bootstrap](http://getbootstrap.com/) 3 markup.
- [Bootstrap Form](https://github.com/dwightwatson/bootstrap-form) - Allows simple creation of [Bootstrap](http://getbootstrap.com/) 3-styled form groups, including horizontal styling.
- [Former](https://anahkiasen.github.io/former/) - Package to structure and format web forms in Laravel idiomatic style.
- [JQuery Validator](https://github.com/davidthingsaker/laravel-validator) - Basic jQuery client-side form validator extension that uses same syntax as [Laravel Validation service](http://laravel.com/docs/validation). \[04/22/2015\]
- [Laravel Form Builder](https://github.com/kristijanhusak/laravel-form-builder) - Package for constructing HTML forms using PHP classes, including support for Laravel [form-model binding](http://laravel.com/docs/4.2/html#form-model-binding).
- [Laravel Form Validator](https://github.com/GrandadEvans/laravel-form-validator) - An extension of [way/generators](https://github.com/JeffreyWay/Laravel-Generators) for setting up form validators.
- [Twitter Bootstrap Forms](https://github.com/boxfrommars/rutorika-laravel-html) - Custom form controls based on Twitter Bootstrap. \[03/09/2016\]

### WordPress Integration
- [Blade for Wordpress](https://github.com/MikaelMattsson/blade) - Wordpress plugin that allows use of Blade syntax. \[07/16/2015\]
- [Classy](https://github.com/anrw/classy) - Light, well-structured WordPress theme framework based on [Laravel Blade](https://laravel.com/docs/blade) template engine. \[07/28/2016\]
- [Corcel](https://github.com/jgrossi/corcel) - PHP class library that allows you to query [Wordpress](https://wordpress.org/) [database](http://codex.wordpress.org/Database_Description) with Laravel Eloquent ORM syntax.
- [Cutlass WordPress Starter Theme](http://cutlasswp.com/) - Use Laravel Blade template syntax in your WordPress templates.  Includes Bootstrap and Font Awesome by default.
- [Koselig](https://github.com/koselig/koselig) - Laravel build that integrates access to WordPress API. \[05/01/2018]\
- [w.eloquent](https://github.com/bruno-barros/w.eloquent) - Wordpress integrated with Laravel via Composer. \[11/19/2016\]
- [WordPress Laravel Bootstrap](https://github.com/golr/wl-bootstrap) - Use any functions, methods, libraries of Laravel in WordPress projects. \[03/15/2017\]

## Tutorials

### Tutorials (General)
- [Getting Started with Pusher and Laravel Echo](https://www.youtube.com/watch?v=Qoti7G-tjN8) - In this screencast, The Skater Dev teaches how to build a real-time comments component using Laravel, Laravel Echo, and the Pusher Laravel Echo integration.
- [25 Laravel Tips and Tricks](http://code.tutsplus.com/tutorials/25-laravel-tips-and-tricks--pre-92818) - Jeffrey Way gives a nice overview/introduction to Laravel 4 in the form of more than two dozen tips.
- [Laravel 101](https://github.com/cviebrock/laravel-101-slides) - Colin Viebrock's introduction to Laravel with associated code.
- [Laravel 4 on Google AppEngine for PHP](http://blog.neoxia.com/laravel-4-on-google-appengine-for-php/) - Step-by-step instructions for setting up Laravel to run on [Google App Engine](https://cloud.google.com/appengine/).
- [Laravel 4 on a shared host](http://driesvints.com/blog/laravel-4-on-a-shared-host) - Shared hosting can be difficult to set up for Laravel. Here are some good tips.
- [Laravel Apz](https://github.com/jp7internet/laravel-apz) - Github repository with full tutorial on building Laravel 5.x application including AJAX CRUD, Bootstrap, and REST API. \[07/26/2017\]
- [Laravel on OpenShift](https://github.com/luciddreamz/laravel) - Instructions and customized package for using Laravel on [OpenShift](https://www.openshift.com/) PaaS.
- [Laravel Tutorials on Creative Punch](http://creative-punch.net/articles/php-articles/laravel-tutorials/) - Series of unique Laravel tutorials, with special focus on available packages.
- [Laravel Video Tutorials](http://andrewperkins.net/laravel) - Free, 10-part Laravel video tutorial with source code.  (Videos mirrored [here](http://www.dwidi.net/video_tag/laravel/).)
- [Learning Laravel](http://learninglaravel.net/) - New book/tutorial site for beginners to the Laravel framework.
- [Test Better, Deploy Faster with Laravel](http://www.developer.com/lang/php/test-better-deploy-faster-with-laravel.html) - Nice overview of Laravel concepts and how to use it for TDD.
- [Tinkering with Tinker Like an Artisan](http://blog.enge.me/post/tinkering-with-tinker-like-an-artisan) - I think Tinker is one of the greatest features in all of Laravel!
- [Using AJAX in Laravel](http://blog.igeek.info/2013/using-ajax-in-laravel/) - While Laravel doesn't have "native" AJAX support, it's routing supports AJAX nicely.
- [Using Laravel Homestead as Your Development Environment](http://blog.teamtreehouse.com/using-laravel-homestead-development-environment) - Excellent, detailed tutorial on setting up [Vagrant](http://www.vagrantup.com/) and using it with Laravel [Homestead](http://laravel.com/docs/homestead) for development.

### Tutorial Series (Multi-part tutorials on Laravel basics)
- [Philip Brown's Cribbb Tutorials](http://culttt.com/tag/cribbb/) - Comprehensive tutorials on building application with Laravel 4.
- [Creating a Basic To Do Application in Laravel 5](https://www.flynsarmy.com/2015/02/creating-a-basic-todo-application-in-laravel-5-part-1/) - Excellent 4-part tutorial that covers all of the concepts for building Laravel application.
- [Laracademy](https://laracademy.co/) - Video tutorials on Laravel topics, similar to Laracasts. \[05/09/2016\]
- [Laravel 4 Tutorials](https://medium.com/laravel-4/) - Drills down into the details that underlie the implementation of Laravel 4 to help you better understand the concepts and principles.
- [Laravel 5 Beauty](http://laravelcoding.com/blog?tag=L5+Beauty) - Comprehensive, step-by-step tutorial for building a complete application with Laravel 5. \[08/13/2015\]

### Tutorials on Specific (and Frequently Occurring) Topics
- [Eloquent Model Relationships](http://codeplanet.io/laravel-model-relationships-pt-1/) - Excellent, detailed explanation of the various [model relationship types](http://laravel.com/docs/eloquent#relationships) in Laravel.  (Source code [here](https://github.com/dtrenz/laravel-model-demo).) \[04/29/2015\]
- [Laravel user types and polymorphic relationships](http://www.richardbagshaw.co.uk/laravel-user-types-and-polymorphic-relationships/) - An alternative to [single-table inheritance (STI)](http://martinfowler.com/eaaCatalog/singleTableInheritance.html) using Laravel's [polymorphic relationships](http://laravel.com/docs/4.2/eloquent#polymorphic-relations).
- [Single-Table Inheritance in Laravel 4](http://www.colorfultyping.com/single-table-inheritance-in-laravel-4/) - Excellent tutorial on dealing with models that share common attributes, except for a small number of class- or type-specific attributes.
- [Limiting 'Belongs To Many' database queries with Pivot table values](http://stephen.rees-carter.net/thought/limiting-belongs-to-many-database-queries-with-pivot-table-values-in-laravel) - Also explains how to access additional attributes on [pivot tables](http://laravel.com/docs/4.2/eloquent#many-to-many).
- [Sharing Laravel Homestead Sites](https://medium.com/@genealabs/sharing-laravel-homestead-sites-ad05aa218022) with [ngrok](https://ngrok.com/) - If you have a Laravel Homestead (or *[other Vagrant Laravel environment](https://github.com/TimothyDJones/laravel-precise32-php5.4)*) that you want to share with others, these instructions will help you get it going.

## Resources
- [Awesome Laravel Repos](https://awesomerepos.com/laravel) - Directory of popular (based on stars) GitHub repositories for Laravel packages/resources. \[11/06/2017\]
- [Eloquent 101](http://eloquent101.com/) - Free tutorial on [Eloquent ORM](https://laravel.com/docs/eloquent) underlying Laravel framework. [Off-line version available](https://github.com/ahuggins/eloquent101), as well. \[06/25/2018\]
- [LaraBrain](http://larabrain.com/) - Directory of tips and tutorials for all aspects of Laravel development. \[11/03/2015\]
- [Laracasts](https://laracasts.com/) - The _de facto_ standard tutorials for Laravel developed by Jeffrey Way.  (Some free Laracasts videos on YouTube [here](https://www.youtube.com/user/laracasts).)
- [Larachat Live](https://www.youtube.com/channel/UCKAj-eBdBINhJ2Bi9lut29A) - YouTube channel with weekly topics on Laravel platform. \[05/30/2017\]
- [Laracon 2014 Videos](http://userscape.com/laracon/2014/) - Directory of videos from 2014 Laracon in NYC.
- [Laravel Database Designer](https://biodesignrealworld.github.io/LaravelDatabaseDesigner/) - Online tool for creating database model, including exporting as migration. \[05/16/2015\]
- [Laravel Dojo](http://www.laravel-dojo.com/) - Tutorials on Laravel in Chinese (English translation [here](https://translate.google.com/translate?hl=en&sl=zh-CN&tl=en&u=http%3A%2F%2Fwww.laravel-dojo.com%2F)).
- [Laravel Hunt](https://laravel-hunt.com/) - A forum/directory for Laravel tutorials, examples, resources, etc. in the style of [Product Hunt](http://www.producthunt.com/). \[06/08/2015\]
- [Laravel Schema Designer](http://laravelsd.com/) - Online tool for creating Laravel database schema and export the migration.  You can share your schemas with others via the site.
- [LaravelSnippets.com](http://laravelsnippets.com/) - A repository of useful code snippets for Laravel PHP framework.
- [Laravel Tricks](http://www.laravel-tricks.com/) - Code snippets, best practices, and tips for Laravel development.
- [The Laravel Podcast](http://www.laravelpodcast.com/) - Brings you Laravel and PHP development news and discussion hosted by Matt Stauffer. \[04/12/2015\]
- [LaraShout](http://www.larashout.com/) - Helps you to learn Laravel, PHP, JavaScript and CSS. Enhance you web development skills and succeed.

### Applications Built with Laravel
- _[External List of Laravel Applications](https://github.com/unicodeveloper/awesome-opensource-webapps#laravel)_ \[03/28/2016\]
- _[Another Directory of Laravel Applications](https://devpost.com/software/built-with/laravel) \[12/31/2016\]
- [92five](http://92fiveapp.com/) - Open-source, self-hosting project management application.
- [A1Pager](https://a1pager.com/) - Free, online tool for creating a one-page web site with no coding. \[07/16/2018\]
- [AccountsPortal](http://www.accountsportal.com/) - Hosted online accounting application with support for invoicing, books and accounts. \[04/20/2015\]
- [AgoraKit](https://github.com/philippejadin/agorakit) - Full-featured, open-source groupware platform for citizens' initatives, including calendar, online discussion forums, and more. \[08/18/2017\]
- [Alpha Coders](https://alphacoders.com/) - Social media site for content creators (mainly graphics) to share their creations. \[08/20/2017\]
- [Amila CMS](https://github.com/AlexStack/Laravel-CMS) - Simple Bootstrap Laravel CMS for any EXISTING or new Laravel 6 website.  \[09/11/2019\]
- [Asgard CMS](http://asgardcms.com/) - CMS built with Laravel with goals of modularity, multi-language support, and ease of installation.
- [Attendize](https://www.attendize.com/) - Free, [open-source](https://github.com/Attendize/Attendize), self-hosted ticket sales and event management platform. \[03/09/2016\]
- [Author's Republic](https://www.authorsrepublic.com/) - E-commerce site for authors to sell audio books. \[10/20/2015\]
- [BarChart.com](https://www.barchart.com/) - Portal for financial experts and businesses to get the latest market data for US, UK, Australia and Canadian stock markets. \[08/20/2017\]
- [Bible Super Search](https://sourceforge.net/projects/biblesuper/) - Bible study tool with advance search capabilities, includes API and GUI front-end. \[04/11/2020\]
- [Bombsite](https://bombsite.io/) - Free, online web site builder built with Laravel. \[04/23/2018\]
- [Bootsnipp](http://bootsnipp.com/) - Element gallery, playground and code snippets for Bootstrap framework.
- [BootstrapCMS](https://github.com/BootstrapCMS/CMS) - Comprehensive CMS built with Laravel using [Sentry](https://cartalyst.com/manual/sentry/) for user management/authentication.
- [BotMan Studio](https://github.com/botman/studio) - Laravel application to build custom chat bots using [BotMan](https://botman.io/). \[08/19/2017\]
- [BuildPrint](https://buildprint.io/) - Document and share your mods for most anything (cars, bicycles, drones) online. \[01/08/2018\]
- [Bumble CMS](http://bumblecms.com/) - CMS platform for Laravel framework with focus on simplicity. \[09/04/2015\]
- [Burnmsg](https://burnmsg.com/) - Simple self-destructing, [encrypted messaging application](http://www.edzynda.com/create-a-self-destructing-encrypted-message-app-in-laravel-part-1/) built on Laravel.  [Open-source, self-hosted version available on Github.](https://github.com/ezynda3/burnmsg)
- [Cachet](https://cachethq.io/) - A single-site, alternative to https://statuspage.io written in PHP with the Laravel project, supporting both SQLite and MySQL databases.
- [Canvas](https://cnvs.io/) - An [open-source](https://github.com/cnvs/canvas) minimalist blogging platform for developers which uses [Summernote WYSIWIG editor](http://summernote.org/) for Markdown support built with Laravel. \[07/07/2016\] 
- [Circuits.com](https://circuits.com/) - Electronic components marketplace with comprehensive search capability and over 3 billion parts in stock.
- [Coanda CMS](http://coandacms.org/) - Coanda CMS is a content management system based on the Laravel PHP Framework. \[04/13/2015\]
- [Coaster CMS](https://www.coastercms.org/) - Full-featured CMS platform with built-in support for [beacons](https://google.github.io/physical-web/). \[03/26/2017\]
- [Codex](http://codex.caffeinated.ninja/) - A simple file-based Markdown documentation platform built on top of Laravel.
- [Collabbing.com](https://collabbing.com/) - Site for collaborating with other developers on ideas and projects. \[04/23/2018\]
- [Colorsublime](http://colorsublime.com/) - Directory of [Sublime Text](http://www.sublimetext.com/) themes along with a plugin to simplify installation of those themes.
- [Confomo](https://confomo.com/) - Simple, [open-source](https://github.com/mattstauffer/confomo) tool for keeping track of contacts that you meet at conferences. \[07/27/2016\]
- [Commentum.io](https://commentum.io/) - A Reddit clone built with Laravel that scores entries based on "momentum" from events like views, comments, etc. \[08/31/2015\]
- [Daybyday CRM](https://github.com/Bottelet/DaybydayCRM) - Full-featured CRM application with tasks and lead management, role-based settings, document attachements, and more (formerly known as Flarepoint CRM). \[08/26/2020\]
- [Decoy CMS](https://github.com/BKWLD/decoy) - Full-featured CMS with support for sharing models with other applications. \[03/15/2017\]
- [Devise CMS](http://devisephp.com/) - Open-source CMS built on Laravel intended to be used for both small and large CMS needs. \[09/29/2015\]
- [DevLeaks](http://devleaks.com/) - Web development news aggregator for tutorials, tools, and other resources of interest to developers. \[08/03/2015\]
- [dnsrecords.io](https://dnsrecords.io/) - [Open-source](https://github.com/spatie/dnsrecords.io) online DNS record lookup utility. \[10/26/2017\]
- [Dying Horizon](https://dyinghorizon.com) - Free post-apocalyptic, turn-based, role-playing browser game built with Laravel 5.1. \[11/21/2017\]
- [Earthquake Stream](https://earthquake.stream/) - Real-time feed of earthquakes reported by USGS to [demonstrate](https://medium.com/@piesse/laravel-horizon-and-earthquake-stream-d67a794bc9b5) Laravel [Horizon queue service](https://horizon.laravel.com/). \[09/21/2017\]
- [Easy Decision Maker](http://easydecisionmaker.com/) - Online tool for creating multiple-choice questions. \[10/21/2015\]
- [Filegr.am](http://filegr.am/) - Share files up to 1GB for 24 hours with no sign up or installation. \[07/31/2015\]
- [Flarum](http://flarum.org/) - Open-source forum software intended to make online discussions simple, fun, and fast. \[08/28/2015\]
- [Flashtag CMS](https://flashtag.org/) - [Open-source](https://github.com/flashtag/cms) simple CMS and blogging platform built with Laravel. \[04/12/2016\]
- [Food Zoo Menu](http://www.umt.edu/dining/foodzoomenu) - University cafeteria menu listings using Laravel REST API and AngularJS. \[05/09/2016\]
- [Geocod.io](http://geocod.io/) - Low-cost (2500 transactions per day free) geocoding web service built by [Mathias Hansen](https://twitter.com/MathiasHansen).
- [Gistlog](https://gistlog.co/) - Markdown-based blogging tool that uses Github's Gist platform for storage (more [here](https://laravel-news.com/2015/02/gistlog/)).
- [Git.cash](https://git.cash/) - Online marketplace for digital products with built-in Git integration. \[08/28/2017\]
- [GitGo](https://gitgo.io/) - Git repository hosting site with beautiful UI (includes free plan).
- [GitScrum](https://github.com/renatomarinho/laravel-gitscrum) - Laravel application that integrates Git version control with Scrum methodology for task management. \[12/16/2016\]
- [Handesk](https://github.com/BadChoice/handesk) - Help desk ticketing and lead management tool built with Laravel. \[01/19/2019\]
- [HasYourBabyArrivedYet.com](http://hasyourbabyarrivedyet.com/) - Free, simple service for sharing news about the arrival of your baby. \[08/11/2016\]
- [HiveStory](http://hivestory.com/) - Online collaborative story-writing application. \[11/09/2015\]
- [Interactive Books' Atelier](http://lostideaslab.com/pirates-lost-pearl/interactive-books-atelier/) - [Open-source](http://github.com/lil-plp/iba) customized CMS for managing small book clubs, including notes, recommendations and more. \[01/09/2018\]
- [Invoice Ninja](https://www.invoiceninja.com/) - Online small business invoicing platform with free plan up to 500 clients.  [Open-source, self-hosted version available on Github.](https://github.com/hillelcoren/invoice-ninja)
- [Jigsaw](http://jigsaw.tighten.co/) - [Open-source](https://github.com/tightenco/jigsaw) static site generator and CMS tool built with Laravel that supports Blade templating and markdown. \[04/13/2016\]
- [Jumpertrax](https://www.jumpertrax.com/homepage) - Online sports event entry and tracking tool. \[05/10/2016\]
- [Kraken CRM](http://krakencrm.github.io/kraken/) - A simple, lightweight CRM (contact management tool) \[Under development\]. \[05/20/2015\]
- [Koel](http://koel.phanan.net) - A simple, [open-source](https://github.com/phanan/koel) web-based personal audio streaming service (i.e., [Spotify](https://www.spotify.com/) clone) written in [Vue.js](http://vuejs.org/) on the client side and Laravel on server side. \[12/14/2015\]
- [Kyle](https://github.com/laravelista/kyle) - Monthly billing/invoicing application built on Laravel. \[06/18/2016\]
- [LaraAdmin](http://laraadmin.com/) - [Open-source](https://github.com/dwijitsolutions/laraadmin) CRM platform that features CRUD generation, module and metadata management, media file (image, multimedia, etc.) management, and built-in code editor (based on [Ace Code Editor](https://ace.c9.io/)). \[08/30/2016\]
- [LaraEstimate](https://github.com/TiagoSilvaPereira/laraestimate) - Complete web design/development estimating and quoting tool built with Laravel and [Vue.JS](https://vuejs.org/). \[07/14/2020\]
- **[Laravel Open Source Projects](https://github.com/goodnesskay/Laravel-Open-Source-Projects)** - Large list of open-source Laravel projects, including flags for projects which can be used for tutorials. \[06/27\2017\]
- [Laravel Site](https://github.com/iZaL/laravel-site) - A custom CMS and event management platform built on Laravel 4.
- [Lavalite](http://www.lavalite.org/) - Multilingual CMS built on Laravel 4 and Bootstrap 3.
- [Learning Locker](https://learninglocker.net/) - An [open-source](https://github.com/LearningLocker/learninglocker) online tool to track learning/education records.
- [Leesmee](https://leesmee.com/) - Dutch language social news site. \[09/17/2018\]
- [Less Than Threes](https://lessthanthrees.com/) - Site to quickly and easily share collections of things you enjoy, such as movies, books, etc. (Source code [here](https://github.com/snipe/lessthanthrees).) \[08/19/2017\]
- [Lightweight Hiker](https://lwhiker.com/) - Site to search for used hiking/backpacking gear. \[02/15/2016\]
- [Listymail](https://listymail.com/) - Free online tool for email distribution lists. \[02/15/2016\]
- **[Made with Laravel](https://madewithlaravel.com/)** - Online gallery of applications and tools built with Laravel. \[06/25/2018\]
- [Makers Cabin](https://makerscabin.com/) - Learn full-stack web development using Laravel, Bootstrap, and other popular technologies. \[08/16/2017\]
- [Mascots](https://mascots.stevil.co/) - An [open-source]() database of mascots of various teams and organizations. \[11/19/2016\]
- [Maghnatis](http://maghnatis.com/) - Open-source Reddit clone forum application built with Laravel.  (Source code available [here](https://github.com/Halnex/laravel-reddit).) \[10/27/2015\]
- [Monica](https://monicahq.com/) - [Open-source](https://github.com/monicahq/monica) personal CRM for helping you keep track of your friends and family. \[10/02/2017\]
- [New Movies Coming Out](https://newmoviescomingout.us/) - Directory of US movie releases, including option for weekly e-mail notification. \[04/23/2018\]
- [OpenDominion](https://opendominion.net/) - [Open-source](https://github.com/WaveHack/OpenDominion), free online text-based strategy game in a medieval fantasy setting where you control a nation ('dominion'). \[11/06/2017\]
- [Opus](https://github.com/zeeshanu/opus) - Open-source knowledge-base platform for teams to improve collaboration. \[03/20/2017\]
- [Orchestra Platform](http://orchestraplatform.com/) - Laravel-based application boilerplate.
- [Paperwork](http://paperwork.rocks/) - Open-source note-taking/PIM alternative to [Evernote](https://evernote.com/) and Microsoft [OneNote](http://www.onenote.com/) built on Laravel, [AngularJS](https://angularjs.org/) and Bootstrap 3.
- [PasteCloud](https://pastecloud.net/) - Free online snippet/notepad. \[12/16/2016\]
- [PhotonCMS](https://photoncms.com/) - RESTful API-driven/headless CMS built on Laravel and Vue.js. \[03/03/2018\]
- [Picnic](http://mjolnic.com/picnic/) - On-demand image post-processing package built on Laravel 4. \[04/25/2015\]
- [Polr](https://polrproject.org/) - Quick, modern, [open-source](https://github.com/cydrobolt/polr) link/URL shortener built with Lumen. \[09/02/2017\]
- [Project Tools](https://sourceforge.net/project/project-tools/) - Self-hosted, open-source application for managing project requests that allows managers to assess the business value. \[05/02/2018\]
- [Pterodactyl](https://pterodactyl.io/) - Open-source (code [here](https://github.com/Pterodactyl/Panel)), game-agnostic game administration/management platform. \[04/24/2017\]
- [pwdquery](https://pwdquery.xyz) - Online tool for checking if your password/account has been compromised. \[06/25/2018\]
- [QnA](https://github.com/TheRealJAG/Laravel-QnA) - Question-and-answer site with support for up and down voting (i.e., Stack Overflow clone) built with Bootstrap and [Material Design](https://mdbootstrap.com/material-design-for-bootstrap/). \[04/11/2017\]
- [RasP.is](http://rasp.is/) - Basic URL shortener and bookmarking utility built with Laravel. Source code [here](https://github.com/kamranahmedse/laravel-url-shortener). \[10/10/2017\]
- [Reddit Grid](https://redditgrid.com/) - Browser for image-heavy Sub-Reddits with NSFW filtering. \[09/26\2017\]
- [Rewind Radio](https://www.rewindradio.com/) - Online tool for making and sharing radio clips including display of waveform audio. \[10/21/2015\]
- [RSS For the Rest of Us](https://rss.fortherestof.us/) - Open-source (code [here](https://github.com/wilderborn/rss-for-the-rest-of-us)) RSS feed reader built on Laravel using the new [JSON Feed](https://jsonfeed.org/) format. \[08/30/2017\]
- [Screeenly](http://screeenly.com/) - Open-source (source code [here](https://github.com/stefanzweifel/screeenly)) tool and API to create screen shots of web sites.
- [Shopopotamus](https://shopopotamus.com/) - Nice, responsive e-commerce site built on Laravel. \[12/11/2017\]
- [Shoulders CMS](https://github.com/ShouldersCMS) - Basic CMS built with Laravel. \[06/25/2018\]
- [snapr.pw](https://snapr.pw/) - Free online image hosting site built on Laravel. \[10/21/2015\]
- [Snipe-IT](http://snipeitapp.com/) - A free open source (source code [here](https://github.com/snipe/snipe-it)) IT asset/license management system built in PHP on Laravel 4.2 and Bootstrap 3. \[08/13/2015\]
- [Spiral](http://spiral.ac/) - Educational technology tools for collaboration and progress reporting. \[10/21/2015\]
- [Sprint Boards](https://sprintboards.io/) - Free agile development project management tool based on user story cards. Check out the [blog](https://blog.sprintboards.io/) to learn about how it works and was built. \[01/19/2019\]
- [SquareBit](https://squarebit.io/) - Digital ecommerce marketplace for books, software, and other goods with Git integration. \[01/08/2018\]
- [StackPile](https://stackpile.io/) - Online tool for managing third-party APIs used by your application, built with Laravel and [Vue.js](http://vuejs.org/). \[03/28/2016\]
- [Statimgram](https://statimgram.com/) - Allows you to publish images to multiple Instagram accounts simultaneously and schedule your posts. \[08/11/2016\]
- [Style CI](https://styleci.io/) - Free PHP coding style continuous integration service that checks and (optionally) fixes Github public repositories against PHP coding standards.
- [TestApi.io](https://testapi.io/) - Free, online API mock creator. \[03/23/2016\] - Allows you to publish images to multiple Instagram accounts simultaneously and schedule your posts. \[08/11/2016\]
- [Thermosis Framework](http://framework.themosis.com/) - [WordPress](http://wordpress.org/) framework that embeds Laravel to build complex applications.
- [Thor CMS](http://thorcms.github.io/) - A multipurpose Laravel 4 CMS platform and CRUD generator with built-in multi-language support. \[04/25/2015\]
- [TimeGrid.io](http://www.timegrid.io/) - Online reservation-booking application. Open-source application with source code available [here](https://github.com/alariva/timegrid). \[11/23/2015\]
- [TruckJee](http://www.truckjee.com/) - Similar to Uber for truck transport in India. \[07/12/2016\]
- [Tumbly](https://github.com/AkgunFatih/Tumbly) - Tumbly is a quick, lite and clean Tumblr Client Web App. \[23/12/2019\]
- [TweetLater](http://tweetlater.xyz/) - Online tool to schedule sending tweets in the future. \[11/06/2017\]
- [Vale Brewing](http://valebrewing.com.au/) - Nice, well-structured web site for Australian craft brewer. \[10/20/2015\]
- [vimrcfu](https://github.com/florianbeer/vimrcfu) - Share your best vimrc snippets.  (Source for [vimrcfu.com](http://vimrcfu.com/).)
- [Visual Bookmark Organizer](https://rivario.com/bookmark/) - Online bookmark tool that shows thumbnails of bookmarked site.  (Source code on [Github](https://github.com/yhbyun/laravel-bookmark).) \[04/22/2015\]
- [Voten](https://voten.co/) - Social bookmarking site with support for up- and down-voting as well as discussions.  (Source code [here](https://github.com/voten-co/voten).) \[08/19/2017\]
- [Vuedo](https://github.com/vuedo/vuedo) - Open-source blogging platform built with Laravel and [Vue.js](https://vuejs.org/) with Markdown editor and Amazon S3 integration. \[07/18/2016\]
- [Wardrobe](http://wardrobecms.com/) - A minimalist blogging platform and CMS supporting Markdown and simple theming.
- [Workeer](https://workeer.de/) - German-language site for helping refugees find jobs. \[11/06/2017\]
- [Xenon Support Center](https://github.com/shellprog/Xenon-Support-Center/) - A comprehensive, but minimal, open-source ticket- and conversation-management platform.

### Books
- *[Easy Laravel 5: A Hands On Introduction Using a Real-World Project](http://easylaravelbook.com/)* - W. Jason Gilmore's book on building applications with Laravel framework.
- [Laravel Application Development Blueprints](https://www.packtpub.com/web-development/laravel-application-development-blueprints)
- [Laravel Application Development Cookbook](https://www.packtpub.com/web-development/laravel-application-development-cookbook) - [Terry Matula](https://github.com/matula)
- [Leanpub Laravel Books](https://leanpub.com/book_search?search=laravel) - Directory of Leanpub books on Laravel.  Some free!
- [Learning Laravel 4 Application Development](https://www.packtpub.com/web-development/learning-laravel-4-application-development) - [Hardik Dangar](https://plus.google.com/+HardikDangar/)
- [Laravel 5 Beauty](https://leanpub.com/l5-beauty) - [Chuck Heintelman](http://laravelcoding.com/blog) \[08/13/2015\]
- [Laravel: Up and Running](http://laravelupandrunning.com/) - Upcoming book from [Matt Stauffer](https://twitter.com/stauffermatt) for experienced developers looking to learn Laravel for the first time. \[02/11/2016\]

### References
- [75 Laravel Tutorials, Packages, and Resources from 2014](https://laravel-news.com/2014/12/75-laravel-tutorials-packages-resources-2014/) - Nice summary of the key events and tutorials in the Laravel world for 2014, from the folks at [Laravel News](https://laravel-news.com/).
- [Alternate Laravel Documentation](http://readouble.com/laravel/) - In easier to read format (Japanese/English). \[04/15/2015\]
- [Cheatsheetr](http://cheatsheetr.com/) - [Maks Surguy](http://maxoffsky.com/)'s topical cheat sheets for Laravel and Bootstrap.
- [Eloquent Relationships Cheat Sheet](https://hackernoon.com/eloquent-relationships-cheat-sheet-5155498c209) \[10/09/2017\]
- [Your One-Stop Guide to ~~Laravel~~ Artisan Commands](http://code.tutsplus.com/tutorials/your-one-stop-guide-to-laravel-commands--net-30349)
- [LaraGuide (Laravel Code Guide)](https://laraguide.surge.sh/) - Comprehensive guide on some of the more complex and esoteric aspects of Laravel for beginners. \[11/02/2017\]
- [LaraPulse](https://github.com/rinvex/larapulse) - Weekly summary of changes to Laravel framework and tips and snippets from Laravel world. \[08/31/2016\]
- [Laravel 5 Cheat Sheet](http://www.linxiang.info/l5-cs/) \[05/11/2015\]
- [Laravel 5.1 LTS Cheat Sheet](https://aufree.github.io/laravel5-cheatsheet/) \[04/13/2016\]
- [Laravel 5.1 LTS Cheat Sheet](https://summerblue.github.io/laravel5-cheatsheet/) \[05/04/2016\]
- [Laravel 5.1 LTS Cheat Sheet (Chinese)](https://cs.laravel-china.org/) \[07/26/2017\]
- [Laravel Cheat Sheet](http://cheats.jesse-obrien.ca/)
- [Laravel Cheat Sheet as a Phone Gap Application](https://github.com/gbanina/laravel-cheat-sheet) - Nice Laravel reference wrapped as a [PhoneGap](http://phonegap.com/)/[Cordova](http://cordova.apache.org/) application for viewing on mobile devices.
- [Laravel Errors](http://eecs.mines.edu/Courses/csci445/ASSIGN/laravel0.html#errors) - Good list of common Laravel errors and tips about typical causes.
- Another [Laravel Cheat Sheet](http://alexrussell.me.uk/laravel-cheat-sheet/)
- Another [Laravel Cheat Sheet (PDF)](https://docs.google.com/viewer?url=http://blog.kyawzinwin.me/wp-content/uploads/2014/03/Laravel-Cheatsheet.pdf)
- Another [Laravel Cheat Sheet (PDF)](https://docs.google.com/viewer?url=https://github.com/Turaylon/laravel4-cheat-sheet/raw/master/cheat-sheet-A4.pdf) \[04/30/2015\]
- [Laravel Guide](http://laravel-guide.readthedocs.io/) - Easy-to-read and navigate view of the Laravel documentaiton. \[05/17/2016\]
- [Laravel The Right Way](http://www.laravelbestpractices.com/) - *Opinionated* guide to Laravel development best practices, inspired by [PHP The Right Way](http://www.phptherightway.com/).
- [LaraVer](https://laraver.xyz/) - Online reference to the current released version of Laravel.  With free account, you can see differences of current version to any previous version. \[12/07/2015\]

### Example Applications
- **[OpenLaravel](http://openlaravel.com/)** - Directory of open-source projects built with Laravel framework. (Source code [here](https://github.com/ammezie/openlaravel).) \[08/30/2016\]
- [Airflix](https://github.com/wells/airflix) - A web application for browsing and playing movies and TV shows from a local home server built with Laravel and [Vue.js](http://vuejs.org/). \[07/27/2016\]
- [Alfred CMS](http://www.alfred-cms.com/) - CMS built with Laravel and AngularJS that supports developer needs, but is simple for users. \[05/09/2016\]
- [Anvil CMS](https://github.com/loic-sharma/Anvil) - A basic CMS built on top of Laravel 4 with other components.
- [Arcanesoft CMS](https://github.com/ARCANESOFT/ARCANESOFT) - CMS built on Laravel with multiple packages that can be used independently. \[12/18/2015\]
- [Auto-Generating Gallery](https://github.com/martindilling/auto-generating-gallery) - Basic image gallery application with support for auto-generation of thumbnails, albums, and more.
- [BookStack](https://github.com/ssddanbrown/BookStack) - A simple, self-hosted, easy-to-use, wiki-like platform and [Confluence](https://www.atlassian.com/software/confluence/) alternative for organising and storing information. \[01/02/2016\]
- [Bookymark](https://github.com/mikedfunk/bookymark) - Basic web site bookmarking application built with Laravel 4, including full tests. \[04/28/2015\]
- [CocoPass](https://github.com/Elvenisboy/CocoPass) - Password management system similar to [LastPass](https://lastpass.com/) build with Laravel 5.3. \[09/13/2016\]
- [Collejo](https://github.com/codebreez/collejo) - Comprehensive ERP platform for schools and other education institutions built with Laravel. \[03/26/2017\]
- [Communalizer](https://github.com/communalizer) - Free, open-source and self-hosted forum system written on top of the Laravel framework. \[06/23/2016\]
- [DClassifieds](https://github.com/gdinko/dclassifieds.laravel) - Free, open-source classified ads script with support for social media login, bonus/reward system, multiple category types and more. \[03/26/2017\]
- [Dingo Project Management](https://github.com/zeeshanu/dingo-project-managment) - A full-featured personal project management tool with task boards. \[04/26/2016\]
- [Doptor CMS](http://www.doptor.org/) - Free, open-source CMS built with Laravel and Bootstrap that includes drag-and-drop form editing. \[03/02/2016\]
- [EasyAdmin](https://github.com/laravelish/EasyAdmin) - Advanced Laravel Login and User Management with Two-Factor Authentication. \[06/09/2016\]
- [Elephant Traders](https://github.com/matthewtrask/elephpant-traders) - Basic Laravel site example for e-commerce built for swapping PHP Elephant plush toys. \[12/11/2017\]
- [EESTEC Platform for Local Committees](https://github.com/angelov/eestec-platform) - Committee management tool for engineering student association. \[11/23/2015\]
- [GH-analytics](https://github.com/GH-analytics) - Reference implementation application with Laravel backend and [AngularJS](https://angularjs.org/) front-end.
- [IVD Assets](https://github.com/TTFerreira/ivd-assets) - IT asset management and ticketing application. \[08/02/2016\]
- [JobsToMail](https://github.com/jobapis/jobs-to-mail) - Opt-in platform for receiving daily e-mail on job postings on 8 popular job boards that uses [JobsApi](http://www.jobapis.com/). \[10/10/2016\]
- [KnowFox](https://github.com/oschettler/knowfox) - Sophisticated personal knowledgebase/PIM application modeled on Evernote.  Free, hosted version also available [here](https://knowfox.com/). \[03/07/2017\]
- [Kwiki](https://github.com/fungku/kwiki) - Markdown-based wiki/blogging platform built on [Lumen](http://lumen.laravel.com/) that uses flat files (no database). \[06/16/2015\]
- [Larabook Updated](https://github.com/forkiven/larabook-updated) - Facebook clone built with Laravel 5.0 based [Laracast tutorial](https://laracasts.com/series/build-a-laravel-app-from-scratch). \[06/16/2015\]
- [LaraContact](https://github.com/kadnan/LaraContact) - Simple contact manager/address book built with Laravel. \[12/16/2016\]
- [Larapress](https://github.com/larapress-cms/larapress) - A work-in-progress CMS built on Laravel 4, which provides good example of building application with Laravel.
- [LaraSqrrl](https://github.com/pauly4it/LaraSqrrl) - Example app that integrates with [Twilio](https://www.twilio.com/) for SMS interaction, provides a simple API, and demonstrates how to deploy a Laravel app to [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/). \[05/09/2016\]
- [Laravel and AngularJS Blog](https://github.com/RachidLaasri/Blog) - Simple blogging application with AngularJS front-end that uses Markdown files for posts. \[08/11/2015\]
- [Laravel and AngularJS CMS]() - CMS built on Laravel 5.1, AngularJS 1.4.7 and Responsive Material Design with REST API. \[10/30/2015\]
- [Laravel Blog](https://github.com/FbF/Laravel-Blog) - A Laravel 4 package to add a simple blog to a site.
- [Laravel Blog](https://github.com/lufficc/laravel-blog) - A fast and powerful blog system powed by Laravel 5.3. \[09/21/2016\]
- [Laravel Blog](https://github.com/summerblue/laravel-blog) - A complete blog application, with admin features, implemented in Laravel 4.2.
- [Laravel Bookmarks](https://github.com/yhbyun/laravel-bookmark) - Visual bookmark organizer application built with Laravel. Online version [here](https://rivario.com/bookmark/). \[08/16/2015\]
- [Laravel Bootstrap Starter Site](https://github.com/mrakodol/Laravel-5-Bootstrap-3-Starter-Site) - Laravel 5 application starter configuration with built-in Bootstrap 3 and [DataTables](https://datatables.net/) support.
- [Laravel Bootstrap](https://github.com/davzie/laravel-bootstrap) - A Laravel 4.1 PHP 5.4 CMS using Bootstrap 3, built with [SOLID](http://en.wikipedia.org/wiki/SOLID_%28object-oriented_design%29) principles.
- [Laravel Community Service Application](https://github.com/npmweb/community-service) - Web application for signing up for community service opportunities.
- [Laravel Datatables Package Demo](https://github.com/yajra/laravel-datatables-demo) - Demo application to show how to use [DataTables](http://datatables.net/) with Laravel 4/5. \[06/11/2015\]
- [Laravel Feed Reader](https://github.com/awjudd/l4-feed-reader) - A simple, self-hosted, online RSS feed reader based on SimplePie for Laravel 4/5. \[05/13/2015\]
- [Laravel Question & Answer](https://github.com/TheRealJAG/Laravel-QuestionAnswer) - Q&A site similar to Stack Overflow that allows voting on answers built with Laravel, Material Design, and Bootstrap. \[06/27/2017\]
- [Laravel Tasks](https://github.com/jeremykenedy/laravel-tasks) - Multi-user tasks/"to do" application user authentication, password reset, etc. \[03/08/2017\]
- [Laravel To Do App](https://github.com/lourenci/laravel-todo-app) - Basic "to do" application to demonstrate Laravel 5.2 services including [authentication](https://laravel.com/docs/5.2/authentication), [e-mail](https://laravel.com/docs/5.2/mail), [Eloquent ORM](https://laravel.com/docs/5.2/eloquent), and [middleware](https://laravel.com/docs/5.2/middleware). \[06/18/2016\]
- [Laravel 4 CMS](https://github.com/alnutile/l4cms) - Quick intro to Laravel using a custom CMS application.
- [Laravel 5 Example](https://github.com/bestmomo/laravel5-example) - Basic blog application with authentication, user roles, admin dashboard, and more. \[05/11/2015\]
- **[Laravel 5 Projects](https://github.com/StreetGT/Laravel-5-Projects/)** - Directory for Laravel 5 example projects for those new to Laravel. \[07/20/2015\]
- [Laravel & VueJS Todo App Example](https://github.com/erayaydin/laravel-todo-vuejs) - Simple "to do" application built with Laravel and [Vue.JS](https://vuejs.org/). \[08/17/2017\]
- [Laravel.io](https://github.com/LaravelIO/laravel.io) - The source code for the [Laravel.IO](http://laravel.io/) website, including comprehensive tests.
- [Library Management System](https://github.com/aziflaj/Book_io) - Simple library management system built on Laravel.
- [Lumen and AngularJS Todo App](https://github.com/DimitriMikadze/lumen-angular-todo) - A basic "to do" tracking application with Lumen backend and [AngularJS](https://angularjs.org/) on frontend. \[08/10/2015\]
- [MailTree](https://github.com/dud3/MailTree) - AngularJS/Laravel e-mail forwarder that uses keywords to forward to defined users. \[08/18/2015\]
- [Make It Snappy](https://github.com/jijoel/make-it-snappy-laravel4) - Independent Laravel **4** implementation of the application built in the Tuts+ ["Build a Practical Web Application with Laravel"](http://code.tutsplus.com/courses/hands-on-build-a-practical-web-application-with-laravel) tutorial.
- [Mapigniter](http://sourceforge.net/projects/mapigniter2/) - A web mapping platform to publish and manage geographic information powered by Laravel 5, [OpenLayers 3](http://openlayers.org/) and AngularJS packaged as a [Virtual Box](https://www.virtualbox.org/) OVA. \[12/05/2015\]
- [Mongoblog](https://github.com/jpcaparas/mongoblog) - REST-based Laravel blog application that uses [MongoDB](https://www.mongodb.com/) for storage. \[08/12/2017\]
- [myPOS](https://sourceforge.net/projects/myposs/) - Full-featured point-of-sale (POS) application built with Laravel. \[10/22/2018\]
- [Open Heroes](https://sourceforge.net/projects/open-heroes/) - Tour-based strategic role-playing game (RPG) similar to [Heroes of Might & Magic](https://en.wikipedia.org/wiki/Heroes_of_Might_and_Magic). \[09/16/2017\]
- [Paypal Processor](https://github.com/martindevnow/paypalproc) - Sample Paypal-based ecommerce site implemented with Laravel.
- [Phonebook](https://github.com/adibhanna/phonebook) - Basic contact manager that demonstrates construction of simple Laravel application. \[10/15/2016\]
- [PhotoShare](https://github.com/pitchinnate/photoshare) - Simple tool for sharing photos with family and friends built with Laravel 5.1. \[11/06/2017\]
- [PHPHub](https://github.com/summerblue/phphub) - Complete forum application built with Laravel 4.2.
- [PHP Geo Demo](https://github.com/jcorry/phpgeo-demo) - Demo application for using geographic data in PHP via Laravel 5.x. \[09/11/2017\]
- [PJ Blog](https://github.com/jcc/blog) - Full-featured, open-source blogging application built with Laravel and Vue.JS. \[09/02/2017\]
- [Neon Tsunami Blog](https://github.com/dwightwatson/neontsunami) - Fully PHPUnit tested Laravel 4.2 app for reference.
- [OpenPub](https://github.com/baileylo/openpub) - Markdown-based blog platform built on Laravel 5. \[04/05/2016\]
- [OrderMVC Laravel Application](https://github.com/OrderMVC/Laravel-App) - Laravel 4 implementation of a basic e-commerce application using MVC architecture. \[06/11/2015\]
- [Origin CMS](https://github.com/akhileshdarjee/origin-cms) - Full-featured CMS built on Laravel 5.2 that can be used as application boilerplate. \[10/10/2016\]
- [Owl](https://github.com/owl/owl) - Simple collaboration tool built on Laravel with support for "favorites" and tags, full text search, email and Slack notifications, and more. \[07/22/2016\]
- [ReMark](https://github.com/Technopathic/ReMark) - Blogging platform with built-in feed aggregator and multimedia hosting built on Laravel and [AngularJS](https://angularjs.org/). \[07/22/2016\]
- [Ribbbon](https://github.com/canvasowl/ribbbon) - Project management application built on Laravel 5.x and [Vue.js](https://vuejs.org/) that supports task weighting and project sharing. \[03/28/2016\]
- [Rusty Nails Adventurers RPG Guild](https://github.com/Riari/rna-guild.net) - RPG guild web site built on Laravel using [Materialize](http://materializecss.com/) CSS framework, [Laravel FullCalendar.io Helper](https://github.com/maddhatter/laravel-fullcalendar), and more. \[05/26/2016\]
- [Sample REST API](https://github.com/fasilkk/SampleRestAPI) - Sample implementation of RESTful API in Laravel with complete [PHPUnit](https://phpunit.de/) tests.
- [Scrumwala](https://github.com/modestkdr/Scrumwala) - A Scrum/agile web application, with plan and work views, for personal use. \[05/29/2015\]
- [Socializer](https://github.com/Evo267/socializer) - Basic social networking application built with Laravel. \[08/12/2017\]
- [Ticket Conductor](https://github.com/Bottelet/ticket-conductor) - Basic ticket management tool built with Laravel 5.5 and [Vue.JS](http://vuejs.org/) as single-page application. \[08/03/2017\]
- [TicketIt](https://github.com/thekordy/ticketit) - A simple help-desk ticket system built on Laravel. \[08/30/2017\]
- [TodoParrot](https://github.com/wjgilmore/todoparrot) - Simple "To Do" application described in [Easy Laravel 5](http://easylaravelbook.com/). \[05/28/2016\]
- [todoProject] - Simple "To Do" tracking application build with Laravel 4 and Bootstrap.
- [Todo Laravel](https://github.com/anam-hossain/Todo-laravel) - A simple Todo app which is built with Laravel 4, Bootstrap 3.0 and AngularJS. \[05/13/2015\]
- [Unreal Estate](https://github.com/thejettdurham/unrealestate) - Simple real estate listings RESTful web application. \[10/06/2016\]
- [Vuebnb](https://github.com/fsvwd/vuebnb) - An Airbnb clone site built with [Vue.JS](https://vuejs.org/] and Laravel as tutoril from upcoming book *Full Stack Vue Web Development*.
- [Webloyer](https://github.com/ngmy/webloyer) - A Web UI for managing [Deployer](http://deployer.org/) deployments. \[11/23/2015\]
- [Zagros Bug Tracking System](http://mohsen-shafiee.github.io/Zagros/) - Simple development bug tracking application built on Laravel 4. \[04/29/2015\]

### Blogs
- [158ltd](http://team.158ltd.com/tag/laravel/)
- [Advanced Laravel](http://advancedlaravel.com/blog)
- [Adam Engebretson](http://blog.enge.me/)
- [Adam Patterson](http://adampatterson.ca/blog/) \[06/15/2015\]
- [Adam Wathan](http://adamwathan.me/) \[04/16/2015\]
- [Adnan Siddiqi](http://blog.adnansiddiqi.me/tag/laravel/) \[05/20/2015\]
- [Ahesanali Suthar](https://ahesanalisuthar.wordpress.com/tag/laravel/)
- [Alan Storm](http://alanstorm.com/category/laravel)
- [Alex Sears](http://alexsears.com/)
- [Alex Kyriakidis](https://dotdev.co/@hootlex) \[10/01/2016\]
- [Alexander Trauzzi](http://atrauzzi.blogspot.ca/) \[04/07/2015\]
- [Alfred Nutile](http://alfrednutile.info/posts)
- [Amit Gaur](http://agalaxyphp.blogspot.com/search/label/Laravel)
- [Amit Merchant](https://www.amitmerchant.com/) \[09/06/2017\]
- [Amitav Roy](http://amitavroy.com/)
- [Amo Chohan](https://dotdev.co/@amo.chohan) \[10/15/2016\]
- [Andrea Sartori](http://blog.andreasartori.me/en/)
- [Andreas Lutro](http://www.lutro.me/)
- [Andy Brudtkuhl](https://brudtkuhl.com/topics/laravel/) \[04/02/2017\]
- [Andy Carter](https://andy-carter.com/) \[03/30/2019\]
- [Andy Fleming](http://andyfleming.com/articles-by-topic/lumen/) \[07/16/2015\]
- [Andy Hinkle](https://medium.com/andyhinkle91) \[07/23/2018\]
- [Anytch.com](http://anytch.com/category/laravel/) \[09/02/2016\]
- [AppDividend](http://appdividend.com/category/laravel/) \[07/17/2017\]
- [Appstract](https://medium.com/appstract/tagged/laravel) \[03/20/2017\]
- [Arda Kılıçdağı](https://arda.pw/tag/laravel/) \[09/30/2015\]
- [Armen Markossyan](http://blog.armen.im/tag/laravel/) \[06/01/2015\]
- [Asked.io](https://asked.io/search/laravel) \[04/13/2016\]
- [AskJong](http://www.askjong.com/) \[10/08/2015\]
- [AskLagBox](http://asklagbox.com/blog/tag/laravel) \[03/23/2017\]
- [Baljeet Singh](http://baljeetsingh.in/blog/tag/laravel/) \[11/09/2015\]
- [Bao Pham](http://baopham.github.io/) \[07/27/2016\]
- [Barry van Veen](https://barryvanveen.nl/) \[12/04/2016\]
- [Barry vd. Heuvel](http://barryvdh.nl/)
- [Belar Design](http://belardesign.com/category/dev/laravel/)
- [Ben Sampson](https://sampo.co.uk/blog) \[05/20/2019\]
- [Ben Smith](http://bensmith.io/) \[07/07/2015\]
- [Benjamin Kohl](http://benjaminkohl.com/)
- [Bhavyanshu Parasher](https://bhavyanshu.me/tags.html#laravel-ref) \[04/28/2015\]
- [Boris Strahija](http://creolab.hr/category/blog/)
- [Bosnadev](https://bosnadev.com/)
- [Brian Retterer](http://brianretterer.com/) \[10/02/2015\]
- [Chris Fuller](http://blog.cjwfuller.com/) \[06/01/2015\]
- [Chris Gmyr](http://www.chrisgmyr.com/)
- [Chris Hayes](http://chrishayes.ca/blog/category/code/laravel)
- [Chris Schalenborgh](http://chris.schalenborgh.be/category/laravel/) \[05/16/2015\]
- [Chris White](https://cwhite.me/tag/laravel/) \[06/16/2016\]
- [Christoph Rumpel](http://christoph-rumpel.com/)
- [Christopher Pitt](https://medium.com/@assertchris)
- [Chuck Heintzelman](http://laravelcoding.com/blog) \[06/11/2015\]
- [ClÃ©ment Rigo (Mydnic)](https://mydnic.be/search?q=laravel) \[03/10/2017\]
- [Clivern](http://clivern.com/tag/laravel/)
- [Cloudways Blog](http://www.cloudways.com/blog/category/applications/laravel/) \[08/02/2016\]
- [Code And Be Happy (Jesse Walton)](http://codeandbehappy.com/tags/#laravel) \[09/23/2015\]
- [Code Gains](http://codegains.com/tag/laravel-2/)
- [Code4Fun](http://code4fun.io/tag/laravel) \[01/25/2017\]
- [Codeem](https://codeem.co/blog/) \[03/31/2017\]
- [CodeHeaps](http://www.codeheaps.com/)
- [CodeHow](http://codehow.io/) \[09/02/2016\]
- [Codelution](http://codelution.com/tag/laravel/) \[04/16/2015\]
- [CodeRabbi (Yitzchok Willroth)](http://coderabbi.github.io/)
- [CODETutorial.io](http://www.codetutorial.io/tutorial/laravel-5/) \[08/06/2015\]
- [Codingo](https://tuts.codingo.me/category/web-development/laravel) \[07/07/2016\]
- [CoffeeCupWeb](http://coffeecupweb.com/category/laravel/) \[08/06/2015\]
- [Cogito, Ergo Sum (Shankar Manamalkav)](https://mnshankar.wordpress.com/)
- [Connor Leech](https://medium.com/@connorleech) \[12/31/2016\]
- [Coveros](https://www.coveros.com/tag/laravel/) \[05/17/2016\]
- [Craig Morris](https://medium.com/@morrislaptop) \[05/06/2015\]
- [Creative Punch](http://creative-punch.net/articles/php-articles/laravel-tutorials/)
- [ctf0](https://ctf0.wordpress.com/tag/laravel/) \[03/30/2017\]
- [crynobone (Mior Muhammad Zaki)](http://crynobone.com/) \[04/07/2015\]
- [Cubet Techno Labs](http://blog.cubettech.com/category/laravel-frame-work) \[04/27/2015\]
- [Dan Course](http://www.dancourse.co.uk/category/tech/laravel/) \[08/16/2015\]
- [Daniel Li](http://blog.danyll.com/) \[04/20/2015\]
- [Darwin Biler](http://www.darwinbiler.com/category/php/laravel/) \[04/14/2015\]
- [David Carr](https://dcblog.dev/) \[07/13/2020\]
- [David Hemphill](http://davidhemphill.com/blog/) \[07/09/2015\]
- [David Frame](http://www.cryst.co.uk/tag/laravel/) \[02/14/2017\]
- [David Piesse](https://medium.com/@piesse) \[07/24/2017\]
- [Delia Curiel](http://www.scoop.it/t/laravel-by-delia-curiel) \[07/02/2015\]
- [Delicious Brains](https://deliciousbrains.com/tag/laravel/) \[10/30/2016\]
- [Dennis Decoene](http://avidsoftware-be.github.io/) (German/[English translation](https://translate.google.com/translate?sl=auto&tl=en&u=http%3A%2F%2Favidsoftware-be.github.io%2F)) \[09/10/2015\]
- [Dennis Smink](https://medium.com/@dennissmink) \[09/13/2018\]
- [Designing Lives](http://designinglives.net/) \[07/07/2015\]
- [DevMarketer](http://devmarketer.io/learn/category/laravel/) \[09/24/2016\]
- [Dev Metal](http://www.dev-metal.com/tag/laravel/)
- [Dev Problems](http://www.devproblems.com/category/laravel/) \[05/03/2016\]
- [Devartisans](http://devartisans.com/categories/laravel5) \[09/02/2016\]
- [developed.be](http://www.developed.be/languages/frameworks/lavarel/)
- [DeveloPHP](http://www.develophp.org/)
- [Dhviti Infotech](http://www.dhvitiinfotech.com/tag/laravel-application-development/) \[05/09/2016\]
- [Diego Hernandes](http://blog.hernandev.com/en)
- [Discuss Desk](http://www.discussdesk.com/) \[11/09/2015\]
- [Dixit Patel](http://dixitpatel.com/category/web-2/laravel/)
- [dor.ky](http://dor.ky/tag/laravel/)
- [dotdev](https://dotdev.co/tagged/laravel) \[06/16/2016\]
- [Duilio Palacios](http://duilio.me/) \[04/12/2015\]
- [Dunebook](http://dunebook.com/category/useful-resources-for-laravel/) \[08/08/2015\]
- [Dustin Parham](http://imbringingsyntaxback.com/) \[05/16/2016\]
- [Dwayne Charrington](http://ilikekillnerds.com/category/laravel/) \[04/12/2015\]
- [Dwight Watson](https://www.neontsunami.com/) \[07/12/2016\]
- [Eagle Peak Consulting](https://www.eaglepeakweb.com/blog) \[07/26/2018\]
- [EasyLara](http://www.easylara.com/)
- [Edvinas Krucas](http://blog.krucas.lt/category/laravel/) \[10/06/2015\]
- [Eftakhairul Islam](http://eftakhairul.com/) \[06/29/2015\]
- [El Coderino](http://www.elcoderino.com/)
- [Elena Kolevska](http://blog.elenakolevska.com/)
- [Elliot Hesp](http://blog.elliothesp.co.uk/) \[07/13/2015\]
- [Eric Barnes](http://ericlbarnes.com/)
- [Esben Petersen](http://esbenp.github.io/) \[10/10/2017\]
- [Ewan Valentine](http://ewanvalentine.io/) \[08/31/2015\]
- [Experience](https://experiencehq.net/blog/tags/laravel) \[05/30/2015\]
- [Feliciano Prochera](http://felicianoprochera.com/) \[04/12/2017\]
- [Fideloper](http://fideloper.com/)
- [Fleka](https://tech.fleka.me/tagged/laravel) \[02/16/2017\]
- [Francesco Lettera (Portuguese)](https://medium.com/@francescolettera) \[08/17/2017\]
- [Flynsarmy](https://www.flynsarmy.com/)
- [For Laravel](https://forlaravel.com/) \[10/12/2015\]
- [Format C:](http://www.formatccolon.com/category/web-development/laravel/)
- [Francesco Malatesta](http://hellofrancesco.com/) \[09/09/2015\]
- [Full Stack Blog](http://fullstack4u.com/category/laravel/) \[07/21/2015\]
- [Garrett St. John](http://garrettstjohn.com/) \[05/30/2015\]
- [G-Design (Gunther Groenewege)](http://blog.g-design.net/tagged/laravel) \[07/22/2015\]
- [Geek & Dummy](http://geekanddummy.com/tag/laravel/) 
- [Geekpub (German)](https://www.geekpub.de/tag/laravel/) \[08/21/2017\]
- [George Bohnisch](http://georgebohnisch.com/) \[08/30/2015\]
- [George Cameron](https://medium.com/@grmcameron) \[07/02/2018\]
- [Geshan Manandhar](http://geshan.com.np/blog/categories/laravel/) \[07/28/2015\]
- [Gijs Jorissen](https://medium.com/@gizburdt) \[01/25/2017\]
- [Glen Davies](http://caughtexceptions.blogspot.co.nz/) \[04/14/2015\]
- [Gilbert Pellegrom](http://gilbert.pellegrom.me/tag/laravel/)
- [Gliding Phenomena (Ravi Panchumarthy)](http://glidingphenomena.blogspot.com/search/label/laravel)
- [Gufran.me](http://www.gufran.me/)
- [Goodheads](http://goodheads.io/category/laravel/) \[04/26/2016\]
- [Hello Laravel](https://medium.com/hello-laravel) \[10/26/2017\]
- [How To Solve Now](http://www.howtosolvenow.com/category/language/php/larevel/) \[09/02/2016\]
- [Isaac Castillo](http://icastwork.com/) \[09/10/2015\]
- [Isaac Earl](https://isaacearl.com/tag:laravel) \[07/24/2017\]
- [Imron Rosindia](https://imron02.wordpress.com/category/laravel/)
- [IMWZ Web Design](https://imwz.io/category/laravel/) \[07/26/2018\]
- [Inani El Houssain](https://medium.com/@InaniT0) \[12/31/2016\]
- [IntoLaravel.com](http://www.intolaravel.com/)
- [Ionut Bajescu](http://ionut-bajescu.com/)
- [ItSolutionStuff](http://itsolutionstuff.com/tag/laravel.html)
- [Jad Joubran](https://medium.com/@JoubranJad/) \[04/05/2017\]
- [Jack Wall](https://jkwl.io/)
- [Jacob Bennett](https://gistlog.co/JacobBennett)
- [Jacopo Beschi](http://www.jacopobeschi.com/tag/laravel)
- [Jagadesha NH](https://medium.com/@jagadeshanh) \[03/16/2018\]
- [James Brooks](http://james-brooks.uk/)
- [James Mills](https://blog.jamesmills.co.uk/category/laravel/) \[06/25/2018\]
- [Jamie Rumbelow](http://jamieonsoftware.com/tagged/laravel) \[04/12/2015\]
- [Jan Ostlund](https://janostlund.com/) \[07/26/2018\]
- [Janik von Rotz](https://janikvonrotz.ch/category/work/laravel/) \[04/14/2015\]
- [Jason Lewis](http://jasonlewis.me/laravel-tutorials)
- [Jeff Madsen (codebyjeff)](http://codebyjeff.com/blog) \[06/08/2015\]
- [Jeff Mould](http://www.jeffmould.com/category/laravel/) \[07/22/2016\]
- [Jeff Simons Decena](https://medium.com/@jsdecena) \[03/16/2018\]
- [Jens Segers](http://jenssegers.be/)
- [Jesper Jarlskov](https://jesperjarlskov.dk/category/software/laravel/) \[10/18/2016\]
- [Jesse Schutt](http://zaengle.com/blog/tag/laravel) \[04/13/2016\]
- [Jim Frenette](http://jimfrenette.com/tag/laravel/) \[07/09/2016\]
- [Joao Peribeiero](http://joaoperibeiro.com/tag/laravel/) \[02/06/2017\]
- [Joe Ferguson](http://www.joeferguson.me/blog/) \[08/30/2015\]
- [Joe Tannorella](http://www.joetannorella.com/archive/) \[04/14/2015\]
- [Jon Phipps](http://jonstuff.blogspot.ca/search/label/Laravel%205) \[11/30/2015\]
- [Jonathan Stassen](http://blog.jstassen.com/tag/laravel/) \[04/13/2015\]
- [Jose Padilla](http://jpadilla.com/tagged/laravel) \[12/01/2015\]
- [Joseph Ralph](http://josephralph.co.uk/tag/laravel/) \[05/05/2015\]
- [Joseph Silber](https://josephsilber.com/posts) \[09/06/2016\]
- [Josh Forbes](https://joshforb.es/) \[07/17/2017\]
- [Justin Voelkel](http://justinvoelkel.me/category/angularjs/) \[08/08/2015\]
- [Jyrone Parker](https://jyroneparker.com/category/blog/php/laravel/) \[05/21/2017\]
- [Kamran Ahmed](http://kamranahmed.info/) \[04/07/2015\]
- [Kaloraat](https://kaloraat.com/categories/laravel) \[04/24/2018\]
- [KaltenCoder](http://kaltencoder.com/category/laravel/) \[08/13/2016\]
- [Kane Cohen](http://kanecohen.github.io/) \[07/12/2015\]
- [Kathir 'Sid' Vel](http://www.kathirvel.com/blog/) \[05/06/2015\]
- [KaixersofT](https://kaixersoft.wordpress.com/category/php-2/laravel/) \[07/02/2015\]
- [Keith Watanabe](http://www.keithwatanabe.net/tag/laravel/) \[07/29/2015\]
- [KernelDev](https://www.kerneldev.com/category/web-development/laravel/) \[10/04/2018\]
- [Kelt Dockins](http://keltdockins.com/tags/laravel/)
- [Kirk Bushell](http://kirkbushell.me/) \[04/14/2015\]
- [Kode Blog](http://www.tutorials.kode-blog.com/laravel-5-tutorial) \[11/05/2015\]
- [KodeInfo](http://kodeinfo.com/main_category/laravel)
- [Kongnir](http://blog.kongnir.com/)
- [Koomai](http://blog.koomai.net/)
- [Kovah](https://kovah.me/en/tag/laravel/) \[11/09/2015\]
- [KVCodes](http://www.kvcodes.com/category/laravel/)
- [Kyle Huynh](http://kylehuynh.com/blogs/category/c8-technology-blog/laravel/) \[10/18/2016\]
- [Lanre Adelowo](https://lanreadelowo.com/blog/) \[03/31/2017\]
- [Learning Laravel Blog](http://learninglaravel.net/blog) \[04/22/2015\]
- [Laracasts Snippets](https://laracasts.simplecast.fm/) \[08/11/2016\]
- [Laraget (Filip Zdravkovic)](http://laraget.com/blog) \[03/31/2017\]
- [Laratips](https://laratips.io/) \[07/07/2016\]
- [Laravel & VueJS](https://www.laravel-vuejs.com/) \[10/05/2017\]
- [Laravel 5 Tutorials](https://medium.com/laravel-5-tutorials) \[06/01/2015\]
- [Laravel Coder](http://sheepy85.wordpress.com/)
- [Laravel Daily](http://laraveldaily.com/) \[07/10/2015\]
- [Laravel Factory](https://laravelfactory.com/blog) \[04/23/2018\]
- [Laravel Feed](http://laravelfeed.com/) \[04/26/2016\]
- [Laravel Tips (Bill Keck)](https://laraveltips.wordpress.com/) \[04/26/2016\]
- [Laravel Tips N Tricks](http://laraveltnt.com/) \[10/18/2016\]
- [Laravel Tutorials](http://learn-laravel.blogspot.com/) \[04/28/2015\]
- [Laravelista](http://laravelista.com/) \[05/16/2015\]
- [Leader Internet](https://leaderinternet.com/blog) \[04/23/2017\]
- [Logan Bailey](http://logansbailey.com/) \[04/18/2016\]
- [Loris Leiva](https://lorisleiva.com/) \[09/17/2018\]
- [Liza Shulyayeva](http://liza.io) \[09/22/2015\]
- [Luca Bernardino](http://www.codeanchor.net/) \[07/13/2015\]
- [Luciano Mammino](http://loige.co/tag/laravel/) \[04/29/2015\]
- [Lukas White](http://lukaswhite.com/blog) \[10/15/2016\]
- [Luke Whitehouse](https://assortment.io/tags/laravel) \[02/14/2017\]
- [Mack Hankins](http://www.mackhankins.com/blog/)
- [Made With Love](http://blog.madewithlove.be/) \[08/16/2015\]
- [Maks Surguy](http://maxoffsky.com/blog/)
- [Manan Jadhav](https://curos.in/category/laravel/) \[07/31/2015\]
- [Mario Basic](http://mariobasic.com/)
- [Marc Mulzer](http://mulzer.tumblr.com/)
- [Marcel Pociot](http://marcelpociot.com/tag:Laravel) \[11/04/2015\]
- [Marco Aurelio Deleu](https://hackernoon.com/@deleugpn) \[08/28/2017\]
- [Mark Van Eijk](http://markvaneijk.com/)
- [Martin Bean](http://martinbean.co.uk/blog/)
- [Martin Betz](https://martinbetz.eu/articles/) \[01/03/2020\]
- [Marty Thomas](https://martythomas.svbtle.com/) \[09/02/2016\]
- [Mateus Guimaraes](http://mguimaraes.co/) \[01/16/2016\]
- [Matt Sparks](http://mattsparks.com/blog/) \[07/13/2015\]
- [Matt Stauffer](http://mattstauffer.co/blog/)
- [Matt's Notes](http://www.mattsnotes.com/php)
- [Matthew Daly](http://matthewdaly.co.uk/blog/categories/laravel/) \[09/09/2016\]
- [Matthew Hailwood](http://matthewhailwood.co.nz/)
- [Matthew T. Brown](http://ryantbrown.io/tag/laravel/)
- [Maurizio Bonani](http://blog.mauriziobonani.com/tags/#laravel) \[09/02/2016\]
- [Menara Solutions](https://blog.menara.com.au/tag/laravel/) \[01/07/2016\]
- [Mera Mustaqbil](https://meramustaqbil.com/category/laravel/) \[05/20/2019\]
- [Merix Studio](http://www.merixstudio.com/blog/category/code-tools/) \[08/17/2017\]
- [Metric Loop](https://metricloop.com/blog/tag/Laravel) \[09/02/2016\]
- [Michael Brooks](http://michaelbrooks.co.uk/tag/laravel)
- [Michael Dyrynda](https://dyrynda.com.au/blog?tag=laravel) \[05/26/2016\]
- [Michael Stivala](https://michaelstivala.com/) \[10/01/2016\]
- [Milan Chheda](https://milanchheda.com/tag/laravel) \[03/27/2018\]
- [Mike Smith](https://medium.com/@splatEric) \[02/06/2017\]
- [Mitch Stanley](http://fullstackstanley.com/read/categories/laravel) \[09/16/2015\]
- [Mitchell McKenna](http://mitchmckenna.com/blog/category/programming/laravel/) \[09/26/2017\]
- [Mohamed Said](http://themsaid.github.io/) \[04/13/2016\]
- [Morgan Davidson](http://morgandavison.com/tag/laravel/) \[09/02/2016\]
- [Muhammad Usman](http://usman.it/tag/laravel/)
- [Muharrem Tigdemir](http://muharremtigdemir.com/category/laravel/) \[07/02/2015\]
- [Mulia Arifandi Nasution](https://mul14.wordpress.com/tag/laravel/) \[07/16/2015\]
- [Murze.be](https://murze.be/tag/laravel/)
- [Nate Denlinger](https://natedenlinger.com/) \[11/06/2017\]
- [Nedex.io](http://blog.nedex.io/) \[03/30/2017\]
- [Neoelemento (Vishnu Padmanabhan)](http://neoelemento.com/blog/)
- [Nick Basile](https://nick-basile.com/blog/tag/Laravel) \[12/21/2017\]
- [Nick Boyle](http://bicknoyle.com/) \[02/15/2016\]
- [Nicola Malizia](https://unnikked.ga/tagged/laravel) \[01/25/2017\]
- [Nicolas Widart](https://nicolaswidart.com/blog) \[07/28/2016\]
- [Ollie Read](http://ollieread.com/)
- [Oliver Kaufmann](https://okaufmann.ch/) \[11/19/2016\]
- [Ominceps](http://www.omniceps.com/tag/laravel/) \[08/17/2017\]
- [Overtrue](http://overtrue.me/) \[10/27/2015\]
- [Parth Patel](https://www.parthpatel.net/category/laravel/) \[08/19/2017\]
- [Pascal Baljet](https://pascalbaljetmedia.com/en/blog/tag/laravel) \[02/04/2017\]
- [Pascal Landau](http://www.pascallandau.com/blog/) \[08/31/2016\]
- [Paul Foryt](http://blog.goforyt.com/category/laravel/) \[11/11/2015\]
- [Pete Houston](https://medium.com/@petehouston) \[07/22/2015\]
- [Peter Fox](https://medium.com/@SlyFireFox) \[04/23/2018\]
- [Peter Plucinski](http://blog.peterplucinski.com/) \[03/03/2018\]
- [Peter Steenbergen](http://petericebear.github.io/) \[04/02/2017\]
- [PHP Builder](http://www.phpbuilder.com/) \[01/08/2017\]
- [PHP Clicks](http://phpclicks.com/laravel/) \[02/20/2016\]
- [PHP Expert](http://www.expertphp.in/tag/laravel-php-framework) \[10/03/2016\]
- [PHP Lab](http://www.phplab.info/) \[10/18/2016\]
- [PHP Ocean](http://phpocean.com/tutorials/back-end) \[07/30/2015\]
- [PiedCode (Simon Reinsperger)](http://www.piedcode.com/tag/laravel/) \[09/08/2015\]
- [Prasenjit Kumar Nag](http://joycse06.github.io/blog/categories/laravel/) \[03/09/2016\]
- [Programming Are Hard (David Adams)](http://programmingarehard.com/tag/laravel.html)
- [Prosper Otemuyiwa](http://prosperotemuyiwa.com/tag/laravel/) \[05/14/2015\]
- [Quantizd](https://quantizd.com/) \[04/23/2018\]
- [Raffworks](http://raffworks.com/category/series/getting-started-with-laravel-4/)
- [Recursive Iterator](https://recursiveiterator.wordpress.com/category/laravel/)
- [Reza Shadman](http://rezashadman.ir/) \[09/30/2015\]
- [Richard Bagshaw](http://www.richardbagshaw.co.uk/)
- [Richard Hawthorn](http://richardhawthorn.com/)
- [Ringaal Sandbox](http://sandbox.ringaal.com/category/tutorials/laravel-tutorials/)
- [Rizqi Djamaluddin](http://rizqi.id/archive) \[05/03/2016\]
- [Ryan Chenkie](http://ryanchenkie.com/category/laravel/)
- [Ryan Meier](https://www.rfmeier.net/tag/laravel/) \[08/28/2017\]
- [Ryan Tablada](http://ryantablada.com/tag/Laravel)
- [Ryan Winchester](https://ryanwinchester.ca/posts) \[10/15/2016\]
- [Sarav](http://sarav.co/blog/) 
- [Scotch.io](http://scotch.io/)
- [Sean O'Neill](http://seanoneill.me/tag/laravel/) \[05/30/2017\]
- [Sebastian De Deyne](https://sebastiandedeyne.com/) \[03/09/2017\]
- [Saqueib Ansari](http://www.qcode.in/category/laravel/) \[05/30/2017\]
- [Sergi Tur Badenas](https://medium.com/@sergiturbadenas) \[08/12/2017\]
- [Servage](https://www.servage.net/blog/tag/laravel/) \[08/16/2016\]
- [Sillo (in French)](http://laravel.sillo.org/) \[01/08/2017\]
- [Simon Archer (ArchyBold)](http://www.archybold.com/blog/tagged/laravel) \[06/08/2015\]
- [Simon Hamp](https://medium.com/@simonhamp) \[02/08/2016\]
- [Simple Developer](http://simpledeveloper.com/category/laravel-framework/)
- [Simplest Web](https://simplestweb.in/blog?tag=laravel) \[12/01/2018\]
- [Stephen Jude](https://stephenjude.me/) \[07/06/2020\]
- [Sky Blue Sofa (Dave Rogers)](http://skybluesofa.com/blog/) \[01/07/2017\]
- [Skyshi Digital](https://medium.com/skyshidigital/tagged/laravel) \[07/26/2017\]
- [Slashnode](http://slashnode.com/blog/)
- [Small Dog Studios](https://blog.smalldo.gs/category/code-2/laravel/) \[04/27/2015\]
- [SOFTonSOFA](http://softonsofa.com/)
- [Stampede Design](http://constructs.stampede-design.com/tag/laravel/) \[08/15/2016\]
- [Stefan Zweifel](https://stefanzweifel.io/posts/) \[07/22/2016\]
- [Stephen Rees-Carter](http://stephen.rees-carter.net/tag/laravel)
- [Steve Azzopardi](https://medium.com/@steveazz) \[04/05/2016\]
- [Steven Maguire](https://stevenmaguire.com/publications/) \[11/19/2016\]
- [Stidges' Blog](http://blog.stidges.com/)
- [StillAt (Johnathon Koster)](http://www.stillat.com/) 
- [Stormpath](https://stormpath.com/blog/category/php) \[08/11/2016\]
- [Styde](https://styde.net/category/laravel-5/) (Spanish/[English translation](https://translate.google.com/translate?sl=auto&tl=en&js=y&prev=_t&hl=en&ie=UTF-8&u=https%3A%2F%2Fstyde.net%2Fcategory%2Flaravel-5%2F&edit-text=&act=url)) \[05/30/2015\]
- [South LaSalle (Bob Bloom)](https://www.southlasalle.com/posts)
- [Sujip Thapa](https://sujipthapa.co/blog/tag/laravel) \[08/30/2017\]
- [Taha Shashtari](http://taha-sh.com/tags/laravel) \[10/07/2015\]
- [Tanner Hearne](http://www.tannerhearne.com/category/development/laravel/)
- [Taylor Otwell](http://taylorotwell.com/)
- [Techigniter](http://www.techigniter.in/category/laravel/) \[07/13/2015\]
- [Technology Shouters](https://www.technologyshouters.com/?s=laravel) \[11/20/2017\]
- [Techuz](https://www.techuz.com/blog/category/laravel-development/) \[08/21/2017\]
- [Terry Matula](http://www.terrymatula.com/)
- [The App Guruz](http://www.theappguruz.com/blog) \[04/26/2016\]
- [The Reluctant Web Developer](http://thereluctantdeveloper.com/category/laravel)
- [Tighten.co](http://blog.tighten.co/) \[04/13/2016\]
- [Tim Leland](http://timleland.com/) \[09/29/2015\]
- [Tirdea Mihai](https://tirdeamihai.com/blog/tag/laravel) \[03/30/2017\]
- [TJ Miller](https://www.tjmiller.me) \[10/13/2018\]
- [TNT Studio](http://tntstudio.us/blog)
- [Todd Francis](http://toddish.co.uk/blog/tag/laravel/) \[07/30/2015\]
- [Tom Schlick](https://tomschlick.com/) \[03/20/2017\]
- [Tomas Votruba](https://www.tomasvotruba.cz/blog/) \[03/19/2018\]
- [Tommy Ku](http://blog.tommyku.com/)
- [Tutelage Systems](http://tutelagesystems.com/) \[05/09/2016\]
- [Tutsnare](http://tutsnare.com/category/laravel/)
- [Unlikenesses](http://unlikenesses.com/) \[04/10/2018\]
- [Vegi Bit](http://vegibit.com/tag/laravel/)
- [Vincent Klaiber](https://vinkla.com/) \[08/11/2015\]
- [Vehikl](http://transmission.vehikl.com/) \[08/10/2015\]
- [W3Laravel](http://www.w3laravel.com/) \[08/15/2016\]
- [Web Design & Development Talk](http://www.web-design-talk.co.uk/category/laravel-4/)
- [Web Monkeys](https://www.webmonkeys.io/forums/laravel.27/) \[09/02/2016\]
- [WebDevTuts](http://webdevtuts.co.uk/tag/laravel/) \[07/13/2015\]
- [Web Fosters, The](https://thewebfosters.com/tag/laravel) \[11/21/2017\]
- [Weblint4u](http://weblint4u.com/category/laravel/)
- [Websanova](http://www.websanova.com/blog/) \[09/23/2015\]
- [Webs Mentor](https://websmentor.wordpress.com/category/laravel/) \[10/18/2016\]
- [Wogan](https://wogan.blog/tag/laravel/) \[02/16/2017\]
- [WSnippets](http://wsnippets.com/category/laravel/)
- [Yottaram (Jonathan Stavis)](http://yottaram.com/blog/)
- [zwacky](https://medium.com/@zwacky)

### Forums and Groups
- [Forge Recipes](http://forgerecipes.com/) - Community-maintained recipes for using [Laravel Forge](https://forge.laravel.com/). \[09/21/2017\] 
- [Go Laravel](http://www.golaravel.com/) - Chinese-language forum and shared blog site for Laravel. \[04/22/2015\]
- [Google+ Laravel Community](https://plus.google.com/communities/106838454910116161868)
- [LaraChat](https://larachat.co/) - A Slack channel for learning and sharing about Laravel framework. \[09/04/2015\]
- [Laravel China](https://laravel-china.org/) \[10/01/2016\]
- [Laravel LinkedIn Group](https://www.linkedin.com/groups/Laravel-PHP-Framework-4419933)
- [Laravel Recipes](http://laravel-recipes.com/)
- [Laravel Reddit](http://www.reddit.com/r/laravel/)
- [Laravel.io Forums](http://laravel.io/forum) - The Official Laravel PHP Framework Community Portal
- [Larazona](http://larazona.org/) - Scottsdale, AZ Laravel Meetup group. \[09/09/2015\]
- [Learn Laravel Reddit](http://www.reddit.com/r/learnlaravel/) - Good forum for Laravel beginners (however, not very active).
- [Quora Laravel Forum](http://www.quora.com/Laravel)
- [Twitter Laravel Resources](https://twitter.com/search?q=laravel&src=typd)

### Conferences, Meetups, and User Groups
- [ArtisanConf](https://www.artisanconf.com/) \[04/20/2015\]
- [Laracon EU](http://laracon.eu/)
- [Laracon US](http://laracon.us/) \[04/09/2015\]
- [Laravel Austin](http://laravelaustin.com/) \[03/28/2016\]
- [Laravel Berlin](http://www.meetup.com/laravel-berlin/) \[03/28/2016\]
- [Laravel Buenos Aires](https://www.meetup.com/Laravel-Buenos-Aires/) \[10/17/2016\]
- [Laravel Chicago](http://www.meetup.com/laravel-chicago/) \[03/28/2016\]
- [Laravel London](https://www.meetup.com/London-Laravel/) \[10/17/2016\]
- [Laravel Nairobi](https://www.meetup.com/Nairobi-Laravel-Meetup/) \[10/17/2016\]
- [Laravel Sao Paulo](https://www.meetup.com/Laravel-SP/) \[10/17/2016\]
- [Laravel Tokyo](https://laravel.tokyo/) \[03/28/2016\]
- [PHP Laravel Framework Sydney](https://www.meetup.com/PHP-Laravel-Framework-Sydney/) \[10/17/2016\]
- [San Diego Laravel User Group (SDLUG)](https://www.sdlug.com/) \[03/28/2016\]
- [Laravel Hungary](https://laravel.hu)
- [Laravel Hungary Meetup](https://www.meetup.com/Laravel-Hungary-Meetup/)

### Newsletters
- [Daily Laravel](http://paper.li/stevenklar/1389804586) - Aggregator of new/upcoming Laravel articles and tutorials. \[07/09/2015\]
- [Laravel Weekly](https://github.com/LaravelIO/LaravelWeekly) - Publication currently suspended, but lots of good information in back issues.
- [Laravel News](http://laravel-news.com/) - Popular newsletter with updates from the Laravel community including excellent profiles of community members.
- [Laravel Quick Tips](http://codebyjeff.com/newsletter) - Weekly e-mail with tips on Laravel to be read in under 5 minutes. \[01/11/2016\]
- [Laravel Reading List](http://boringmonday.com/) - Automatically updated news aggregator for Laravel articles, packages, and Reddit posts. \[08/28/2017\]
- [paper.li Laravel Weekly](http://paper.li/akhy/1356948419#!) - Weekly news and articles on Laravel.

### Job Sites/Postings
- [Laravel Gurus](http://laravelgurus.com/) - The best place to find consultants and freelancers for your Laravel projects.
- [LaraJobs](http://larajobs.com/) - The best place to post your PHP, Laravel, or technical guru jobs.
- [Laralance](https://laralance.com/) - Job listing site for Laravel freelancers. \[03/27/2018\]

### Development Tools
- [docker-laravel](https://github.com/mtmacdonald/docker-laravel) - A Ubuntu [LEMP](https://lemp.io/) [Docker](https://www.docker.com/) base image for Laravel development loosely based on [Phusion Base Image](https://github.com/phusion/baseimage-docker). \[06/01/2015\]
- [docker-laravel](https://github.com/harshjv/docker-laravel) - Laravel 5 environment built on Docker with PHP-FPM, MySQL, nginx, and Gulp managed using [Docker Compose](https://github.com/docker/compose). \[05/17/2016\]
- [docker-laravel](https://github.com/richbayliss/docker-laravel) - A set of docker-compose files for running a Laravel PHP application in Docker. \[02/06/2017\]
- [LaraBug](https://www.larabug.com/) - Online error reporting tool for Laravel (limited free plan available). \[12/16/2016\]
- [LaraDock](https://github.com/LaraDock/laradock) - Complete, very well documented toolkit for setting up Homestead-like Laravel development environment using Docker. \[04/12/2016\]
- [Laragen](http://makzumi.com/laragen/) - Online tool for generating Laravel views for *index*, *create*, and *edit*, based on your model definition.
- [Laragon](http://laragon.org/) - Open-source toolkit for setting up Laravel development environment on Windows.
- [Laravel Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Awesome tool that adds a JavaScript-based bar to bottom of page which shows details about routes, HTTP requests, variables, and much more.
- [Laravel Docker](https://github.com/SteveAzz/laravel-docker) - [Docker](http://docker.io/) configuration for building Laravel development environment. \[10/30/2015\]
- [Laravel Drydock](https://github.com/atrauzzi/laravel-drydock) - A pre-built local development environment for Laravel using Docker. \[02/08/2016\]
- [Laravel Extension Pack for Visual Studio Code](https://github.com/onecentlin/laravel-extension-pack-vscode) - Several extensions for [Visual Studio Code](https://code.visualstudio.com/) for Laravel syntax highlighting and productivity. \[10/16/2018\]
- [Laravel Model/Migration Generator](http://andressantibanez.com/laravel-model-generator/) - Simple online tool for generating Laravel model class definition and database migration code by entering details about database table. \[08/04/2016\]
- [Laravel on Windows](https://laravelonwindows.com/) - Help for developers using Windows, including how to use Homestead and Vagrant. \[03/08/2017\]
- [Laravel Stats](https://github.com/stefanzweifel/laravel-stats) - Add Artisan command to show summary statistics of your project, such as number of classes, methods, lines of code, etc. \[11/06/2017\]
- [Laravel Tail](https://github.com/spatie/laravel-tail) - Brings back the awesome `tail` command for artisan to Laravel 5. \[02/14/2017\]
- [Laravel 
*for Ubuntu*](https://github.com/cpriego/valet-ubuntu) - Port of [Laravel Valet](http://laravel.com/docs/valet) (for Mac) to run on Ubuntu. \[05/31/2016\]
- [Lumen](http://lumen.laravel.com/) - PHP micro-framework based on Laravel (official).
- [Orator](http://www.midnightcowboycoder.com/) - Online tool to convert legacy SQL queries to Laravel [Query Builder](https://laravel.com/docs/5.5/queries) format. \[09/02/2017\]
- [PHP Framework Benchmarks](https://github.com/kenjis/php-framework-benchmark) - Real-world benchmarks of many popular (and a few obscure!) PHP frameworks, including Laravel 4.x and 5.x and Lumen. \[07/28/2016\]
- [PHP Storm Laravel Live Templates](https://github.com/koomai/phpstorm-laravel-live-templates) - Comprehensive set of templates for Laravel for [PHP Storm](https://www.jetbrains.com/phpstorm/). \[05/25/2015\]
- [Pier](https://github.com/codecasts/pier) - A set of customized Docker images for running Laravel with support for PHP 7.x, Nginx, Caddy, MySQL, and PostgreSQL. \[08/15/2016\]
- [Scotch Box](https://box.scotch.io/) - A complete [LAMP](https://en.m.wikipedia.org/wiki/LAMP_%28software_bundle%29) [Vagrant](http://vagrantup.com/) box with PHP 5.5, Laravel installer, and Node.JS front-end tools. \[05/22/2015\]
- [SQL to Laravel Seeder Converter](http://laravel.stonelab.ch/sql-seeder-converter/) - Online tool to convert SQL INSERT statements to Laravel seeder syntax. \[05/05/2015\]
- [Understand.io](https://www.understand.io/) - Online service for managing, searching, and deciphering PHP and Laravel log files. \[04/27/2015\]
- [valet4windows](https://github.com/vitr/valet4windows) - Windows version of Laravel Valet \[03/19/2017]
- [Valet for Windows](https://github.com/cretueusebiu/valet-windows) - Port of the popular [Laravel Valet](https://laravel.com/docs/valet) environment for Macs to Windows. \[03/08/2017\]
- [vim-blade](https://github.com/jwalton512/vim-blade) - Vim syntax highlighting for Laravel's Blade template syntax. \[01/04/2016\]
- [VS Web Essentials](http://vswebessentials.com/) - Free Visual Studio extension with support for Laravel syntax. \[07/13/2015\]
- [Laravel MultiMix](https://github.com/fandogh/laravel-multimix) - Laravel-Mix helper for projects with complex & multi assets.

##### Testing & Debugging

* [Laravel TestTools](https://chrome.google.com/webstore/detail/laravel-testtools/ddieaepnbjhgcbddafciempnibnfnakl) - Chrome extension to generate Laravel integration tests while using your app
* [Laravel Test Factory Generator](https://github.com/mpociot/laravel-test-factory-helper) - Generate Laravel test factories from your existing models
* [Clockwork](https://github.com/itsgoingd/clockwork) - Integrates Clockwork Chrome extension for debugging and profiling apps
* [Debug Bar](https://github.com/barryvdh/laravel-debugbar) - Integrates PHP Debug Bar with Laravel
* [Ignition](https://github.com/facade/ignition) - A beautiful error page for Laravel apps
* [Laravel 5 Log Viewer](https://github.com/rap2hpoutre/laravel-log-viewer) - Log viewer
* [LogViewer](https://github.com/ARCANEDEV/LogViewer) - Provides a log viewer
* [LERN](https://github.com/tylercd100/lern#lern-laravel-exception-recorder-and-notifier) - Record exceptions into a database and will send you a notification
* [Mail Preview](https://github.com/themsaid/laravel-mail-preview) - Preview sent mail in a web browser or mail client
* [Laravel Tracy](https://github.com/recca0120/laravel-tracy) - A Laravel Package to integrate Nette Tracy Debugger
* [Laravel Terminal](https://github.com/recca0120/laravel-terminal) - run artisan in a web browser
* [Laravel API Tester](https://github.com/asvae/laravel-api-tester) - Postman-like tool with Laravel routes
* [Laravel Tail](https://github.com/spatie/laravel-tail) - The missing tail command
* [Laravel Telescope](https://github.com/laravel/telescope) - Laravel Telescope is an elegant debug assistant for the Laravel framework

### Other
- [My Pinboard Links for Laravel](https://pinboard.in/u:tdjones/t:laravel/)
- Another [Awesome Laravel List](https://github.com/chiraggude/awesome-laravel) :)
- Another [Awesome Laravel List](https://github.com/tuwannu/awesome-laravel)
- [TinyLara](http://tinylara.com/) - A simple framework based on the principles of Laravel ("Tiny Laravel"). \[04/22/2015\]
- [We Made the Front Page of PHP Reddit!  Thanks!](https://www.reddit.com/r/PHP/comments/5xaa6g/a_curated_list_of_delightful_laravel_php/) \[03/06/2017\]
