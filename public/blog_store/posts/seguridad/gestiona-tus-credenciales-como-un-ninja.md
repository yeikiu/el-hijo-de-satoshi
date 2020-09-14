# Gestiona tus credenciales como un ninja 🔐
#### September 4, 2020

Seguro que has pensado alguna vez que el sitema de acceso de cualquier web/app/sistema estaba simplemente diseñado contra ti. Admitámoslo, las contraseñas son un problema desde que existen. De hecho ¿Hay algo más odioso que tener que crear una nueva? Conozco muchos gilipollas y aún así me cuesta imaginarme a ninguno de ellos reposando su primer café de la mañana mientras frota sus manos 5 cm. sobre el teclado y exclama _"Bien y ahora... ¡A generar un par de contraseñas épicas!"_

Pero hoy voy a tratar de convencerte de algo tan cierto que si lo firmara un griego de nombre cool tipo _Trifásides_ de hace alguno siglos por ejemplo todos aplaudirían con las orejas. ¿Estás sentado?

> "Utilizar un sistema seguro de gestión de credenciales es más fácil, más rápido y más cómodo que no hacerlo" 😎

<iframe src="https://giphy.com/embed/8cjj74dzci0EnjxqOJ" width="480" height="480" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/SpotifyJapan-spotify-stray-kids-straykids-8cjj74dzci0EnjxqOJ">via GIPHY</a></p>

Eso lo firmo yo. Y esto es mi intento por convencerte.

### Lo que has hecho siempre vs Usar un software de gestión de credenciales

| Acción | ~Tiempo hasta ahora (s) | ~Tiempo con software (s) |
| ------ | ----------- | ------------------------------------ |
| Crear un nuevo par usuario/contraseña | 75 | 15 |
| Recordar usuario - ¿Era el email? ¿Terminaba en número? | 25 | 0 |
| Recordar una contraseña específica | 25 | 0 |
| Insertar usuario y contraseña en cada campo del formulario | 15 | 5 |

### Manual sintetizado de buenas praxis

* Utiliza un software de gestión. Aquí algunas recomendaciones:
  - [KeePass (Win)](https://keepass.info/) | [KeePassX (Mac)](https://www.keepassx.org/) - open-source, gratuito
  - [1Password](https://1password.com/) - suscripción

* Ahora sólo tendrás una contraseña que recordar: La maestra que descifra el resto. Ten en cuenta estos consejos a la hora de establecerla.
  - Tarda el tiempo necesario y ten en cuenta que nada bajo 12 caracteres y que no utilice algún caracter fuera del rango `[a-z]` o `[0-9]` se puede considerar seguro.
  - Tampoco te excedas poniéndote un reto diario a la hora de recordar la forma de escribirla incluso cuando recuerdas perfectamente la base.
  - Utiliza una frase o secuencia de palabras (tipo letra de canción pero no en el orden exacto o con cambios sutiles) y separa con algo diferente del espacio las palabras `[$,%,&,*,...]`
  
* A la hora de crear un nuevo usuario para cualquier sitio elige la generación automática y no te preocupes de intentar recordarla, es más seguro así.

* Descarga tu software en todas las plataformas que necesites, por ejemplo [Keepass2Android Password Safe](https://play.google.com/store/apps/details?id=keepass2android.keepass2android) puede abrir en tu teléfono _Android_ el fichero que has generado en el PC con _KeePass_ y viceversa.
  - Si tu móvil tiene lector de huella, podrás vincular tu huella a tu clave maestra y así escribirla una sóla vez. ☝️

* Procura mantener un Pen-Drive exclusivamente con tu software (descarga la versión portable que no requiere instalación) y tu fichero de credenciales cifrado bajo clave maestra.

* No mantengas copias de tu fichero en _La Nube_, hazme caso. De nada.
