# 🔄 useCallback Example

Este proyecto es una demostración del uso del hook `useCallback` en React para optimizar el rendimiento de componentes que dependen de funciones memoizadas.

## 📌 Características

- **Botón Optimizado**: Utiliza `React.memo` y `useCallback` para evitar renders innecesarios.
- **Botón Normal**: Muestra cómo un componente sin optimización se renderiza en cada cambio de estado.
- **Estado Compartido**:
  - `randomNumber`: Genera un número aleatorio.
  - `counter`: Incrementa un contador.

## 🧠 Hooks Utilizados

### `useState`
- Maneja el estado de `randomNumber` y `counter`.

### `useCallback`
- Memoriza la función `createRandom` para evitar su recreación en cada render.

### `React.memo`
- Evita renders innecesarios del componente `ButtonOptimizado`.

## 🛠️ Cómo Probarlo

1. Clona el repositorio o copia el archivo `index.html`.
2. Abre el archivo en un navegador.
3. Interactúa con los botones:
   - **Generar Número Aleatorio**: Observa que solo se renderiza el botón optimizado.
   - **Aumentar Contador**: Observa que el botón normal se renderiza en cada clic.

## 🌐 Demo en Línea

[https://www.awita.site/usuarios/lop23242/useCallback/](https://www.awita.site/usuarios/lop23242/useCallback/)