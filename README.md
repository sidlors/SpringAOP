# SpringAOP


Spring AOP (programación orientada a aspectos) se utiliza para modularizar servicios "transversales". de forma simple diriamos que es un componente diseñado para interceptar algunos procesos, por ejemplo, cuando un método es ejecutado, Spring AOP puede auditar el método de ejecución y añadir funcionalidad extra antes y/o después de la ejecución del método. 

En Spring AOP, 4 "momentos" son auditables: 

1. Antes del susceso (Ejecutar "algo" antes de la ejecución del método)
2. Después del retorno (Ejecutar algo después del retorno del resultado de algun método)
3. Después del arrojo de una excepcion (Ejecutar algo luego de una exception del método) 
4. Alrededor del susceso  (combinar los tres suscesos anteriormente.)

Siguiendo el ejemplo le mostrará cómo funciona 
