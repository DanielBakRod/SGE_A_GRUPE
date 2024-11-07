# SGE_A_GRUPE
-------------
## Integrants del grup
Som el grup E, format per:
>* A: Daniel Baquedano
>* B: Adria Mele
>* C: Marc Bertran
>* D: Josselin De la cruz

## Divisió de tasques:

La repartició de les tasques serà de la següent forma:

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

Per començar, hem d'instal·lar el mòdul d'Empleats, que seria el següent:
![alttext](img/Empleats/AplicacióEmpleats.png "Aplicació")

Un cop instal·lada, podem clicar a "Crear" i allà en sortirà la següent pestanya en la qual podem omplir amb les dades dels treballadors.
![alttext](img/Empleats/TestCreacioEmpleats.png "Test Exemple Empleats")

Un cop creats ens sortirien cada cop que entrem a empleats d'aquesta manera:
![alttext](img/Empleats/ExempleEmpleatsCreats.png "Exemple Empleats")

També podem crear "Departaments" on posar a cada empleat:
![alttext](img/Empleats/TestDepartamentos.png "Test Departament")

Un exemple d'un parell de departaments seria com aquests:
![alttext](img/Empleats/EjemploDepartamentos.png "Exemple Departaments")


### Compres(C)
----

Entrem a l'apartat de compres del nostre odoo:
![alttext](img/Compres/1entrarCompres.png "Entrar a compres")

Veurem la següent pàgina on crearem un nou pressupost.
![alttext](img/Compres/2nouPresupost.png "Creem nou pressupost")

Cal completar, com a mínim, els camps marcats en vermell:
![alttext](img/Compres/3presuCreat.png "P00001")

Un cop creat el pressupost podem afegir els ítems que volem/necessitem comprar com per exemple:
![alttext](img/Compres/4afegirProductes.png "Afegir productes")
Fent servir els botons "Agregar producto" i "Agregar sección" oh podrem tenir més ordenat.

Un cop tenim tot el que volem comprar apuntat confirmem la comanda amb el botó "Confirmar pedido".
![alttext](img/Compres/5confirmemComanda.png "Confirmar comanda")

Amb els botons de la dreta "Enviar mensaje", "Registrar nota" i "Actividades" es pot anar comentant i organitzant el procés de compra.
![alttext](img/Compres/6seguimentPressu.png "Seguiment pressupost")

>En activitats cal tenir en compte les següents coses:
>![alttext](img/Compres/6.1Activitats.png "Activitats")     
>>Quina activitat és:   
>>![alttext](img/Compres/6.2tipusActivitat.png "Tipus Activitats")    
>>El dia que s'ha d'acabar.     
>>Un resum de l'activitat.

Un cop acabades les activitats es crea la factura des del botó "Crear factura".
![alttext](img/Compres/7crearFactura.png "Crear factura")

Després de comprovar la factura per últim cop la podrem aprovar. S'han d'omplir tots els camps.
![alttext](img/Compres/8confirmarFactura.png "Confirmar Factura")

I finalment es paga la factura.
![alttext](img/Compres/9pagarFactura.png "Pagar factura")

>Per pagar, primer s'ha de crear el pagament.
>![alttext](img/Compres/10crearPago.png "Crear pagament")

Un cop pagada es veurà d'aquesta forma.
![alttext](img/Compres/11facturaPagada.png "Factura pagada")
Des d'aquesta última pàgina es pot rectificar la factura o tornar-la a un esborrany.

Des del menú de dalt a l'esquerra podràs navegar entre els teus pressupostos, productes i sol·licituds de compra que hagis creat. A més a més, en "Informes" podràs veure gràfics de les teves gestions de compres.
![alttext](img/Compres/12mesInfo.png "Més informació")

### Costos(C)
----

Benvingut a l'apartat de Costos de odoo! Per gestionar-lo primer hem d'entrar fent clic a la icona de "Gastos":
![alttext](img/Costos/1Entrar.png "Entrar a Costos")

Un cop dins veure'm aquesta pàgina.
![alttext](img/Costos/2Principal.png "Pàgina principal")

Afegim un rebut d'alguna compra. Per fer-ho fem clic al botó "Nuevo", o "Subir" si el tenim en digital.
![alttext](img/Costos/3CrearRebut.png "Crear rebut")

Un cop creat s'ha d'afegir la informació del rebut. No t'oblidis de completar-ho tot. Com més informació hi entris, més fàcil serà comprendre de què és el rebut en un futur.
![alttext](img/Costos/4OmplirRebut.png "Omplir rebut")

> Molt important! Si la companyia és la que ha pagat el rebut, apareixerà la casella de "Proveedor". 
>![alttext](img/Costos/4.1PagatXcompanyia.png)

Un cop creat el rebut, creem l'informe.
![alttext](img/Costos/5CrearInforme.png "Crear informe")

Ara haurem d'omplir la informació del Gerent i amb quin mètode de pagament farem servir. I l'enviem al gerent amb el botó "Enviar al gerente".
![alttext](img/Costos/6OmplirEnviarInforme.png "Omplir i enviar")

Ara ens apareixerà el botó per: Aprovar o Denegar el rebut.
![alttext](img/Costos/7Aprobar.png "Aprovar")
Aprobem el rebut.

Per pagar el rebut, fem clic al botó "Registrar asientos contables"
![alttext](img/Costos/8Pagem.png "Pagar el rebut")

Un cop pagat es veurà d'aquesta manera.
![alttext](img/Costos/9Pagat.png)
Des d'aquesta mateixa pàgina es pot tornar el rebut com a esborrany.

Quan hi haguin diversos rebuts i informes, segurament es voldrà veure un historial, o fer gràfics. Amb la pestanya d'"Informes" es crearan gràfics automàticament amb tota la informació que es necessiti.
![alttext](img/Costos/10mesinfo.png "Més informació")