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

mostrar(" ingresó números idénticos ")

SiNo

//

Fin Si

Fin Si

Fin Si

Fin Si

fin

	
![diagrama de flujo ordenar 3 números  menor a mayor drawio](https://user-images.githubusercontent.com/104279978/168390227-3893da0b-2313-43e1-825d-46d18cb7724b.png)
  


![diagrama ordn 3 num menor a may](https://user-images.githubusercontent.com/104279978/168389738-dc6bd788-48a2-4328-a91b-890972354b48.png)







# * De un programa que pida un número del 1 al 12 y diga el nombre del mes correspondiente.

Inicio

declarar(num)int

mostrar ("ingresa un número ")

asignar(num)

Si num<=0 & num>12 Entonces

		mostrar(" Ingresó un número incorrecto")
		
	SiNo
		Si num>0 y numnum<=12 Entonces
		
			Si num=1 Entonces
			
				mostrar("   ENERO  es el mes correspondiente a su número ")
				
			SiNo
			
				Si num=2 Entonces
				
				mostrar("  FEBRERO  es el  mes correspondiente a su número ")
				
				SiNo
				
					Si  num=3 Entonces
					
			         mostrar("   MARZO  es el  mes correspondiente a su número ")
				 
					SiNo
					
						Si num=4 Entonces
						
		               mostrar("   ABRIL  es el  mes correspondiente a su número ")
			       
						SiNo
						
				Si num=5 Entonces
				
			mostrar("   MAYO  es el  mes correspondiente a su número ")
			
							SiNo
							
				Si num=6 Entonces
				
		     mostrar("   JUNIO  es el  mes correspondiente a su número ")
		     
						      SiNo
						      
				Si num=7 Entonces
				
		    mostrar("   JULIO  es el  mes correspondiente a su número ")
		    
							SiNo
							
				Si num=8 Entonces
				
		   mostrar("   AGOSTO  es el  mes correspondiente a su número ")
		   
			       SiNo
			       
			      Si num=9 Entonces
												mostrar("   SEPTIEMBRE  es el  mes correspondiente a su número ")
												
		          SiNo
			  
			Si num=10 Entonces
												mostrar("   OCTUBRE  es el  mes correspondiente a su número ")
												SiNo
													Si num=11 Entonces
														mostrar("   NOVIEMBRE  es el  mes correspondiente a su número ")
													SiNo
														Si num=12 Entonces
															mostrar("  DICIEMBRE  es el  mes correspondiente a su número ")
														SiNo
															mostrar(" Ingresó un número incorrecto")
														Fin Si
													Fin Si
												Fin Si
											Fin Si
											
										Fin Si
										
									Fin Si
									
								Fin Si
								
							Fin Si
							
						Fin Si
						
					Fin Si
					
				Fin Si
				
			Fin Si
			
		SiNo
		
			mostrar(" Ingresó un número incorrecto")
			
		Fin Si
		
	Fin Si
	



Fin





![diagrama mes a número corres](https://user-images.githubusercontent.com/104279978/168396067-5a1614ef-d05f-43cf-b5e6-70d79df422e5.png)




# * De un programa que permita al usuario elegir un candidato por el cual votar. Las posibilidades son: candidato A por el partido rojo, candidato B por el partido verde, candidato C por el partido azul. Según el candidato elegido (A, B ó C) se le debe imprimir el mensaje “Usted ha votado por el partido [color que corresponda al candidato elegido]”. Si el usuario ingresa una opción que no corresponde a ninguno de los candidatos disponibles, indicar “Opción errónea”.



Inicio

declarar(candidato)char
	
	mostrar ("  Usted solo puede votar por los siguientes candidatos :  ")
	
	mostrar (" - Candidato A del partido rojo ")
	
        mostrar (" - Candidato B  del partido verde ")
	
	
	mostrar (" - Candidato C  del partido azul ")
	

	mostrar ("       Ingrese su voto ")
	
	asignar(candidato)
	
	Si candidato="A" o candidato= "a"  Entonces
	
		mostrar ("   Usted ha votado por el partido rojo ")
		
	SiNo
		Si candidato="B" o candidato="b" Entonces
		
			mostrar ("  Usted ha votado por el partido verde ")
			
		SiNo
			Si candidato="C" o candidato="c" Entonces
			
				mostrar ("    Usted ha votado por el partido azul ")
				
			SiNo
			
Si candidato<>"a" o candidato<>"a" o candidato<>"B" o candidato<>"b" o candidato<>"C" o

candidato<>"C"  Entonces
			
					mostrar ("     Ingresó una opción errónea en el voto")
					
				SiNo
				
					//
					
				Fin Si
				
			Fin Si
			
		Fin Si
		
	Fin Si
	
Fin







# * Para un programa que almacene la cadena de caracteres para una contraseña y email, pregunte al usuario por la contraseña y email e imprima por pantalla si la contraseña y el email introducidos por el usuario coincide con los guardadados en las variables.







