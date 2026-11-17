# **Como inicializar un repositorio**
# 1: iniciar uno en guthib
- ✅ **Con README** opcional
# 2: comandos en la terminal
## inicializar repositorio
```bash
git init
```
```bash
git branch -M main
```
### agregar el repositorio por enlace
```bash
git remote add origin (link_del_repositorio)
```
## preparar repositorio
### actualizar datos
```bash
git pull origin main --allow-unrelated-histories
```
### agregar los archivos
```bash
git add .
```
### guardar cambios (local)
```bash
git commit -m "commit_1"
```
### publicar en github
```bash
git push -u origin main
```

# Extra
### Forzar la subida a la nube
```bash
git push -u (nombre) main --force
```
### desvincular repositorio
```bash
Remove-Item -Recurse -Force .git
```