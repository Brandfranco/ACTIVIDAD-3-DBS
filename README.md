# ACTIVIDAD-3-DBS
Conceptos y comandos básicos de la replicación en bases de datos NoSQL
REPLICACION EN BD

La replicación de datos es cuando los mismos datos se almacenan intencionalmente en más de un sitio o servidor. Hay varias razones por las que las empresas replican datos. Permite que los datos estén disponibles sin problemas en el caso de un tiempo de inactividad del servidor o mucho tráfico hacia el servidor. Los datos se vuelven accesibles para los usuarios de manera constante sin interferir ni ralentizar el acceso de otros usuarios. Para las aplicaciones en la nube, la replicación de datos le permite acceder a una copia de los datos en una base de datos local con un rendimiento mucho mayor que acceder a los datos a través de la API de la aplicación en la nube, que es especialmente útil para análisis y la ciencia de datos. La replicación de datos también puede permitirle evitar los límites de transacción de la API y la aceleración que tienen algunas aplicaciones en la nube.
•	Aumento de la fiabilidad: mediante la replicación de base de datos a través de múltiples servidores, te aseguras que los datos van a estar disponibles incluso en el caso de que una de las máquinas tenga un fallo grave de hardware. El sistema distribuido de gestión de bases de datos debe ser capaz de enrutar a los usuarios afectados a otro de los nodos disponibles.
•	Mejora en el rendimiento: al estar los datos distribuidos en diferentes servidores, los múltiples accesos no saturan los servidores. Esto es importante sobre todo en el caso de aplicaciones que pueden tener miles o cientos de miles de peticiones simultáneas. El rendimiento de las aplicaciones aumenta notablemente.
•	Mejora en la seguridad de los datos: en un sistema transaccional tradicional, todas las actualizaciones de una base de datos se guardan en un mismo disco. La seguridad de tus datos queda entonces en manos de la estrategia de copias de seguridad que tengas implementada en ese servidor. Con la replicación de base de datos aumentas la seguridad de los datos ya que las actualizaciones están siendo escritas en varios servidores. Es decir, varios discos, varias fuentes de alimentación, CPU’s, etc. son utilizadas para asegurar que tus datos estarán a salvo en algunos servidores, aunque pueda ocurrir un desastre en otros.

PROCESO

Requerimientos no funcionales

•	La base de datos debe permitir realizar todas las operaciones de consulta necesarias.
•	La base de datos debe estar disponible 24/7
•	Se debe garantizar la seguridad de la información.
•	Debe permitir el acceso de varios usuarios al mismo tiempo (concurrencia)
•	Se debe garantizar la fiabilidad de la información. 			
