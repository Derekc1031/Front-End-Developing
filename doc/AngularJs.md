# Angular2 & Angular 4
  * [A curated list of awesome Angular 2 and Angular 4 resources by @AngularClass](https://github.com/AngularClass/awesome-angular)

# AngularJS Develope Guide

  1. ## AngularJS-Style-Guide

  * [angular-style-guide from johnpapa](https://github.com/johnpapa/angular-styleguide)

  * [angular-style-guide from toddmotto](https://toddmotto.com/opinionated-angular-js-styleguide-for-teams/)

  * [angular-style-gudie for Angular 1.5 & 2.0 from toddmotto](https://github.com/toddmotto/angular-styleguide#controllers)

  * [Minimal Angular module/syntax approach using an IIFE](https://toddmotto.com/minimal-angular-module-syntax-approach-using-an-iife)

  2. ## Coding Suggestion

  * [AngularJS 1.5 最佳實務](https://amobiz.github.io/2016/04/15/angularjs-1.5-best-practices/)

  * [Top 18 Most Common Mistakes that AngularJS Developers Make](https://www.toptal.com/angular-js/top-18-most-common-angularjs-developer-mistakes)

  * [How we messed up our Angular App](https://blogs.mumairkhan.com/2015/03/14/how-we-messed-up-our-angular-app.html)

  * [Speeding up AngularJS apps with simple optimizations](http://www.binpress.com/tutorial/speeding-up-angular-js-with-simple-optimizations/135)

  3. ## The [Bootstrap](https://docs.angularjs.org/guide/bootstrap) Phase of AngularJS
  
  * load the [Modules](https://docs.angularjs.org/guide/module) associated with the directive. 
  * create the application [injector](https://docs.angularjs.org/api/auto/service/$injector).
    Note: injector is used to retrieve object instances defined by [provider](https://docs.angularjs.org/api/auto/service/$provide), instantiate types, invoke methods and load modules.
 
      ### The related concept about the Bootsrap phase   
      * [Dependency Injection (DI)](https://docs.angularjs.org/guide/di)
         * [AngularJS DI 介紹](http://blog.hellojcc.tw/2015/02/04/angular-providers/)
         
      * [Modules](https://docs.angularjs.org/guide/module)
         * [AngularJS 模組化](http://ithelp.ithome.com.tw/articles/10160976) 
         
      * [Provider](https://docs.angularjs.org/api/auto/service/$provide)
         * [service](https://docs.angularjs.org/guide/services)
         * factory
         * [淺談Angular.js的Provider機制](http://kirkchen.logdown.com/posts/245678-angularjs-talking-about-the-angularjs-provider-mechanisms)
         * [AngularJS: Factory vs Service vs Provider](https://medium.com/m/global-identity?redirectUrl=https%3A%2F%2Ftylermcginnis.com%2Fangularjs-factory-vs-service-vs-provider%2F)
         * [AngularJS: Factory vs Service vs Provider by TheRoks](http://www.theroks.com/angularjs-factory-vs-service-vs-provider/)
         * [AngularJS Service, Factory, Provider 差別](http://youradsor.appspot.com/u?purl=bG10aC5yZWRpdm9ycC15cm90Y2FmLWVjaXZyZXMtc2pyYWx1Z25hLzEwLzQxMDIvbW9jLnRvcHNnb2xiLmFyZW5uYXhvci8vOnB0dGg%3D)
         * [AngularJS Service / Factory Tutorial with Example](http://viralpatel.net/blogs/angularjs-service-factory-tutorial/)
         
 4. ## The [Compile](https://docs.angularjs.org/api/ng/service/$compile) Phase of AngularJS
 * Traverse the static DOM and collecting all the [directives](https://docs.angularjs.org/guide/directive). 
 * [Link](https://docs.angularjs.org/api/ng/service/$compile#-link-) the directives with [Scopes](https://docs.angularjs.org/guide/scope) and produce a live view. It will help for "The Runtime Data Binding Phase" to dectect any changes in the scope model are reflected in the view, and any user interactions with the view are reflected in the scope model.
      
      ### The related concept about the Compile phase
      * [Compile](https://docs.angularjs.org/api/ng/service/$compile)
         * [HTML Compiler](https://docs.angularjs.org/guide/compiler)
         * [Directive Compilation in AngularJS – step-by-step](http://triangular.io/blog/directive-compilation-in-angularjs-step-by-step/) 

      * [Directives](https://docs.angularjs.org/guide/directive)
         * Creating Custom AngularJS Directives by Dan Wahlin: 
            * [part1](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-i-the-fundamentals)
            * [part2](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-2-isolate-scope)
            * [part3](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-3-isolate-scope-and-function-parameters)
            * [part4](http://weblogs.asp.net/dwahlin/creating-custom-angularjs-directives-part-4-transclusion-and-restriction)
         * [A Practical Guide to AngularJS Directives](https://www.sitepoint.com/practical-guide-angularjs-directives/) 
         * [AngularJS Custom Directives](http://tutorials.jenkov.com/angularjs/custom-directives.html)
         
      * [Components](https://docs.angularjs.org/guide/component)
         * [Using AngularJS Component – Beginner guide](http://jsconfig.com/component-angularjs-1-5-beginner-guide/)
         * [EXPLORING ANGULAR 1.5: LIFECYCLE HOOKS](http://blog.thoughtram.io/angularjs/2016/03/29/exploring-angular-1.5-lifecycle-hooks.html)
         * How to upgrade your app to componet style following with Angular 1.5 and beyound:
            * [Refactoring Angular Apps to Component Style](http://proxyfile2.appspot.com/u?purl=bG10aC5zdG5lbm9wbW9jLW90LXNwcGEtcmFsdWduYS1nbmlyb3RjYWZlci84MS8wMS81MTAyL2dvbGIvb2ZuaS5hcG9yZXQvLzpwdHRo)
            * [Upgrade Your App to Angular 1.5 Components and Beyond!](https://www.sitepoint.com/upgrade-to-angular-components/)
            * [Build an Angular 1.5 component – An AngularJS tutorial](https://tests4geeks.com/tutorials/build-angular-1-5-component-angularjs-tutorial/)
            * [Exploring the Angular 1.5 .component() method](https://toddmotto.com/exploring-the-angular-1-5-component-method/)
            
      * [Controllers](https://docs.angularjs.org/guide/controller)
         * [Rethinking AngularJS Controllers](https://toddmotto.com/rethinking-angular-js-controllers/) 
         * [Digging into Angular’s “Controller as” syntax](https://toddmotto.com/digging-into-angulars-controller-as-syntax/)
         * [關於 AngularJS 控制器 (ngController) 的多種宣告方法](http://blog.miniasp.com/post/2013/07/23/AngularJS-five-ways-to-register-ngController.aspx)

5. ## The Runtime Data Binding Phase of AngularJS
* any changes in the scope are reflected in the view and any changes in the view are directly updated in the scope.
    
  ### The related concept about the Compile phase
     * [Scopes](https://docs.angularjs.org/guide/scope)
        * scope context:
           * [AngularJS Scopes: An Introduction](http://blog.carbonfive.com/2014/02/11/angularjs-scopes-an-introduction/)
           * [Understanding Scopes](https://github.com/angular/angular.js/wiki/Understanding-Scopes)
           * [Mastering the Scope of the Directives in AngularJS](https://www.undefinednull.com/2014/02/11/mastering-the-scope-of-a-directive-in-angularjs/)
           * [5 Guidelines For Avoiding Scope Soup in Angular](http://www.technofattie.com/2014/03/21/five-guidelines-for-avoiding-scope-soup-in-angular.html)
           * [No $scope soup, bindToController in AngularJS](https://toddmotto.com/no-scope-soup-bind-to-controller-angularjs/)
            
        * [data binding & scope flow: $watch, $digest and $apply](https://docs.angularjs.org/guide/scope#integration-with-the-browser-event-loop)
           * [生生不息的 watcher-介紹 data-binding](http://ithelp.ithome.com.tw/articles/10161497) 
           * [AngularJS $watch() , $digest() and $apply()](http://tutorials.jenkov.com/angularjs/custom-directives.html#compile-and-link)
           * [Make Your Own AngularJS: Scopes And Digest](http://your-zone.appspot.com/u?purl=bG10aC50c2VnaWQtZG5hLXNlcG9jcy0xLXRyYXAtcmFsdWduYS1ud28tcnVveS1la2FtLzMwLzExLzMxMDIvZ29sYi9vZm5pLmFwb3JldC8vOnB0dGg%3D)

6. ## Useful Tools
* [AngularJS Batarang](https://chrome.google.com/webstore/detail/angularjs-batarang/ighdmehidhipcmcojjgiloacoafjmpfk?hl=en)
* [Tutorial about AngularJS Bataran](https://egghead.io/lessons/angularjs-angularjs-batarang)

7. ## Others
* [Everything about custom filters in AngularJS](https://toddmotto.com/everything-about-custom-filters-in-angular-js/) 
* [Pretty URLs in AngularJS: Removing the #](https://scotch.io/tutorials/pretty-urls-in-angularjs-removing-the-hashtag)
* [AngularJS-Learning](https://github.com/Derekc1031/AngularJS-Learning)
* [AngularJS 開發實戰：重要的開發觀念與經驗分享](https://www.youtube.com/watch?v=aXuK2ACHLcU)
* [How do I think in angularjs if have a jquery background](/doc/How do I think in angularjs if have a jquery background.docx)
