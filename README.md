# hcart8
Angular 8

hello git      

start new ng project, adding routing, using css
ng new ng-cart8

create nav named top-bar
cd ng-cart8
new g c top-bar
update app/top-bar/top-bar.component.html with html

add style
update app/styles.css with css
update app/index.hmtl with html link to icons
notice blue nav bar and cart icons

add products 
ng g c product-list
update app/app.module.ts, import RouterModule to point toplevel to productlist 
notice product list works
create app/products.ts
adding json data
update app/product-list.component.ts
udpate app/procut-list.component.html
notice product data
adding share button
update app/product-list.component.ts, share(){ ...
udpate app/procut-list.component.html, <button ...