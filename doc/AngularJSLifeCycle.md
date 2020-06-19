# An Overview of the AngularJS Life Cycle

Now that you understand the components involved in an AngularJS application, 

you need to understand what happens during the life cycle, which has three phases: bootstrap, compilation, and runtime. 

Understanding the life cycle of an AngularJS application makes it easier to understand how to design and implement your code.

The three phases of the life cycle of an AngularJS application happen each time a web page is loaded in the browser. 

The following sections describe these phases of an AngularJS application.

## The Bootstrap Phase
The first phase of the AngularJS life cycle is the bootstrap phase, 

which occurs when the AngularJS JavaScript library is downloaded to the browser. 

AngularJS initializes its own necessary components and then initializes your module, which the ng-app directive points to. 

The module is loaded, and any dependencies are injected into your module and made available to code within the module.

## The Compilation Phase
The second phase of the AngularJS life cycle is the HTML compilation stage. 

Initially when a web page is loaded, a static form of the DOM is loaded in the browser. 

During the compilation phase, the static DOM is replaced with a dynamic DOM that represents the AngularJS view.

This phase involves two parts: 

1. Traversing the static DOM and collecting all the directives and then 

2. Linking the directives to the appropriate JavaScript functionality in the AngularJS built-in library or custom directive code. 

The directives are combined with a scope to produce the dynamic or live view.

## The Runtime Data Binding Phase
The final phase of the AngularJS application is the runtime phase,

which exists until the user reloads or navigates away from a web page. 

At that point, any changes in the scope are reflected in the view, 

and any changes in the view are directly updated in the scope,making the scope the single source of data for the view.

AngularJS behaves differently from traditional methods of binding data. 

Traditional methods combine a template with data received from the engine and then manipulate the DOM each time the data changes. 

AngularJS compiles the DOM only once and then links the compiled template as necessary, making it much more efficient than traditional methods.


### Reference: 

[Learning AngularJS by Brad Dayley](http://www.informit.com/store/learning-angularjs-9780134034546?w_ptgrevartcl=Getting+Started+with+AngularJS_2271482)
