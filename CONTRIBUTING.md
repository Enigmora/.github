CONTRIBUTING

¡Gracias por tu interés en colaborar con nosotros! Este documento establece las bases legales y técnicas para asegurar que el proyecto crezca de forma ordenada y protegida.

---

## ⚖️  1. Acuerdo de Licencia del Colaborador (CLA)

Al contribuir a este repositorio, aceptas que tus aportaciones se rigen por la licencia especificada en el archivo LICENSE de este repositorio y por los siguientes términos de **Cesión de Derechos**:

### Marco Legal (México / Internacional)

- **Cesión y Temporalidad:** El Colaborador cede de manera irrevocable y exclusiva a favor de **ENIGMORA S.C.** la totalidad de los derechos patrimoniales sobre sus Contribuciones. Según el **Artículo 103 de la LFDA (México)**, esta cesión para programas de computación no tiene límite temporal y es válida por toda la vigencia legal de los derechos.
- **Onerosidad:** La cesión es **onerosa**. La contraprestación consiste en la atribución de autoría (derechos morales), el uso del software resultante y la exposición profesional dentro del ecosistema.
- **Jurisdicción:** Este acuerdo se rige por las leyes federales de los **Estados Unidos Mexicanos**. Las partes se someten a los tribunales de la **Ciudad de México**.

---

## 🛠️  2. Preparación del Entorno

Debido a la diversidad de nuestros proyectos, los requisitos específicos de software se detallan fuera de este documento:

1. **Consulta el `README.md` principal:** Ahí encontrarás las dependencias exactas, versiones de runtime y herramientas necesarias para este repositorio específico.
2. **Asegúrate de tener Git instalado:** Es la herramienta base para todas nuestras contribuciones.
3. **Configuración de identidad:** Verifica que tu nombre y correo en Git coincidan con tu perfil de GitHub para facilitar la trazabilidad legal.

---

## 🔄 3. Flujo de Trabajo (Git Workflow)

Para mantener la integridad de la arquitectura de los sistemas que desarrollamos y la trazabilidad de los cambios, seguimos este proceso:

### Pasos para contribuir:

- **Fork & Clone:** Crea una copia del repo y clónala localmente.
- **Rama de Trabajo:** Crea una rama descriptiva (`feature/nombre`, `fix/nombre` o `docs/nombre`).
- **Firma de Commits:** Utiliza el comando `git commit -s`. Esto añade la marca `Signed-off-by`, que actúa como tu firma digital de aceptación de este acuerdo.
- **Sincronización:** Mantén tu rama actualizada con `upstream/main` para evitar conflictos complejos.

---

## 📋 4. Estándares de Calidad

Independientemente del lenguaje de programación, aplicamos principios de ingeniería de software robustos:

| **Principio**                       | **Aplicación**                                                                                             |
| ----------------------------------- | ---------------------------------------------------------------------------------------------------------- |
| **Separación de Responsabilidades** | El código debe estar organizado modularmente.                                                              |
| **Documentación**                   | Los cambios significativos deben reflejarse en los comentarios y, si aplica, en archivos `.md` de soporte. |
| **Trazabilidad**                    | Cada Pull Request debe explicar claramente el "qué" y el "por qué" del cambio.                             |

---

## ✅ 5. Proceso de Aceptación

Al enviar un **Pull Request (PR)**:

1. Un bot o mantenedor verificará que hayas aceptado los términos del CLA.
2. Se ejecutarán las pruebas automatizadas (si el proyecto las tiene).
3. Se realizará una revisión de código (_Code Review_) para asegurar que se alinean con la arquitectura del sistema.

---
