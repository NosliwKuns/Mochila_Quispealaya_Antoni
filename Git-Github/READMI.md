
1. **Configuración:**

  - *git config --global user.name "Tu Nombre":* Configura tu nombre de usuario.
  - *git config --global user.email "tu@correo.com":* Configura tu dirección de correo electrónico.
  - *git config --global alias.nombrecomando "comando":* Crea un alias para un     comando de Git.
  
2. **Crear y clonar repositorios:**

  - *git init:* Inicializa un nuevo repositorio local.
  - *git clone <url>:* Clona un repositorio remoto existente en tu máquina local.

3. **Ramas:**

  - *git branch:* Muestra la lista de ramas y resalta la rama actual.
  - *git branch <nombre_rama>:* Crea una nueva rama.
  - *git checkout <nombre_rama>:* Cambia a la rama especificada.
  - *git merge <nombre_rama>:* Fusiona una rama con la rama actual.

4. **Trabajo con cambios:**

  - *git status:* Muestra el estado actual del repositorio.
  - *git add <archivo>:* Agrega un archivo al área de preparación (staging).
  - *git add .:* Agrega todos los archivos modificados al área de preparación.
  - *git commit -m "Mensaje del commit":* Crea un nuevo commit con los cambios agregados.
  - *git push:* Envía los commits locales al repositorio remoto.

5. **Actualizar y sincronizar:**

  - *git pull:* Obtiene los cambios más recientes desde el repositorio remoto y los fusiona con tu rama local.
  - *git fetch:* Obtiene los cambios más recientes desde el repositorio remoto, pero no los fusiona automáticamente.
  - *git merge origin/<nombre_rama>:* Fusiona los cambios remotos en tu rama local.

6. **Deshacer cambios:**

  - *git checkout -- <archivo>:* Descarta los cambios en un archivo no confirmado.
  - *git reset HEAD <archivo>:* Quita un archivo del área de preparación.
  - *git reset --hard:* Descarta todos los cambios locales y regresa al commit   más reciente.
