# Pulso Híbrido

Prototipo de plataforma interna de supervisión de turno con módulo de robótica.
Una sola página estática, sin dependencias de servidor.

**Todos los datos son de demostración.** No contiene registros reales de personal
ni de clientes; la simulación es una función determinista de la hora del turno
(06:00 a 14:00).

## Vistas

- **Panorama** — resumen del grupo y tabla de sitios.
- **Torre** — los ocho sitios avanzando al mismo minuto.
- **Mapa vivo** — personas y robots moviéndose por zonas, con estelas de recorrido.
- **Turno** — línea de tiempo del sitio.
- **Rutinas** — catálogo de rutinas de limpieza.
- **Control** — programación de corridas con validaciones y cola del día.
- **Flota** — inventario de equipos.
- **Supervisión** — recorridos y hallazgos.

El módulo de Control no envía ninguna orden a equipo real: guarda la programación
en la propia página.
