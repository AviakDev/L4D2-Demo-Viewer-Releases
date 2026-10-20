# 🎮 L4D2 Demo Viewer

<p align="center">
  <img src="https://img.shields.io/badge/PROJECT-IN%20DEVELOPMENT-orange?style=for-the-badge&logo=github" alt="Project status: In development" />
  <img src="https://img.shields.io/badge/PLATFORM-Windows-0078D4?style=for-the-badge&logo=windows" alt="Target platform: Windows" />
  <img src="https://img.shields.io/badge/GAME-Left%204%20Dead%202-red?style=for-the-badge" alt="Left 4 Dead 2" />
</p>

<p align="center">
  <strong>RECONSTRUIR. EXPLORAR. REVIVIR CADA PARTIDA.</strong>
</p>

<p align="center">
  Un visor de escritorio en desarrollo cuyo objetivo es reconstruir y visualizar demos originales de Left 4 Dead 2 en un entorno 3D.
</p>

<p align="center">
  <a href="#-visión-del-proyecto">Visión</a> •
  <a href="#-características-en-desarrollo">Características</a> •
  <a href="#-investigación-técnica">Investigación</a> •
  <a href="#-descargas">Descargas</a> •
  <a href="#-estado-del-proyecto">Estado</a>
</p>

---

> [!IMPORTANT]
> **L4D2 Demo Viewer está en desarrollo.** Todavía no hay una versión final pública disponible para descargar. Este repositorio está destinado a distribuir futuras versiones e instaladores.

## 🧟 Visión del proyecto

Las demos de *Left 4 Dead 2* guardan información de una partida que puede estudiarse más allá de una grabación de vídeo convencional.

**L4D2 Demo Viewer** nace con el objetivo de convertir esa información en una reconstrucción visual navegable de la partida, dentro de una aplicación de escritorio independiente.

La idea es investigar cómo recuperar los estados de jugadores y entidades, interpretar la secuencia temporal de los acontecimientos y representar los elementos disponibles en un entorno tridimensional.

El objetivo es ofrecer nuevas formas de explorar partidas grabadas, estudiar posiciones y movimientos, y observar los acontecimientos desde diferentes perspectivas cuando la reconstrucción lo permita.

<p align="center">
  <em>Una demo no es simplemente una imagen de la partida: es información que puede investigarse para reconstruir lo sucedido.</em>
</p>

## 🎯 Objetivos principales

<table>
  <tr>
    <td width="50%">
      <h3>📂 Interpretación de demos</h3>
      Investigar y procesar los archivos originales <code>.dem</code> de Left 4 Dead 2.
    </td>
    <td width="50%">
      <h3>🌐 Reconstrucción 3D</h3>
      Transformar los datos recuperables en una representación visual del escenario y la partida.
    </td>
  </tr>
  <tr>
    <td width="50%">
      <h3>🎥 Exploración libre</h3>
      Desarrollar herramientas de cámara y navegación para observar la partida desde distintas perspectivas.
    </td>
    <td width="50%">
      <h3>🔬 Investigación técnica</h3>
      Comprender los datos de red, entidades, modelos y animaciones necesarios para mejorar la fidelidad.
    </td>
  </tr>
</table>

## ⚙️ Características en desarrollo

Las siguientes áreas representan objetivos de desarrollo, no una garantía de que todas las funciones estén implementadas.

| Área | Objetivo |
|---|---|
| 📁 Archivos `.dem` | Lectura y análisis de demostraciones |
| ⏱️ Línea temporal | Reconstrucción de los estados a lo largo de los ticks |
| 🧍 Jugadores y entidades | Representación de posiciones y estados recuperables |
| 🗺️ Escenarios 3D | Utilización de mapas y recursos compatibles |
| 🎥 Cámara libre | Exploración desde distintas perspectivas |
| 🦴 Modelos y animaciones | Investigación de modelos, secuencias y huesos |
| 🔎 Análisis técnico | Estudio del formato de demo y del motor Source |

La disponibilidad real de cada función se documentará cuando su implementación y funcionamiento estén verificados.

## 🧪 Investigación técnica

La reconstrucción de una demo implica más que leer un archivo. Es necesario comprender cómo se registran y actualizan los estados de la partida y cómo relacionarlos con los recursos visuales correspondientes.

Las principales áreas de investigación incluyen:

- **Formato `.dem`:** estructura del archivo, comandos y secuencia temporal.
- **Mensajes de red:** paquetes, snapshots y mensajes registrados.
- **Entidades:** propiedades de red y actualización de estados.
- **Recursos gráficos:** modelos, materiales, mapas y archivos VPK.
- **Animación:** secuencias, capas y datos necesarios para representar movimientos.
- **Representación visual:** relación entre la información reconstruida y la escena 3D.

La documentación distingue entre hallazgos verificados, inferencias y cuestiones que siguen pendientes de investigación.

## 🖥️ Aplicación de escritorio

L4D2 Demo Viewer está concebido como una aplicación de escritorio para Windows.

El objetivo es disponer de un entorno propio de visualización que no dependa de abrir la ventana normal del juego para explorar una reconstrucción.

El funcionamiento efectivo dependerá de la arquitectura implementada, los recursos disponibles y las limitaciones técnicas de las demos originales.

## 📥 Descargas

<p align="center">
  <img src="https://img.shields.io/badge/STATUS-Not%20Released-orange?style=for-the-badge" alt="Public release not available" />
</p>

<p align="center">
  <strong>La versión pública todavía no está disponible.</strong>
</p>

El proyecto continúa en desarrollo. Cuando exista una compilación adecuada para su distribución, se publicará aquí con su número de versión, notas de cambios y archivo de instalación.

<p align="center">
  <a href="../../releases">
    <img src="https://img.shields.io/badge/CONSULTAR-PRÓXIMAS%20VERSIONES-252525?style=for-the-badge&logo=github" alt="Consultar versiones en GitHub" />
  </a>
</p>

No se ofrecen instaladores ficticios ni se presenta una compilación interna como versión estable.

## 📊 Estado del proyecto

| Etapa | Estado |
|---|---|
| Desarrollo de la aplicación | 🚧 En desarrollo |
| Investigación de la reconstrucción | 🔬 En curso |
| Verificación de funcionalidades | 🧪 Progresiva |
| Distribución pública | ⏳ Pendiente |
| Lanzamiento estable | ⏳ Sin fecha confirmada |

Esta tabla describe el estado general del proyecto. La disponibilidad de funciones concretas debe comprobarse por separado.

## 🛠️ Filosofía del proyecto

- **Fidelidad:** priorizar una reconstrucción respaldada por los datos disponibles.
- **Investigación:** documentar cómo funciona el formato de demo en lugar de asumir su comportamiento.
- **Transparencia:** distinguir lo que funciona de lo que todavía se está investigando.
- **Independencia:** desarrollar una herramienta de escritorio con su propio entorno de visualización.
- **Evolución:** mejorar progresivamente la cobertura, la precisión y la experiencia de uso.

## 📦 Sobre este repositorio

Este repositorio está destinado a alojar los instaladores y archivos de distribución de las futuras versiones públicas de L4D2 Demo Viewer.

El código fuente de desarrollo se mantiene separado de este repositorio público.

Consulta las versiones publicadas en [Releases](../../releases).

## ⚖️ Aviso legal

L4D2 Demo Viewer es un proyecto independiente, no afiliado, respaldado ni aprobado oficialmente por Valve.

*Left 4 Dead 2* y las marcas relacionadas pertenecen a sus respectivos titulares. El nombre del juego se utiliza para identificar el software al que está relacionado este proyecto.

---

<p align="center">
  <strong>L4D2 DEMO VIEWER</strong>
  <br />
  <em>Explorando nuevas formas de reconstruir y visualizar partidas.</em>
  <br /><br />
  <sub>Proyecto independiente · En desarrollo · Windows</sub>
</p>
