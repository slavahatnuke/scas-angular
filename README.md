# scas-angular
This is Angular 2/4 scaffolding. [+1G](http://plus1generation.com/)

### How to install:
- `npm install -g scas` [https://www.npmjs.com/package/scas](https://www.npmjs.com/package/scas)
- `npm install scas-angular --save-dev` install 
- `scas init` it will generate `.scas.js`
- open in editor `.scas.js`
- setup `imports`

```javascript

// ...
imports: [
	{ path: 'scas/.scas' },
	{ path: 'scas-angular' },
]
// ...
```
- run `scas`

```bash
$ scas [actions] <arguments>
  Angular scaffolding [+1G]

    module                       Module + routing
    service.module               Module + service + model
    component                    Simple component
    service                      Simple service
    class                        Simple class/model
    routing.module               Simple routing module
    routing.can.activate         Simple can activate guard
    resolver                     Simple resolver
    rest.resource                RESTFul Resource
    rest.service                 RESTFul Service
```

Follow more info about `scas` [https://www.npmjs.com/package/scas](https://www.npmjs.com/package/scas)

Thanks,
[+1G](http://plus1generation.com/)