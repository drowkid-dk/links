### [Linkfree: Links in Bio](https://github.com/harsh98trivedi/Links)

Bonito, simple y llamativo

![Linkfree](https://raw.githubusercontent.com/harsh98trivedi/links/master/assets/images/links.jpg)

### Screenshot
![20230729_090822](https://github.com/drowkid-1/Linksfree/assets/135056994/317a14be-9e2c-4f43-8579-a8cb111e8e3e)

[ver demo / vista previa](https://drowkid-1.github.io/Linksfree/)
### #Open-Source
Este proyecto es de código abierto, por lo que puedes crear una versión de Linkfree personalizada a tu gusto.(:
A continuación te enseño cómo hacerlo.

## Pasos para crear tu Linkfree personalizado.

Necesitas saber dos cosas antes de empezar:

1.- Linkfree no está escrito en el formato HTML común y regular, es decir, no es una plantilla como tal.

Su formato es Typescript (Next.js) para ser desplegado en [Vercel](https://vercel.com), [Netlify ](https://netlify.com), [CloudFlare](https://cloudflare.com) o similares.
2.- Sólo hay 2 maneras de editar y desplegar correctamente tu Linksfree: descargar el [repositorio](https://github.com/drowkid-1/Linksfree) y modificarlo en tu
<strong id="cli">CLI/Terminal</strong> o <strong id="forks">Clonar (forks)</strong> el repositorio y modificarlo en línea.
<a href="#
  cli">Usar CLI/Terminal</a><br>
<a href="forks">Clonar</a>

Para modificar Linksfree en tu <strong id="cli">CLI/Terminal/Termux</strong> sigue estos pasos:

<strong>1.-</strong> Descarga el repositorio en tu terminal/cli/termux y entra a su carpeta:
Necesitas tener instalado npm o yarn previamente:
<code>pkg install npm</code> o <code>pkg install yarn</code>
Comandos:
npm install o yarn install para instalar dependencias 
npm run dev o yarn dev para ver el previo de tu Linksfree


Después:
<code>git clone https://github.com/drowkid-1/Linksfree;cd Linksfree;</code>

o 
<strong>Importa el repositorio</strong>>
dirígete al menú de GitHub ubicado en la parte superior derecha de tu pantalla, y presiona en importar el repositorio.
Este es el link: <code>https://github.com/drowkid-1/Linksfree</code>

## Modificación de tu Linksfree

<strong>Ahora:</strong> Modifica el archivo '<em>_config.yml</em>'
<code>nano _config.yml</code> o <code>vim _config.yml</code>

<strong>Encontrarás el siguiente formato en el archivo:</strong>

<code>
  #Nombre del sitio o tu nombre
  name: DrowKid
  #Links:
  links:
   - name: Mi Página Web
   link: 'https://lalo.my.to'
</code>
Cada línea que comience con '#' puedes borrarla, no afecta ni beneficia a tu proyecto, simplemente es para que tengas una guía.
Las líneas "name: , link: -name:" <strong>No las borres pues son los datos que aparecerán en tu Linksfree</strong> 
Para cambiar los iconos (facebook, Instagram, github etc) entra en [Fontawesome](https://.fontawesome.com/)
y busca el emoji o icono de la opción que modificaste, es decir, si agregaste Pinterest, busca Pinterest, etc.. normalmente saldrá un "fa fa-facebook", solo copia ese fragmento "fa fa-facebook" y entra al archivo _config.yml y en la sección de links, al final de cada uno aparecera "Icon:"
borra el que viene por defecto y pega tu nuevo icono.

## ¡Listo!
Ahora puedes subir el proyecto a GitHub  para despues desplegarlo.
pero si solo importaste el repositorio, solo modificando el _config.yml y llendo a configuración/pages y modificar las opciones tal cual como en la imagen, podrás acceder a tu sitio.
