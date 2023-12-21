# Trabajo Practico Nº2 de Métodos Numéricos

## 📚 Enunciado

 1. Considerar la función : $$f(x) = 2x^3 - 3x - 4$$
	a) Graficar la función.  
	b) ¿Se puede usar bisección para hallar una aproximación a la raíz que presenta en (1,2)? Encuentre el número de iteraciones que se requieren para lograr una exactitud de 0.001 en la solución. Realice las iteraciones.  
	c) Utilice el método de Regula Falsi y compare los resultados.  
	d) Implemente en Python los dos métodos  

2. Dada la función $$f(x) = x^3 - 2x^2 + x - 3$$

	a) Grafique la función.  
	b) Utilice el método de Newton para encontrar una raíz de la misma en el intervalo [1,3], con una precisión de por lo menos 3 decimales. Comience a iterar con x = 3.  
	c) Utilice el método de la Secante, para encontrar la misma raíz, con la misma precisión.  
	d) Implemente en Python y concluya.  

3. La siguiente función tiene una raíz en x = 0.6180339. $$f(x) = x^2 + x - 1$$   
	
	a) Calcular una función de iteración g1(x) que permita estimar esta raíz. Grafique.  
	b) La función de iteración g2 converge a la raíz para x0=1. ¿Cuántas iteraciones del método de punto fijo se requieren para obtener la raíz correcta hasta 3 dígitos? Calcular los errores en cada iteración. $$g_2(x) = \frac{1}{x+1}$$
	c) Si usamos aceleración de Aitken, ¿cuántas iteraciones se requieren? Calcular los errores cometidos.  

4. La siguiente ecuación tiene dos raíces, en x = -1 y en x = 3. $$x^2 - 2x - 3 = 0$$
	a) Grafique la función en el intervalo [-4 ,4]  
	b) Se proponen las siguiente funciones de iteración:  
$$g_1(x) = \sqrt{2x+3}$$
$$g_2(x) = \frac{x^2 - 3}{2}$$
$$g_3(x) = \frac{3}{x-2}$$

Implemente el método de Punto Fijo para aproximar las raíces de f(x) con cada una de las funciones anteriores.  

Utilice los siguientes valores iniciales:  

i) -4  
ii) 3.5  
iii) 0   
iv) -0.99  
  
Grafique en una misma gráfica cada función g(x), f(x) y la primera bisectriz. Concluya.  
## Construidos con 🛠️

- [Google Colab](https://colab.research.google.com/?hl=es) - Plataforma en línea que proporciona un entorno de cuaderno Jupyter con recursos de cómputo gratuitos, facilitando el desarrollo de programas en Python y la ejecución de código en la nube.

## 👨‍💻 Autor

- Luis Medina Raed