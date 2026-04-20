# COMANDOS GIT

### Visualizar status de cambios
```
git status
```

### Incluir al stage
```
git add .
git add archivo_especifico.py
```

### Comprometer o seleccionar cambios para subir al repositorio remoto
```
git commit -m 'comentario'
```

### Establecer Configuracones basicas
```
git config --global user.name "nombre de usuario de git"
git config --global user.email "email de git"
git config --global core.editor "code --wait"
git config --global color.ui auto
git config --global init.defaultBranch main
```
### Consultar Configuraciones
```
git config --list
git config user.name
git config user.email
```

### Consultar logs
```
git log 
git log --oneline
git log --online --graph --all
git log --stat 
git log -P
git log -S
git log  --oneline -10 
git log --author="isrraelrobles742@gmail.com"
```

### Por fercha
```
git log --after="2025-25-12"
git log --before="2025-25-12"
git log --after="2025-25-12" before="2025-25-12"
```

### consultar por commit 
```
git show 2f078b86fdf78a0fe37d70503b105c289cde66fc
git show 2f078b86fdf78a0fe37d70503b105c289cde66fc --name-only
git show 2f078b86fdf78a0fe37d70503b105c289cde66fc --stat
git show 2f078b86fdf78a0fe37d70503b105c289cde66fc:services/order_services.py
git ls-tree 2f078b86fdf78a0fe37d70503b105c289cde66fc
git diff 2d1b0f0cc3b8219a916cdf2a56f55b83b9ceb725 bd2e699eeea067d8f85fbaf243c5b6a89e088015
```

### Modificar committs
```
gti commit --ammed -m "feat
```