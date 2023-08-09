# angular-shopping-site-part1

Hi,

This is a simple Angular POC created by Abhishek Choubey. In this POC I started building Shopping website <br/>
This is 1st build push for the Shopping website, for building this portal I am using Angular. <br/>


<b>Highlights of 1st Push</b> <br/>
ng g new customerportal //for creating project <br/>
stylesheet format would you like to use? = SCSS <br/>
npm i bootstrap //for installing bootstrap <br/>
npm install font-awesome //for installing font awesome <br/>

<br/><br/>

routing = yes <br/>
scss = selected <br/>
setting ---> assets <br/>
themify icons search google ---->download icon font <br/>
theme.scss <br/>
Inside assets folder create file = app.scss <br/>
and put reference of theme.scss and css/themify-icons.css <br/>
npm install bootstrap <br/>
npm install ng-bootstrap  <br/>
npm install font-awesome  <br/>
npm install ngx-toastr  <br/>
npm install @angular/animations   <br/>
inside app.scss put import of toastr, bootstrap.scss,font-awesome.scss  <br/>
npm install ng5-slider  <br/>
npm install ngx-bar-ratting  <br/>
npm install ngx-infinite-scroll  <br/>
npm install slick-carousel <---- for image slider  <br/>
npm install smartmenus  <br/>
node-sass <--- package {depcreated in latest version}  <br/>
npm i node-sass  <br/>
ngx-translate  <br/>
npm install @ngx-translate/core  <br/>
npm install @ngx-translate/http-loader  <br/>
https://stackoverflow.com/questions/51020285/loading-httploaderfactory-translator-not-work-after-resume-network-connectivity  <br/>

<b>ng-bootstrap ; Installing from npm is simply doing </b> <br/>
npm install @ng-bootstrap/ng-bootstrap  <br/>
npm install @angular/localize --save  <br/>

Version Used ==> ng-bootstrap v15.1.0 <br/>
https://ng-bootstrap.github.io/#/components/progressbar/examples <br/>
npm i --save-dev @types/feather-icons  <--------------- This worked <br/>

const feather = require('feather-icons');  //<--------------------- This is required when we use above command inside ts file. <br/>
https://stackoverflow.com/questions/41292559/could-not-find-a-declaration-file-for-module-module-name-path-to-module-nam <br/>
https://feathericons.com/?query=git     <------------------ Official site which contains icons. <br/>
ng g c feather-icon --skip-tests  <br/>

ngx-toastr <br/>
========
<br/>
npm i ngx-toastr@12.0.0
<br/>
npm install @angular/animations@12.0.0 --save
<br/>

<b>Important Note </b> <br/>
tsconfig.json <br/>
{
<br/>
...
<br/>
  complilerOptions: { <br/>
        ...
        "skipLibCheck": true <br/>
    } <br/>
} 

<br/>
Inside styles.css -----------> @import '../node_modules/ngx-toastr/toastr-old.css';  //<=============Imp
<br/>

npm i sweetalert2@11.7.1
<br/>
https://sweetalert2.github.io/#examples
<br/>
https://sweetalert2.github.io/#usage
<br/> <br/>

<b> Version details of third party packages </b>
<br/>

"bootstrap": "^5.2.3",<br/>
"feather-icons": "^4.29.0",<br/>
"font-awesome": "^4.7.0",<br/>
"ngx-toastr": "^12.0.0",<br/>
"rxjs": "~7.5.0",<br/>
"sweetalert2": "^11.7.1",<br/>


Software Used <br/>
node --version = v14.20.0 <br/>
npm --version = 6.14.17 <br/>
ng version <br/>
Angular CLI: 14.0.0 <br/>

Check my work 👉👉👉👉 https://abhigit799.github.io/angular-shopping-site-part1/

<br/>
