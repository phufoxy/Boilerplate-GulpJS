# VanPhu-GG
## Hướng dẫn sử dụng Bộ Boilerplate (GULPJS)
GulpJS hổ trợ việc viết html css và js. Viết dev có thể viết cách thuận lợi nhất.
### lệnh cài đặt
    npm install 
### lệnh chạy
    npm run dev
### server live
    http://localhost:1234/
### lệnh build prod
    npm run prod
### lệnh build dist
    npm run build
### khi build
    ta sẽ được file dist 
### Link Project https://github.com/vanphudhsp2015/Boilerplate-GulpJS

### Hướng dẫn Dẫn Import Thư viện từ node module
    import link style  css node_modules/bootstrap/dist/css/bootstrap.css (1)
        <!-- build:css(.) style/vendor.min.css -->
            (1)
        <!-- endbuild -->
    import Link JS  node_modules/materialize-css/js/waves.js (2)
        <!-- build:js(.) script/vendor.min.js -->
            (2)
        <!-- endbuild -->
    #### lưu ý nhớ để đúng trong ...để build ra đúng

### Hướng dẫn sử dụng wow JS
    lệnh cài đặt "npm install wow.js"
    import JS node_modules/wow.js/dist/wow.js
    add class "wow name(3)" (3) tên class của animation (theo link: "https://daneden.github.io/animate.css/")



