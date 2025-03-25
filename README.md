
# Mi Primer Repositorio en GitHub 🚀

Este repositorio es una práctica para aprender los conceptos básicos de **Git y GitHub** en Windows.

## 📌 Pasos Iniciales

### 1. Instalación y Configuración
- Descargué Git desde [git-scm.com](https://git-scm.com/download/win).
- Configuré mi usuario y correo:
  ```bash
  git config --global user.name "MiNombre"
  git config --global user.email "miemail@example.com"
  ```

### 2. Inicializar un Repositorio Local
- Creé una carpeta para el proyecto y ejecuté:
  ```bash
  git init
  ```

### 3. Mi Primer Commit
- Creé este archivo `README.md` y lo agregué al área de preparación:
  ```bash
  git add README.md
  ```
- Guardé los cambios con mi primer commit:
  ```bash
  git commit -m "Agregar README con instrucciones iniciales"
  ```

## 🌿 Ramas y Fusiones (Rama desarrollo)
1. Creé una rama llamada `desarrollo`:
   ```bash
   git checkout -b desarrollo
   ```
2. Modifiqué este archivo y fusioné los cambios con `main`:
   ```bash
   git checkout main
   git merge desarrollo
   ```

## 🔗 Subir a GitHub
1. Creé un repositorio vacío en GitHub.
2. Vincular mi repositorio local:
   ```bash
   git remote add origin https://github.com/miusuario/mi-primer-repo.git
   git push -u origin main
   ```

## 📚 Recursos
- [Documentación oficial de Git](https://git-scm.com/doc)
- [Guía rápida de GitHub](https://guides.github.com)

