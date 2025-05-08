
# 🪪 Generador de Credenciales de Evento

### Estudiante(s):  
- Bastián Parraguez – Patrones de Diseño (Sección 1)
- Diego Carrasco - Patrones de Diseño (Sección 2)

---

## 🎯 Objetivo del Proyecto

Este sistema permite emitir credenciales personalizadas para un evento, a partir de una plantilla clonable. Se aplican los patrones de diseño **Prototype** (para clonar credenciales) y **Singleton** (para configuración global del evento). (redactar el suyo)

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

![Diagrama de Clases UML]
(https://i.ibb.co/6c7Xw5Fg/image.png)

---

## 📸 Captura del sistema funcionando

(https://i.ibb.co/DDkBsJsG/image.png) (https://i.ibb.co/cSBgdPnv/image.png)
