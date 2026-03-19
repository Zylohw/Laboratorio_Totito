# Lab: Tutorial Tic-Tac-Toe — React Official Docs

## 📋 Descripción

Lab basado en el tutorial oficial de React: [Tutorial: Tic-Tac-Toe](https://react.dev/learn/tutorial-tic-tac-toe). El objetivo fue construir un juego interactivo de Tic-Tac-Toe (gato) utilizando los fundamentos de React, siguiendo una metodología de **aprender haciendo**.

---

## 🎯 Objetivos de aprendizaje

- Comprender la estructura básica de una aplicación en React
- Crear y componer **componentes** reutilizables
- Manejar el flujo de datos con **props**
- Gestionar el estado de la aplicación con el hook **`useState`**
- Implementar lógica de juego e interactividad en el navegador
- Practicar el concepto de **inmutabilidad** al actualizar el estado

---

## 🧠 Conceptos cubiertos

| Concepto            | Descripción                                               |
| ------------------- | --------------------------------------------------------- |
| Componentes         | Funciones que retornan JSX (`Square`, `Board`, `Game`)    |
| Props               | Paso de datos de componente padre a hijo                  |
| Estado (`useState`) | Memoria del componente para datos que cambian             |
| Lifting state up    | Elevar el estado al componente padre para compartirlo     |
| Inmutabilidad       | Crear copias del estado en lugar de mutarlo directamente  |
| Time travel         | Historial de movimientos para viajar a jugadas anteriores |

---

## 🏗️ Estructura del proyecto

```
tic-tac-toe/
├── public/
├── src/
│   ├── App.js        # Componentes Square, Board y Game
│   ├── index.js      # Punto de entrada
│   └── styles.css    # Estilos del tablero
├── package.json
└── README.md
```

---

## ▶️ Cómo ejecutar el proyecto

1. Clona el repositorio:

```bash
   git clone <url-del-repo>
   cd tic-tac-toe
```

2. Instala las dependencias:

```bash
   npm install
```

3. Inicia el servidor de desarrollo:

```bash
   npm start
```

4. Abre tu navegador en `http://localhost:3000`

---

## ✅ Funcionalidades implementadas

- [x] Tablero de 3x3 con casillas interactivas
- [x] Alternancia de turnos entre jugador **X** y jugador **O**
- [x] Detección automática de ganador
- [x] Indicador del turno actual o del ganador
- [x] Historial de movimientos
- [x] **Time travel:** botones para volver a cualquier jugada anterior

---

## 🔗 Recursos

- [Tutorial oficial — react.dev](https://react.dev/learn/tutorial-tic-tac-toe)
- [Documentación de useState](https://react.dev/reference/react/useState)

---

## 👤 Autor

**Zylo** — Curso: Fundamentos de Aplicaciones Web
