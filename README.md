# Credit Card Validation - Warmi Store

## Índice

* [1. Cómo ejecutar](#1-cómo-ejecutar)
* [2. Resumen del proyecto](#2-resumen-del-proyecto)
* [3. Definición del producto](#3-definicion-del-producto)
* [4. Indicaciones del feedback](#4-indicaciones-del-feedback)
* [5. Prototipado de papel](#5-prototipado-de-papel)
***

## 1. Cómo ejecutar

Esta web App es el interfaz de la marca Warmi Store :womans_clothes::leaves: una tienda de ropa peruana :heart:. En la página encontraremos el último paso del proceso de compra, para lo cual el usuario debe validar su tarjeta de crédito o débito, ingresando sus datos personales: nombre de usuario y número de tarjeta :credit_card:

No se necesita descargar niguna app para poder usarla, solo es necesario acceder al siguiente link :link: https://shirleyramosm.github.io/LIM013-card-validation/src/ :point_left:

## 2. Resumen del proyecto

Este proyecto se ha desarrollado con Javascript, HTML y CSS.

Para la realización de la validación se utilizó el algoritmo de Luhn, el cual consiste en: 

:tulip: La fórmula verifica un número contra su dígito de chequeo incluido, el cual el usualmente agregado a un número de cuenta parcial para generar el número de cuenta completo. 

:tulip: A partir del dígito de chequeo incluido, el cual está a la derecha de todo el número, ir de derecha a izquierda duplicando cada segundo dígito.

:tulip: Sumar los dígitos del resultado: (ejemplo: 10 = 1 + 0 = 1, 14 = 1 + 4 = 5) juntos con los dígitos sin duplicar del número original.

:tulip: Si el total de módulo 10 es igual a 0 (si el total termina en cero), entonces el número es válido de acuerdo con la fórmula Luhn, de lo contrario no es válido.

## 3. Definición del producto

Los principales usuarios de esta web App son mujeres :information_desk_person:, aunque es abierta para todo público :couple:. La marca Warmi Store :womans_clothes::leaves: es una marca de ropa para mujeres. Por ello el nombre: "Warmi" que significa Mujer en quechua :ok_woman:, idioma nativo del Perú :heart:

Los objetivos de los usuarios es realizar la compra de los productos que ofrece Warmi Store, pero con una debida validación de tarjeta de crédito :credit_card:, por la seguridad del usuario. :computer:

Esta web App presenta la interfaz del momento posterior a la elección y ejecución de compra :shopping_cart:, le muestra al usuario el formulario donde debe indicar su nombre y número de tarjeta :pencil:, para que así se le indique si es válidad :heavy_check_mark: o no :x: y proseguir con la etapa final de pago del producto 	:money_with_wings:

## 4. Indicaciones del feedback

Con respecto a las mejoras, como esta interfaz de validación es el piloto de una futura web App para esta marca de ropa de mujeres peruana, se tendrá en cuenta las siguiente consideraciones:

:leaves: Presentar un interfaz de fácil acceso

:fallen_leaf: Mostrar adecuadamente los productos a elegir por el usuario

:leaves: Incluir información de contacto, así como los precios, vistas previas de los productos y una despcripción detallada del producto.

:fallen_leaf: El proceso de compra será ágil y amigable para evitar molestias o retrasos para los usuarios.

:leaves: Asimismo, se mejorará la parte visual con botones mucho más interactivos y sliders con imágenes de los productos. 

## 5. Prototipado de papel

La idea surgió con la realización de dos pantallas:
* La primera le permite al usuario ingresar sus datos personales, en este caso: el nombre de usuario y el número de tarjeta.

* En la segunda pantalla se logra ver el resultado de la validación, así como los primeros 12 dígitos ocultos mientras solo se logran ver los últimos 4 de la tarjeta de crédito o débito.

A continuación se adjuntan las imágenes del prototipado: 

* Pantalla 1

![WhatsApp Image 2020-08-07 at 08 39 40](https://user-images.githubusercontent.com/65095938/89656808-bb276480-d891-11ea-8d28-32b28cae47d2.jpeg)


* Pantalla 2

![WhatsApp Image 2020-08-07 at 08 39 47](https://user-images.githubusercontent.com/65095938/89656933-edd15d00-d891-11ea-8785-e5217982111e.jpeg)

