
# 🪪 Generador de Credenciales de Evento

### Estudiante(s):  
- Bastián Parraguez – Patrones de Diseño (Sección 1)
- Diego Carrasco - Patrones de Diseño (Sección 2)

---

## 🎯 Objetivo del Proyecto

Sistema de emisión de credenciales personalizadas para eventos, utilizando los patrones de diseño Prototype y Singleton. Permite generar credenciales con nombre, cargo y RUT desde una plantilla base mediante una interfaz por consola.

---

## 🚀 Cómo ejecutar

1. Clonar el repositorio:
```bash
git clone https://github.com/bastian221158/Rut.git
cd Rut
```

2. Compilar y ejecutar:
```bash
javac DemoEvento.java
java DemoEvento
```

---

## 🧬 Patrón Prototype – Aplicación

- `Prototype` implementa `Cloneable`.
- Clonado

```java
Prototype clon = plantilla.clone();
clon.setNombre("Federicó");
```

---

## 🔒 Patrón Singleton – Aplicación

- `Singleton` contiene:
  - plantilla
- Se accede con `getInstancia()`:

```java
GestorCredenciales.getInstancia().setPlantilla(plantilla);
```

---

## 🖥️ Menú por consola

```
--- MENÚ ---
1.Crear credencial
2.Salir
```

---

## 📊 Diagrama de Clases (UML)

![Diagrama de Clases UML](https://i.ibb.co/6c7Xw5Fg/image.png)

---

## 📸 Captura del sistema funcionando

![Prueba 1](https://i.ibb.co/DDkBsJsG/image.png) ![Prueba 2](https://i.ibb.co/cSBgdPnv/image.png)
