# Pendientes trabajos para essential

## Pagina de manual withdraw 

> Colocar en la tabla un boton para que salga un modal con la siguiente info:
   
   + ~~ID del Retiro~~
   + ~~Cantidad en Coins~~
   + ~~El Monto del Retiro en la Crypto que Retiro~~
   + ~~Fecha~~ "Solo para el admin. Ya al usuario se le muestra"
   + ~~Nombre Completo de la Crypto con Acronimo~~
   + ~~La red que uso, es decir, (BSC / BEP2 / Mainnet)~~
   + ~~El fee~~
   + ~~Y lo que recibira, es decir, El Monto menos el Fee~~
   + ~~El Precio de la Crypto en el monto que retiro~~
   + ~~El Tx HASH~~
   + ~~Si se consumio el fee burn~~

> Esto se colocó en withdraw manual y en el usuario
---
   
# Fee Burn
	es un fee para nuevas address, es necesario usar la api para saber si se va a cobrar o no el fee

---

+ Pagina de /withdraw en la parte del admin

-Colocar en el modal la siguiente info:

   -Que red se uso para el retiro
   -El Precio de la Crypto en el momento del retiro
   -Y lo que recibira, es decir, (El Monto - Fee) pero dejar tambien el monto completo , es decir, (Solo el Monto si la resta del Fee)
   -Boton que me llevara a ver las actividades del usuario

+ Pagina de /withdraw

-Colocar en la card de las Cryptos

   -Solo dejar El Minimo del Retiro sin la suma del fee por que crea confusion
   -Dejar el Precio de la Crypto
   -y Colocar el Fee de la Crypto
   
-Colocar en el Modal del Retiro

   -Colocar lo que el usuario recibira, es decir, (Monto  - Fee)
   
   
+ Lo que aun Falta

   1-OfferWalls y Ref Contest pero con normas de validacion, es decir, ( en Offerwalls que valga mas la cantidad y no el numero de OferWalls completadas y en Ref que el referido cumpla con por lo menos 10 Faucet Claims, 10 OfferWalls, etc)
   
   2-AntiBot en la Faucet pero que salga en otra pagina
   
   3-Los Nodes para Pagos instantaneos
   
   4-Colocar una Opcion mas en /coins y /withdraw donde se pueda poner input que es el fee burn y que se cobre en algunas coins no en todas y en /withdraw indicando que se le puede cobrar este fee burn si la cuenta esta inactiva y en la tabla del retiro en la parte del modal tambien colocar lo del fee burn indicando que si la cuenta era inactiva se le cobro dicho fee burn con una imagen de una llama
   
   5-Colocar las siguientes OfferWalls:

-pollfish
https://www.pollfish.com/docs/api-documentation
https://www.pollfish.com/docs/webplugin

-mediumpath
https://www.mediumpath.com/documentation

-theoremreach
https://docs.theoremreach.com/

-bitlabs
https://bitlabs.ai/integrations/web-integration

-adgem
https://adgem.com/docs/api-integration/offer-wall-api/

-lootably & loot.tv
https://lootably.com/
----------------------------------------------------   
que como en la de la red salga un mensaje diciendo un fee puesto en /coin y ese fee salga en el momento del retiro y en el modal indicando que este fee extra se descuenta si la cuenta es nueva

en withdraw/manual se debe indicar si se cobro el fee burn si/no
se debera colocar otro input en /coin sera y que se guarde en la db ya que solo alguna los cobran no toda
si esta en 0 que no salga la info












