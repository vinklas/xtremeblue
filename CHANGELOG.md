<!-- START CONTENT -->
<div id="content">
<h1>Change Log</h1>
<h2><span style="color: #ff0000;">Version 0.1.9</span></h2>
<h3>Fecha del cambio: 06/01/2021</h3>
<ul>
<li>Modificado el .topmenu ul li .top-menu &gt; li &gt; a.dropdown-submenu (6755), Letra de los titulos del Menu estan en Mayuscula
<ul>
<li style="list-style-type: none;">
<ul>
		<li>color: #888 !important;</li>
</ul>
</li>
	<li>Hacia
<ul>
		<li>color: #000 !important;</li>
</ul>
</li>
</ul>
</li>
<li>Modificado el .top-menu { (15312), Ahora el menu se muestra hacia abajo totalmente
<ul>
<li style="list-style-type: none;">
<ul>
		<li>display: inline-block</li>
</ul>
</li>
	<li>Hacia
<ul>
		<li>display: inline-table</li>
</ul>
</li>
</ul>
</li>
<li>Modificado li.product-flag (10163)
<ul>
<li style="list-style-type: none;">
<ul>
		<li>li.product-flag {<br />display: block;<br />position: absolute;<br />z-index: 1;<br />left: 15px;</li>
</ul>
</li>
	<li>Hacia
<ul>
		<li>li.product-flag {<br />display: block;<br />position: absolute;<br />z-index: 1;<br />left: 1px;</li>
</ul>
</li>
</ul>
</li>
<li>Modificado li.product-flag.new (10184)
<ul>
<li style="list-style-type: none;">
<ul>
		<li>color: #000000;<br />left: 15px;<br />margin: 0;<br />text-align: center;<br />top: 10px !important;</li>
</ul>
</li>
<li style="list-style-type: none;">&nbsp;</li>
	<li>Hacia
<ul>
		<li>color: #000000;<br />left: 1px;<br />margin: 0;<br />text-align: center;<br />top: 10px !important;</li>
</ul>
</li>
</ul>
</li>
<li>Editado la opacidad de los logos del carrusel de logos .brands #ttbrandlogo-carousel li .brand-image img&nbsp; (15104)
<ul>
<li style="list-style-type: none;">
<ul>
		<li>-webkit-opacity: 0.6;</li>
</ul>
</li>
	<li>Hacia
<ul>
		<li>-webkit-opacity: 0.9;</li>
</ul>
</li>
</ul>
</li>
<li>Tama&ntilde;o de las imagenes de los productos trabajada a 1900x2880</li>
<li>Eliminada las fotos de las Subcategorias editando el archivo category-header (catalog/_partials/category-header.tpl) lineas 46 a 54
<ul>
	<li>&lt;div class="subcategory-image"&gt;<br />&lt;a href="{$link-&gt;getCategoryLink($subcategory.id_category, $subcategory.link_rewrite)|escape:'html':'UTF-8'}" title="{$subcategory.name|escape:'html':'UTF-8'}" class="img"&gt;<br />{if $subcategory.id_image}<br />&lt;img class="replace-2x" src="{$link-&gt;getCatImageLink($subcategory.link_rewrite, $subcategory.id_image, 'small_default')|escape:'html':'UTF-8'}" alt="{$subcategory.name|escape:'html':'UTF-8'}"/&gt;<br />{else}<br />&lt;img class="replace-2x" src="{$img_cat_dir}{$lang_iso}-default-small_default.jpg" alt="{$subcategory.name|escape:'html':'UTF-8'}"/&gt;<br />{/if}<br />&lt;/a&gt;<br />&lt;/div&gt;</li>
</ul>
</li>
<li>Modificado el tama&ntilde;o y separacion del menu de categorias block-categories .category-sub-menu li a { (9501)
<ul>
<li style="list-style-type: none;">
<ul>
		<li>color: #888 !important;<br />font-size: 14px !important;<br />line-height: 28px !important;</li>
</ul>
</li>
	<li>Hacia
<ul>
		<li>color: #000 !important;<br />font-size: 15px !important;<br />line-height: 29px !important;</li>
</ul>
</li>
</ul>
</li>
<li>El menu de subcategoria de la parte derecha ahora solo muestra las categorias de la seccion que te encuentres presente&nbsp;</li>
<li>Eliminado el texto de subcategoria</li>
<li>La seccion de Hacienda Araucano ha sido reconstruida (No es oficial)</li>
<ul>
	<li>http://shop.xtreme-blue.com/16-hacienda-araucano</li>
</ul>
<li>Nombre de la tienda cambiado de Xtreme-Blue a XtremeBlue</li>
</ul>
<h3>Problemas conocidos</h3>
<ul>
<li>Hacer centrado los logos</li>
<li>Registrar la empresa en Culqi</li>
<li>Descripcion a cada tipo de vino para el catalogo de la web</li>
<li>Descripcion de los vinos del catalogo</li>
<li>Imagen de la parte inferior cambiarla</li>
<ul>
</ul>
</ul>
</div>
<h2><span style="color: #ff0000;">Version 0.1.8</span></h2>
<h3>Fecha del cambio: 04/01/2021</h3>
<ul>
<li>Modificado el .top-menu .sub-menu (6711), arreglando el distanciamiento del menu&nbsp;
<ul>
<li style="list-style-type: none;">
<ul>
	<li>.top: 95px !important</li>
</ul>
</li>
<li>Hacia&nbsp;
<ul>
	<li>&nbsp;top: 88px !important</li>
</ul>
</li>
</ul>
<h3>Problemas conocidos</h3>
<ul>
<li>Hacer centrado los logos</li>
<li>Registrar la empresa en Culqi</li>
<li>Descripcion a cada tipo de vino para el catalogo de la web</li>
<li>Descripcion de los vinos del catalogo</li>
	
<ul>
<li style="list-style-type: none;">&nbsp;</li>
</ul>
</li>
</ul>
<h2><span style="color: #ff0000;">Version 0.1.7</span></h2>
<h3>Fecha del cambio: 28/12/2020</h3>
<ul>
<li>Modificado el de Product-Cover (14492) Muestra del producto puesta&nbsp;
<ul>
<li style="list-style-type: none;">
<ul>
<li>.product-cover {<br />margin-bottom: 1.25rem;<br />position: relative;<br />float: left;<br />width: 100%;<br />text-align:center;</li>
</ul>
</li>
<li>Hacia&nbsp;
<ul>
<li>.product-cover {<br />position: relative;<br />float: right;<br />width: 75%;<br />text-align:center;</li>
</ul>
</li>
</ul>
</li>
<li>Modificado el tama&ntilde;o de la letra de producto hacia letra 40 (9704)
<ul>
<li>.product-price {<br />color: #333333;<br />font-size: 40px;<br />font-weight: normal;<br />display: inline-block;</li>
</ul>
</li>
<li>modificado el ttproduct-tittle (12551) letra 26 y en negrita (bold)
<ul>
<li>.tt-producttitle {<br />border-bottom: 1px solid #e5e5e5;<br />color: #222222;<br />font-family: Poppins;<br />font-size: 26px;<br />font-weight: bold;<br />line-height: 26px;<br />margin: 0 auto 10px;<br />padding: 0 0 10px;<br />position: relative;<br />text-align: left;<br />text-transform: capitalize;</li>
</ul>
</li>
<li>Modificada la Linea (8454) para poner letra de los precios en negro
<ul>
<li>color: #000000;</li>
</ul>
</li>
<li>&nbsp;</li>
</ul>
<h3>Problemas conocidos</h3>
<ul>
<li>Hacer centrado los logos</li>
<li>Registrar la empresa en Culqi</li>
<li>Descripcion a cada tipo de vino para el catalogo de la web</li>
<li>Descripcion de los vinos del catalogo</li>
</ul>
<h1>Change Log</h1>
<p>&nbsp;</p>
<h2><span style="color: #ff0000;">Version 0.1.6</span></h2>
<h3>Fecha del cambio: 21/12/2020</h3>
<ul>
<li>Alineado los logos de las marcas en la parte inferior de la pagina web</li>
<li>Arreglado el BannerCMS con una sola linea grafica de imagenes</li>
<li>Arreglado el logo de cabezera de la pagina por uno mas nitido</li>
<li>A&ntilde;adido mas productos</li>
<li>#6755 Titulo las bodegas y vinos del Menu ahora estan en Negrita(Bold)</li>
<li>#6790 Tama&ntilde;o de las letras del menu aumentadas a Letra 15</li>
<li>A&ntilde;adido modulo ElevateZoom para poder hacerle zoom a los productos</li>
<li>Instalado el Modulo de MailChimps</li>
<li>Isntalado modulo de WhatsApp (aun en prueba)</li>
</ul>
<h3>Problemas conocidos</h3>
<ul>
<li>Hacer centrado los logos</li>
<li>Registrar la empresa en Culqi</li>
<li>Descripcion a cada tipo de vino para el catalogo de la web</li>
<li>Descripcion de los vinos del catalogo</li>
</ul>
<p>&nbsp;</p>
<h2><span style="color: #ff0000;">Version 0.1.5</span></h2>
<h3>Fecha del cambio: 19/12/2020</h3>
<ul>
<li>A&ntilde;adida las cepas y la distribuccion de los tipo de vino conforme al catalogo 2020</li>
<li>#12230 Menu principal tama&ntilde;o de la letra fue aumentada a 20.</li>
<li>En el banner publicitario se ha modificado el orden de los vinos</li>
<li>Se elimino la palabra "productos en tendencia"</li>
<li>Se elimino el titulo de las marcas en la parte inferior</li>
<li>Cambiado el modulo de CMS AboutUs entre el Carrusel y el CMSBanner para mejor estetica de la pagina</li>
</ul>
<h3>Problemas conocidos</h3>
<ul>
<li>Alinear los logos de las marcas en la parte superior y tratar de hacerlos centrados</li>
<li>Verificar accion de Lupa en el catalogo</li>
<li>BannerCMS arreglar imagen de la bodega piedra negra Chacayes</li>
<li>Logo de XtremeBlue en la parte superior de la pagina se ve en baja calidad</li>
<li>Registrar la empresa en Culqi</li>
<li>Descripcion a cada tipo de vino para el catalogo de la web</li>
<li>Descripcion de los vinos del catalogo</li>
</ul>
<p>&nbsp;</p>
<h2><span style="color: #ff0000;">Version 0.1.4</span></h2>
<h3>Fecha del cambio: 18/12/2020</h3>
<ul>
<li>Solucionado el modulo de comparar productos (Gracias equipo de soporte de WineClub)</li>
<li>Menu principal tama&ntilde;o de la letra fue aumentada a 20.</li>
<li>En el banner publicitario .</li>
<li>Letras en Bold para los precios y color Azul XtremeBlue #000cc4</li>
<li>Eliminado el Newletter y el CMS Testimonials</li>
</ul>
<h3>Problemas conocidos</h3>
<ul>
<li>Descripcion a cada tipo de vino para el catalogo de la web</li>
<li>Descripcion de los vinos del catalogo</li>
<li>Registrar la empresa en Culqi</li>
</ul>
<h2>&nbsp;</h2>
<h2><span style="color: #ff0000;">Version 0.1.3</span></h2>
<h3>Fecha del cambio: 17/12/2020</h3>
<ul>
<li>Agregada plataforma de pago Culqi(Falta registrar la empresa)</li>
<li>Agregada peque&ntilde;a descripcion a las subcategorias de bodegas.</li>
<li>Eliminado el Copyright de Prestashop en la parte inferior.</li>
<li>A&ntilde;adida las a&ntilde;adas faltantes.</li>
</ul>
<h3>Problemas conocidos</h3>
<ul>
<li>Registrar la empresa en Culqi</li>
</ul>
<h2>&nbsp;</h2>
<h2><span style="color: #ff0000;">Version 0.1.2</span></h2>
<h3>Fecha del cambio: 16/12/2010</h3>
<ul>
<li>Traduccion al espa&ntilde;ol a lugares aun no traducidos</li>
<li>Eliminado el tiempo de despacho (chequear despues)</li>
<li>Arreglado los precios y nombres (Gracias equipo de soporte de WineClub)</li>
</ul>
<h2>&nbsp;</h2>
<h2><span style="color: #ff0000;">Version 0.1.1</span></h2>
<h3>Fecha del cambio: 15/12/2020</h3>
<ul>
<li>Arreglado el icono superior de la barra de navegacion.</li>
<li>Eliminada barra de publicidad en el catalogo</li>
<li>Eliminado icono de contacto y textos en la parte superior de la pagina.</li>
<li>Agregada los logos de las bodegas
<ul>
<li>Hacienda Araucano</li>
<li>Huarpe Wines</li>
<li>Piedra Negra</li>
<li>San Pedro de Yacochuya</li>
</ul>
</li>
</ul>
<h2>&nbsp;</h2>
<h2><span style="color: #ff0000;">Version 0.1.0</span></h2>
<h3>Fecha del cambio: 14/12/2010</h3>
<ul>
<li>Barra del menu cambiada a otro color "Plomo" HEX:&nbsp;#262629</li>
<li>Eliminado el tiempo de despacho (chequear despues)</li>
<li>Arreglado los precios y nombres (Gracias equipo de soporte de WineClub)</li>
</ul>
<h2>&nbsp;</h2>
<h2><span style="color: #ff0000;">Version 0.0.9</span></h2>
<h3>Fecha del cambio: 13/12/2010</h3>
<ul>
<li>Carrucel de imagenes arreglado el tama&ntilde;o de imagenes a 1900x800</li>
<li>CMS Banner imagenes estandarizadas a 400x600 y 600x800</li>
</ul>
<h2>&nbsp;</h2>
<h2><span style="color: #ff0000;">Version 0.0.1 -&gt; 0.0.8</span></h2>
<ul>
<li>Instalacion de la pagina web</li>
<li>Configuracion e Instalacion del Tema "WineClub"</li>
<li>Configuracion de las categorias del menu
<ul>
<li>Bodegas
<ul>
<li>Hacienda Araucano</li>
<li>Huarpe Wines</li>
<li>Piedra Negra</li>
<li>San Pedro de Yacochuya</li>
</ul>
</li>
<li>Vinos
<ul>
<li>Tintos
<ul>
<li>Blend&nbsp;</li>
<li>Varietal</li>
</ul>
</li>
<li>Blancos
<ul>
<li>Blend</li>
<li>Varietal</li>
</ul>
</li>
<li>Rosados
<ul>
<li>Blend</li>
<li>Varietal</li>
</ul>
</li>
</ul>
</li>
</ul>
</li>
<li>Subido logo de XtremeBlue</li>
<li>Subido los productos en un 70%</li>
<li>A&ntilde;adidas caracteristicas y atributos para los vinos
<ul>
<li>A&ntilde;o</li>
<li>Tipo</li>
<li>Cepa</li>
<li>Bodega</li>
</ul>
</li>
<li>Traduccion de la pagina a un 85% terminado</li>
<li>Configuracion de modulos&nbsp;</li>
</ul>
<h2>&nbsp;</h2>
</div>
<!-- END CONTENT -->
<div id="footer">
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p><a href="#top">Top of Page</a></p>
</div>
