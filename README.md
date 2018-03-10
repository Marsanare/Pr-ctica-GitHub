# PracticaGit - Respuestas

### Santana Areces, Marta



--

**1. ¿Qué comando utilizaste en el paso 11? ¿Por qué?**

`git reset --hard HEAD~1` 

Porque ese comando borra tanto el commit como lo que hay en el working copy.

--

**2. ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?**

`git reflog`, `git reset --hard eb45b0f`

Porque primero quería ver el historial de los commits y copiar el identificador que correspondía al último que hice, para así mediante el segundo comando llevar a *HEAD* a ese commit y modificándose el working copy.

--

**3. El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?**

No causó ningún conflicto porque *master* no está en la
misma línea que *styled*.

--

**4. El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?**

Causó conflicto porque *styled* y *htmlify* están en la misma línea en dos ramas diferentes.

--

**5. El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?**

No causó conflicto porque *styled* no estaba en la misma línea que *master*.

--

**6. ¿Qué comando o comandos utilizaste en el paso 25?**

`git graph` 

--

**7. El merge del paso 26, ¿Podría ser fast-forward? ¿Por qué?**

No podría ser fast-forward, porque al haber absorbido *master* a *styled*, *master* pasó a situarse a la misma altura que *styled*, es decir, bastante más arriba de su raíz y como *title* se situó donde la raíz de *master*, pues 
al absorber *master* a *title* el merge fue no fast-forward.

--

**8. ¿Qué comando o comandos utilizaste en el paso 27?**

`git reset HEAD~1`

--

**9. ¿Qué comando o comandos utilizaste en el paso 28?**

`git checkout don-quijote.md`


--

**10. ¿Qué comando o comandos utilizaste en el paso 29?**

`git branch -d title`,`git branch -D title` 


--

**11. ¿Qué comando o comandos utilizaste en el paso 30?**
`git reset --hard  5a58e43`, `git branch title`, `git merge title`

--

**12. ¿Qué comando o comandos utilizaste en el paso 32?**
`git tag title`, `git reset --hard 03d6efb`, `git tag htmlify`, `git reset --hard eb45b0f`, `git tag styled`, `git reset --hard 3dd10da`


--
**13. ¿Qué comando o comandos utilizaste en el paso 33?**
`git reset --hard 5a58e43`


