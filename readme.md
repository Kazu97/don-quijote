

## - ¿Qué comando utilizaste en el paso 11? ¿Por qué?
` $ git reset --hard HEAD~1`

He reseteado el Commit con este comando para que afectase también a Working Copy.

## - ¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
`$ git reflog` 
	`$ git reset ("tag del estado anterior")`
		`($ git checkout -- *.md)`
Primero he desplegado una lista con todos los estados y sus Tags, he utilizado el tag junto a reset para llegar hasta donde deseaba y por último he vaciado la working copy para dejarlo en su estado inicial.
		


## - El merge del paso 13, ¿Causó algún conflicto? ¿Por qué?

No., la rama master esta detrás de la Styled en Commits.

## - El merge del paso 19, ¿Causó algún conflicto? ¿Por qué?

Si, htmlify y styled estaban hechas a partir de Master.

## - El merge del paso 21, ¿Causó algún conflicto? ¿Por qué?

No, porque master estaba detrás de Commits.

## - ¿Qué comando o comandos utilizaste en el paso 25?

`git log --graph`

## - El merge del paso 26, ¿Podría ser fast forward? ¿Por qué?

No podía porque tendría un conflicto al estar title encima de master.

## - ¿Qué comando o comandos utilizaste en el paso 27?
`$ git reset HEAD~1`

## - ¿Qué comando o comandos utilizaste en el paso 28?
`$ git checkout -- *.md`