#Escuela Colombiana de Ingeniería
Parte I. Ejercicio básico.

2. Para el proyecto suministrado, cree un nuevo archivo de configuración de Contextos para Spring, el cual, por convención, se llamará applicationContext.xml:

	![img](img/NetbeansSpringConf.png)

	![img](img/ResourcePath.png)


	* Se tendrá un bean llamado 'schecker' (spellChecker), el cual -por ahora- estará asociado a la clase SpanishSpellChecker.
	* Se tendrá un bean 'grammarChecker' asociado a la clase GrammarChecker.
	* El bean GrammarChecker tiene una propiedad 'spellChecker' (dado que tiene unos métodos getSpellChecker/setSpellChecker). En dicha propiedad se inyectará (cuando se construya una instancia de spellChecker) el bean 'schecker' definido anteriormente.



```java