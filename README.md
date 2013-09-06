# [A3M (Account Authentication & Authorization)] (https://github.com/donjakobo/A3M/)

A CodeIgniter 2.x package that leverages bleeding edge web technologies like OpenID and OAuth to create a user-friendly user experience. It gives you the CRUD to get working right away without too much fuss! A3M is a full package meant for building websites from scratch without all that tiresome login / logout / admin stuff thats always required.

## Original Authors

**Jakub** [@kubanishku](https://twitter.com/kubanishku/)  
**PengKong** [@pengkong](https://github.com/pengkong)
		
## Key Features & Design Goals

See our **[app task board on Trello](https://trello.com/board/a3m/512c08b874b855f26200e690)** to get a glimps of to-do items

* Native Sign Up, Sign In with 'Remember me' and Sign Out  
* Native account Forgot Password and Reset Password  
* Facebook/Twitter/Google/Yahoo/OpenID Sign Up, Sign In and Sign Out  
* Manage Account Details, Profile Details and Linked Accounts  
* reCAPTCHA Support, SSL Support, Language Files Support  
* Gravatar support for picture selection (via account profile) **(NEW)**
* Create a painless user experience for sign up and sign in  
* Create code that is easily understood and re-purposed  
* Utilize Twitter Bootstrap (a fantastic CSS / JS library)  
* Graceful degradation of JavaScript and CSS  
* Proper usage of CodeIgniter's libraries, helpers and plugins  
* Easily Configurable via config file  

## Folder structure  

* `/application/` - what you should be editing / creating in    
* `/system/` - default CodeIgniter system folder (don't touch!)   
* `/resource/` - css / images / javascript (folder configurable via `constants.php`)   
* `/user_guide/` - latest guide for CI (can be deleted, just for CI reference)

## 3rd Party Libraries & Plugins

* [recaptcha_pi.php](http://code.google.com/p/recaptcha/) - recaptcha-php-1.11
* [facebook_pi.php](https://github.com/facebook/facebook-php-sdk/) - v.3.2.2 
* [twitter_pi.php](https://github.com/jmathai/twitter-async) - Updated to latest release - [Jun 21, 2013](https://github.com/jmathai/twitter-async/commits/master)  
* [phpass_pi.php](http://www.openwall.com/phpass/) - Version 0.3 / genuine _(latest)_ 
* [openid_pi.php](http://sourcecookbook.com/en/recipes/60/janrain-s-php-openid-library-fixed-for-php-5-3-and-how-i-did-it) - php-openid-php5.3  
* [gravatar.php](https://github.com/rsmarshall/Codeigniter-Gravatar) - codeigniter (6/25/2012) rls

## Dependencies

* CURL
* DOM or domxml 
* GMP or Bcmatch

## How to install?
Check out the wiki: https://github.com/donjakobo/A3M/wiki/Installation-Instructions

