# by Createtor

## DEV
- Generate Service `ng g service --spec=false services/__`
- Generate Component `ng g component --spec=false components/__`
- การ Deploy Project
    `ng build` หรือ `ng build --p` เพื่ออัพเดท โปรเจคใน /dist
    *ถ้ามีปัญหาลบ folder dist ออกหลัง build แล้วทำการ build ใหม่อีกครั้ง
    `firebase deploy` เพื่ออัพงานขึ้น firebase

## Fix Error node_modules appears empty, you may need to run npm install
- cd ไปที่ตำแหน่งโฟลเดอโปรเจค รัน `npm install`
- แก้ .map ตอนยิง http rxjs/add/operator/map `npm i --save rxjs-compat`

## Deploy and Manage
- Project Console: https://console.firebase.google.com/u/0/project/portfolioangular/overview
- Hosting URL: https://portfolioangular.firebaseapp.com

# JSON
- DummyJSON : https://jsonplaceholder.typicode.com/
- Generate Typescript From JSON : http://json2ts.com/

# 

# AngularPortfolio

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 6.0.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
