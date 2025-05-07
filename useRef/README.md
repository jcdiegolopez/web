# ⏱️ Stopwatch App - React Hooks

Este proyecto es una **aplicación de cronómetro** desarrollada con React que demuestra el uso práctico de hooks como `useState`, `useEffect` y `useRef`.

🌐 **Demo en línea**: [Ver app](https://www.awita.site/usuarios/lop23242/wab/useRef/)

---

## 📌 Características

* Iniciar, pausar y reiniciar el cronómetro.
* Guardar múltiples sesiones con su tiempo.
* Mostrar listado de sesiones guardadas.
* Uso eficiente de `setInterval` con limpieza adecuada.
* Sin clases: 100% componentes funcionales y hooks.

---

## 🧠 Hooks utilizados

### `useState`

* Manejo del tiempo transcurrido.
* Estado de ejecución (corriendo o pausado).
* Lista de sesiones guardadas.

### `useEffect`

* Control del temporizador.
* Limpieza automática del `setInterval` para evitar múltiples instancias.

### `useRef`

* Guardado del ID del intervalo sin disparar re-render.

---

## 🛠️ Funcionalidades

| Botón             | Acción                                                       |
| ----------------- | ------------------------------------------------------------ |
| ⏯️ Iniciar/Pausar | Comienza o pausa el temporizador.                            |
| 🔁 Reiniciar      | Reinicia el tiempo a 0.                                      |
| 💾 Guardar sesión | Guarda el tiempo actual en la lista de sesiones registradas. |

---

## ✅ Requisitos cumplidos

* [x] Mostrar el tiempo actual.
* [x] Alternar entre iniciar y pausar.
* [x] Reiniciar el contador.
* [x] Guardar múltiples sesiones.
* [x] Limpiar el `setInterval` al pausar o reiniciar.
* [x] No modificar directamente el array de sesiones (se usa copia).

---

## ⚠️ Errores evitados

* 🔁 Limpieza del `setInterval` con `useEffect` para evitar múltiples intervalos activos.
* 🚫 No se muta el estado directamente (`push()` no se usa).
* 🧼 Se usa `return` en `useEffect` para limpiar correctamente recursos.

---

## 🧪 ¿Quieres probarlo?

1. Visita: [https://www.awita.site/usuarios/lop23242/wab/useRef/](https://www.awita.site/usuarios/lop23242/wab/useRef/)
2. ¡Presiona los botones y observa cómo se comporta el cronómetro!
