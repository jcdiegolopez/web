# 🔍 UserSearch App - Optimización con useMemo

Este proyecto es una **aplicación de búsqueda de usuarios** desarrollada con React. Utiliza el hook `useMemo` para **evitar cálculos innecesarios** en cada render y mejorar el rendimiento al filtrar una lista de usuarios.

🌐 **Demo en línea**: [Ver app](https://www.awita.site/usuarios/lop23242/wab/useMemo/)

---

## 📌 Características

* Buscar usuarios por nombre o descripción.
* Agregar nuevos usuarios a la lista.
* Filtro sensible a mayúsculas/minúsculas.
* Optimización con `useMemo` para evitar recalcular en cada render.

---

## 🧠 Hooks utilizados

### `useState`

* Guarda la lista de usuarios.
* Maneja el texto de búsqueda.
* Maneja el formulario de nuevos usuarios.

### `useMemo`

* Memoriza el resultado del filtro de usuarios.
* Solo recalcula si cambia el texto de búsqueda o la lista de usuarios.

---

## ⚙️ Funcionamiento

| Acción             | Detalle                                                            |
| ------------------ | ------------------------------------------------------------------ |
| 🔎 Buscar usuarios | Filtra por nombre o descripción. Sensible a mayúsculas/minúsculas. |
| ➕ Agregar usuario  | Permite añadir nombre y descripción al listado.                    |
| ⚡ Optimización     | El filtrado se recalcula solo cuando cambia el input o la lista.   |

---

## 👥 Datos iniciales

* Los usuarios están basados en personajes del anime **One Piece**.
* El primer usuario es el creador de la app, con su nombre real y una descripción personalizada.

---

## ✍️ ¿Cómo probarlo?

1. Ingresa a: [https://www.awita.site/usuarios/lop23242/wab/useMemo/](https://www.awita.site/usuarios/lop23242/wab/useMemo/)
2. Usa el input para buscar usuarios.
3. Añade nuevos usuarios con el formulario.
