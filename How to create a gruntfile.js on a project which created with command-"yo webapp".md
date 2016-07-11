## How to create a gruntfile.js on a project which created with command "yo webapp"??

Since generator-webapp uses Gulp as the default build system, so if you want to use Grunt instead,

please checkout the legacy-grunt branch and npm link that as the generator:

1. git clone https://github.com/yeoman/generator-webapp

2. cd generator-webapp

3. git checkout legacy-grunt

4. npm link # this will install dependencies and link it as the global package

5. cd path/to/your/project

6. yo webapp

