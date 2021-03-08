# Web Namespace Registry
A namespaces registry for things like custom elements, classes and css properties.  
There can be multiple frameworks using the same namespace.

## Check if a namespace is used
[check here](
  https://raw.githack.com/nuxodin/web-namespace-registry/main/web/index.html
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
Can we, the frontend community, agree on a project-specific namespace?  
This should not be used for frameworks, so it can be used in a project without hesitation.  
So far I have always used "cd", (customer data) but maybe another one is more suitable.  

- c- (customer)
- p- (project)
- ps- (project specific)  

What is your opinion?
