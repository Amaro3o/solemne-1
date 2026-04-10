# solemne-1  
## proceso  
para este trabajo utilize como referencia al artista vasili kandinsky  
![referencia](https://cms.guggenheim-bilbao.eus/uploads/2012/05/2002-Kandinsky-en-su-contexto-1024x706.jpg)  
tomé las figuras geometricas que estan presentes dentro de su obra para crear mi propia composición, agregando tambien colores azul, rosado, verde y rojo  

para comenzar aplique una grilla de 50 en 50 dentro del lienzo de 500x500 para poder ubicar las figuras \(imagen 1)  
luego comence a ubicar figuras en el plano \(imagen 2)  
finalmente obteniendo la pieza final \(imagen 3)  

## problemas en el proceso  
lo que mas me costo fue escalar el tamaño de mi dibujo original al lienzo digital teniendo que calcular la equivalencia de los valores y tamaños de algunas figuras, sobretodo las que no tenian una medida exacta es decir terminada en 0, asi mismo colocar las figuras segun x,y tambien me costo pero de menor forma  

## codigo comentado  
* stroke(170, 5, 255); // da color al trazo
* //line(0, 0, 0, 500); //crea linea de punto x1,y1 a x2,y2
* createCanvas(500, 500); //crea el canvas sobre el que se va a trabajar
* background(255, 255, 255); //da color al canvas
* angleMode(DEGREES); //activa angulos para crear elipses
* stroke(0, 0, 0); // da el color negro al trazo
* fill(207, 255, 102); //rellena figuras de un color verde
* circle(280, 450, 40); //crea un circulo en x,y,diametro
* fill(252, 157, 215); //rellena figuras de color rosado
* fill(214, 49, 49); //rellena figuras de color rojo
* triangle(380, 240, 380, 400, 300, 320); //crea un triangulo en x1,y1,x2,y2,x3,y3
* arc(140, 240, 180, 180, 180, 0, CHORD); //crea un arco en x,y,w,h,start,stop, con una altura y anchura predeterminada y un angúlo
* square(320, 140, 60); //crea un cuadrado en x,y,lado
* rect(420, 220, 40, 60); //crea un rectangulo en x,y,ancho,alto
* quad(20, 420, 160, 280, 220, 340, 80, 480); //crea un cuadrilatero en x1,y1,x2,y2,x3,y,x4,y4
* strokeCap(SQUARE); //define forma de la linea o borde
  
