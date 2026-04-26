# Guía Esencial de Git y GitHub

Este repositorio sirve como una guía práctica para comprender los pilares fundamentales del control de versiones utilizando Git y la plataforma colaborativa GitHub.

## 1. El Concepto de Versionamiento
El **versionamiento** es la gestión de los cambios realizados en un conjunto de archivos a lo largo del tiempo. Git es un sistema de control de versiones distribuido que permite:
* **Trazabilidad:** Saber quién, cuándo y por qué se cambió algo.
* **Recuperación:** Regresar a versiones anteriores en caso de errores críticos.
* **Colaboración:** Permitir que múltiples personas trabajen sobre el mismo código sin sobrescribir el trabajo ajeno.

## 2. ¿Qué es un Fork?
Un **Fork** es una copia personal de un repositorio de otro usuario. Al hacer "fork":
1.  Obtienes una instancia completa del proyecto en tu propia cuenta de GitHub.
2.  Puedes realizar experimentos y cambios sin afectar el proyecto original.
3.  Es el punto de partida estándar para contribuir a proyectos de Código Abierto (Open Source).

## 3. Pull Requests (PR)
Un **Pull Request** es la forma en que le comunicas a los mantenedores de un proyecto que has realizado cambios y te gustaría que fueran integrados.
* **Revisión:** Permite que los colaboradores revisen tu código antes de que sea parte del proyecto principal.
* **Discusión:** Se pueden dejar comentarios sobre líneas específicas para mejorar la calidad del código.
* **Fusión (Merge):** Una vez aprobado, el código se integra a la rama principal (main).

## 4. GitHub Actions (Automatización y CI/CD)
Un concepto vital en el desarrollo moderno es **GitHub Actions**. Permite automatizar flujos de trabajo (workflows) directamente en tu repositorio.
* **CI (Integración Continua):** Ejecuta pruebas automáticas cada vez que alguien sube código o crea un PR.
* **CD (Despliegue Continuo):** Despliega el código a servidores de producción automáticamente si las pruebas pasan.
* **Seguridad:** Escanea el código en busca de vulnerabilidades de forma automática.

## 5. Flujo de Trabajo Básico (Guía Rápida)

Para trabajar de manera efectiva, sigue estos pasos comunes en la terminal:

| Comando | Descripción |
| :--- | :--- |
| `git clone <url>` | Clona un repositorio remoto a tu máquina local. |
| `git branch <nombre>` | Crea una nueva rama para trabajar en una funcionalidad. |
| `git checkout <nombre>` | Te mueve a la rama especificada. |
| `git add .` | Prepara todos los cambios para el siguiente commit. |
| `git commit -m "msj"` | Guarda los cambios en el historial local con un mensaje descriptivo. |
| `git push origin <rama>` | Sube tus commits locales a GitHub. |
| `git pull origin main` | Trae las últimas actualizaciones del servidor para evitar conflictos. |

## 6. Resolución de Conflictos
Cuando dos personas modifican la misma línea de un archivo y Git no puede decidir cuál es la correcta, ocurre un **conflicto**.
- Git marcará el archivo con indicadores visuales (`<<<<<<<`, `=======`, `>>>>>>>`).
- El desarrollador debe elegir qué versión conservar y luego realizar un nuevo commit.

## Conclusión
Dominar estos conceptos es fundamental para cualquier profesional del software. GitHub no es solo un sitio para guardar código; es una plataforma social que potencia la colaboración global, la calidad del software mediante revisiones de pares y la eficiencia a través de la automatización.

---
*Este documento fue generado para fines educativos sobre control de versiones y DevOps.*