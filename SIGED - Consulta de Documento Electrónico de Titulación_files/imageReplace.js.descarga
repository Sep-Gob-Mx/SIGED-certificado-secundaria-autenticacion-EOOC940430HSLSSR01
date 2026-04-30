window.onload = function () {
    var imagenes = [];
    imagenes = document.getElementsByTagName('img');
    for (i = 0; i < imagenes.length; i++) {
        reemplazar(imagenes[i]);
    }
}

function reemplazar(ima) {
    var reemplazo = 'http://framework-gb.cdn.gob.mx/logo.png';
    var ImagenPrueva = new Image();
    ImagenPrueva.src = ima.src;
    ImagenPrueva.onerror = function () {
       ima.src = reemplazo;
        ima.title = "No diponible";
    }
}
;
