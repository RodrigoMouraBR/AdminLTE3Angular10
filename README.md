# AdminLTEAngular

## Passo a Passo

Instalar angular cli:    npm install -g @angular/cli

criar um novo:           ng new adminlteangular

Instalar o AdminLte 3:   npm install admin-lte@^3.0 --save

verificar o package.json se ta tudo la

acessar o site do adminlte: https://adminlte.io/themes/v3/index.html

atualizar o angular.json com os css e javascripts da template

atualizar o app.component.html

copiar as imagens [ node_modules\admin-lte\dist\img ] para src/assets


## CSS e js para o arquivo angular.json

          styles: [
            "node_modules/admin-lte/plugins/fontawesome-free/css/all.min.css",
            "node_modules/admin-lte/plugins/overlayScrollbars/css/OverlayScrollbars.min.css",
            "node_modules/admin-lte/docs_html/assets/css/adminlte.css" 
            ]
           

        scripts: [
          "node_modules/admin-lte/plugins/jquery/jquery.js",
          "node_modules/admin-lte/plugins/bootstrap/js/bootstrap.bundle.js",
          "node_modules/admin-lte/plugins/overlayScrollbars/js/jquery.overlayScrollbars.js",
          "node_modules/admin-lte/dist/js/adminlte.js",
          "node_modules/admin-lte/dist/js/demo.js",
          "node_modules/admin-lte/plugins/jquery-mousewheel/jquery.mousewheel.js",
          "node_modules/admin-lte/plugins/raphael/raphael.js",
          "node_modules/admin-lte/plugins/jquery-mapael/jquery.mapael.js",
          "node_modules/admin-lte/plugins/jquery-mapael/maps/usa_states.js",
          "node_modules/admin-lte/plugins/chart.js/Chart.js",
          "node_modules/admin-lte/dist/js/pages/dashboard2.js"
        ]
