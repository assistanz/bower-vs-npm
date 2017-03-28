# Bower vs Npm
Bower and Npm are package managers for javascript. Many developers have confusion where we should use Bower or Npm. Some projects has Npm and Bower. But developers don't know, why they are using these two in projects. Here, we have explained about purposes of these two tools. Then you will come to know where bower must be used and where npm must be used.  
  
## Bower
Bower is created solely for the front-end development and is optimized with that in mind. It uses flat dependency tree, requiring only one version for each package, reducing the page load. It mainly aims for minimal resource load.  

Bower has a configuration file called bower.json. In this file we can maintain the configuration for Bower like which dependencies we need and license details, description, name and so on.  

Bower is suitable for front-end packages like jquery, angular, react, ember, knockout, backbone and so on.  

## Npm (Node package manager)
Npm is most commonly used for managing Node.js modules, but it works for the front-end too.  It uses nested dependency tree, which means that your dependencies can have their own dependencies which can have their own, and so on. A nested dependency tree means that your dependencies can have their own dependencies which can have their own, and so on. This is really great on the server where you don't have to care much about space and latency.  

This obviously doesn't work that well on the front-end, because we need jQuery in our projects. We need only one copy of jQuery, but when another package requires jQuery, then it will download again one more copy of jQuery. This is one of the main drawbacks of Npm.  

Npm has a configuration file called package.json. In this file we can maintain the configuration for Npm like which dependencies we need and license details, description, name and so on. Npm provides Dependencies and DevDependencies. Dependencies will download and maintain the front-end files like Jquery, Angular and so on. DevDependencies will download and maintain development tools like Grunt, Gulp, JSHint and so on.  

The reason many projects use both is that they use Bower for front-end packages and Npm for developer tools like Grunt, Gulp, JSHint etc.  

All package managers have their own drawbacks. We need to choose which one is best for our projects.  

For further queries email to    
sales@assistanz.com  
amal@assistanz.com  
