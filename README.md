# AplicacionPruebaDeEJBs
Una aplicación de prueba con ejemplos de EJBs de sesión stateless y stateful. Tiene proyectos eclipse EAR, Web y EJB.
Los parámetros JNDI están hechos para ser ejecutado en un servidor de aplicaciones JBoss.

Hay dos ejemplos de EJBs de sesión, uno de tipo Stateless (CalculatorBean) y el otro de tipo Stateful (ShoppingCartBean). 

Se les llama por JNDI. En el caso del CalculatorBean se comenta dicha llamada y se hace por INYECCIÓN DE DEPENDENCIAS. También tiene el ejemplo PROGRAMACIÓN ORIENTADA A ASPECTOS (AOP), utilizando el interceptor Logueador.class respecto al método add:   @Interceptors(Logueador.class)

Al apuntar la variable "CalculatorRemote calculator" a un proxy que a su vez llama al CalculatorBean, se pueden hacer este tipo de cosas.


Links manuales sencillos con ejemplos:
  http://www.arquitecturajava.com/introduccion-a-ejb-3-1-i/
  http://www.tutorialspoint.com/ejb/
