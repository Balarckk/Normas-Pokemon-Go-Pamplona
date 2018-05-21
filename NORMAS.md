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

* Para poder entrar al grupo, deberás confirmar tu identidad de Pokémon GO (validarte ). Con el comando: /register@ProfesorOak_bot 

* Es obligatorio cumplir las normas del siguiente enlace:

https://github.com/duhow/Trainer-Conduct-Code/blob/master/es/TCC-V1-OAK-GENERAL.md

* El hecho de no haber leido las normas, no implica que no pueda haber un aviso/sanción correspondiente.

* Para poder dirigirse a ti e identificarse es obligatorio que te pongas un alias y una imagen de perfil (desde ajustes de telegram).

* Se pueden enviar imagenes y demás multimedia siempre que no se abuse de ello, en la medida de lo posible evitar estas practicas ya que se satura el grupo de cosas inservibles para la mayoría, si se es pesado en este tema, puede conllevar limitación a la hora de enviar multimedia, lo mismo con los stikers.

* Para evitar que vuelvan a suceder situaciones en las que hay gente que no quiere saber el contenido nuevo que hayan sacado (misiones y demás) usaremos el bot @SpoilerzBot, no cuesta nada y así no se molesta a nadie, no todos jugamos al mismo ritmo y creo que es una buena manera de respetar a todos, el que juegue con esto, puede acabar baneado/expulsado.

No somos estrictos, pero hay que cumplir un mínimo de convivencia para estar bien entre todos. Dicho esto, disfruta de tu estancia aquí, ¡y hazte con todos!

## Grupos relacionados<a name="section2">

* **RAIDS:** Cuando estés validado, pide a algún admin que te meta.  En ese grupo se organizan las Raids (Incursiones). Todo lo relacionado con la organización de ellas debe hablarse aquí. Para unirse es necesario estar validado.

## Registro y validación de usuarios<a name="section3">

* Lo primero que has de hacer, es validarte con oak, para eso haz lo siguiente:

1 - Abre el juego.

2 - Renombra tu compañero como Oak (después del proceso podrás volver a ponerle el nombre que quieras).

3 - Abre un privado con @ProfesorOak_bot dale a iniciar abajo y dile "Quiero validarme" y te pedirá una serie de cosas, entre ellas una captura de pantalla de tu perfil del juego en donde sales con el compañero que acabas de renombrar (Tiene que verse la hora del teléfono).

4 - Envia la captura dentro de los 5 siguientes minutos a haberle dicho quiero validarme, si no la validación fallará.

5 - Ahora toca esperar, oak contestará con un enviado correctamente y al cabo de un rato (el tiempo depende del trabajo del equipo de validación), te dirá que ya estas validado.

6 - Siguiente paso, validarse con @detectivepikachubot , abre privado con el, vete al privado del @ProfesorOak_bot y preguntale "Quien soy?" sin las comillas, reenvía su respuesta a @detectivepikachubot , si lo has hecho bien te dirá que reconoce tu nivel y color, no sirve copiar y pegar, tiene que ser reenviar.

7 - Ponte un alias y un avatar en los ajustes del telegram.

8 - Cuando hayas hecho eso, avisa a un admin escribiendo que ya estas validado y poniendo @admin en el cuerpo del mensaje, un admin lo revisará y te meterá al grupo de raids de Pamplona.

9 - En el grupo de raids no se puede hablar, solo crear raids, todo lo que no sea raids es borrado por el bot, asi que si quieres consultar algo, es mejor que permanezcas en este grupo.

10 - Para actualizar tú nivel en oak solo has de decirle a oak por privado soy nivel y tú nuevo nivel y para actualizarlo en pikachu has de preguntar a oak por privado quién soy y reenviarlo a pikachu también por privado. 

11 - Cualquier duda, preguntala en el grupo poniendo en el cuerpo @admin , o abriendo privado con uno, son los que en la lista de usuarios salen con una estrellita, si no te resuelve la duda cualquier usuario amable, aparecerá algun admin y la resolverá, tened paciencia, los admins tenemos vida privada y también trabajamos

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

7 - Ponte un alias y un avatar en los ajustes del telegram.

8 - Cuando hayas hecho eso, avisa a un admin escribiendo que ya estas validado y poniendo @admin en el cuerpo del mensaje, un admin lo revisará y te meterá al grupo de raids de Pamplona.

9 - En el grupo de raids no se puede hablar, solo crear raids, todo lo que no sea raids es borrado por el bot, asi que si quieres consultar algo, es mejor que permanezcas en este grupo.

10 - Para actualizar tú nivel en oak solo has de decirle a oak por privado soy nivel y tú nuevo nivel y para actualizarlo en pikachu has de preguntar a oak por privado quién soy y reenviarlo a pikachu también por privado. 

11 - Cualquier duda, preguntala en el grupo poniendo en el cuerpo @admin , o abriendo privado con uno, son los que en la lista de usuarios salen con una estrellita, si no te resuelve la duda cualquier usuario amable, aparecerá algun admin y la resolverá, tened paciencia, los admins tenemos vida privada y también trabajamos

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

`/raid`

También se pueden especificar los parámetros directamente. La sintaxis para crear una Raid de esta forma debe ser así:

`/raid pokemon hora gimnasio`

Es importante seguir este mismo orden, sino lo más seguro es que el bot no te entienda. También se puede añadir una hora a la que desaparece el Pokémon.

`/raid pokemon hora gimnasio horafin`

Algunos ejemplos:

`/raid Latios 14:30 Pasen y Beban
/raid Tyranitar 3:30 Burrito Piedra
/raid Magikarp 12 Monumento al Encierro 12:15`

En lugar de especificar un Pokémon, se puede especificar un huevo, por ejemplo, para un huevo de nivel 4 se pondría N4:

`/raid N4 13:00 Pasen y Beban`

Para crear Raids EX se debe utilizar la palabra EX y especificar el día de la Raid con el siguiente formato:

`/raid EX dia/hora gimnasio`

Por ejemplo, para una Raid EX el día 12 a las 15:30 en el gimnasio Burrito Piedra:

`/raid EX 12/15:30 Burrito Piedra`

Para poder crear una Raid es necesario tener un alias definido en Telegram y estar validado.

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
