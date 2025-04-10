# 🏢 Registro de Visitantes a Edificio de Departamentos – Aplicación en Java (Consola)

Esta aplicación de consola desarrollada en **Java** permite registrar la información de los visitantes que ingresan a un edificio de departamentos. El sistema está diseñado para ser simple, robusto y funcional, haciendo uso de **todos los tipos de datos primitivos en Java** y buenas prácticas de programación.

## ✅ Características principales:

- Captura de datos clave del visitante:
  - Nombre y apellido
  - Número de identificación personal (ID)
  - Teléfono
  - Nombre del residente que visita
  - Número de departamento y piso
  - Motivo de la visita
  - Duración estimada de la visita (en minutos)
  - Indicador de si tiene cita previa
- Validaciones básicas de entrada
- Generación automática de la fecha de visita
- Almacenamiento persistente en archivo de texto (`registro_visitantes.txt`)
- Uso de tipos primitivos como `byte`, `short`, `int`, `long`, `char`, `boolean`
- Interfaz de consola amigable con mensajes claros para el usuario

## 💻 Tecnología usada:
- Java (JDK 17 o superior recomendado)
- Consola de comandos
- Archivo plano `.txt` para almacenamiento local

## 📁 Estructura del proyecto:
```plaintext
registro-visitante-java/
│
├── RegistroVisitante.java     # Código fuente principal
└── registro_visitantes.txt    # Archivo generado automáticamente con los registros

