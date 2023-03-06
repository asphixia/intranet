#Dokumentation
Dette er min egen dokukmentation af Java Webstack. 
Vi skal lave et intranet og vil bruge denne dokumentation til 
bedre at kunne huske hvad vi lavede.

## Sådam start af et nyt webproject

1. opret ny project i IntelliJ
2. Vælg javaEE i projectskabelon
3. Javan + Maven
4. Servlet dependecies
 
## Arkitektur

Vi anvender en slags MVC-pattern.

-M(odel) - Entiteter of hjælpe- metoder og klasser. Business-logic
-V(iew) - JSP og frontend (css, bootstrap mm)
-C(ontroller) - Servlets

Husk! Ingen kommunikation mellem Model og View. Gå altid 
igennem Controlleren

