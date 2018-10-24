## MOOCademy ##
<hr/>

> 2.1 Tu dois créer une plateforme d'apprentissage en ligne. Il y a plein de cours. Chaque cours a un titre et une description. Enfin, chaque cours a plusieurs leçons, qui ont un titre et un body

<hr/>

## De la reflection sur l'architecture aux dernières erreurs rencontrées:  

* 2 tableaux répartis comme suis/  

L tab **course** :   
----L champs :  
--------L id (integer primary key autoincrement)  
--------L title (string)  
--------L description (text)  
  
L tab **lesson**:  
----L champs :  
--------L id (integer primary key autoincrement)  
--------L cours_id (belongs_to user: index)   
--------L title (string)  
--------L body (text)  
  
* chaque cours a plusieurs le lecons associées, mais chaque lecons n'a qu'un seul cours en reference.