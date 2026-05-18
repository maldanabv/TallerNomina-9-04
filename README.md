# Taller de Nómina - Proyecto Finalizado

Este proyecto es el resultado del taller de programación en JavaScript, donde se implementó un calculador de nómina básico para empleados en Colombia, aplicando conceptos vistos en clase.

## Descripción del Proyecto

El taller consistió en desarrollar una aplicación web simple que calcula la nómina de un empleado, incluyendo ingresos, deducciones y retenciones, basándose en las normativas laborales colombianas vigentes.

## Tecnologías Utilizadas

- **HTML**: Estructura básica de la página web.
- **JavaScript**: Lógica de cálculo y procesamiento de datos.
- **Git**: Control de versiones para el desarrollo colaborativo.

## Funcionalidades Implementadas

- **Validación de Perfil del Empleado**: Determina si el empleado es menor de edad, beneficiario, pensionado o activo, afectando los cálculos.
- **Cálculo de Nómina**:
  - Ingresos: Salario base, comisiones y horas extra.
  - Deducciones: Salud, pensión, fondo de solidaridad, ARL y retención en la fuente.
  - Auxilio de transporte condicional.
- **Retención en la Fuente**: Aplicación de la tabla de retención progresiva según UVT.
- **Constantes Actualizadas**: Uso de valores actuales de SMLV, UVT y subsidio de transporte.

## Estructura del Código

- `index.html`: Archivo HTML principal que carga el script.
- `script.js`: Contiene todas las funciones de cálculo y constantes.
- `README.md`: Documentación del proyecto.

## Cómo Usar

1. Abre `index.html` en un navegador web.
2. El script se ejecuta automáticamente (actualmente imprime resultados en consola; se puede extender para interfaz gráfica).
3. Modifica las variables de usuario en el código para probar diferentes escenarios.

## Conceptos Aplicados en Clase

- **Variables y Constantes**: Definición de constantes para valores fijos como SMLV y UVT.
- **Funciones**: Creación de funciones modulares para validación y cálculos.
- **Condicionales**: Uso de if-else para lógica de validación y cálculos condicionales.
- **Objetos y Arrays**: Estructura de datos para tarifas ARL.
- **Operadores Matemáticos**: Cálculos aritméticos para porcentajes y retenciones.
- **Comentarios**: Documentación del código con comentarios descriptivos.
- **Control de Versiones**: Uso de Git para commits y push al repositorio.

## Mejoras Futuras

- Interfaz gráfica con formularios para entrada de datos.
- Validación de entradas del usuario.
- Generación de PDF para desprendibles de nómina.
- Integración con bases de datos para múltiples empleados.

## Instalación y Ejecución

No requiere instalación adicional. Solo abre `index.html` en un navegador compatible con JavaScript.

## Contribución

Este proyecto fue desarrollado como parte de un taller educativo. Para contribuciones, realiza un fork y envía un pull request.

## Licencia

Proyecto educativo - Sin licencia específica.
