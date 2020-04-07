# Material de apoyo para la utilizacion de Hyperledger Fabric

El objetivo de este repositorio es proporcionar un material de apoyo para la utilizacion de 
[Hyperledger Fabric](https://hyperledger-fabric.readthedocs.io/en/release-2.0/). Actualmente la curva de aprendizaje 
de las herramientas es bastante alta, adicionalmente no existe mucho material en español. 
Con el interes de compartir la experiencia d eun grupo de investigadores y profesionales interesados en las
tecnologias blockchain vamos a propoircionar un material que esperamos permita ayudar a la comunidad a implmentar soliciones
utilizando este y otros ambientes.

## Participantes

* Camilo Molano, profesor Universidad Sergio Arboleda
* Carlos Castro-Iragorri, profesor Universidad del Rosario
* Julian Ramirez, Joven Investigador Universidad del Rosario,
* Hans

## Estructura preliminar del proyecto

1. Desplegar un contrato inteligente sobre una red basica de Fabric
    * Utilizando el ejemplo de Marble (intercambio de esferas) especificado en la distribucion 
    basica de Fabric bajo el archivo [marble_chaincode.js](https://youtu.be/cpxzewMSQRo).
    * Desplegamos el contrato inteligente sobre la red Basica.
    * Probar el funcionamiento.
    * Monitorear transacciones en CouchBD.
    * Conectar con servicios web a traves de [SDK](https://hyperledger.github.io/fabric-sdk-node/) 

2. Entender el desarrollo de contratos inteligentes utilizando NodeJS
    * Entender contrato marble_chaincode.js
    * Desarrollar lógica negocios y desarrollar en NodeJS 
    * Utilizar clases del [API Fabric](https://hyperledger.github.io/fabric-sdk-node/master/module-fabric-network.html). 
    * Realizar modificaciones al contrato marble_chaincode.js
    * Escribir un contrato para una lógica de negocio diferente.

3. Desplegar una red en la nube

4. Interoperabilidad de Fabri y otras herramientas de desarrollo para Blockchain
