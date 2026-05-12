Este repositorio contiene 3 ejercicios practicos:
1. Sistema academico de documentos
2. Sistema bancario de pagos
3. sistema de roles empresariales

- Algunas tecnologias utilizadas
1. Java
2. IntelliJ IDEA
3. Interfaces
4. Scanner
5. Switch

A continuacion empezamos con los Ejercicios
## Tarea 1 : SISTEMA ACADEMICO DE DOCUMENTOS
# Descripción
Este sistema nos va a permitir imprimir diferentes tipos de documentos academicos mediante una unica interfaz común
# Interfaz Utilizada
interface imprimible{void imprimir();}
# Clases utilizadas
1. Certificados
2. ActaNotas
3. HorarioAcademico
# Funcionalidades
1. Se implemento las interfaces a las clases
2. Se utilizo el @Override para sobreescribir el metodo declarada en la interfaz
3. Utilizacion de encapsulamiento con atributos private
4. Se imprimio diferentes documentos en el main utilizando el polimorfismo

## Tarea 2: SISTEMA BANCARIO DE PAGOS
# Descripción
Este sistema debe permitir simular metodos de pagos utilizados por los bancos 
# Interfaz utilizada
interface pagable{void procesarPago(double monto)}
# Clases utilizadas
1. PagoEfectivo
2. PagoTarjeta
3. Transferencia
# Funcionalidades 
1. Se implemento la interfaz en cada una de las clases 
2. Se validaron los montos dentro de el metodo declarado en la interfaz
3. Se calculó las comisiones tanto en la clase PagoTrjeta como en la clase Transferencia
4. Se utilizo el Polimorfismo en el main

## Tarea 3: SISTEMA DE ROLES EMPRESARIALES
# Descripción
Este sistema nos permite administrar diferentes roles empresariales con permisos especificos mediante interfaces 
# Interfaces utilizadas 
1. interface Autenticable { boolean iniciarSesion(String usuario,String clave)}
2. interface Reportable { void generarReporte()}
3. interface Gestionable { void gestionarDatos()}
# Clases utilizadas
1. Cajero
2. Administrador
3. Supervisor
# Funcionalidades
1. Se implemento la interfaz en cada una de las clases
2. Validacion del usuario y clave en cada clase utilizando la interfaz inicioSesion
3. Se hizo la generacion de reportes y gestion de datos
4. Se implemento un menu interactivo con switch en el main
5. Por ultimo se utilizo el uso del Scanner para que el usuario ingrese por teclado

# Conceptos aplicados
- Interfaces
- Encapsulamiento
- Polimorfismo
- Validaciones
- Sobreescritura de metodos(@Override)
