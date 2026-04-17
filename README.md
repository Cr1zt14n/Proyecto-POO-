# Proyecto 1 POO - Sistema de envío 


**Autor:** Cristian Penagos
**Fecha:** 20/3/2026

---

## Descripción

Este proyecto consiste en una simulación de envíos de mercancía utilizando diferentes tipos de vehículos.
Se aplican conceptos de Programación Orientada a Objetos como herencia, clases abstractas y polimorfismo.

El sistema permite calcular el costo y tiempo de un envío, además de validar la carga y mostrar información adicional como la huella de carbono.

---

## Tecnologías usadas

* Java
* Programación Orientada a Objetos

---

## Cómo ejecutar

1. Clonar o descargar el repositorio.
2. Abrir el proyecto en NetBeans (o cualquier IDE de Java).
3. Ejecutar el archivo `Main.java`.

---

## Uso del programa

Al ejecutar, el sistema muestra un menú donde se puede:

* Seleccionar un tipo de vehículo (Auto, Moto, Camión o Dron)
* Ingresar distancia (km) y carga (kg)
* Ver resultados como:

  * Costo del envío (COP)
  * Tiempo estimado (horas)
  * Huella de carbono (kg CO2)
  * Nivel de eficiencia

También existe una opción para comparar todos los vehículos.

---

## Notas

* El programa valida que la carga no supere la capacidad del vehículo.
* Los valores utilizados son aproximados (simulación).
* Se incluye una métrica de huella de carbono como extensión del proyecto.
* Se añadió una función adicional de eficiencia del transporte.

---

## Estructura

* `Main.java` → Contiene todo el código del programa
## Ejecución del programa

### Menú principal

El programa inicia mostrando las opciones disponibles para seleccionar el tipo de vehículo.
```
=== SISTEMA DE ENVIO ===
1. Auto
2. Moto
3. Camion
4. Dron
5. Comparar todos
0. Salir
Opcion: 1
```

---

### Ingreso de datos

El usuario debe ingresar la distancia en kilómetros y la carga en kilogramos.
```
Opcion: 2
Distancia (km): 50
Carga (kg): 500
-------------
Vehiculo: Moto
Velocidad: 100 km/h
Capacidad: 100 kg
Carga excedida (max 100 kg)
```
---

### Resultado de un vehículo

Se muestran los resultados del envío, incluyendo costo, tiempo, huella de carbono y eficiencia.



---

### Comparación de vehículos

El sistema permite comparar todos los vehículos con los mismos datos ingresados.


