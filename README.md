# acta-guardian-lab
Arquitectura Experimental de Verificación Ciudadana Distribuida
# ACTA GUARDIAN (Laboratorio Experimental)

Proyecto de Investigación en Sistemas Distribuidos y Seguridad

---

## ⚠️ Aviso Importante

Este repositorio contiene una arquitectura experimental de investigación.

NO es:
- Un sistema electoral oficial
- Un sistema de conteo de votos
- Una herramienta conectada a ninguna autoridad electoral
- Un sistema desplegado en elecciones reales

Este proyecto explora conceptos técnicos como:

- Validación multi-fuente de imágenes (N ≥ 3)
- Hash perceptual + coincidencia de características
- Verificación de consenso vía OCR
- Detección de fraude mediante ML
- Anclaje criptográfico en blockchain (solo hash)
- Registro de auditoría inmutable

Todo el contenido se publica con fines académicos, técnicos y de discusión arquitectónica.

---

## 📘 Descripción General

ACTA GUARDIAN propone una capa paralela de verificación ciudadana para actas de casilla, basada en:

- Múltiples envíos independientes
- Análisis de visión computacional
- Motor de consenso por quórum
- Almacenamiento descentralizado
- Registro criptográfico verificable públicamente

La arquitectura completa se encuentra en la carpeta `/docs`.

---

## 🏗 Capas del Sistema

1. Cliente móvil para captura y envío
2. Nodos de validación regionales
3. Clúster de procesamiento OCR + CV
4. Motor de consenso por quórum
5. Capa de almacenamiento + IPFS + blockchain
6. Panel público de transparencia

---

## 🔐 Principios de Seguridad

- Modelo Zero-Trust
- TLS 1.3
- Hash SHA-3
- Auditoría inmutable
- Sin almacenamiento de datos personales de votantes
- Anclaje blockchain solo de huellas criptográficas

---

## 📜 Licencia

AGPL-3.0 (ver LICENSE)

---

## 🛡 Uso Responsable

Este proyecto no debe utilizarse en procesos electorales reales sin:

- Revisión legal completa
- Auditoría independiente
- Evaluación ética
- Cumplimiento regulatorio

Ver DISCLAIMER.md
