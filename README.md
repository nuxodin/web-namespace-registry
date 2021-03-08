# Web Namespace Registry
A registry for namespaces for custom elements, data attributes, custom attributes and css properties.   

This registry is not meant to reserve a namespace for yourself, rather to see which framework your framework might collide with.
There can be multiple frameworks using the same namespace.

## Check if a namespace is used
[check here](
  https://rawcdn.githack.com/nuxodin/web-namespace-registry/b3bdc2fb27eda4f558e569bad0210153e4ea2c4d/web/index.html
)

## Add your own framework
Make a fork, extend registry.v1.json and make a pull request.  
"affected:['ce',...]" means:
- ce = custom elements `<x-box>`
- ca = custom attributes `<div x-color=red>` (non standard)
- data-a = data attributes `<div data-x-color=red>`
- class = class attributes `<div class="x-color">`
- css-cp = css custom properties (css variables) `--x-color:red;` 

## A project-specific namespace?
Can we agree on a project-specific namespace?  
This should not be used for frameworks, so it can be used in a project without hesitation.  
So far I have always used "cd", (customer data) but maybe another one is more suitable.  

- c- (customer)
- p- (project)
- ps- (project specific)  

What is your opinion?
