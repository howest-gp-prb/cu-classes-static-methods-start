# Voorbeeld van een klasse met uitsluitend statische methoden
  
Haal deze repo binnen.  
In de solution zit momenteel 1 WPF project.  
In XAML werden alle controls reeds aangemaakt alsook de 3 eventhandlers van de button.  
De bedoeling is dat je een Class Library gaat aanmaken met daarin 1 klasse : **Geometry** 
  
In deze klasse maak je onderstaande 6 statische methoden aan :   
•	double CircleCircumference(double radius)   // omtrek cirkel (straal)  
•	double CircleArea (double radius)    // oppervlakte cirkel (straal)  
•	double SquareCircumference(double side)   // omtrek vierkant (zijde)  
•	double SquareArea(double side)    // oppervlakte vierkant (zijde)  
•	double RectangleCircumference (double height, double width)   // omtrek rechthoek (hoogte, breedte)  
•	double RectangleArea(double height, double width)   // oppervlakte rechthoek (hoogte, breedte)  
 
Implementeer vervolgens deze methoden in je WPF event handlers.  

> omtrek cirkel = 2 * straal * Pi  
> oppervlakte cirkel = straal * straal * Pi  
> omtrek vierkant = zijde * 4  
> oppervlakte vierkant = zijde * zijde  
> omtrek rechthoek = (hoogte + breedte) * 2  
> oppervlakte rechthoek = hoogte * breedte  
> pi kan je opvragen via Math.Pi of voer je zelf in (als constante) : 3.1415926535897931  
