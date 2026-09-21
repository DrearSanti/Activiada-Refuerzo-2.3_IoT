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

La simulación fue desarrollada en Cisco Packet Tracer 8.2.2.

Si se quiere reproducir la operación, se debe iniciar el broker en PLAT-BROKER desde la
pestaña Programming, y conectar los clientes MQTT de GW-A, GW-B y DASH-01
al broker en 203.0.113.10. Aunque esto no es necesario ya que en el video anexo a este repositorio se hacen unas pruebas con respecto a la reproducción y el funcionamiento de la simulación. El estado del broker no se conserva entre
sesiones.
