# Normas Pokemon Go Pamplona

En estas normas, además de tratar de que haya una buena conducta y buen ambiente, pondremos un resumen de las utilidades de los bots que mas usamos y como se usan estas.

## Índice

1. [Normas Básicas](#section1)
2. [Grupos relacionados](#section2)
3. [Registro y validación de usuarios](#section3)
4. [Raids](#section4)
	1. [Crear una Raid](#section11)
    2. [Editar, cancelar y borrar una Raid](#section12)
	3. [Apuntarse a una Raid](#section13)

## Normas Básicas<a name="section1">

* Para poder entrar al grupo, deberás confirmar tu identidad de Pokémon GO (validarte ). 

* Es obligatorio cumplir las normas del siguiente enlace:

https://github.com/duhow/Trainer-Conduct-Code/blob/master/es/TCC-V1-OAK-GENERAL.md

* El hecho de no haber leido las normas, no implica que no pueda haber un aviso/sanción correspondiente.

* No se permite la entrada a menores de 16 años, en caso de hacer caso omiso de esta norma, se llevará un ban permanente.

* Para poder dirigirse a ti e identificarse es obligatorio que te pongas un alias y una imagen de perfil (desde ajustes de telegram).

* Se pueden enviar imagenes y demás multimedia siempre que no se abuse de ello, en la medida de lo posible evitar estas practicas ya que se satura el grupo de cosas inservibles para la mayoría, si se es pesado en este tema, puede conllevar limitación a la hora de enviar multimedia, lo mismo con los stikers.

* No se pueden compartir imagenes de noticias que salen en el propio juego, asi como noticias de grupos que lanzan bulos sin fundamento como team evolution o team legendary, son bien conocidos por enviar falsas especulaciones.

* Para evitar que vuelvan a suceder situaciones en las que hay gente que no quiere saber el contenido nuevo que hayan sacado (misiones y demás) usaremos el bot @SpoilerzBot, no cuesta nada y así no se molesta a nadie, no todos jugamos al mismo ritmo y creemos que es una buena manera de respetar a todos, el que juegue con esto, puede acabar baneado/expulsado.

* No se va a permitir a la gente que se desapunte de una raid dependiendo de lo que ha salido, si no vas a participar si sale X pokemon, no te apuntes, espera a saber lo que sale, el desapuntarse de estas raids se considerará falta de respeto.

* No está permitido hablar de religión, política, deportes o temas que lleven a cualquier debate interminable y subido de tono.

No somos estrictos, pero hay que cumplir un mínimo de convivencia para estar bien entre todos. Dicho esto, disfruta de tu estancia aquí, ¡y hazte con todos!

## Grupos relacionados<a name="section2">

* **RAIDS:** Cuando estés validado, pide a algún admin que te meta.  En ese grupo se organizan las Raids (Incursiones). Todo lo relacionado con la organización de ellas debe hablarse aquí. Para unirse es necesario estar validado.

* **AVISTAMIENTOS:** En este grupo se anuncian pokemon, misiones y demas cosas que se han encontrado por la comarca por si hay algún interesado en ir a por ello.

https://t.me/joinchat/GldVhhHOwzIiZQk2UO6pRA

## Registro y validación de usuarios<a name="section3">

1 - Pide nombre para tu compañero y hacer una captura de pantalla del perfil de tu juego.

2 - Abre el juego y renombra tu compañero con el nombre que te haya dicho un admin, haz la captura de pantalla y envíala al grupo de validaciones, no pueden pasar más de 5 minutos desde que se hace hasta que se envía.

3 - Abre un privado con @detectivepikachubot, dale abajo a iniciar, escribe /register y sigue las indicaciones, te pedirá otra captura de pantalla con unas condiciones específicas.

4 - Envía una captura de pantalla de la confirmación de pikachu en el grupo de validaciones.

5 - Ponte un alias y un avatar en los ajustes del telegram.

6 - Cuando hayas hecho eso, un admin lo revisará y te meterá al grupo de raids de Pamplona y al General.

7 - En el grupo de raids no se puede hablar, solo crear raids, todo lo que no sea raids es borrado por el bot, asi que si quieres consultar algo, es mejor que permanezcas en el grupo general.

8 - Para indicar una subida de nivel, basta con enviar una captura de pantalla del perfil donde se vea el nuevo nivel, una vez se esté validado. Si el bot no contesta nada, es debido a que el estado de validación no es correcto. 

9 - Cualquier duda preguntala en el grupo, si no te resuelve la duda cualquier usuario amable, aparecerá algun admin y la resolverá, tened paciencia, los admins tenemos vida privada y también trabajamos.

## Raids<a name="section4">

### Crear una Raid<a name="section11">

* Se puede crear una Raid de forma interactiva con el comando:

`/raid`

* También se pueden especificar los parámetros directamente. La sintaxis para crear una Raid de esta forma debe ser así:

`/raid pokemon hora gimnasio`

* Es importante seguir este mismo orden, sino lo más seguro es que el bot no te entienda. También se puede añadir una hora a la que desaparece el Pokémon.

`/raid pokemon hora gimnasio horafin`

* Algunos ejemplos:

`/raid Latios 14:30 Pasen y Beban
/raid Tyranitar 3:30 Burrito Piedra
/raid Magikarp 12 Monumento al Encierro 12:15`

* En lugar de especificar un Pokémon, se puede especificar un huevo, por ejemplo, para un huevo de nivel 4 se pondría N4:

`/raid N4 13:00 Pasen y Beban`

* Para crear Raids EX se debe utilizar la palabra EX y especificar el día de la Raid con el siguiente formato:

`/raid EX dia/hora gimnasio`

* Por ejemplo, para una Raid EX el día 12 a las 15:30 en el gimnasio Burrito Piedra:

`/raid EX 12/15:30 Burrito Piedra`

* Para poder crear una Raid es necesario tener un alias definido en Telegram y estar validado.

### Editar, cancelar y borrar una Raid<a name="section12">

Se pueden editar y añadir todos los detalles de la Raid después de crearla: cambiar la hora, el gimnasio, el Pokémon (o el huevo) y la hora a la que desaparece.

Para editar o añadir cualquiera de estos detalles, el creador de la Raid puede contestar al mensaje de la Raid con uno de estos comandos:

`/time 12:00
/pokemon Wartortle
/gym Plaza de Abastos
/endtime 12:30
/endtime -`

En el caso de pasar una barra horizontal - como argumento a `/endtime`, se borrará la hora de fin.

Una Raid también puede ser **cancelada** contestando con el comando `/cancel` y ser **borrada** con el comando `/delete`.

Las incursiones se finalizan automáticamente pasada media hora desde la hora de inicio, **pero se puede forzar** la finalización con el comando `/close` en cualquier momento, pasada la hora de inicio de la Raid.

Los participantes recibirán **avisos por privado** cuando se edite, cancele o borre una Raid.

Al editar una hora hay las mismas restricciones que al crear la Raid. Con `/time` es **necesario especificar el día** si no es el día actual. Con `/endtime`, sin embargo, no es necesario, ya que por defecto se toma el mismo día en que se realiza la Raid.

El creador de una Raid es el responsable de mantener informados a los jugadores de cualquier cambio en el curso de la Raid, horarios, ubicación, cancelación...pudiendo recibir baneo/expulsión de no hacerlo correctamente.

### Apuntarse a una Raid<a name="section13">

Una vez creada la Raid, puedes apuntarse pulsando en el botón `Voy`. Si te apuntas unos pocos minutos antes de la hora fijada, o incluso después, podrías aparecer con un icono de un caracol 🐌 en el listado, dependiendo de cómo esté configurado el grupo.

Si vas con acompañantes, puedes pulsar el botón `+1` por cada acompañante adicional. Si te has pasado, pulsa en `Voy` para poner esta cuenta a cero y volver a empezar. Ten en cuenta que los administradores de los grupos pueden limitar el número de acompañantes permitidos o deshabilitar completamente esta opción.

Cuando estés en el lugar de la Raid, puedes pulsar el botón `Estoy ahí` para indicarlo.

Si te has apuntado pero no vas a ir, pulsa en `No voy`. Si han pasado más de cinco minutos desde que te apuntaste, permanecerás en la lista con una ❌ para que la gente sepa que te has desapuntado.

Para poder apuntarse a una Raid es `necesario tener un alias definido` en Telegram. Además, `hay que estar validado` en el bot. Si no puedes apuntarte por alguno de estos motivos, el bot te informará.

Para que la participación sea contabilizada para los rankings hay que `apuntarse antes de la hora de inicio acordada` y `pulsar en Estoy` en cualquier momento, de forma que quede marcado que has acudido a la Raid. La configuración del caracol 🐌 no tiene efecto alguno. Además deben estar validados en el momento de generar el ranking.
