Buenas tardes. En esta carpeta encontrarán todos mis intentos de corrida del workflow gerencial. 
Realmente el primer cambio importante fue la realización de la Bayesiana robusta, realizando la BO con 5 semillas y promediando resultados. 
Claramente esto tiene un alto costo computacional, por lo que cada corrida duró aproximadamente 18hs. Por supouesto, a las 12hs se corta el runtime, lo que debia hacer es reiniciarlo manualmente y que siga en la parte inteligente de la BO. 

Intenté aplicar un par de modificaciones pero no terminaba subiendo la ganancia media, por lo menos no como la esperada. El submit elegido es del worflow llamado: 610_WorkFlow_01_gerencial_Modificado4.ipynb. 
En ese workflow que decidí hacer el submit, tiene las 5 semillas promediadas y optimiza la BO 4 hiperparametros llegando a 40 iteraciones. En la modificación5 que subí, implementé un par de "mejoras" pero no se vió reflejado en la ganancia de Kaggle, por ellos decidí volver al modificado4.

No hay muchas instrucciones para correr el workflow, más alla que correr todas sus partes. El corte elegido fue el "900", que efectivamente fue el que mayor ganancia me mostró. 

Encuentro quizá cierta preocupación ya que veo compañeros tocando los 5000 en kaggle y no estuve ni cerca, corriendo días y días los workflow. Pero bueno, ya no queda tiempo y debo presentar esta ganancia como la mejor. 

Por las dudas repitiendo nuevamente, el submit elegido corresponde al workflow: 610_WorkFlow_01_gerencial_Modificado4.ipynb
