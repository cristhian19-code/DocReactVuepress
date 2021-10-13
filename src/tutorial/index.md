# Antes de empezar el tutorial
Vamos a construir un pequeño juego durante este tutorial. D**eberás estar tentado a obviarlo porque tú no estás construyendo juegos en el día a día, pero dale una oportunidad**. Las técnicas que aprenderás en el tutorial son fundamentales para construir cualquier aplicación de React, y dominarlo te dará un entendimiento profundo de React.

:::warning Tip
Este tutorial está diseñado para personas que prefieren aprender haciendo. Si tu prefieres aprender los conceptos desde el principio, revisa nuestra guía paso a paso. Podrías encontrar este tutorial y la guía, complementarias entre sí.
:::

Este tutorial está dividido en varias secciones:

* Configuración para el tutorial te dará un punto de partida para seguir el tutorial.
* Visión general te enseñará **los fundamentos** de React: componentes, props y estado.
* Completando el juego te enseñará **las técnicas más comunes** en desarrollo de React.
* Agregando viaje en el tiempo te dará una **visión más profunda** de las fortalezas únicas de React.

No tienes que completar todas las secciones a la vez para obtener el valor de este tutorial. Prueba llegar tan lejos como puedas, incluso si es una o dos secciones.

## ¿Qué estamos construyendo?
En este tutorial, te mostraremos cómo construir un juego de tic-tac-toe interactivo con React.

Puedes ver lo que construiremos aquí: [Resultado Final](https://codepen.io/gaearon/pen/gWWZgR?editors=0010). Si el código no te hace sentido, o si no estás familiarizado con la sintaxis de código, ¡no te preocupes! El objetivo de este tutorial es ayudarte a entender React y su sintaxis.

Recomendamos que revises el juego de tic-tac-toe antes de continuar con el tutorial. Una de las características que notarás es que hay una lista enumerada a la derecha del tablero del jugador. Esta lista da una historia de todos los movimientos que han ocurrido en el juego, y se va actualizando conforme el juego progresa.

Puedes cerrar el juego de tic-tac-toe una vez que te familiarizaste con él. Empezaremos desde una plantilla más simple en este tutorial. Nuestro siguiente paso es configurarlo de tal forma que puedas empezar a construir el juego.

## Prerrequisitos
Asumimos que tienes cierta familiaridad con HTML y JavaScript, pero deberías ser capaz de seguir adelante incluso si vienes de un lenguaje de programación diferente. También suponemos que estás familiarizado con conceptos de programación como funciones, objetos, arrays, y en menor medida, clases.

Si necesitas revisar JavaScript, te recomendamos leer [esta guía](https://developer.mozilla.org/es/docs/Web/JavaScript/A_re-introduction_to_JavaScript). Ten en cuenta que también usamos algunas características de ES6, una versión reciente de JavaScript. En este tutorial, estamos usando [funciones flecha](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Functions/Arrow_functions), [clases](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Classes), sentencias [let](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/let) y [const](https://developer.mozilla.org/es/docs/Web/JavaScript/Reference/Statements/const). Puedes usar el Babel REPL para revisar a qué código compila ES6.
