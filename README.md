# Prueba Técnica - Clonación de Visualización de Tokens por Capitalización de Mercado

Este proyecto es una recreación de la visualización de tokens por capitalización de mercado disponible en el enlace [Moral is Money - Top Tokens by Market Cap](https://moralismoney.com/top-tokens-by-market-cap). El objetivo es replicar la interfaz de usuario y la funcionalidad de interactuar con las burbujas utilizando la API de CoinGecko.

## Tecnologías Utilizadas

- Rwik: Framework para desarrollo web.
- Tailwind: Framework de CSS para diseño de interfaces.
- TypeScript: Superset de JavaScript que añade tipado estático a la sintaxis del lenguaje.

## Funcionalidades Implementadas

- Clonación visual de la visualización de tokens por capitalización de mercado.
- Interacción con las burbujas para obtener información adicional sobre cada token.
- Utilización de la API de CoinGecko para obtener los datos de los tokens.

## Implementación de la Visualización de Burbujas

Para la implementación de la visualización de burbujas se utilizó la librería D3.js. Se empleó el template disponible en [Circular Packing](https://d3-graph-gallery.com/graph/circularpacking_template.html) como base para la representación de los tokens en forma de burbujas.

## Limitaciones y Consideraciones

- La versión gratuita de la API de CoinGecko solo proporciona datos de los últimos 24 horas, por lo que la información mostrada puede no ser la más actualizada.
- El sidebar y navbar no están implementados funcionalmente, ya que el foco principal fue la visualización de las burbujas.

## Instrucciones de Ejecución

1. Clona este repositorio en tu máquina local.
2. Instala las dependencias utilizando el gestor de paquetes de Rwik.
3. Ejecuta el proyecto utilizando el comando adecuado para tu entorno de desarrollo.

## Autor

[Cristian Treachi](https://github.com/cris3h)


