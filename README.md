# Proyecto Informatico 2

## Integrantes del grupo :

### Zaira Machuca
### Xiomara Ureña 

#CODIGO

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">


    <title>Tienda Discos</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-sRIl4kxILFvY47J16cr9ZwB07vP4J8+LH7qKQnuqkuIAvNWLzeN8tE5YBujZqJLB" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.8/dist/js/bootstrap.bundle.min.js" integrity="sha384-FKyoEForCGlyvwx9Hj09JcYn3nv7wiPVlz7YYwJrWVcXK/BmnVDxM+D2scQbITxI" crossorigin="anonymous"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.13.1/font/bootstrap-icons.min.css">
</head>




<body>




  <nav id="navbar-example2" class="navbar bg-body-tertiary px-3 mb-3">
    <a class="navbar-brand" href="#">Menú</a>
   <ul class="nav nav-pills">
    <li class="nav-item">
      <a class="nav-link" href="#scrollspyHeading1">DISCOS</a
    </li>


    <li class="nav-item">
      <a class="nav-link" href="#scrollspyHeading2">STICKERS</a>
    </li>


    <li class="nav-item">
      <a class="nav-link" href="#scrollspyHeading3">LIBROS</a>
    </li>


    <li class="nav-item">
      <a class="nav-link" href="#scrollspyHeading4">CARRITO</a>
    </li>


   </ul>
  </nav>




<div data-bs-spy="scroll" data-bs-target="#navbar-example2" data-bs-root-margin="0px 0px -40%" data-bs-smooth-scroll="true" class="scrollspy-example bg-body-tertiary p-3 rounded-2" tabindex="0">
    <div id="main-content">
    <div class="container my-4">
        <h4 id="scrollspyHeading1">DISCOS</h4>
        <div data-bs-spy="scroll" data-bs-target="#navbar-example3" data-bs-smooth-scroll="true" class="scrollspy-example-2" tabindex="0">
        <div id="item-1">
            <div class="row row-cols-3 row-cols-md-3 g-3">




    <div class="col">
        <div class="card">
        <a href="https://www.youtube.com/watch?v=OcBk8Lv0XK8&list=OLAK5uy_lKiBr_oI8tFQKz77c-Li2FVPSAtwAZMGw">
            <img src="Discos/Las leyendas nunca mueren.jpg" class="card-img-top" alt="...">
        </a>




        <div>
            <input type="checkbox"id="En vinilo">
            <label for="En vinilo">En vinilo(10k extra)</label>
        </div>




        <div>
            <button onclick="Agregardisco('Las leyendas nunca mueren - Anuel aa', 40000)">Agregar Disco</button>
        </div>
        <div id="carrito"></div>




        <div class="card-body">
            <h5 class="card-title">Las leyendas nunca mueren</h5>
        </div>
        </div>
    </div>






    <div class="col">
        <div class="card">
        <a href="https://www.youtube.com/watch?v=ukUxtvJdTWs&list=PLEpjZ6a3i26d_ZvTTNxItCgpNhMi-dZfq">
            <img src="Discos/La vida es una.jpg" class="card-img-top" alt="...">
        </a>




        <div>
            <input type="checkbox"id="En vinilo">
            <label for="En vinilo">En vinilo(10k extra)</label>
        </div>




        <div>
            <button onclick="Agregardisco('La vida es una - Myke Towers', 30000)">Agregar Disco</button>
        </div>
        <div id="carrito"></div>




        <div class="card-body">
            <h5 class="card-title">La vida es una</h5>
        </div>
        </div>
    </div>












    <div class="col">
        <div class="card">
        <a href="https://www.youtube.com/watch?v=NBghhjuMNKM&list=OLAK5uy_l3rT1z1t11Pn6CugxRd3ZxQQOpWGqzUMU">
            <img src="Discos/Un verano sin ti.jpg" class="card-img-top" alt="...">
        </a>




        <div>
            <input type="checkbox"id="En vinilo">
            <label for="En vinilo">En vinilo(10k extra)</label>
        </div>




        <div>
            <button onclick="Agregardisco('Un verano sin ti - Bad Bunny', 50000)">Agregar Disco</button>
        </div>
        <div id="carrito"></div>




        <div class="card-body">
            <h5 class="card-title">Un verano sin  ti</h5>
        </div>
        </div>
    </div>








    <div class="col">
        <div class="card">
        <a href="https://www.youtube.com/watch?v=-O3mZShde5c&list=PL_wnau4Q10S-JLCRteBCswZI3SDIfQMGh">
            <img src="Discos/Trinidad bendida.jpg" class="card-img-top" alt="...">
        </a>


        <div>
            <input type="checkbox"id="En vinilo">
            <label for="En vinilo">En vinilo(10k extra)</label>
        </div>




        <div>
            <button onclick="Agregardisco()">Agregar Disco</button>
        </div>
        <div id="carrito"></div>




        <div class="card-body">
            <h5 class="card-title">Trinidad Bendita - Blessd</h5>
        </div>
    </div>
  </div>






    <div class="col">
        <div class="card">
        <a href="https://www.youtube.com/watch?v=DlXTTudB-lI&list=PLEpjZ6a3i26egS3ie6iOmySyzrhJ_52Oy">
            <img src="Discos/Sixdo.jpg" class="card-img-top" alt="...">
        </a>
        <div>
            <input type="checkbox"id="En vinilo">
            <label for="En vinilo">En vinilo(10k extra)</label>
        </div>




        <div>
            <button onclick="Agregardisco()">Agregar Disco</button>
        </div>
        <div id="carrito"></div>
        <div class="card-body">
            <h5 class="card-title">Sixdo - Feid</h5>


        </div>
        </div>
    </div>












    <div class="col">
        <div class="card">
        <a href="https://www.youtube.com/watch?v=5JCIhdfEghs&list=OLAK5uy_ld6ZIg3gZWczRy-kFFYHjW6nGrt9wkB30&pp=0gcJCe4COCosWNin">
            <img src="Discos/Viva el perreo.jpg" class="card-img-top" alt="...">
        </a>




        <div>
            <input type="checkbox"id="En vinilo">
            <label for="En vinilo">En vinilo(10k extra)</label>
        </div>




        <div>
            <button onclick="agregarDisco()">Agregar Disco</button>
        </div>
        <div id="carrito"></div>




        <div class="card-body">
            <h5 class="card-title">Viva el perreo - Jowell y Randy</h5>
        </div>
        </div>
    </div>
    </div>
        </div>








        <div id="item-1-1">
              <h4 id="scrollspyHeading2">STICKERS</h4>
            <button type="button" style="border: 1; background-color: transparent;" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-title="Tos">
                <img src="Stickers/que me crezca el pelo.jpg" height="200" width="200" alt="Tos" title="anuel pelado">
            </button>


            <button type="button" style="border: 1; background-color: transparent;" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-title="Tooltip on right">
                <img src="Stickers/corazon bad bunny.jpg" height="200" width="200" alt="Tos" title="Corazon de bad bunny">
            </button>


            <button type="button" style="border: 1; background-color: transparent;" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-title="Tooltip on right">
                <img src="Stickers/anti g.jpg" height="200" width="200" alt="Tos" title="Señalizacion ">
            </button>


            <button type="button" style="border: 1; background-color: transparent;" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-title="Tooltip on right">
                <img src="Stickers/tristeza.webp" height="200" width="200" alt="Tos" title="Tristeza">
            </button>


            <button type="button" style="border: 1; background-color: transparent;" class="btn btn-secondary" data-bs-toggle="tooltip" data-bs-placement="right" data-bs-title="Tooltip on right">
                <img src="Stickers/Payaso triste.jpg" height="200" width="200" alt="Tos" title="Payaso triste">
            </button>






        </div>
        <div id="item-1-2">
           
        </div>  
    </div>
</div>
<div id="main-content">
    <div class="container my-4">
        <h4 id="scrollspyHeading3">LIBROS</h4>
        <div id="item-1"></div>
            <div class="row row-cols-2 row-cols-md-3 g-3">
    <div class="col">
        <div class="libro">
        <a>
            <img src="Libros/El pequeño elfo cierraojos.jpg" class="card-img-top" alt="...">
        </a>








        <div>
            <input type="checkbox"id="Tapa dura">
            <label for="Tapa dura">Tapa dura</label>
            <input type="checkbox"id="Tapa blanda">
            <label for="Tapa blanda">Tapa blanda</label>
        </div>








        <div>
            <button onclick="Agregar('El pequeño elfo Cierraojos', 15000)">Agregar Libro</button>
        </div>
        <div id="carrito"></div>








        <div class="card-body">
            <h5 class="card-title">El pequeño elfo Cierraojos</h5>
        </div>
        </div>


        <div class="card">
        <a>
            <img src="Libros/El reglamento es el reglamento.jpg" class="card-img-top" alt="...">
        </a>


        <div>
            <input type="checkbox"id="Tapa dura">
            <label for="Tapa dura">Tapa dura</label>
            <input type="checkbox"id="Tapa blanda">
            <label for="Tapa blanda">Tapa blanda</label>
        </div>








        <div>
            <button onclick="Agregar('El reglamento es el reglamento', 15000)">Agregar Libro</button>
        </div>
        <div id="carrito"></div>


        <div class="card-body">
            <h5 class="card-title">El reglamento es el reglamento</h5>
        </div>
        </div>




        <div class="card">
        <a>
            <img src="Libros/el pulpo está crudo.jpg" class="card-img-top" alt="...">
        </a>








        <div>
            <input type="checkbox"id="Tapa dura">
            <label for="Tapa dura">Tapa dura</label>
            <input type="checkbox"id="Tapa blanda">
            <label for="Tapa blanda">Tapa blanda</label>
        </div>








        <div>
            <button onclick="Agregar('El pulpo está crudo', 15000)">Agregar Libro</button>
        </div>
        <div id="carrito"></div>








        <div class="card-body">
            <h5 class="card-title">El pulpo está crudo</h5>
        </div>
        </div>
















       
    </div>
   
   <script>
    let carrito=[];
















    function agregarDisco(nombre, precioBase){
















        let precio=precioBase;
















        if(document.getElmentbyId("En vinilo").checked){
            precio+=10000;
        }
















        carrito.push({
            nombre:nombre,
            precio:precio
        })
















        document.getElementById("carrito").innerHTML="Discos en el carrito: "+carrito.length;
    }



   </script>
</body>
</html>
