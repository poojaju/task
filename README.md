# task

## ngRx install command for setup
ng generate effect Company --root -m app.module.ts ,
ng generate selector Company ,
ng generate reducer Company --reducers reducers/index.ts  ,
ng generate action company ,
ng generate store State --root --module app.module.ts ,
npm install @ngrx/store --save ,
npm install @ngrx/effects --save ,
npm install @ngrx/store-devtools --save ,
npm i -g @schematics\angular ,
ng generate store State ,

## json 
json-server --watch data.json ,
npm install -g json-server ,

# creating interface and services to call data
ng g interface company ,
ng g service company ,

# folder- structure 
app- 
company-data - components,
reducers-index.ts,
company.model.ts,
comapany.service.ts,
company.selector.ts,
company.action.ts,
company.effect.ts,
assets/data.json,
app.module.ts,

