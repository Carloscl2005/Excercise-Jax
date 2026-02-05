# Excersise_Jax

# ¿Qué es JAX?

**JAX** es una biblioteca de Python desarrollada por Google que combina la simplicidad de **NumPy** con el poder de la **aceleración por hardware (GPU y TPU)**. Su enfoque principal no es solo ejecutar cálculos numéricos, sino **transformar funciones matemáticas en código altamente optimizado**.

JAX es especialmente popular en investigación en inteligencia artificial, simulaciones científicas y modelos de alto rendimiento.

---

<br><br>

## 🚀 Principales Características

### 1️⃣ Sintaxis estilo NumPy  
JAX usa una API casi idéntica a NumPy, lo que permite a científicos de datos e investigadores adoptarlo rápidamente sin reaprender desde cero.

### 2️⃣ Compilación con XLA  
Gracias al compilador **XLA (Accelerated Linear Algebra)**, JAX puede fusionar operaciones y compilar funciones completas para ejecutarlas de forma extremadamente eficiente en GPU y TPU.

### 3️⃣ Programación funcional  
JAX funciona mejor con funciones puras y datos inmutables, lo que permite transformar, rastrear y optimizar cálculos de manera segura y escalable.

---

<br><br>

## 🧠 Transformaciones Clave

Estas funciones hacen que JAX sea especialmente potente:

- **`jit()`** – Compila funciones para ejecutarlas mucho más rápido  
- **`grad()`** – Calcula derivadas automáticamente (esencial en deep learning)  
- **`vmap()`** – Vectoriza funciones para procesar grandes volúmenes de datos sin bucles lentos  

---

<br><br>

## ⚔️ Comparación General

| Característica        | JAX | PyTorch | TensorFlow |
|----------------------|-----|---------|------------|
| Filosofía            | Programación funcional y transformaciones | Imperativa y flexible | Grafos y producción |
| Velocidad            | Muy alta con compilación | Muy buena | Muy buena |
| Derivación automática| Sí (nativa y avanzada) | Sí | Sí |
| Soporte TPU          | Nativo | Limitado | Nativo |
| Despliegue           | Mediante librerías externas | Bueno | Excelente |

---

<br><br>

## 🌐 Ecosistema

JAX es una herramienta de bajo nivel que se complementa con librerías especializadas:

### Redes Neuronales
- **Flax** – Modelos a gran escala e investigación  
- **Haiku** – Diseñada por DeepMind, estilo TensorFlow  
- **Equinox** – Enfoque más simple y estilo PyTorch  

### Optimización y utilidades
- **Optax** – Optimizadores como Adam y SGD  
- **Chex** – Testing y validación  
- **Orbax** – Guardado y carga de modelos  

### Computación científica
- **Brax** – Motor de física en GPU/TPU  
- **Diffrax** – Resolución de ecuaciones diferenciales  

---

**En resumen:** JAX convierte código matemático simple en programas acelerados y diferenciables, ideales para IA, ciencia y simulación de alto rendimiento.
