# 1.3. Luces

Las fuentes de iluminación son las mismas que se tienen en todos los software 3D, bien sea software de edición como maya, motores gráficos como el caso de UDK, Unity o bibliotecas como podría ser OGRE, OpenGL. Los tipos de luces son por tanto:
•	Spot: es una luz de linterna, permite indicar la distancia de iluminación y el ángulo.
•	Directional: es la luz solar, se indica una dirección y una intensidad.
•	Point: el equivalente a una bombilla, se indica intensidad y rango.
•	Area: anteriormente no se puedía usar en la versión gratuita ahora parece que sí. Es iluminación sobre una superficie como si fuera un panel.
•	Reflection probe: tipo de luz nueva en unity 5. http://docs.unity3d.com/es/current/Manual/class-ReflectionProbe.html.
En caso de manejar luces la gestión de las sombras se puede hacer en tiempo real o crear un mapeo de luces previo usando lightmapping para los objetos estáticos de la escena.
