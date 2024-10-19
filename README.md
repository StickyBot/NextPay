#Next Pay
Nuestro objetivo como equipo, era el crear un sistema de **Pago de lincencias de manejo**  en donde la transacciones, información y procesos que se generen por parte del usuario, sean seguros. Mediante la implementacion de las tecnologías **blockchain** y el protocolo **ICP** 

## Que permite nuestro proyecto

Nuestro proyecto le otorga al usuario la confianza y facilidad de pagar, almacenando su información y sus pagos, como contratos inteligentes (**CANISTERS**), asegurando que la información esta protegida y solo sera visualizada si ambas partes estan de acuerdo. Emitiendo la licencia una vez el contrato se haya concretado de manera transparente.

## Caracteristicas Principales
- Seguridad:  Utiliza blockchain para registrar y verificar todas las transacciones.

- Desentralización: Los datos no dependen de una base de datos centralizada, gracias a la implementación del ICP.

- Automatización: Gracias a los **Contratos inteligentes** (Canisters) el proceso de pagos y emisión de las licencias es completamente automatico.


## Tecnologías implementadas
- Motoko
- Mops
- ICP

## Estructura del proyecto

* Canisters: Se almacena los archivos de código en Motoko para poder gestionar los contratos inteligentes.

* Scripts: Auxiliares para la interacción con la red ICP.

* Frontend: Guardamos los archivos tanto HTML, CSS y JavaScript, para la interfaz del usuario.

* Assets: Archivos como imágenes o fuentes.

## Instalación y configuración
### Prerrequisitos necesarios
* Node.js (version 14 o superior)
* dfx sdk  (para interactuar con el ICP).

* MOPS (repositorios para una buena gestión de las dependencias de motoko).
### Pasos de instalación
1 Clonamos el repositorio
`git clone https://github.com/tu-usuario/pago-licencias-manejo-icp.git`

	2 Dirígete al directorio del proyecto:   
	
	`cd pago-licencias-manejo-icp`
	
	3 instala las dependencias
	    npm install
    Instala las dependencias de Motoko con mops:
	    mops install
    Inicia el entorno de desarrollo de ICP con DFX:
	    dfx start --background
    Despliega los canisters:
	    dfx deploy
    Inicia la aplicación web con React:
	    npm run start


## Uso de entornos locales
Asegúrate de que el DFX está corriendo en segundo plano. Para ello, puedes utilizar el siguiente comando:

	`dfx start --background
Accede a la aplicación web en tu navegador utilizando la URL local proporcionada por DFX, generalmente será:

	`http://localhost:8000`

La aplicación estará disponible para que puedas realizar pruebas y utilizarla localmente. Las características principales del sistema, como el registro, el pago de licencias y la emisión automática de estas, estarán funcionando en un entorno simulado de ICP.

Para interactuar con los canisters, puedes utilizar la consola de DFX. Por ejemplo, para consultar los registros de transacciones o probar funcionalidades específicas del contrato inteligente:

	`dfx canister call <nombre_canister> <funcion>`


Si deseas reiniciar el entorno o redeployar los canisters para pruebas, simplemente detén el servidor con:
	`dfx stop`

Luego, puedes reiniciar con:
	`dfx deploy`
------------
###  Next Team


![](https://img.shields.io/github/stars/pandao/editor.md.svg) ![](https://img.shields.io/github/forks/pandao/editor.md.svg) ![](https://img.shields.io/github/tag/pandao/editor.md.svg) ![](https://img.shields.io/github/release/pandao/editor.md.svg) ![](https://img.shields.io/github/issues/pandao/editor.md.svg) ![](https://img.shields.io/bower/v/editor.md.svg)


**Table of Contents**

[TOCM]

[TOC]

