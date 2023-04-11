El primer error esta en la linea 94
el cual se corrige escribiendo de forma correcta el addEventListener

El segundo error esta en la linea 86
la solucion es que le falta un punto en el query selector el cual debe ir asi
linea 57 const lowOrHi = document.querySelector(".lowOrHi");
y en la linea 84 corregirla y dejarla de esta manera 
lowOrHi.textContent = "El número es mayor!";
al igual que en la linea 86
lowOrHi.textContent = "El número es menor!";

Luego en la linea 52 cambiar el 10 a 100 para que sean numeros a leatorios del 1 al 100
let randomNumber = Math.random() * 100;

Luego a los if y los else if a partir de la linea 67 solo dejar dos signos =

Luego en la linea 55 en la variable ATTEMPS asignarle 10 ya que se utilizaran 10 intentos

Luego convertir el numero aleatorio a number de la siguiente manera
let randomNumberD = Math.random() * 100;
let randomNumber = Number(randomNumberD.toFixed(0));

Luego en la linea 104 corregir evento listener la e minuscula pasarla a E mayuscula
resetButton.addEventListener("click", resetGame);

Luego el if de la linea 73 cambiar el texto !!!Pérdistes!!! por Felicitaciones! adivinaste el número! y el color a green

Luego en el else de la linea 82 cambiar el color a black

Luego el else if de la linea 78 cambiar el texto a !!!Pérdistes!!!

Luego eliminar la linea 123
randomNumber = Math.floor(Math.random()) + 1;

Y eso seria todo, Gracias!
