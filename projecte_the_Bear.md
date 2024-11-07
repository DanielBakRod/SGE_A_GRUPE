# SGE_A_GRUPE
-------------
## Integrants del grup
Som el grup E, format per:
>* A: Daniel Baquedano
>* B: Adria Mele
>* C: Marc Bertran
>* D: Josselin De la cruz

## Divisio de tasques:
La repartició de les tasques sera de la seguent forma:
>* Empleats (A)
>* Vendes (B)
>* Compres (C)
>* Punts de venda (D)
>* Events (A)
>* Calendari (B)
>* Costos (C)
>* Planificació (D)

### Empleats(A)
----
Per començar hem de instalar el modul d'Empleats, que seria el seguent:
![alttext](img/Empleats/AplicacióEmpleats.png "Aplicació")

Un cop instalada, podem clicar a "Crear" i alla en sortira la seguent pestanya en la que podem omplir amb les dades del treballadors.
![alttext](img/Empleats/TestCreacioEmpleats.png "Test Exemple Empleats")

Un cop creats ens sortirien cada cop que entrem a empleats d'aquesta manera:
![alttext](img/Empleats/ExempleEmpleatsCreats.png "Exemple Empleats")

Tambe podem crear "Departaments" on posar a cada empleat:
![alttext](img/Empleats/TestDepartamentos.png "Test Departament")

Un exemple de un parell de departaments seria com aquets:
![alttext](img/Empleats/EjemploDepartamentos.png "Exemple Departaments")

### Compres(C)
----
Entrem al apartat de compres del nostre odoo:
![alttext](img/Compres/1entrarCompres.png "Entrar a compres")

Veurem la següent pagina on crearem un nou presupost.
![alttext](img/Compres/2nouPresupost.png "Creem nou presupost")

Cal completar, com a minim, els camps marcats en vermell:
![alttext](img/Compres/3presuCreat.png "P00001")

Un cop creat el presupost podem afegir els items que volem/nececitem comprar com pre exemple:
![alttext](img/Compres/4afegirProductes.png "Afegir productes")
Fent servir els botons "Agregar producto" i "Agregar sección" oh podrem tenir mes ordenat.

Un cop tenim tot el que volem comprar apuntat comfirmem la comanda amb el boto "Confirmar pedido".
![alttext](img/Compres/5confirmemComanda.png "Confirmar comanda")

Amb els botons de la dreta "Enviar mensaje", "Registrar nota" i "Actividades" es pot anar comentant i organitzant el proces de compra.
![alttext](img/Compres/6seguimentPressu.png "Seguiment pressupost")

>En activitats cal tenir en compte les seguents coses:
>![alttext](img/Compres/6.1Activitats.png "Activitats")     
>>Quina activitat es:   
>>![alttext](img/Compres/6.2tipusActivitat.png "Tipus Activitats")    
>>El dia que s'ha d'acabar.     
>>Un resum de l'activitat.

Un cop acabades les activitats es crea la factura desde el boto "Crear factura".
![alttext](img/Compres/7crearFactura.png "Crear factura")

Despres de comprovar la factura per ultim cop la podrem aprobar. S'han d'omplir tots els camps.
![alttext](img/Compres/8confirmarFactura.png "Confirmar Factura")

I finalment pagem la factura.
![alttext](img/Compres/9pagarFactura.png "Pagar factura")

>Per pagar, primer s'ha de crear el pagament.
>![alttext](img/Compres/10crearPago.png "Crear pagament")

Un cop pagada es veura d'aquesta forma.
![alttext](img/Compres/11facturaPagada.png "Factura pagada")
Desde aquesta ultima pagina es pot rectificar la factura o tornar-la a un borrador.

Desde el menu d'adalt a la esquerra podras navegar entre els teus presupostos, productes i solicituts de compra que haguis creat. A mes a mes, en "Informes" podras veure grafics de les teves gestions de compres.
![alttext](img/Compres/12mesInfo.png "Mes informació")

### Costos(C)
----
Benvingut al apartat de Costos de odoo! Per gestionar-l'ho primer hem d'entrar fent clic a la icona de "Gastos":
![alttext](img/Costos/1Entrar.png "Entrar a Costos")

Un cop dins veurem aquesta pagina.
![alttext](img/Costos/2Principal.png "Pagina principal")

Anem a afegir un rebut d'alguna compra. Per fero fem clic al boto "Nuevo", o "Subir" si el tenim en digital.
![alttext](img/Costos/3CrearRebut.png "Crear rebut")

Un cop creat s'ha d'afegir la informació del rebut. No t'oblidis de completar-ho tot. Com mes informació hi entris, mes facil serà comprendre de que es el rebut en un futur.
![alttext](img/Costos/4OmplirRebut.png "Omplir rebut")
> Molt important! Si la compañia es la que ha pagat el rebut, apareixera la casella de "Proveedor". 
>![alttext](img/Costos/4.1PagatXcompanyia.png)

Un cop creat el rebut, creem l'informe.
![alttext](img/Costos/5CrearInforme.png "Crear informe")

Ara haurem d'omplir la informació del Gerent i amb quin metode de pagament farem servir. I l'enviem al gerent amb el boto "Enviar al gerente".
![alttext](img/Costos/6OmplirEnviarInforme.png "Omplir i enviar")

Ara ens apareixera el boto per: Aprobar o Denegar el rebut.
![alttext](img/Costos/7Aprobar.png "Aprobar")
Aprobem el rebut.

Per pagar el rebut, fem clic al boto "Registrar asientos contables"
![alttext](img/Costos/8Pagem.png "Pagar el rebut")

Un cop pagat es veura d'aquesta manera.
![alttext](img/Costos/9Pagat.png)
Desde aquesta mateixa pagina es pot tornar e rebut com a borrador.

Quan hi haguin varios rebuts i informes, segurament es voldra veure un historial, o fer grafics. Amb la pestanya de "Informes" es crearan grafics automaticament amb tota la informació que es necessiti.
![alttext](img/Costos/10mesinfo.png "Mes informació")