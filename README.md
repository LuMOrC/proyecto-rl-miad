# Proyecto Aplicado de Reinforce Learning - Ambiente de dos habitaciones

Este repositorio contiene un notebook de jupyter y algunos archivos de soporte donde se implementa, entrena y evalúa un agente de Q-learning para resolver el problema de navegación en un ambiente de dos habitaciones separadas por una puerta con llave, tal como se propuso en la definición y descripción del proyecto final del curso en la semana 1 de Coursera.

El agente debe completar una secuencia de subtareas:

1. Recoger la bola que bloquea la puerta  
2. Recoger la llave azul  
3. Abrir la puerta usando la llave  
4. Navegar hasta la casilla de salida en la habitación derecha  

---

## 🧩 Requisitos

- Python 3.11.3 (recomendado)
- Git

---

## ⚙️ Configuración del entorno

### 1. Clonar el repositorio
```bash
git clone https://github.com/LuMOrC/proyecto-rl-miad.git
cd repositorio
```
### 2. Crear entorno virtual
```bash
python -m venv venv
```
### 3. Activar entorno
Windows
```bash
venv\Scripts\activate
```
Mac/Linux
```bash
source venv/bin/activate
```
### 4. Instalar dependencias
```bash
pip install -r requirements.txt
```
### 5. Configurar kernel para Jupyter (recomendado)
```bash
pip install ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```
Luego, en el notebook, seleccionar el kernel Python (venv).

---

## ▶️ Uso del proyecto

* Los notebooks se encuentran en la carpeta correspondiente (por ejemplo: Modelos_ML/)
* Ejecutar las celdas en orden
* Verificar que el kernel activo sea el correcto (venv)

---

## 🔁 Actualización de dependencias

Si se agregan nuevas librerías se debe actualizar el archivo de requirements.txt, asi:
```bash
pip install nombre_libreria
pip freeze > requirements.txt
```
Luego actualizar el repositorio:
```bash
git add requirements.txt
git commit -m "Actualiza dependencias"
git push
```

---

## 🚫 Archivos ignorados

Este repositorio no incluye:

* Entornos virtuales (venv/)
* Archivos temporales (__pycache__/)
* Checkpoints de Jupyter (.ipynb_checkpoints/)

---

## 📌 Buenas prácticas

* No trabajar directamente sobre la rama principal (master)
* Crear una rama para cada cambio o desarrollo
* Hacer commits claros y frecuentes
* Mantener actualizado el archivo requirements.txt

---

## 👥 Flujo de trabajo colaborativo

Crear una nueva rama:
```bash
git checkout -b mi-rama
```
Realizar cambios y guardar:
```bash
git add .
git commit -m "Descripción del cambio"
```
Subir la rama:
```bash
git push origin mi-rama
```
Crear un Pull Request en GitHub

---

## ⚠️ Solución de problemas comunes

### Error: módulos no encontrados
* Verificar que el entorno virtual esté activado
* Confirmar que se instalaron las dependencias correctamente
* Validar que el notebook esté usando el kernel correcto

### Validar entorno activo
Dentro de Python:
```bash
import sys
print(sys.executable)
```
Debe apuntar al entorno venv.

---

---
