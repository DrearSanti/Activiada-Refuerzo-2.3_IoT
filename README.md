# Monitoreo distribuido de disponibilidad de agua en Sabana Centro

Componente de conectividad de un sistema IoT para el monitoreo de nivel,
temperatura y turbidez en cuatro puntos de Sabana Centro, Cundinamarca.

Curso de Internet de las Cosas, Universidad de La Sabana, 2026-2.
Autores: Santiago Escobar, Esteban Sequeda.

## Documentación

La documentación completa del diseño y la validación está en el
[wiki de este repositorio](../../wiki).

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `SabanaAgua_v6_pruebas.pkt` | Simulación final con los casos de prueba ejecutados |
| `/versiones` | Versiones intermedias del montaje |
| `/capturas` | Evidencias de los casos de prueba |

## Simulación

Desarrollado en Cisco Packet Tracer 8.2.2. Abrir el archivo en esa versión
o superior.

Para reproducir la operación: iniciar el broker en PLAT-BROKER desde la
pestaña Programming, y conectar los clientes MQTT de GW-A, GW-B y DASH-01
al broker en 203.0.113.10. El estado del broker no se conserva entre
sesiones.
