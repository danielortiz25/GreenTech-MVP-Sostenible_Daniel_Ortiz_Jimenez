## GreenTech MVP Sostenible
Este repositorio contiene la versión refactorizada y optimizada de la landing page “Salvemos el Planeta”, desarrollada bajo criterios de sostenibilidad digital, ecodiseño y eficiencia energética. El objetivo principal ha sido reducir el peso total de la página, eliminar dependencias innecesarias y mejorar el rendimiento en dispositivos de gama baja, contribuyendo así a una menor huella ambiental.

## 1. Objetivo del Proyecto
El código original presentaba un uso excesivo de librerías externas y recursos pesados que no aportaban valor real al funcionamiento de la página. Esto generaba:

Un consumo elevado de ancho de banda.

Mayor uso de CPU y memoria en dispositivos modestos.

Incremento del consumo energético en centros de datos.

Riesgo de acelerar la obsolescencia programada del hardware del usuario.

El propósito de este MVP es demostrar que una web ligera, eficiente y bien diseñada puede ofrecer la misma funcionalidad con un impacto ambiental significativamente menor.

## 2. Refactorización Realizada
Dependencias eliminadas
Se han eliminado las siguientes librerías externas:

Bootstrap (CSS y JS)

jQuery

Font Awesome

Moment.js

Google Fonts

Estas dependencias sumaban más de 700 KB de transferencia innecesaria.

Sustituciones aplicadas
Reescritura completa del diseño utilizando CSS nativo.

Uso de JavaScript nativo para funcionalidades mínimas.

Sustitución de fuentes externas por system fonts, que no requieren descarga.

Eliminación de iconos externos.

Limpieza de código redundante y simplificación de la estructura HTML.

## 3. Optimización Técnica
Imagen principal optimizada
La imagen de cabecera se ha reducido y convertida a un formato más eficiente (JPG o WebP), disminuyendo el peso total de la página y mejorando los tiempos de carga.

CSS separado y minimalista
El archivo styles.css contiene únicamente las reglas necesarias para el diseño, evitando sobrecarga y manteniendo una estructura clara.

Eliminación de peticiones externas
La página funciona sin CDNs ni recursos remotos, reduciendo la huella de carbono asociada a cada visita.

JavaScript mínimo
El único script presente se utiliza para mostrar el año actual en el footer mediante una línea de código nativo.

## 4. Impacto Ambiental
La reducción del peso de la página tiene efectos directos en la sostenibilidad digital:

Menor consumo energético en centros de datos: Cada byte transferido requiere energía para ser almacenado, procesado y enviado. Reducir el tamaño de la web disminuye este consumo.

Menor uso de CPU en dispositivos de gama baja: Al eliminar librerías pesadas, los dispositivos trabajan con menos esfuerzo, reduciendo el calentamiento y el desgaste.

Mayor vida útil del hardware: Un software más eficiente evita exigir potencia innecesaria, lo que contribuye a retrasar la obsolescencia programada y reduce la generación de residuos electrónicos.

Reducción del tráfico de red: Menos datos transferidos implica un menor impacto ambiental asociado a la infraestructura de telecomunicaciones.

## 5. Comparativa Antes / Después
Elemento	Versión Original	Versión Optimizada
Peso total aproximado	+700 KB	~100–200 KB
Dependencias externas	5	0
Imagen principal	Sin optimizar	Optimizada
Peticiones externas	Múltiples	Ninguna
Coherencia ecológica	Baja	Alta

## 6. Conclusión
La versión final del MVP demuestra que es posible desarrollar una web visualmente atractiva y funcional sin recurrir a frameworks pesados ni dependencias innecesarias.
El resultado es una página más rápida, más accesible, más eficiente y más respetuosa con el medio ambiente, alineada con los principios de ecodiseño y economía circular.