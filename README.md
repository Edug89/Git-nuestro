# Práctica de Git y Git Hub Eduardo Martinez.

-¿Qué comando utilizastes en el paso 11? ¿Por qué?
El comando fué, **git reset --hard HEAD~1-**
Porque, nos indican que devemos echar para atrás con el commit y borrar dichos cambios.

-¿Qué comando o comandos utilizaste en el paso 12? ¿Por qué?
Los comandos que utilicé fueron **git reflog** para ver donde estaba el commit borrado y luego para 
ir hacia él **git reset <codigo de dicho comit>**

-El merge del paso 13,¿Causó algún conflicto? ¿Por qué?
No, generó ningún conflicto absorvió dichos commit con el merge ya que los 2 archivos no tenían 
cambios en el mismo lugar.

-El merge del paso 19,¿Causó algún conflicto? ¿Por qué?
Sí, porque habíamos modificado las mismas líneas del mismo archivo **git-nuestro.md** y generó el 
conflicto

-El merge del paso 21,¿Causó algún conflicto? ¿Por qué?
No, porque se trataba de un merge desde Main hasta la rama Styled, la absorbe sin problemas y no 
genera conflictos(Ya que el único archivo modificado es el de Styled)

-¿Qué comando o comandos utilizaste en el paso 25?
**git log --graph**

-El merge del paso 26,¿Podría ser fast forward? ¿Por qué?
No, ya que hemos forzado el merge ya que una rama esta bifurcada con la otra. Si hubieramos 
utilizado el merge normal daría error o algún conflicto.

-¿Qué comando o comandos utilizaste en el paso 27?
**git reset HEAD~1**

-¿Qué comando o comandos utilizaste en el paso 28?
**git restore**

-¿Qué comando o comandos utilizaste en el paso 29?
**git branch -D title**

-¿Qué comando o comandos utilizaste ne el paso 30?
Utilice primero **git reflog** para buscar el rastro del commit y luego **git reset** + **codigo 
del commit**

-¿Qué comando o comandos usaste en el paso 32?
Utilice el **git reflog** para mirar el rastro del commit y luego **git checkout** + **codigo del 
commit inicial**

-¿Qué comando o comandos usaste en el punto 33?
**git checkout main**
