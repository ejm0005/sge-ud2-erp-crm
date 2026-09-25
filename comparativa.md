# Comparativa.md
## Sección 1: Datos  
Nombre de usuario: ejm0005  
Empresa: 04 - Electrosur  
Palabra del día: Compañero  
## Sección 2: Licencias y modelos  
### Software libre vs Código abierto vs Propietario 
* __Software Libre:__ Este tipo de software permite ver, usar y cambiar el código, es promovido por la Free Software Fundation (FSF) y se centra principalmente en los derechos de los usuarios y garantizar las 4 libertades esenciales: Usar el programa con cualquier propósito, Estudiar el como funciona, Redistribuir copias de él y Mejorar el programa publicamente. Su principal enfoque es defender que el usuario deba tener el control absoluto sobre sus herramientas digitales.
  
* __Código abierto:__ Este tipo de software, al igual que el Libre, permite ver usar y cambiar el código fuente, pero a diferencia de este, el código abierto es más flexible ya que tolera restricciones que la Free Software Fundation considera inaceptables como por ejemplo mezclar código abierto con componentes propietarios. Su principal enfoque es la eficiencia técnica, la seguridad y la renovación mediante la compartición del código.
  
* __Propietario:__ En este tipo de software, el código fuente esta cuidadosamente guardado y pertenece a una empresa o individuo. Los derechos de uso son restrictivos mediante licencias de usuario final o EULAs y el usuario tiene prohibido modificar o distribuir el código. 

### ¿Por qué "libre" no es "gratuito"? 
Que un software sea libre no quiere decir que sea gratuito ya que el Software Libre como tal se centra en los derechos de los usuarios y no en el coste económico del programa. Esta confusión de libre=gratuito se originó debido a que la palabra "free" en ingles significa tanto "gratis" como "libre" en español
### Ediciones Community y Enterprise
* Las ediciones community estan orientadas a desarrolladores individuales, proyectos pequeños o entornos de prueba. La mayoría de ediciones community son gratuitas y reciben actualizaciones constantes con las últimas características disponibles. Su principal desventaja es que carecen de soporte técnico oficial, ya que este viene de foros o comunidades.

* Las ediciones enterprise son aquellas que están orientadas a corporaciones cuyo trabajo exige una estabilidad crítica. Son de pago, aunque dependiendo del programa, el pago es por el uso o por el soporte. Su principal ventaja es que ofrece acuerdos de nivel de servicio con tiempos de respuesta garantizados y actualizaciones de seguridad a largo plazo, junto con herramientas avanzadas de gestión, auditoría y alta disponibilidad. Su principal desventaja en comparación con las ediciones community es su elevado coste económico.  

## Sección 3: Fichas técnicas
### ERP Libre - ODOO Community
* __Licencia:__ ODOO Community utiliza una licencia de tipo GNU LGPLv3, la cual es completamente gratuita, libre de costes por usuario o aplicación y permite la modificación y redistribución del código.  

* __Versión vigente:__ 19.0.  

* __SGBDs Compatiles:__ Solo es compatible con PostgreSQL en sus versiones 13 a 17, siendo la 16 la más recomendada para estabilidad.  

* __Lenguaje del servidor:__ Python versión 3.10 o superior.  

* __Modalidad de despliegue:__ Esta edición de ODOO necesita de servidores propios o nubes contratadas a terceros como AWS o Google Cloud.  

* __Módulos principales incluidos:__ Ventas/CRM, Compras, Inventario, Fabricación, Facturación, Comercio Electrónico y Recursos humanos.  

* __Requisitos del Sistema:__ En cuanto a los requisitos en software, neesita Linux (Debian 12 o Ubuntu 22.04 LTS principalmente), dependencias de wkhtmltopdf (para generación de reportes en PDF), Node.js (para compilar recursos frontend)y librerías Python (Pillow, psycopg2, Babel y Werkzeug) y un servidor web de tipo Nginx o Apache. Por otro lado, los requisitos de hardware suelen variar según el volumen de usuarios concurrentes y el tamaño de la base de datos. Para un entorno de pruebas o desarrollo se requiere 1 CPU, 2GB RAM y 20GB HDD. Para un entorno de producción de entre 5-10 usuarios, se requieren 2 CPUs, 4GB RAM y 40GB SSD. Para un entorno de producción de entre 20-50 usuarios se requiere 4-6 CPUs, 8-16GB RAM y 100GB SSD.

### ERP Propietario - Oracle Fusion Cloud ERP  
* __Licencia:__ Oracle Fusion Cloud ERP utiliza una Suscripción Comercial de Tipo SaaS (Software como servicio), ofreciendo licencias por volumen de uusarios mensuales o mediante métricas por volumen de transacciones.

* __Versión vigente:__ Release 26C.

* __SGBDs Compatiles:__ Oracle Database

* __Lenguaje del servidor:__ Java, XML, HTML5 y BPEL (Lógica de negocio y procesos). C/C++ (Componentes críticos).

* __Modalidad de despliegue:__ Exclusivamente en la nube de Oracle Cloud Infraestructure.

* __Módulos principales incluidos:__ Oracle Financials Cloud (Finanzas), Oracle Procurement Cloud (Compras), Oracle Project Management (Recursos Humanos), Oracle Risk Management Cloud (Administración) y Oracle Supply Chain & Manufacturing (Almacén y Logística)

* __Requisitos del Sistema:__ Para usar este ERP, se requiere: Conexión a Internet estable de banda ancha, Navegadir Web moderno compatible (ej: Chrome, Firefox, Edge o Safari), uso de APIs REST/SOAP nativas y Certificados de seguridad emitidos por Autoridades de Certificación (CA) y aprobados por Oracle.

### CRM Libre: SuiteCRM
* __Licencia:__ SuiteCRM utiliza una licencia de tipo GNU Affero General Public License v3 (AGPLv3) que permite el uso gratuito y la modificación y distribución del código de forma libre.

* __Versión vigente:__ SuiteCRM 8.10.2 y SuiteCRM 7.15.2 (Rama de soporte extendido).

* __SGBDs Compatiles:__ MariaDB (versiones 10.6, 10.11, 11.4 y 11.8) y MySQL (Versiones 8.0 y 8.4).

* __Lenguaje del servidor:__ PHP.

* __Modalidad de despliegue:__ Soporta tanto instalación local/servidor propio como en la nube.

* __Módulos principales incluidos:__ Ventas, Marketing, Atención al cliente y Produtividad.

* __Requisitos del Sistema:__ SuiteCRM necesita servidores basados en Linux/Unix, Servidor web Apache 2.4 y navegadores web como Chrome (143+), Firefox (140+), Edge (143+) o Safari (26+).

### CRM Propietario: Zoho CRM
* __Licencia:__ Zoho CRM utiliza una licencia de tipo SaaS (Software como servicio) por suscripción la cual se comercializa en 5 planes con diferentes características: Free, Standard, Professional, Enterprise y Ultimate.

* __Versión vigente:__ Su API principal se encuentra actualmente en la versión 8.

* __SGBDs Compatiles:__ PostgreSQL.

* __Lenguaje del servidor:__ Deluge, Node.js, Java y Python.

* __Modalidad de despliegue:__ Exclusivamente en la nube.

* __Módulos principales incluidos:__ Automatización de fuerza de ventas, Marketing, Soporte al cliente, Estadísticas e Inventario.

* __Requisitos del Sistema:__ Requiere de Navegadores web modernos y actualizados, Soporte de cifrado TLS v1.2 o superior, JavaScript y Conexión a Internet continua y estable.

## Sección 4: Fe de erratas del tema
* __Versión actual de ODOO:__ En el temario aparece que la versión actual de ODOO es la 14, dato el cual ha quedado obsoleto ya que la version mas reciente a fecha de septiembre de 2026 es ODOO 19.0 según su web oficial.

* __Versión actual de ERPNext:__ En el temario también se da otro caso de versión actual desasada, ya que pone que la versión mas reciente de ERPNext es la 15 cuando actualmente es la 16.36 según su web oficial.

## Sección 5: Justificación de decisiones
### Explicación de criterios
* __Coste total (30%):__ A este apartado se le da el mayor peso ya que el presupuesto y la inversión es la restricción mas determinante en la selección de una solución u otra.

* __Seguridad (25%):__ Se le ha asignado este peso ya que la protección y privacidad de los datos es crítica para cualquier empresa.

* __Soporte (15%):__ El soporte es importante ya que garantiza la continuidad del negocio y puede reducir en gran medida los tiempos de inactividad por incidencias.

* __Usabilidad (15%):__ Es determinante para la facilidad de adopcion por parte de los trabajadores, lo cual afecta directamente en la productividad y costes de formación en la empresa.

* __Dependencia del proveedor (10%):__ Se debe de tener en cuenta la flexibilidad para usar otras herramientas de otros proveedores junto con el software, aunque este punto es menos importante que los anteriores.

* __Migración futura (5%):__ Suele ser un factor secundario a la hora de elegir un software. Representa la escalabilidad y las posibilidades de cambio de tecnología a futuro.

### Puntuaciones
#### 1.- ODOO Community
Coste total (5), Seguridad (3), Soporte (2), Usabilidad (4), Dependencia del proveedor (4) y Migración futura (3).  
  
  Al ser una solución gratuita obtiene la puntuación máxima en el apartado coste total. En cuanto a la seguridad y soporte ODOO Community solo cuenta con una comunidad gratuita, recayendo estos 2 aspectos en la gestión propia y partners de la comunidad, lo que hace que en cuanto a seguridad y soporte esté mas limitado. Cuenta con una interfaz moderna e intuitiva y su dependencia de proveedor es principalmente baja al ser open source (esto tambien es positivo para la migración futura, aunque más limitado).  

  Puntuación final: 74%

#### 2.- Oracle Fusion Cloud ERP
Coste total (1), Seguridad (5), Soporte (5), Usabilidad (3), Dependencia del proveedor (1) y Migración futura (4).  
  
  Sus costes de licencia, implementación y mantenimiento son muy elevados, por lo que obtiene la menor puntuación en este aspecto. En cuanto a la seguridad y el soporte, este cuenta con los máximos estandares de seguridad corporativa y soporte tecnico global los 365 dias del año, obteniendo la maxima puntuacion en ambos aspectos. Cuenta con una interfaz algo mas compleja y en cuanto a dependencia del proveedor obtiene la minima puntuacion ya que esta fuertemente ligado al ecosistema cerrado de Oracle. En cuanto a la migración, contiene estandares robustos que facilitan el proceso, aunque migrar hacia fuera es mas complejo.  

  Puntuación final: 70%

#### 3.- SuiteCRM
Coste total (5), Seguridad (3), Soporte (3), Usabilidad (3), Dependencia del proveedor (5) y Migración futura (3).  
  
  Al igual que ODOO Community, cuenta con licencias gratuitas, por lo que obtiene la maxima puntuacion en este aspecto. También es similar a ODOO en cuanto a la seguridad y soporte, ya que recae en su comunidad activa. En cuanto a la usabilidad, cuenta con una interfaz algo mas anticuada que el resto de opciones, lo que hace que en este aspecto esté mas limitado. Su dependencia de proveedor es principalmente baja al ser open source (esto tambien es positivo para la migración futura, aunque más limitado).  

  Puntuación final: 61%

  ### Recomendación
  Teniendo en cuenta la situación de la empresa Electrosur, mi recomendación es el uso de ODOO Community debido a que es 100% gratuito, fácil de usar para los empleados y tiene poca dependencia de su proveedor, lo que permiete tener a la empresa una herremienta de muy bajo coste y gran libertad.