# RETOS
## REALIZAR LOS SIGUIENTES RETOS CON SU ALGORITMO Y DIAGRAMA DE FLUJO CORRESPONDIENTE CADA UNO 

# * Programa que pida un número y diga si es positivo o negativo


inicio

declarar(numero)int

mostrar("ingresa el número")

asignar(numero)

si numero >0 entonces

mostrar(" El número es positivo ")

sino

mostrar(" El número es negativo ") 

finsi

fin 



![dagar nume negativco posit](https://user-images.githubusercontent.com/104279978/167670994-dfba57bc-fc96-486b-8e11-304a03265b43.png)











# * Programa que solicite se ingrese una letra y sólo permita introducir los caracteres s y n.


inicio

declarar(letra)char

mostrar(" ingrese una letra ")

asignar(letra)

si letra=s || letra=n entonces

mostrar(" introdujo una letra permitida ")

sino

mostrar(" introdujo un caracter erróneo ") 

finsi

fin 



![letraperimitida sn](https://user-images.githubusercontent.com/104279978/167671566-4fc1d79e-cdcc-4085-937b-a272bef0d23b.png)







# * Un programa que pida una letra y detecte si es una vocal. 


Inicio

declarar(letra)char

mostrar( " Ingrese una letra ")

asignar(letra)

si letra=a || letra=e || letra=i || letra=o || letra=u  entonces

mostrar(" La letra que introdujo es una vocal")

sino

mostrar(" La letra es una consonante")

finsi

Fin



![diagrama flujop vocal ](https://user-images.githubusercontent.com/104279978/167669967-500bb503-8c44-43a1-940e-d304a7ea23f7.png)












# * Programa que pida 3 números y los muestre en pantalla de menor a mayor.  


Inicio

declarar(n1,n2,n3)int

mostrar ("ingresa el primer número")

asignar(n1)

mostrar ("ingresa el segundo número")

asignar(n2)

mostrar ("ingresa el tercer número")

asignar(n3)


Si n1<n2 & n1<n3 Entonces
                 
Si n2<n3 Entonces

mostrar(" El orden de los nùmeros es: ",n1," / ",n2," / ",n3)

SiNo

mostrar(" El orden de los nùmeros es: ",n1," / ",n3," / ",n2)

Fin Si

SiNo

Si  n2<n1 & n2<n3 Entonces
                  
Si n1<n3 Entonces

mostrar(" El orden de los nùmeros es: ",n2," / ",n1," / ",n3)

SiNo

mostrar(" El orden de los nùmeros es: ",n2," / ",n3," / ",n1)

Fin Si

SiNo

Si n3<n1 & n3<n2 Entonces
                 
Si n1<n2 Entonces

mostrar(" El orden de los nùmeros es ",n3," / ",n1," / ",n2)

SiNo

mostrar(" El orden de los nùmeros es ",n3," / ",n2," / ",n1)

Fin Si

SiNo

Si n1=n2 o n2=n3 o n1=n3 Entonces

mostrar(" ingresó números idénticos "

SiNo

//

Fin Si

Fin Si

Fin Si

Fin Si

fin
	
  








# * De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.









# * De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.







# * Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.







