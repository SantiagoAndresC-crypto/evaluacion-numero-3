
<!DOCTYPE html>
<html>

<head>
    <title>index</title>
    <link rel="stylesheet" href="foundation/foundation.css" />
</head>
<style>
	#lol{
		margin-left: 120px;
	}
    body {
        background-image: url("images/imagendefondocomida.jpg");
        background-size: cover;
    }
   div{
   	background-color:rgba(192,192,192,0.3);
   }

   #fondosecundario{

   	background-color:rgba(255,0,0,0.3);
   }

    #imgb {
        margin-top: 20px;
    }
</style>

<body>
        <!--ESte seria el bloque de la izquierda-->
        <div class=" large-4 columns" style="text-align: left;">
            <h1 class="text-left" style="color: white">Comida internacional</h1>
            <h3 class="text-left" style="color: white">prepara lo que quieras sin importar en que pais te encuentres</h3>
            <!--Saque el buscar del grupo de botones para que ocupe todo el ancho de la columna-->
            <div class="row">
                <div class="input-group">
                    <input class="input-group-field" type="text">
                    <div class="input-group-button">
                        <button type="submit" class="button">
              <i class="step fi-magnifying-glass"></i><!--Estee icono no cargar por te falta añadir el css de iconos de foundation-->
            </button>
                    </div>
                </div>
            </div>
            <div class="row">
                <div class="button-group stacked">
                    <a class="button">desalluno, almuerzo y cena</a>
                    <a class="button">snacks</a>
                    <a class="button">postres</a>
                </div>
            </div>
            <div class="row">
                <div class="columns small-4"><img id="imgc" class="small-12" src="images/favorito1.jpg"></div>
                <div class="columns small-4"><img id="imgc" class="small-12" src="images/favorito2.jpg"></div>
                <div class="columns small-4"><img id="imgc" class="small-12" src="images/favorito3.jpg"></div>
            </div>
            <div class="row">
                <div class="columns small-4"><img id="imgc" class="small-12" src="images/favorita4.jpg"></div>
                <div class="columns small-4"><img id="imgc" class="small-12" src="images/favorito5.jpg"></div>
                <div class="columns small-4"><img id="imgb" class="small-12" src="images/favorito6.jpg"></div>
            </div>
            <ul class="vertical menu">
                <li><a href="#">Tamales</a></li>
                <li><a href="#">Pasticho</a></li>
                <li><a href="#">Limonada</a></li>
                <li><a href="#">Helado</a></li>
                <li><a href="#">Empanadas</a></li>
                <li><a href="#">Torta</a></li>
                <li><a href="#">Pastel</a></li>
                <li><a href="#">Ensalada</a></li>
                <li><a href="#">Hamburguesa</a></li>
                <li><a href="#">Enchilada</a></li>
                <li><a href="#">Mole</a></li>
                <li><a href="#">Salsas</a></li>
                <li><a href="#">Arepas</a></li>
                <li><a href="#">Pastas</a></li>
                <li><a href="#">Pollo</a></li>
                <li><a href="#">Carnes</a></li>
                <li><a href="#">Pescados</a></li>
                <li><a href="#">Mariscos</a></li>
                <li><a href="#">Panesillos</a></li>
            </ul>
        </div>
        <!--ESte seria el bloque de la derecha-->
        <div id="fondosecundario" class="small-8 b columns">
            <div style="margin-left: 40px" class="row">
                <h1 style="color: white"> Hielo de limonada </h1>
                <h2>publicado en 28/6/2019</h2>
                <p> <img id="lol" src="images/limonada.jpg" style="width: 60%"></img> </p>
                <p style="color: white"> Instrucciones
                	Lleva el agua al fuego y disuelve el azúcar. Apaga y deja refrescar.
Combina el sirope con el jugo de limón en una jarra junto al agua.
Vierte la limonada en moldes de hielo y distribuye las rebanadas de limón y hierbas en las cavidades de los moldes.
Lleva al congelador hasta formar cubos de hielo firmes, mejor de un día para otro.
Sirve el agua con gas con los cubos de hielo de limonada.</p>
<h4>Agregue un comentario</h4>
<textarea></textarea>
   <a class="button">publicar</a>
               <h1 style="color: white">Tamales panameños</h1>
               <h2>publicado en 28/6/2019</h2>
               <img id="lol" src="images/tamales.jpg" style="width: 60%">
               <p style="color: white">
Cocine el maíz pelado hasta que quede suave. Se escurre y se enfría. Se deja escurrir, se muele y se reserva.
A parte, sofría la gallina con los pimientos (ajies), la cebolla, el cilantro, el ajo, la pimienta y la sal.
Luego agréguele la pasta de tomate, la salsa de tomate y el caldo concentrado. Se deja cocinar 10 minutos y luego, se le añade agua hasta que cubra bien la gallina. Se tapa y, a fuego lento, se deja cocer hasta que esté suave.
Colóquele las pasitas, las aceitunas y alcaparras, y se deja cocinar por 20 minutos más.
Finalmente, añádale los guisantes (petits-pois). Si tiene muy poca agua se le puede verter un poco más. 
Cocer hasta que los guisantes están cocidos. Cuélalo todo y agrega el caldo a la masa de maíz. Amasa bien hasta que quede todo bien repartido y suave.
Lave bien las hojas de plátano, luego introdúzcalas en una olla con agua hirviendo y escúrralas enseguida. Corte los hilos de pabilo, lo suficientemente largos que le alcance para amarrar el tamal.
En cada hoja se vierte un cucharón de masa, encima se pone una presa de gallina con las verduritas y luego se vierte medio cucharón más de masa, se envuelve y ata. Se repite este procedimiento hasta emplear toda la masa.
En una olla grande de agua hirviendo se introducen los tamales y se cocinan una hora. Al sacarlos quedan listos para servir.</p>
<h4>Agregue un comentario</h4>
<textarea></textarea>
<a class="button">publicar</a>
            </div>

        </div>


    </div>
</body>
<!DOCTYPE html>
<html>
<head>
		<title>index</title>
		<link rel="stylesheet" href="frameworks/bootstrap-4.3.1-dist/css/bootstrap.css">
		<link rel="stylesheet" type="text/css" href="css/mi css.css">
		<meta name="viewport" content="width=device-width, initial-scale=1">
		<style>
			.social{
				width: 20%;
				padding-bottom: 20%
			}
		</style>
</head>
<body style="background-color: #F8EAA4">
	<header style="background-color: #A00909; ">
<div class="row container position-relative-md">
	<div class="col-md-3 col-xs-12 text-center">
		<img style="background-color: #A00909;; border-radius: 20px; " src="images/logomusica.jpg">
	</div>
	<div class="col-md-4 col-md-offset-7 text-center col-xs-12 redes-sociales align-self-end">
		<img style="background-color: #A00909; border-image-slice: fill;border-radius: 20px ;" src="images/facebook.jpg" class="social">
		<img style="background-color: #A00909; border-image-slice: fill;border-radius: 20px ;" src="images/instagram.jpg" class="social">
		 <div style="background-color: #A04009; padding-right: 30px; border-radius: 20px;" class="row">
  	 <ul style="text-align: right;" class="nav justify-content-center">
  <li class="nav-item">
    <a class="nav-link active" href="#">Inicio</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">System of a Down</a>
  </li>
  <li class="nav-item">
    <a class="nav-link" href="#">Slipknot</a>
  </li>
<a class="nav-link" href="#">Conciertost</a>
  </li>
<a class="nav-link" href="#">Merchandasing</a>
  </li>
</ul>
</div>
</div>
</div>
</header>
  <div style="background-color: " class="row">
		<div class="col">
			<p>La primera grabación de la banda se cree que fue un demo que contenía dos canciones: Flake y Toast. El primer demo no oficial es conocido como "The Untitled Demo Tape", que contenía los temas P.I.G. (demo de Mr. Jack), la primera versión de The Metro (cover del grupo Berlin), Flake y Toast. Otros temas que también se cree que fueron grabados en ese tiempo son Roulette, 36 y X, que después serían usados lanzamientos oficiales de System, además de Friik, Blue, Storaged y Marmalade.

En 1995 la banda lanzó su primer demo oficial, éste tenía muy baja calidad y solo era vendido en sus presentaciones. El demo contenía Dam, Sugar, Suite-Pee y P.L.U.C.K., estas 3 últimas fueron utilizadas en el primer álbum homónimo de la banda. La banda seguía dando conciertos y escribiendo nuevo material, y en 1996 salió a la luz su segundo demo. Este tenía mucha mejor calidad que el anterior, y contenía las canciones Honey, Temper y Soil. La última fue utilizada para el primer álbum en 1998, las otras dos nunca fueron regrabadas, pero existen diversas versiones en vivo. En 1997 la banda grabó su tercer demo, que contenía Peephole, Know y War. Existe otra versión promocional de este demo, que estuvo a la venta sólo unos días y muy poca gente compró. La diferencia es que éste demo contenía una canción más, que no había sido listada, al parecer durante la grabación del demo fue como una "improvisación". Esta canción se filtró en Internet apenas en 2009, cuando un fan la descubrió y decidió compartir la noticia. La canción es conocida como "The Missing Song"</p>
<img style="border: #219476 10px groove;" src="images/system.jpg">
		</div>

			<div class="col" >
				<div id="Buscador">
				<input style="width: 750px; background-color: blue; color:white"  type="Buscador" name="Buscador">
				<div style="text-align: center; background-color:#00159C; border: #A0A0A0 5px ridge;"><a href="">canciones destacadas</a></div>
				<div style="text-align: center; background-color:#00159C; border: #A0A0A0 5px ridge;"><a href="">listado de canciones</a></div>
				<div style="text-align: center; background-color:#00159C; border: #A0A0A0 5px ridge;"><a href="">miembros de Slipknot</a></div>
				<div style="text-align: center; background-color:#00159C; border: #A0A0A0 5px ridge;"><a href="">miembros de System of a Down</a></div>
				<div style="text-align: center; background-color:#00159C; border: #A0A0A0 5px ridge;"><a href="">manager de Slipknot</a></div>
				<div style="text-align: center; background-color:#00159C; border: #A0A0A0 5px ridge;"><a href="">manager de System of a Down</a></div>
				<div style="text-align: center; background-color:#00159C; border: #A0A0A0 5px ridge;"><a href="">giras anteriores</a></div>
				<div style="text-align: center; background-color:#00159C; border: #A0A0A0 5px ridge;"><a href="">fecha de proximas giras</a></div>
			   </div>
			   
			   <textarea style="width: 600px "></textarea>
		    </div>
			   
	 </div>

    <div class="row">
		<div class="col">
			<img style="width: 100%; border: #219476 10px groove;" src="images/slip.jpg">
		</div>
		<div class="col">
			<p>En agosto de 2009, Slipknot ganó dos premios Kerrang!, mejor banda en directo, y mejor banda internacional. Fue confirmado por Corey que la banda se tomaría otro breve descanso después de All Hope Is Gone World Tour, para que pueda volver a grabar con Stone Sour y también para trabajar en su álbum en solitario. El 17 de septiembre Clown reveló que estaba escribiendo un libro titulado The Apocalyptic Nightmare Journey, donde relata su relación con la banda, aunque no hay fecha oficial de puesta en venta. También ha expuesto en su propia galería de arte, donde están a la venta sus cuadros y fotografías
Slipknot ha confirmado una actuación en la primera celebración anual Trinity of Terrors, que tendrá lugar en el Palms Resort Casino el 31 de octubre (coincidiendo con Halloween).

El 24 de mayo de 2010, el bajista Paul Gray fue encontrado muerto, a causa de una sobredosis accidental de morfina, alrededor de las 10:50 a. m. en una habitación de un hotel de Des moines en el estado de Iowa, Estados Unidos.

Durante una entrevista antes del debut de la banda en Sonisphere en los Países Bajos, el percusionista Chris Fehn declaró que el grupo estaba haciendo un nuevo álbum que será lanzado en 2010, aproximadamente. La banda también ha confirmado una nueva edición conmemorando el décimo aniversario de su homónimo álbum debut, que incluirá todas las pistas de la versión original, así como varias demos, remixes y la canción Purity. También saldrá a la venta un nuevo DVD, titulado Of the (Sic): Your Nightmares, Our Dreams, que contendrá material de 1999-2000.</p>
<textarea style="width: 600px "></textarea>
		</div>
  	    
     </div>
  	 </div>
			</ul>
 	 </div>
 	</div>
 	</div>
</div>
</body>
<!DOCTYPE html>
<html>
 <head>
  <link href="https://fonts.googleapis.com/icon?family=Material+Icons" rel="stylesheet">
  <link type="text/css" rel="stylesheet" href="css/materialize.min.css"  media="screen,projection"/>
  <link rel="stylesheet" type="text/css" href="lol/lol.css">
      <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
    </head>
<style> body{
	background-image: url("images/fondo de llanura.jpg");
        background-size: cover;
	}
	header{
		background-color: rgba(173, 255, 47, 0.5);
	}
     #principal{
     	background-color: rgba(0, 255, 0, 0.5);
     }
     .row-card{
     	background-color: rgba(50, 205, 50, 0.5)
     }
</style>
    <body>
    	<header>
            <img id="logo" src="images/logoviaje.jpg"></img>
              <a href="#" id="btn" class="btn waves-effect orange boton-menu"><i class="material-icons left">store</i><span class="hide-on-small-only">Inicio</span></a>
              <a href="#" id="btn" class="btn waves-effect orange botton menu"><i class="material-icons left">room</i><span class="hide-on-small-only">donde estuve</span></a>
              <a href="#" id="btn" class="btn waves-effect orange botton menu"><i class="material-icons left">grade</i><span class="hide-on-small-only">viajes</span></a>
              <a href="#" id="btn" class="btn waves-effect orange botton menu"><i class="material-icons left">chat_bubble_outline</i><span class="hide-on-small-only">recomendaciones</span></a>
         </header>
         <div class="container">
         	<div class="row">
         		<div class="col 12">
         			<h2 class="center-align slogan">El mejor viaje es el que disfrutas con familia y amigos</h2>
         		</div>
         	</div>
         	<div id="principal" class='col m2'>
<div class="col m12"><img id="icono" src='images/images.jpg'></img></div>
<div id="icono" class="col m12"><img  id="icono"src='images/instagram.jpg'></img></div>
<div id="icono" class="col m12"><img id="icono" src='images/facebook.jpg'></img></div>
</div>
<div class="row">
    <div class="col l4 m4 s12" >
      <div class="content ">
        <img style="width: 100%" id="quebradas" class="resposive-img  z-depth-3" src="images/quebrada de jaspe.jpg">
      </div>
      <div class="content">
        <img style="width: 100%" id="piramide" class="resposive-img  z-depth-3" src="images/piramide de mexico.jpg">
      </div>
    </div>
    <div class="col l4 m4 s12">
      <div class="content ">
        <img style="width: 100%" id="volcan" class="resposive-img img1  z-depth-3" src="images/volcan baru.jpg" >
      </div>
    </div>
    <div class="col l3 m3 s12">
      <div class="content ">
        <img style="width: 100%" id="boquete" class="resposive-img  z-depth-3" src="images/boquete.jpg">
      </div>
      <div class="content ">
        <img style="width: 100%" id="costa" class="resposive-img  z-depth-3" src="images/costa caribe.jpg">
      </div>
    </div>
  </div>
         </div>
<div class="row card">
<div class="col s12">
<div class="row">
<h4>La gran sabana</h4> 
<p>Fecha de publicación: 10/5/2017 -- Número de comentarios: 3</p>
</div>
<div class="row">
<div class="col s4">
<img class="materialboxed responsive-img" width="100%" src="images/La gran sabana.jpg">
</div>
<div class="col s8">
<p>  La Gran Sabana ofrece al visitante paisajes únicos en todo el mundo, cuenta con ríos, cascadas y quebradas, valles profundos y extensos, selvas impenetrables, y sabanas que alojan una gran cantidad y variedad de especies vegetales, una fauna diversa, y las mesetas de arenisca mejor conocidas como tepuyes

  </p>
  <div class="input-field col s6">
          <input  id="first_name" type="text" class="validate">
          <label for="first_name">First Name</label>
        </div>
        <div class="input-field col s6">
          <input id="last_name" type="text" class="validate">
          <label for="last_name">Last Name</label>
        </div>
      </div>
      <div class="row">
        <div class="input-field col s12">
          <textarea row="4" id="disabled" type="text"  class="materialize-textarea validate" > </textarea>
          <label for="disabled">Comentario</label>
        </div>
      </div>  
      <button class="btn waves-effect waves-light" type="submit" name="action">Submit
    <i class="material-icons right">send</i>
  </button>
</div>
</div>
</div> 
</div>
<div class="row card">
<div class="col s12">
<div class="row">
<h4>La cascada de jaspe</h4> 
<p>Fecha de publicación: 16/7/2017 -- Número de comentarios: 1</p>
</div>
<div class="row">
<div class="col s4">
<img class="materialboxed responsive-img" width="100%" src="images/quebrada de jaspe.jpg">
</div>
<div class="col s8">
<p> Quebrada de Jaspe​ es el nombre que recibe un río y una serie de Cascadas o caídas de agua en el país suramericano de Venezuela.​ Se localizan específicamente en el sector oriental del Parque nacional Canaima, en el Municipio Gran Sabana

  </p>
  <div class="input-field col s6">
          <input  id="first_name" type="text" class="validate">
          <label for="first_name">First Name</label>
        </div>
        <div class="input-field col s6">
          <input id="last_name" type="text" class="validate">
          <label for="last_name">Last Name</label>
        </div>
      </div>
      <div class="row">
        <div class="input-field col s12">
          <textarea row="4" id="disabled" type="text"  class="materialize-textarea validate" > </textarea>
          <label for="disabled">Comentario</label>
        </div>
      </div>  
      <button class="btn waves-effect waves-light" type="submit" name="action">Submit
    <i class="material-icons right">send</i>
  </button>
</div>
</div>
</div> 
</div>
      <script type="text/javascript" src="js/materialize.min.js"></script>
    </body>
