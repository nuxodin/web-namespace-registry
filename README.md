# Web Namespace Registry
Welcome to the web namespaces registry.  

The goal of this project:  
If someone is planning to develop a web framework, they can check to see if there might be a naming conflict with another framework.

## Check if a namespace is used
Check a namespace on [webnamespaces.org](
  https://webnamespaces.org
)

## Add your own framework
Make a fork, extend registry.v1.json and make a pull request.  
Extend it like this:
```json
    ...
    "myns": [
        {
            "name":"Name of your Framework",
            "url":"https://github.com/xxx/xxx",
            "affected":["ce","class"]
        }
    ],
    ...
```
url: Preferably a repository or project home on github  

affected means:  
- ce = custom elements `<x-box>`
- ca = custom attributes `<div x-color=red>` (non standard)
- class = class attributes `<div class="x-color">`
- css-cp = css custom properties (css variables) `--x-color:red;`   

**_NOTE:_** Please specify only technologies that you actually use, not those that are planned.

There can be multiple frameworks using the same namespace.  


### Add a badge
[![Registred on webnamespaces.org](https://img.shields.io/static/v1?label=webnamespaces.org&color=blue&message=myns)](https://webnamespaces.org)
```
[![Registred on webnamespaces.org](https://img.shields.io/static/v1?label=webnamespaces.org&color=blue&message=myns)](https://webnamespaces.org)
```
Replace "myns" with your namespace.

## Contribute

### Discussion
Discuss the issues with us and create new ones
https://github.com/nuxodin/web-namespace-registry/issues


### Help wanted
Any help is welcome.  
In particular: expand the list and share the project.  
