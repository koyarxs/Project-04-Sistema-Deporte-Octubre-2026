# Módulo Jugador

> Proyecto 04 | [Project-04-Sistema-Deporte-Octubre-2026](https://github.com/koyarxs/Project-04-Sistema-Deporte-Octubre-2026)

Resumen:
- Endpoints: `POST /jugador/agregarJugador`, `GET /jugador/obtenerJugadores`, `GET /jugador/obtenerJugador/:id`, `PATCH /jugador/actualizarJugador/:id`, `DELETE /jugador/eliminarJugador/:id`.

CreateJugadorDto (documentado con `@ApiProperty`):
- `correo: string` (email)
- `password: string`
- `nombre: string`
- `posicion: string`
- `esAnonimo?: boolean`
- `esPuntual?: boolean`
- `asistencia?: boolean`

Notas:
- Validaciones con `class-validator` (ej: `@IsEmail`, `@IsString`).
