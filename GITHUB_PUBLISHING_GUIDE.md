# 🚀 Publicación en GitHub - Ivy Lee Weekly Planner

## ✅ Estado Actual

- ✅ Repositorio Git inicializado localmente
- ✅ Commit inicial creado
- ✅ .gitignore configurado
- ⏳ Pendiente: Crear repositorio en GitHub y hacer push

---

## 📋 Opción 1: Crear Repositorio desde GitHub Web (Recomendado)

### Paso 1: Crear el repositorio en GitHub.com

1. **Ir a GitHub:**
   - Visita: https://github.com/new

2. **Configurar el repositorio:**
   ```
   Owner: AlexG182
   Repository name: IvyLeeWeeklyPlanner
   Description: 🎯 Productivity app combining Ivy Lee Method + Eat That Frog (Brian Tracy) - Plan your week with maximum efficiency
   Visibility: ✅ Public
   
   ⚠️ NO marcar ninguna de estas opciones:
   ❌ Add a README file
   ❌ Add .gitignore
   ❌ Choose a license
   ```

3. **Click en "Create repository"**

### Paso 2: Conectar y subir (ejecutar estos comandos)

Una vez creado el repositorio, ejecuta estos comandos en tu terminal:

```bash
cd "c:\Users\AWOO TEAM\Documents\ANTIGRAVITY5\IvyLeeWeeklyPlanner"

# Agregar el remote de GitHub
git remote add origin https://github.com/AlexG182/IvyLeeWeeklyPlanner.git

# Cambiar la rama a 'main' (si es necesario)
git branch -M main

# Subir los archivos a GitHub
git push -u origin main
```

**URL del repositorio será:** https://github.com/AlexG182/IvyLeeWeeklyPlanner

---

## 📋 Opción 2: Usar GitHub CLI (Requiere instalar gh)

Si quieres usar GitHub CLI en el futuro, primero debes instalarlo:

### Instalar GitHub CLI:

**Windows (usando winget):**
```bash
winget install --id GitHub.cli
```

**O descargar manualmente:**
- https://cli.github.com/
- Descargar el instalador para Windows
- Ejecutar e instalar

### Después de instalar:

```bash
# Autenticarse
gh auth login

# Crear y publicar el repositorio
gh repo create IvyLeeWeeklyPlanner --public --source=. --description="🎯 Productivity app combining Ivy Lee Method + Eat That Frog - Plan your week with maximum efficiency" --push
```

---

## 📋 Opción 3: Comando Manual Completo

Si prefieres hacerlo todo por comando (después de crear el repo en GitHub web):

```bash
cd "c:\Users\AWOO TEAM\Documents\ANTIGRAVITY5\IvyLeeWeeklyPlanner"

# Verificar el estado del repositorio local
git status

# Agregar el remote (reemplaza USERNAME con tu usuario de GitHub)
git remote add origin https://github.com/AlexG182/IvyLeeWeeklyPlanner.git

# Verificar el remote
git remote -v

# Renombrar rama a main (si está en master)
git branch -M main

# Subir a GitHub
git push -u origin main
```

---

## 🎨 Configurar GitHub Pages (Opcional pero Recomendado)

Para que tu aplicación esté disponible online:

1. **Ir al repositorio en GitHub:**
   - https://github.com/AlexG182/IvyLeeWeeklyPlanner

2. **Settings → Pages**

3. **Configurar:**
   ```
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
   ```

4. **Save**

5. **Tu app estará disponible en:**
   ```
   https://alexg182.github.io/IvyLeeWeeklyPlanner/
   ```

---

## 📝 Actualizar el README con la URL de GitHub Pages

Después de configurar GitHub Pages, actualiza el README.md para incluir el enlace en vivo.

---

## 🔄 Comandos Útiles para Futuras Actualizaciones

### Subir cambios:
```bash
cd "c:\Users\AWOO TEAM\Documents\ANTIGRAVITY5\IvyLeeWeeklyPlanner"

# Ver cambios
git status

# Agregar todos los cambios
git add .

# Commit con mensaje descriptivo
git commit -m "Descripción de los cambios"

# Subir a GitHub
git push
```

### Ver el historial:
```bash
git log --oneline --graph --all
```

### Ver diferencias:
```bash
git diff
```

---

## ✅ Checklist de Publicación

- [x] Repositorio Git inicializado
- [x] Archivo .gitignore creado
- [x] Commit inicial realizado
- [ ] Repositorio creado en GitHub.com
- [ ] Remote agregado (origin)
- [ ] Push a GitHub completado
- [ ] (Opcional) GitHub Pages configurado
- [ ] (Opcional) README actualizado con URL en vivo

---

## 🎯 Próximos Pasos

1. **Crear el repositorio en GitHub:** https://github.com/new
2. **Ejecutar los comandos** de conexión y push
3. **(Opcional) Configurar GitHub Pages** para tener la app online
4. **Compartir el enlace** con quien quieras

---

*Documento creado el 16/02/2026*
