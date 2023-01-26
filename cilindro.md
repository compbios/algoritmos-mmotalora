Algoritmo calc_volyarea
	Escribir "Escribe el valor del radio del cilindro en cm"
	Leer r
	Escribir "Escribe el valor de la altura del cilindro cm"
	Leer h
	areacirc <- (3.1416*r^2)
	arearect <- (3.1416*(2*r)*h)
	areacil <- (2*(areacirc)+arearect)
	vol <- 3.1416*(r^2)*h
	Escribir "El área de la superficie del cilindro en cm2 es: ", areacil
	Escribir "El volumen del cilindro en cm3 es: ", vol
	
FinAlgoritmo
