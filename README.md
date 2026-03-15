# PokéDex – Taller Ingenieria Web

##  Propósito

El objetivo de esta aplicación es practicar con APIs públicas desde el navegador usando JavaScript, junto con el diseño de interfaces usando HTML y CSS.

La aplicación permite:
- Ver los primeros 10 Pokémon al cargar la página.
- Buscar cualquier Pokémon por **nombre** (ej: `pikachu`) o **número** (ej: `25`).
- Ver la **imagen**, **nombre**, **número** y **tipo(s)** de cada Pokémon.
- Manejar errores cuando el Pokémon buscado no existe.


## 🛠️ Tecnologías Usadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de la página |
| CSS | Estilos, diseño responsive, colores por tipo |
| JavaScript | Lógica, fetch a la API, manejo de errores |
| [PokéAPI](https://pokeapi.co) | Fuente de datos de los Pokémon |
| Google Fonts | Fuentes: *Press Start 2P* y *Roboto* |


##  Funciones JavaScript

| Función | Descripción |
|---|---|
| `buscarPokemon()` | Busca un Pokémon por nombre o número usando la API |
| `cargarPokemonPorDefecto()` | Carga los primeros 10 Pokémon al iniciar la app |
| `crearTarjeta(datos)` | Genera el HTML de una tarjeta con los datos del Pokémon |
| `obtenerClaseTipo(tipo)` | Devuelve la clase CSS según el tipo del Pokémon |
| `mostrarError(mensaje)` | Muestra un mensaje de error en pantalla |
| `limpiarError()` | Limpia el mensaje de error |
| `mostrarCargando(visible)` | Muestra u oculta el indicador de carga |

---

##  Decisiones de Diseño

- **Fondo negro** (`#0a0a0a`) para un estilo oscuro y moderno.
- **Fuente retro** (*Press Start 2P*) para los nombres, con estética de videojuego clásico.
- **Colores por tipo**: cada tipo de Pokémon (fuego, agua, planta, etc.) tiene su propio color en la etiqueta.
- **Grid responsive**: las tarjetas se reorganizan automáticamente según el tamaño de la pantalla.


##  API Utilizada

**PokéAPI** – `https://pokeapi.co/api/v2/`

Endpoints usados:
- `GET /pokemon/{nombre_o_id}` → Detalles de un Pokémon específico.
- `GET /pokemon?limit=10&offset=0` → Lista de los primeros 10 Pokémon.


##  Autor

- **Nombre:** Assandry Barón Rodríguez  
- **Curso:** Ingeniería Web  
- **Docente:** Juan Pablo Arango  
