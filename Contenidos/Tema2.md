![Image text](/Imagenes/BannerTema2.png)
# 📚 Conceptos fundamentales de Azure
## 🔎 Objetivo
- Ventajas y consideraciones de los servicios en la nube.
- Diferencias entre categorias de servicios en la nube.
- Describir las diferencias que hay entre los tipos de informática en la nube.
## Tabla de contenidos
1. [Modelo basado en el consumo](#modelo-basado-en-el-consumo)
2. [Gastos de capital](#gastos-de-capital)
3. [Gastos operativos](#gastos-operativos)
3. [Aptitudes](#aptitudes)
3. [Limitaciones de la plataforma](#limitaciones-de-la-plataforma)
3. [Limitaciones de software](#limitaciones-de-software)

## Conceptos
### Modelo basado en el consumo
Significa que los usuarios finales solo pagan por los recursos que usan. Lo que usan es lo que pagan.

Los modelos basados en el consumo aportan muchas ventajas, por ejemplo:
-Sin costes por adelantado.
-No es necesario comprar ni administrar infraestructuras costosas que es posible que los usuarios no aprovechen del todo.
-Se puede pagar para obtener recursos adicionales cuando se necesiten.
-Se puede dejar de pagar por los recursos que ya no se necesiten.
***
### Gastos de capital
Los gastos de capital (CapEx) hacen referencia a la inversión previa de dinero en infraestructura física, que se podrá deducir a lo largo del tiempo. El costo previo de CapEx tiene un valor que disminuye con el tiempo. Un ejemplo de esto es la compra de equipos.
***
### Gastos operativos
Los gastos operativos (OpEx) son dinero que se invierte en servicios o productos y se factura al instante. Este gasto se puede deducir el mismo año que se produce. No hay ningún costo previo, ya que se paga por un servicio o producto a medida que se usa.
***
### Aptitudes
No se requieren conocimientos técnicos avanzados para implementar y usar una nube pública u obtener las ventajas que esta ofrece. Las organizaciones pueden utilizar las aptitudes y la experiencia del proveedor de nube para asegurarse de que las cargas de trabajo sean seguras, estén protegidas y tengan alta disponibilidad.

Junto con el hospedaje de aplicaciones, Azure proporciona ofertas de servicio que pueden mejorar la funcionalidad. Azure también puede mejorar el desarrollo y el mantenimiento de las aplicaciones, tanto en la nube como en el entorno local.
  - Instrumentación. Generación de los datos sin procesar, desde registros de aplicaciones, registros de servidor web, diagnósticos integrados en la plataforma de Azure, y otro     orígenes.
  - Recopilación y almacenamiento. Consolidar los datos en un solo lugar.
  - Análisis y diagnóstico. Para solucionar problemas y ver el estado general.
  - Visualización y alertas. Usar datos de telemetría para detectar tendencias o alertar al equipo de operaciones.
  - Auténtico escalado en la nube. Las aplicaciones pueden diseñarse para ejecutarse en cientos o incluso miles de nodos, alcanzando escalados que no son posibles en un único       nodo.
  - El escalado horizontal es elástico. Puede agregar más instancias si aumenta la carga, o quitarlas durante períodos más tranquilos.
***
### Limitaciones de la plataforma
Es posible que en las plataformas en la nube haya una serie de limitaciones que pueden afectar al modo en el que una aplicación se ejecuta.

- Limitaciones de la pataforma:
   1. Las máquinas virtuales deben estar en un host dedicado o bien crearse con un tamaño de máquina virtual aislada.
   2. Si se declara una programación de mantenimiento, debe tener un mínimo de 2 horas.
   3. Después de 35 días, se aplicará automáticamente una actualización.
   4. El usuario debe tener acceso de colaborador del recurso.
***
### Limitaciones de software
Es posible que en las aplicaciones de software haya una serie de limitaciones que pueden afectar al modo en el que los usuarios trabajan. Como está usando el software tal cual, no tiene un control directo de las características. 
  - Se recomienda implementar un máximo de 5000 VM por suscripción de Azure y por región. Esta recomendación se aplica a los grupos de hosts personales y agrupados basados en       Windows 10 Enterprise y Windows 10 Enterprise para sesiones múltiples. 
  - En el caso de las herramientas de escalado de host de sesión automatizadas, los límites son unas 1200 máquinas virtuales por suscripción de Azure por región, porque la           interacción del estado de la máquina virtual consume más recursos.
  - Para administrar entornos empresariales con más de 5000 VM por suscripción de Azure en la misma región, puede crear varias suscripciones de Azure en una arquitectura tipo       hub-and-spoke, y conectarlas mediante el emparejamiento de redes virtuales, como en la arquitectura de ejemplo anterior. También puede implementar las VM en otra región de       la misma suscripción para aumentar el número de VM.
  - Las limitaciones de la API de la suscripción de Azure Resource Manager (ARM) no permiten más de 600 reinicios de máquina virtual de Azure por hora mediante Azure Portal. 
  - Actualmente, puede implementar 399 máquinas virtuales por implementación de plantilla de ARM de Windows Virtual Desktop sin conjuntos de disponibilidad o 200 máquinas           virtuales por conjunto de disponibilidad.
  - Los prefijos de nombre de host de sesión de máquina virtual de Azure no pueden superar los 11 caracteres, debido a la asignación automática de nombres de instancia y al        límite de NetBIOS de 15 caracteres por cuenta de equipo.
***
