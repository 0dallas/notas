# notas
Creo que has captado el problema: actualmente, los registros (logs) que se envían a Dynatrace desde distintas funciones Lambda y otros servicios no llegan como deberían; a veces, simplemente no llegan. Por lo que entiendo, necesitan centralizar todo en un único lugar donde los registros estén unificados; esa es la razón por la que quieren enviarlos a Dynatrace.

Básicamente, tenemos que revisar la llamada, los registros dinámicos y todo lo que se está enviando; asegurarnos de que efectivamente se esté enviando y, además, verificar el formato y demás, teniendo en cuenta los comentarios de esta persona —¿cómo se llamaba? ¿Tao? ¿Tao qué?—. Sí, básicamente eso.

A ver... Bueno, básicamente tú ya sabes lo que hay que hacer. ¿Podemos avanzar? No. ¿Existe alguna dependencia con el otro equipo? Por ahora, sí. Te estoy dando una visión general de lo que es necesario hacer, pero para concretar, él tendrá que coordinarse con el otro equipo, y nosotros también debemos comunicarnos con nuestro equipo para verificar todo lo que he comentado, además de revisar los datos que se han enviado y todo lo demás.
