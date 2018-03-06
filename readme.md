
# Práctica GIT

### Gómez Pérez, Carolina

# PracticaGit - Respuestas

--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque sirve para deshacer el ultimo commit incluyendo los cambios del working copy, es mas "duro" que `git reset HEAD~1`, que no borra los cambios en working copy.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog` 

Para conseguir el número del commit eliminado y poder copiarlo.

`git reset --hard 884d516`

Para recuperar el commit.

--

**3. ¿Qué comando o comandos utilizaste en el paso 13? ¿Causó algún conflicto? ¿Por qué?**

`git merge master` 

Desde style para absorver a la rama master, en la consola pone Already up to date, pero en `git log`, no aparece el cambio o yo no lo veo.

--

**4. ¿Qué comando o comandos utilizaste en el paso 19? ¿Causó algún conflicto? ¿Por qué?**

`git merge htmlify`

no causa conflicto, aparece fast-forward don01.md 3 +--

--

**5. ¿Qué comando o comandos utilizaste en el paso 21? ¿Causó algún conflicto? ¿Por qué?**

`git merge style`

no causa conflicto, aparece fast-forward don01.md 2 +-

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git log --graph`

--

**7. El merge del paso 26 ¿Podría ser fast forward? ¿Por qué?**

`git merge --no-ff title`

`--no-ff` impide que `git merge`ejecute un avance rapido en caso de ver que la cabeza es un antecesor de lo que estamos intentando fusionar. Para evitar esto y ver exactamente donde hemos estado trabajando hacemos `--no-ff`.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git chekcout -- don01.md`

--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`Git branch -d title `

--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**

`git reset --hard "numeros del merge"`

--

**12. ¿Qué comando o comandos utilizaste en el paso 32?**

`git reset --hard 89ab9f2`

--

**13. ¿Qué comando o comandos utilizaste en el paso 33?**

`git reset --hard 7761012`

--

