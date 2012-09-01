Se creo el repositorio desde el sitio de git-hub.
Se utilizo el cliente de git-hub para "clonar" (descargar el repositorio localmente).
se grego el archivo index.html vacio mediante el comando git add. y posteriormente
se hizo el git commit -m con el mensaje inicial.
Posteriormente se modifico localmente el index.html para agregar los integrantes y la imagen correpondiente.
Se realizó el git commit -m y el git push para subirlo al repositorio remoto.
Luego de esto y teniendo ambos integrantes el repositorio local actualizado, se
procedió a crear un branch local (datosParticulares) mientras el otro integrante modificaba el mismo archivo
sobre el trunk (master).
Quien modificó el trunk realizo git commit -m y posteriormente git push.
Quien estaba trabajando en el branch agrego datos personales (dni) y luego realizó el merge.
Para realizar el merge, primero desde el cliente cambiamos el branch donde estabamos parado. Posteriormente
hicimos git pull, luego al dar los conflictos del primer merge arreglamos el conflicto
utilizamos git commit -a y git push, con esto quedo todo en el repositorio remoto.
El otro integrante sincronizo su repositorio local para tener los ultimos cambios.
Luego procedimos a generar el conflicto modificando la misma linea ambos en sus repositorios locales.
para resolver el conflicto nuevamente quien no había llegado a hacer el push, tuvo que
hacer git pull para descargar los ultimos cambios, cuando estos mostraban error, se procedió 
a modificar el archivo index.html y luego mediante git commit -a y git push se subió
el archivo corregido al repositorio remoto.
Por ultimo para subir este texto, voy a hacer git commit -a y posteriormente 
y verificando que no hayan errores de conflicto el git push.

Las cuentas de github son:
margenats de Juan Diego Margenats
afichera de Alejandro Fichera
