# Proyecto: Sistema de Control de pedidos y clientes 

## Quien soy ?
- Tengo 53 años
- Trabajo para la industria automotriz en el departamento de IT Field Operations
- Estoy estudiando el 8vo tetramestre en TecMilenio On Line

## Descripcion del proyecto 
FASE I
- Es Un sistema el cual podra controlar los clientes y ventas de la empresa "Flautas la doña"
- Tendra un registro de los clientes
- Podra reportear listado de clientes
  
FASE II
- se podran registrar las ventas y manejo de las ordenes de ventas
- Podrar imprimir notas de venta y de pedidos

## Necesidad identificada 
- De acuerdo con la empresa se tiene la proyección de crecimiento del negocio a un año donde se prevé negociar con una línea de tiendas de conveniencia y de concretarse se pretende ir incrementado de forma mensual la incorporación del producto en cada una de las tiendas hasta llegar al total de 12 tiendas ,es aqui donde nace la necesidad de tener un mejor control de los clientes tanto de los actuales como de los nuevos, de la msma forma tener la visibilidad y control de sus pedidos, con la finalidad de dar un mejor servicio al cliente asi para entregar en tiempo y forma el producto requerido,se tiene el interés de poder generar reportes impresos de estas ventas para con ello generar las ordenes necesarias de elaboración y entrega a domicilio de los clientes. 

## Solucion
En la empresa Flautas la Doña se llevará a cabo la implantación del sistema para controlar la información de sus clientes y de sus ventas realiza. 
El proyecto estará dividido en dos fases es decir estará delimitado. El sistema será realizado en el lenguaje de programación Java en la plataforma de programación Intellij IDE 2023.3.2, contara con almacenamiento de los datos de forma local dado el presupuesto de inversión del cliente se reducirán algunos gastos ,posteriormente se buscaran los recursos para almacenar la base de datos en la nube , se pretende utilizar el almacenamiento en la nube de Microsoft Azure,en esta primera parte se estará trabajando con los requerimientos solicitados para el control y reporte de los clientes ,así mismo se integrara la parte de seguridad en la cual el usuario deberá de accesar al sistema mediante un usuario y contraseña  posteriormente se trabajara con la Fase 2 que refiere a los requerimientos del control de la órdenes de venta.
En el plan de desarrollo está incluido la capacitación en el uso del sistema para los usuarios finales , así mismo está implícito el mantenimiento y actualizaciones necesarias del sistema 
El sistema será del tipo TPS “sistemas de procesamiento de transacciones (TPS Transaction Processing System).”
Para la primera entrega al cliente (Fase I) El sistema permitirá realizar las siguientes funciones:

Fase I
•	El sistema contara con acceso seguro ya que deberá de tener un usuario y contraseña para poder accesar a él. 
•	Registrar altas, bajas y modificaciones de datos de sus clientes.
•	Los datos para registrar y almacenar serán nombre del cliente, dirección, teléfono y nombre de contacto.
•	Se podrán obtener reportes impresos de los datos del cliente.

Con estos resultados la propietaria de la empresa podrá tener la visión de sus clientes 


## Arquitectura
  
![image](https://github.com/Edward7110/EduardoRep/assets/157240969/8001a7dc-245c-4c1a-b214-cbcce07e9805)

## Tabla de contenidos
- [Requerimientos](https://github.com/Edward7110/EduardoRep/edit/Develop/README.md#requerimientos)
- [Instalacion](https://github.com/Edward7110/EduardoRep/edit/Develop/README.md#instalacion)
- [Configuracion]([https://github.com/Edward7110/EduardoRep/Develop/README.md#configuracion](https://github.com/Edward7110/EduardoRep/edit/Develop/README.md#configuracion))
- Uso
- Contribución
- Roadmap

### Requerimientos
- El sistema será realizado en el lenguaje de programación Java en la plataforma de programación Intellij IDE 2023.3.2,  , es necesario tener instaldo el kit de desarrollo de Java (JDK) la version de 64x "Java SE Development Kit versión 11" ,17.	Crea una cuenta en algún servicio de repositorios en línea ,por el momento no contendra alguna base de datos de SQL u otros ya que esta en fase de pruebas  para el harware se sugiere una porcesador I7 von 16 mb Ram , con un disco duro de preferencia de estado solido de 1 Tb de capacidad , para la parte de reporteos una impresora lazer M600 de HP 

### Instalacion
Parte 1. Java SE Development Kit versión 11
1.	Visita la página https://www.oracle.com/java/, y ubica la sección de descargas de Java.
2.	Descarga Java SE Development Kit en su versión más reciente compatible con el sistema operativo que utilices.
3.	Sigue las instrucciones de instalación de Java SE Development Kit según el sistema operativo que utilices.
4.	Configura las variables de entorno necesarias para el funcionamiento de Java SE Development Kit de acuerdo al método especificado para el sistema operativo que utilices.
5.	Ejecuta los comandos java y javac para verificar la instalación de Java SE Development Kit.
Parte 2. Entorno Integrado de Desarrollo
6.	Visita la página https://www.jetbrains.com/, y ubica la sección de descargas de IntelliJ IDEA.
7.	Descarga el IDE IntelliJ IDEA en su versión más reciente y compatible con el sistema operativo que utilices.
8.	Sigue las instrucciones de instalación de IntelliJ IDEA según el sistema operativo que utilices.
9.	Configura las variables de entorno de Java en IntelliJ IDEA, necesarias para el funcionamiento correcto del IDE.
10.	Crea un proyecto en IntelliJ IDEA y escribe el programa “HelloWorld.java”.


public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}


6.	Ejecuta el código para verificar la instalación de IntelliJ IDEA.
Parte 3
11.	Visita la página https://git-scm.com/, ubica la sección de descargas de Git.
12.	Descarga Git en su versión más reciente y compatible con el sistema operativo que utilices.
13.	Sigue las instrucciones de instalación de Git según el sistema operativo que utilices.
14.	Configura Git de acuerdo a las instrucciones adicionales según el sistema operativo.
15.	Visita la página http://jlord.us/git-it/
16.	Realiza cada uno de los ejercicios del tutorial.
17.	Crea una cuenta en algún servicio de repositorios en línea. Se recomienda https://github.com/, pero puedes optar por otras alternativas como https://bitbucket.org, https://about.gitlab.com/, entre otros.


### Configuración

### Instrucciones para la instalación y configuración de Java SE Development Kit versión 11

<img width="276" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/9324c5dd-1d1f-460a-a9f0-94d90fe6e5cb">

<img width="146" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/291447be-8550-442d-a638-12498a342f3a"> ![image](https://github.com/Edward7110/EduardoRep/assets/157240969/c19db2ce-900e-4fdd-9b0f-cc915b676c9e)

<img width="278" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/17153eac-c305-4432-9ceb-2ff94cb0314a">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/ac06f727-b16d-4905-9eec-2ae1f8a1d946)

<img width="303" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/e990f98d-71f2-4d1c-8ea8-e609af28912c">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/04799c69-9d88-4be1-b56d-ed81341aa65d)

<img width="303" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/07e4cbe8-8a72-4a9e-9416-259942630e5e">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/33c9d774-c447-4d6e-a3cf-fff2b6bfb081)

<img width="303" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/a361ae67-59c2-430e-acf8-d25c7d3829da">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/ca971f99-9468-4ada-b5d5-645127be813f)


### Instrucciones para la instalación y configuración de IntelliJ IDEA

<img width="482" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/fa90beb3-e9bc-44e6-b5b4-721dacbaabac">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/7733e6de-056a-4754-8c70-6fd014e29ffc)

<img width="146" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/d5cf25bc-1e73-46ca-adb2-09ace6098e08">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/b66ddecc-14b7-4c94-b137-5869ba8facf7)

<img width="180" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/232b03b7-ad09-40f0-9037-73dc3bda931c">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/d0961dc8-84ef-43b7-b0cb-cde55d67ed15)

<img width="257" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/b295fc6b-b81e-4d0a-b853-f808d93a04c6">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/18b6184e-a403-4775-9d0b-4ddc5bc87737)

<img width="257" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/288e121e-1172-45c0-acb8-f2f0122e5d9b">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/5be628f1-8d92-4561-94f2-2abb4ec5045f)


<img width="303" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/7468ab6b-adfe-46ee-81a2-e8f60cb4221e">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/10b65362-a9e7-4413-9f03-2f7980ffc088)

<img width="303" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/7e220e77-2121-4d1c-9a59-6b5fadd2460d">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/1e1379e9-0e2a-4cbb-8571-5f0818cf1a61)

<img width="303" alt="image" src="https://github.com/Edward7110/EduardoRep/assets/157240969/7b5941c4-002f-4018-82d3-d4b2c4430321">![image](https://github.com/Edward7110/EduardoRep/assets/157240969/718f5858-1b1f-4c8a-b788-a9ede151ebd0)

### Uso

1.	Abrir el sistema 
2.	Teclear usuario y contraseña
3.	Seleccionar una de las tres opciones 
4.	Si seleccionas opción 1 (Alta de información de los clientes)
5.	Se abre la pantalla de captura 
6.	Se genera en automático el ID del cliente
7.	Teclear nombre completo del Cliente
8.	Teclear la Direccion
9.	El sistema almacena los datos 
10.	Si seleccionas opción 2 (Baja del Cliente)
11.	Se abre la pantalla
12.	teclear ID del Cliente a dar de baja
13.	El sistema da de baja al cliente 
14.	Si seleccionas opción 3 (Modificar datos cliente)
15.	Se abre la pantalla de edicion de clientes 
16.	Teclear ID a modificar
17.	se introduce la informacion nueva
18.	se guardan los cambios 
19.	termina

### Contribución
si quieres contribuir puedes accesar a Github a la siguiente direccion:
Acceso a GitHub:
•	Edward7110/EduardoRep (github.com)
•	https://github.com/Edward7110/EduardoRep

el Proyecto cuenta con 3 Branches , develop como default, Master y Main

![image](https://github.com/Edward7110/EduardoRep/assets/157240969/d74928b8-e897-4da6-a290-45777ab1447c)

Issues: se crearon 18 Issues distribuidos en 4 Milestone de los cuales actualmente hay 13 tareas abiertas y 5 cerradas  

![image](https://github.com/Edward7110/EduardoRep/assets/157240969/2f8f0118-89e8-499f-aff7-9bdb6c337db5)

El proyecto cuenta con 4 Milestone que corresponden al proyecto general 
![image](https://github.com/Edward7110/EduardoRep/assets/157240969/5975a056-e496-4d44-89e9-ca09e38e3070)

Grafica de avances 

![image](https://github.com/Edward7110/EduardoRep/assets/157240969/7dbc4439-c4d7-4552-a544-386d1b776513)

### Roadmap
dado que es un fase I , en un futuro y con mas tiempo se estara trabajando en la Fase , esta fase debera de contener lo siguiente:

FASE II
- se podran registrar las ventas y manejo de las ordenes de ventas
- Podrar imprimir notas de venta y de pedidos































   
