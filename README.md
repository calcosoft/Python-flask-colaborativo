# Proyecto Flask Colaborativo PPS-2025

Este repositorio es una práctica para que cada alumno aprenda a usar Git y GitHub trabajando con ramas y pull requests.

Cada alumno debe crear una rama con su nombre y añadir una línea en el archivo `templates/index.html` dentro de la lista de colaboradores.


##  Instrucciones para los alumnos

### 1. Clona el repositorio

```bash
git clone https://github.com/TU_USUARIO/TU_REPO.git
cd TU_REPO
```

Reemplaza `TU_USUARIO` y `TU_REPO` con los datos reales del repositorio que te ha proporcionado el profesor.

---

### 2. Crea una rama con tu nombre

```bash
git checkout -b nombre-apellido
```

Ejemplo:

```bash
git checkout -b juan-perez
```

---

### 3. Haz tu cambio

Edita el archivo `templates/index.html` y añade una línea como esta dentro de la lista:

```html
<li>Juan Pérez</li>
```

---

### 4. Guarda, añade y haz commit

```bash
git add .
git commit -m "Añadido Juan Pérez a la lista"
```

---

### 5. Sube tu rama a GitHub

```bash
git push origin nombre-apellido
```

---

### 6. Crea una Pull Request

1. Entra en GitHub y abre tu repositorio.
2. Verás un mensaje para crear una **Pull Request** desde tu rama.
3. Verifica que sea:
   - **Desde:** tu rama (ej. `juan-perez`)
   - **Hacia:** `main`
4. Añade una descripción breve del cambio y haz clic en **"Create pull request"**

---

### Tu cambio será revisado y aceptado por el profesor.

