## Capítulo III: Requirements Specification
### 3.1. To-Be Scenario Mapping 

**Segmento de empresa de transportes**

Utiliza la aplicación para recibir solicitudes de envío por parte de clientes, ofrecer cotizaciones personalizadas y gestionar los datos logísticos de cada servicio. Este perfil busca flexibilidad en la fijación de precios y claridad en la comunicación con el cliente para brindar un servicio eficiente y seguro. El siguiente mapeo describe las fases, pensamientos y emociones que atraviesa durante el uso de la plataforma.(Ver figura 3.1.1)

<p align="center">
  <img align="center" src="assets/To-Be%20Scenario%20Mapping%20-%20Transportistas.jpg" alt="To-Be Scenario Mapping del Empresa de transporte"></p>
<p align="center"><em>Figura 3.1.1: To-Be Scenario Mapping de la empresa de transporte.</em></p>

**Segmento de empresario pesquero**

Busca empresas de transporte confiables para enviar sus paquetes de forma segura y eficiente. Este perfil valora poder comparar opciones, tener claridad en los precios y recibir información específica sobre el transporte asignado. El siguiente mapeo muestra las fases, pensamientos y emociones que experimenta al utilizar la aplicación para solicitar y coordinar un servicio de transporte.(Ver figura 3.1.2)

<p align="center">
  <img align="center" src="assets/To-Be Scenario Mapping - Pesquero.jpg" alt="To-Be Scenario Mapping del Empresario pesquero">
</p>
<p align="center"><em>Figura 3.1.2: To-Be Scenario Mapping del empresario pesquero.</em></p>

**Enlace del To-Be Scenario Mapping:** [Ver en Miro](https://miro.com/app/board/uXjVID8wvf0=/?share_link_id=911528094729)

### 3.2. User Stories
<table>
<colgroup>
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
<col style="width: 20%" />
</colgroup>
<thead>
<tr>
<th style="text-align: left;">Epic/Story ID</th>
<th style="text-align: left;">Título</th>
<th style="text-align: left;">Descripción</th>
<th style="text-align: left;">Criterios de aceptación</th>
<th style="text-align: left;">Relacionado con (Epic ID)</th>
</tr>
<tr>
<th style="text-align: left;">E1</th>
<th style="text-align: left;">Diseño de la Lading Page</th>
<td style="text-align: left;"><p><strong>Como</strong> Empresario
pesquero o Empresa de transportes</p>
<p><strong>Quiero</strong> ver una página web en la cual tenga
información del servicio que voy a utilizar</p>
<p><strong>Para</strong> tener una vista más clara del servicio que nos
proporcionarán</p></td>
<td style="text-align: left;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<th style="text-align: left;">E1-US01</th>
<th style="text-align: left;">Barra de Navegación en la Landing
Page</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> ver una barra de navegación con una buena
estructura informática</p>
<p><strong>Para</strong> poder acceder a las secciones más relevantes
del servicio</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: El emprendedor o transportista accede a la landing page.</strong></p>
<p><strong>Dado que </strong>el usuario se encuentra en la Landing Page,</p>
<p><strong>Cuando </strong>accede a la página,</p>
<p><strong>Entonces </strong>la barra de navegación es visible en la parte superior de la página.</p>
<p><strong>Escenario 2: El usuario navega a diferentes secciones.</strong></p>
<p><strong>Dado que </strong>el usuario se encuentra en la Landing Page,</p>
<p><strong>Cuando </strong>hace clic en un enlace de la barra de navegación,</p>
<p><strong>Entonces </strong>es dirigido a la sección correspondiente sin necesidad de recargar.</p>
<p><strong>Escenario 3: El usuario visualiza la barra en diferentes dispositivos.</strong></p>
<p><strong>Dado que </strong>el usuario se encuentra en la Landing Page usando un dispositivo móvil o de escritorio,</p>
<p><strong>Cuando </strong>visualiza la Landing Page,</p>
<p><strong>Entonces </strong>la barra de navegación se ajusta de manera adecuada al tamaño de la pantalla, mostrando un menú desplegable en dispositivos móviles si es necesario.</p>
</td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<th style="text-align: left;">E1-US02</th>
<th style="text-align: left;">Información sobre el servicio
brindado</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> que al ingresar a la página web me muestre la
información de los servicios que me van a brindar</p>
<p><strong>Para</strong> entender qué beneficios obtendré al usar la
aplicación web</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: El usuario accede a la información sobre los beneficios del servicio.</strong></p>
<p><strong>Dado que </strong>el usuario está navegando en el sitio web,</p>
<p><strong>Cuando </strong>accede a la sección de beneficios del servicio,</p>
<p><strong>Entonces </strong>encuentra información clara y detallada sobre cómo el servicio puede beneficiarlo.</p>
<p><strong>Escenario 2: El usuario comprende los beneficios del servicio.</strong></p>
<p><strong>Dado que </strong>el usuario está leyendo sobre los beneficios del servicio,</p>
<p><strong>Cuando </strong>revisa la información proporcionada,</p>
<p><strong>Entonces </strong>entiende cómo el servicio puede resolver sus problemas o mejorar sus procesos.</p>
</td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<th>E1-US03</th>
<th style="text-align: left;">Información sobre el procedimiento de uso
de la aplicación web</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> visualizar el procedimiento que tendría que
hacer para usar este servicio</p>
<p><strong>Para</strong> así conocer el grado de satisfacción que tendre
al momento de usar la aplicación web</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: El usuario visualiza el como se usa la aplicación web.</strong></p>
<p><strong>Dado que </strong>el usuario está navegando en el sitio web,</p>
<p><strong>Cuando </strong>llega a la seccion de “Como Funciona”,</p>
<p><strong>Entonces </strong>entiende mas sobre el funcionamiento de la aplicacion web.</p>
</td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<th>E1-US04</th>
<th style="text-align: left;">Conocer los testimonios de clientes
pasados</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> leer algunos testimonios de clientes
anteriores</p>
<p><strong>Para</strong> evaluar la experiencia de otras
personas</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: El usuario accede a testimonios visibles.</strong></p>
<p><strong>Dado que </strong>el usuario está navegando en el sitio web,</p>
<p><strong>Cuando </strong>llega a la sección de testimonios de clientes,</p>
<p><strong>Entonces </strong>ve claramente los testimonios destacados de clientes anteriores.</p>
<p><strong>Escenario 2: El usuario evalúa el impacto de los testimonios.</strong></p>
<p><strong>Dado que </strong>el usuario está considerando contratar el servicio,</p>
<p><strong>Cuando </strong>revisa los testimonios de clientes anteriores,</p>
<p><strong>Entonces </strong>se siente más seguro en su decisión al ver que otros han tenido experiencias positivas y beneficios tangibles con el servicio.</p>
</td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<th>E1-US05</th>
<th style="text-align: left;">Conocer las ventajas de la aplicación
web</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> conocer las ventajas que tiene la aplicación
frente a otras aplicaciones similares</p>
<p><strong>Para</strong> tomar la decisión de tomar o no el
servicio</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Visualización clara de beneficios destacados.</strong></p>
<p><strong>Dado que </strong>el usuario está navegando en la landing page,</p>
<p><strong>Cuando </strong>ingrese a la sección de beneficios,</p>
<p><strong>Entonces </strong>podrá visualizar una lista clara y detallada de las ventajas que ofrece la aplicación frente a otras plataformas.</p>
<p><strong>Escenario 2: Comparativa visual de características.</strong></p>
<p><strong>Dado que </strong>el usuario desea comparar la aplicación con otras opciones del mercado,</p>
<p><strong>Cuando </strong>acceda a la sección de ventajas,</p>
<p><strong>Entonces </strong>podrá visualizar si los beneficios son mejores que la competencia</p>
</td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<th>E1-US06</th>
<th style="text-align: left;">Contacto</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> enviar una solicitud a los dueños de la
aplicación web</p>
<p><strong>Para</strong> poder conocer más sobre su trabajo y/o que me
den más detalles de la misma</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Envío exitoso de solicitud de contacto.</strong></p>
<p><strong>Dado que </strong>el usuario ha llenado el formulario de contacto,</p>
<p><strong>Cuando </strong>complete todos los campos requeridos y presione el botón de enviar,</p>
<p><strong>Entonces </strong>el sistema debe confirmar que la solicitud fue enviada correctamente.</p>
<p><strong>Escenario 2: Validación de campos obligatorios en el formulario de contacto.</strong></p>
<p><strong>Dado que </strong>el usuario desea enviar una solicitud de contacto,</p>
<p><strong>Cuando </strong>intente enviar el formulario sin llenar todos los campos requeridos,</p>
<p><strong>Entonces </strong>el sistema debe mostrar mensajes de error indicando qué campos faltan completar.</p>
</td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<th>E1-US07</th>
<th style="text-align: left;">Cambiar idiomas</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> cambiar el idioma de la página web de Inglés
al Español</p>
<p><strong>Para</strong> así poder comprender el contenido</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Selección exitosa de idioma desde el menú.</strong></p>
<p><strong>Dado que </strong>el usuario visualiza la página en inglés,</p>
<p><strong>Cuando </strong>seleccione la opción de idioma "Español" desde el menú de configuración o selector de idioma,</p>
<p><strong>Entonces </strong>todo el contenido visible de la página debe actualizarse automáticamente en idioma español.</p>
<p><strong>Escenario 2: Conservación de idioma en navegación.</strong></p>
<p><strong>Dado que </strong>el usuario ha cambiado el idioma a "Español",</p>
<p><strong>Cuando </strong>snavegue a otra sección o página dentro del mismo sitio,</p>
<p><strong>Entonces </strong>el idioma seleccionado debe mantenerse sin reiniciarse a inglés hasta que el usuario decida cambiarlo nuevamente.</p>
</td>
<td style="text-align: center;">1</td>
</tr>
<tr>
<th>E2</th>
<th style="text-align: left;">Interfaz de acceso a la aplicación
web</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> registrarme a la aplicación web</p>
<p><strong>Para</strong> identificar qué tipo de usuario soy</p></td>
<td style="text-align: left;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<th>E2-US08</th>
<th style="text-align: left;">Registro para de la empresa prestadora de
vehículos</th>
<td><p><strong>Como</strong> Empresa de transportes</p>
<p><strong>Quiero</strong> llenar mi información</p>
<p><strong>Para</strong> así darme a conocer</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Registro completo con información obligatoria.</strong></p>
<p><strong>Dado que </strong>la empresa de transportes desea registrarse en la plataforma,</p>
<p><strong>Cuando </strong>complete todos los campos obligatorios del formulario de registro,</p>
<p><strong>Entonces </strong>la aplicación debe validar los datos y permitir el registro exitoso.</p>
<p><strong>Escenario 2: Confirmación visual de registro exitoso.</strong></p>
<p><strong>Dado que </strong>la empresa transportista ha completado correctamente el formulario de registro,</p>
<p><strong>Cuando </strong>haga clic en el botón "Registrar" y los datos sean validados sin errores,</p>
<p><strong>Entonces </strong>la aplicación debe mostrar una notificación o mensaje emergente que confirme que el registro fue exitoso.</p>
</td>
<td style="text-align: center;">2</td>
</tr>
<tr>
<th>E2-US09</th>
<th style="text-align: left;">Registro para el emprendedor pesquero</th>
<td><p><strong>Como</strong> Empresario pesquero</p>
<p>Quiero llenar mi información</p>
<p><strong>Para</strong> luego tener comunicación con la empresa
prestadora de vehículos</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Registro completo con información obligatoria.</strong></p>
<p><strong>Dado que </strong>el emprendedor pesquero desea registrarse en la plataforma,</p>
<p><strong>Cuando </strong>complete todos los campos obligatorios del formulario de registro(Correo personal, contraseña),</p>
<p><strong>Entonces </strong>la aplicación registrará sus datos de manera exitosa.</p>
<p><strong>Escenario 2: Confirmación visual de registro exitoso.</strong></p>
<p><strong>Dado que </strong>el emprendedor pesquero ha completado correctamente el formulario de registro,</p>
<p><strong>Cuando </strong>haga clic en el botón "Registrar" y los datos sean validados sin errores,</p>
<p><strong>Entonces </strong>la aplicación debe mostrar una notificación o mensaje emergente que confirme que el registro fue exitoso.</p>
</td>
<td style="text-align: center;">2</td>
</tr>
<tr>
<th>E2-US10</th>
<th style="text-align: left;">Ingreso a la aplicación</th>
<td><p><strong>Como</strong> Empresario pesquero o Empresa de
transportes</p>
<p><strong>Quiero</strong> ingresar mis datos</p>
<p><strong>Para</strong> empezar a hacer uso de la aplicación
web</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Ingreso correcto con credenciales válidas.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero o empresa de transportes ya tiene una cuenta registrada,</p>
<p><strong>Cuando </strong>ingresa su correo electrónico y contraseña correctamente en el formulario de inicio de sesión,</p>
<p><strong>Entonces </strong>la aplicación debe permitir el acceso a su panel principal según su tipo de usuario.</p>
<p><strong>Escenario 2: Mensaje de error al ingresar datos incorrectos.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero o empresa de transportes ingresa sus datos en el formulario de inicio,</p>
<p><strong>Cuando </strong>introduzca un correo o contraseña incorrecta,</p>
<p><strong>Entonces </strong>la aplicación debe mostrar un mensaje de error claro indicando que las credenciales son inválidas.</p>
</td>
<td style="text-align: center;">2</td>
</tr>
<tr>
<th style="text-align: left;">E3</th>
<th style="text-align: left;">Interfaz clara e intuitiva para el
emprendedor pesquero</th>
<td><p><strong>Como</strong> Empresario pesquero</p>
<p><strong>Quiero</strong> poder comprender e interactuar con el
servicio que la aplicación web me está proporcionando</p>
<p><strong>Para</strong> así poder generar mis solicitudes de una manera
clara y correcta sin temor a equivocación</p></td>
<td style="text-align: left;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<th style="text-align: left;">E3-US11</th>
<th style="text-align: left;">Seccion de busqueda</th>
<td><p><strong>Como</strong> Empresario pesquero</p>
<p><strong>Quiero</strong> poder realizar búsquedas por distritos</p>
<p><strong>Para</strong> así poder filtrar la búsqueda de empresas de
transportes</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Búsqueda exitosa por distrito.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero accede a la sección de búsqueda de empresas de transportes,</p>
<p><strong>Cuando </strong>ingresa el nombre de un distrito en el campo de búsqueda y ejecuta la búsqueda,</p>
<p><strong>Entonces </strong>el sistema debe mostrar únicamente las empresas de transporte que operan en el distrito seleccionado.</p>
<p><strong>Escenario 2: Mensaje cuando no hay resultados para un distrito en específico.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero realiza una búsqueda por distrito,</p>
<p><strong>Cuando </strong>ingresa un distrito donde no hay empresas registradas,</p>
<p><strong>Entonces </strong>el sistema debe mostrar un mensaje indicando que no se encontraron resultados para ese distrito.</p>

</td>
<td style="text-align: center;">3</td>
</tr>
<tr>
<th style="text-align: left;">E3-US12</th>
<th style="text-align: left;">Información de la empresa</th>
<td><p><strong>Como</strong> Empresario pesquero</p>
<p><strong>Quiero</strong> observar información de la empresa de
transporte luego de la búsqueda</p>
<p><strong>Para</strong> así poder elegir la que mejor me
convenga</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Visualización de información detallada de la empresa.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha realizado una búsqueda de empresas de transporte,</p>
<p><strong>Cuando </strong>selecciona una empresa de la lista de resultados,</p>
<p><strong>Entonces </strong>la aplicación debe mostrar información detallada como: nombre de la empresa, descripción breve, distritos de entrega, foto entre otros.</p>
<p><strong>Escenario 2: Visualización de información resumida desde la lista de resultados.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha realizado una búsqueda de empresas de transporte,</p>
<p><strong>Cuando </strong>observa la lista de resultados,</p>
<p><strong>Entonces </strong>cada empresa debe mostrar de forma resumida su nombre, una breve descripción, distritos de entrega y una imagen representativa antes de que el usuario acceda al detalle completo.</p>
</td>
<td style="text-align: center;">3</td>
</tr>
<tr>
<th style="text-align: left;">E3-US13</th>
<th style="text-align: left;">Solicitar el servicio a la empresa
prestadora de vehículos</th>
<td><p><strong>Como</strong> Empresario pesquero</p>
<p><strong>Quiero</strong> poder seleccionar la empresa de transporte
adecuada</p>
<p><strong>Para</strong> así poder brindar la información necesaria para
que realice mi servicio</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Selección de la empresa de transporte desde los resultados de búsqueda.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha realizado una búsqueda y ha encontrado varias empresas,</p>
<p><strong>Cuando </strong>selecciona una o varias empresas de transporte de la lista,</p>
<p><strong>Entonces </strong>el sistema debe redirigirlo a un formulario donde pueda ingresar la información detallada de su solicitud de servicio.</p>
<p><strong>Escenario 2: Llenado de formulario con los datos del paquete.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha seleccionado la empresa de transporte y ha sido redirigido al formulario de solicitud,</p>
<p><strong>Cuando </strong>el empresario rellena los campos correspondientes a las dimensiones, cantidad y peso del paquete,</p>
<p><strong>Entonces </strong>el sistema debe permitirle ingresar los datos de manera correcta y debe validar que todos los campos obligatorios estén completos antes de enviar la solicitud.</p>
<p><strong>Escenario 3: Confirmación de envío de la solicitud de servicio.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha completado el formulario de solicitud para una empresa de transporte,</p>
<p><strong>Cuando </strong> envía la información,</p>
<p><strong>Entonces </strong>el sistema debe mostrar una notificación o mensaje de confirmación indicando que la solicitud fue enviada correctamente.</p>
</td>
<td style="text-align: center;">3</td>
</tr>
<tr>
<th style="text-align: left;">E3-US14</th>
<th style="text-align: left;">Gestionar solicitudes enviadas</th>
<td><p><strong>Como</strong> Empresario pesquero</p>
<p><strong>Quiero</strong> tener un apartado en el cual pueda ver las
solicitudes que hice</p>
<p><strong>Para</strong> poder gestionar los precios que me ofrecieron
por el servicio que deseo</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Visualización de solicitudes enviadas.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha enviado varias solicitudes a diferentes empresas de transporte,</p>
<p><strong>Cuando </strong>accede a la sección de "Solicitudes enviadas" en su cuenta,</p>
<p><strong>Entonces </strong>el sistema debe mostrar una lista con todas las solicitudes previas, con detalles como la empresa seleccionada, estado de la solicitud (aceptada, pendiente, rechazada) y precio ofrecido por cada una.</p>
<p><strong>Escenario 2: Gestión de precios ofrecidos.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha recibido varias ofertas de precios de diferentes empresas,</p>
<p><strong>Cuando </strong>accede a una solicitud enviada y revisa los precios ofrecidos,</p>
<p><strong>Entonces </strong>el sistema debe permitirle aceptar o rechazar las ofertas según lo desee.</p>
<p><strong>Escenario 3: Aceptar una sola oferta entre varias solicitadas.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha solicitado el servicio de varias empresas de transporte y ha recibido varias ofertas,</p>
<p><strong>Cuando </strong>accede a la sección de "Solicitudes enviadas" y revisa las ofertas,</p>
<p><strong>Entonces </strong>el sistema debe permitirle aceptar solo una oferta, y una vez aceptada, las otras ofertas deben marcarse como rechazadas automáticamente.</p>
</td>
<td style="text-align: center;">3</td>
</tr>
<tr>
<th style="text-align: left;">E3-US15</th>
<th style="text-align: left;">Pagar a la empresa seleccionada</th>
<td><p><strong>Como</strong> Empresario pesquero</p>
<p><strong>Quiero</strong> pagar el servicio que haya seleccionado</p>
<p><strong>Para</strong> así confirmarle a la empresa de transporte que
estoy de acuerdo con su cotización</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Realizar el pago del servicio seleccionado.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha aceptado una oferta de una empresa de transporte,</p>
<p><strong>Cuando </strong>decide proceder con el pago,</p>
<p><strong>Entonces </strong>el sistema debe permitirle realizar el pago utilizando su método de pago preferido (tarjeta de crédito, transferencia, etc.)</p>
<p><strong>Escenario 2: Notificación de un pago exitoso.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ya pagó por el servicio,</p>
<p><strong>Cuando </strong>la transacción es procesada correctamente,</p>
<p><strong>Entonces </strong>el sistema debe notificar al empresario pesquero que el pago fue exitoso.</p>
</td>
<td style="text-align: center;">3</td>
</tr>
<tr>
<th style="text-align: left;">E3-US16</th>
<th style="text-align: left;">Obtener información del vehículo
repartidor</th>
<td><p><strong>Como</strong> Empresario pesquero</p>
<p><strong>Quiero</strong> tener la información del vehículo que
enviarán mi producto</p>
<p><strong>Para</strong> así poder tener un seguimiento de sus
datos</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Visualización de la información del vehículo asignado.</strong></p>
<p><strong>Dado que </strong>el empresario pesquero ha solicitado el servicio de transporte,</p>
<p><strong>Cuando </strong>se le asigna un vehículo para la entrega,</p>
<p><strong>Entonces </strong>el sistema debe mostrar la información completa del vehículo, incluyendo el modelo, la placa y el nombre del conductor.</p>
</td>
<td style="text-align: center;">3</td>
</tr>
<tr>
<th style="text-align: left;">E4</th>
<th>Interfaz clara e intuitiva para la empresa prestadora de
vehículos</th>
<td><p><strong>Como</strong> Empresa de transportes</p>
<p><strong>Quiero</strong> poder comprender e interactuar con el
servicio que la aplicación web me está proporcionando</p>
<p><strong>Para</strong> así poder generar las solicitudes de una manera
clara y correcta sin temor a equivocación</p></td>
<td style="text-align: left;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<th style="text-align: left;">E4-US17</th>
<th style="text-align: left;">Gestión de solicitudes recibidas</th>
<td><p><strong>Como</strong> Empresa de
transportes</p>
<p><strong>Quiero</strong> observar los detalles de la información de
los emprendedores pesqueros</p>
<p><strong>Para</strong> poder aceptar y gestionar una cotización o
rechazar la solicitud</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Visualización de detalles de la solicitud.</strong></p>
<p><strong>Dado que </strong>soy una empresa de transportes con solicitudes recibidas de emprendedores pesqueros,</p>
<p><strong>Cuando </strong>accedo a la sección de "Solicitudes recibidas" en la plataforma,</p>
<p><strong>Entonces </strong>debo poder ver toda la información relevante de la solicitud, como el nombre del emprendedor, tipo de producto, cantidad, lugar de recogida y entrega, y fecha.</p>
<p><strong>Escenario 2: Aceptar o rechazar la solicitud.</strong></p>
<p><strong>Dado que </strong>estoy revisando una solicitud de una empresa pesquera,</p>
<p><strong>Cuando </strong>presiono los botones "Aceptar" o "Rechazar" en la solicitud correspondiente,</p>
<p><strong>Entonces </strong>el sistema debe actualizar el estado de la solicitud y reflejar mi decisión correctamente en el panel de control del cliente.</p>
</td>
<td style="text-align: center;">4</td>
</tr>
<tr>
<th style="text-align: left;">E4-US18</th>
<th style="text-align: left;">Gestión de pagos</th>
<td><p><strong>Como</strong> Empresa de transportes</p>
<p><strong>Quiero</strong> realizar un seguimiento de quien realizo el
pago o cancelo el servicio</p>
<p><strong>Para</strong> poder continuar con el proceso del servicio a
prestar</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Visualizar estado de pago.</strong></p>
<p><strong>Dado que </strong>soy una empresa de transportes con servicios solicitados por empresas pesqueras,</p>
<p><strong>Cuando </strong>accedo al historial o listado de servicios en la sección de pagos de la plataforma,</p>
<p><strong>Entonces </strong>edebo poder visualizar si el servicio fue pagado o cancelado.</p>
</td>
<td style="text-align: center;">4</td>
</tr>
<tr>
<th style="text-align: left;">E4-US19</th>
<th style="text-align: left;">Enviar información del vehículo hacia el
emprendedor pesquero</th>
<td><p><strong>Como</strong> Empresa de transportes</p>
<p><strong>Quiero</strong> enviar informacion necesaria del vehículo</p>
<p><strong>Para</strong> que el emprendedor pesquero pueda gestionar la
entrega</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Enviar información del vehículo después de aceptar la solicitud.</strong></p>
<p><strong>Dado que </strong>he aceptado una solicitud de transporte realizada por una empresa pesquera,</p>
<p><strong>Cuando </strong>accedo a la solicitud aceptada desde el panel de gestión de servicios,</p>
<p><strong>Entonces </strong>debo poder completar y enviar los datos del vehículo asignado (marca, modelo, placa, nombre y contacto del conductor).</p>
<p><strong>Escenario 2: Confirmación del envío de información.</strong></p>
<p><strong>Dado que </strong>he enviado correctamente la información del vehículo a la empresa pesquera,</p>
<p><strong>Cuando </strong>presiono el botón de "Enviar información del vehículo" en la plataforma,</p>
<p><strong>Entonces </strong>el sistema debe mostrarme una confirmación visual del envío exitoso.</p>
</td>
<td style="text-align: center;">4</td>
</tr>
<tr>
<th style="text-align: left;">E5</th>
<th style="text-align: left;">Backend Api</th>
<td><p><strong>Como</strong> desarrollador</p>
<p><strong>Quiero</strong> utilizar la API de un servicio de backend</p>
<p><strong>Para</strong> que el usuario pueda usar la
aplicación</p></td>
<td style="text-align: left;"></td>
<td style="text-align: center;"></td>
</tr>
<tr>
<th style="text-align: left;">E5-US20</th>
<th style="text-align: left;">Agregar una empresa prestadora de
vehículos</th>
<td><strong>Como</strong> desarrollador</p>
<p><strong>Quiero</strong> agregar una empresa de transporte a través
del backend</p>
<p><strong>Para</strong> que esté disponible para la empresa
pesquera</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Registro exitoso de empresa de transporte.</strong></p>
<p><strong>Dado que </strong>tengo acceso al backend y cuento con los datos necesarios de una empresa prestadora de vehículos,</p>
<p><strong>Cuando </strong>envío una solicitud POST con los datos completos al endpoint correspondiente,</p>
<p><strong>Entonces </strong>la API debe permitir almacenar la información de la empresa correctamente en la base de datos.</p>
</td>
<td style="text-align: center;">5</td>
</tr>
<tr>
<th style="text-align: left;">E5-US21</th>
<th style="text-align: left;">Agregar solicitud del emprendedor
pesquero</th>
<td><p><strong>Como</strong> desarrollador</p>
<p><strong>Quiero</strong> agregar los datos de la solicitud de la
empresa pesquera mediante el backend</p>
<p><strong>Para</strong> que la empresa de transporte pueda utilizar
esos datos</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Registro exitoso de la solicitud de transporte.</strong></p>
<p><strong>Dado que </strong>tengo acceso al backend y recibo los datos de una solicitud generada por una empresa pesquera,</p>
<p><strong>Cuando </strong>realizo una petición POST con información como: nombre del emprendedor, tipo de producto, cantidad, origen, destino y fecha de envío,</p>
<p><strong>Entonces </strong>la API debe permitir guardar correctamente los datos de la solicitud en la base de datos.</p>
</td>
<td style="text-align: center;">5</td>
</tr>
<tr>
<th style="text-align: left;">E5-US22</th>
<th style="text-align: left;">Gestionar usuarios</th>
<td><p><strong>Como</strong> desarrollador</p>
<p><strong>Quiero</strong> gestionar usuarios a través del backend</p>
<p><strong>Para</strong> poder controlar el acceso y permisos de cada
usuario en el sistema</p></td>
<td style="text-align: left;">
<p><strong>Escenario 1: Creación y registro de usuarios con rol asignado.</strong></p>
<p><strong>Dado que </strong>tengo acceso al backend y recibo los datos de registro de un nuevo usuario,</p>
<p><strong>Cuando </strong>realizo una solicitud POST al endpoint de usuarios con los datos correspondientes,</p>
<p><strong>Entonces </strong>la API debe permitir registrar al usuario junto con su rol (por ejemplo: empresa pesquera o empresa de transporte).</p>
</td>
<td style="text-align: center;">5</td>
</tr>
</thead>
<tbody>
</tbody>
</table>

### 3.3. Impact Mapping 

**Segmento de empresa de transportes**

El siguiente Impact Mapping muestra de manera clara cómo las empresas de transporte logran organizar sus procesos dentro de la aplicación, permitiendo definir precios, gestionar solicitudes y brindar confianza a sus clientes mediante la asignación de vehículos y conductores. Esta herramienta ayuda a visualizar las funcionalidades clave que permitirán a las empresas ofrecer un servicio seguro y eficiente.(Ver figura 3.3.1)
<p align="center">
  <img align="center" src="assets/Impact map - Empresario transportista.png" alt="Impact Mapping del segmento de Empresa de Transportes"></p>
<p align="center"><em>Figura 3.3.1: Impact Mapping del segmento de Empresa de Transportes.</em></p>

**Segmento de empresario pesquero**

A continuación, se presenta el Impact Mapping enfocado en los empresarios pesqueros, que buscan seleccionar de forma segura y rápida a empresas de transporte confiables para el envío de sus productos. Este mapeo permite identificar las funcionalidades necesarias para mejorar su experiencia en la búsqueda, selección y mayor manejo en el cuidado de sus paquetes.(Ver figura 3.3.2)
<p align="center">
  <img align="center" src="assets/Impact map - empresario pesquero.png" alt="Impact Mapping del segmento de Empresario pesquero"></p>
<p align="center"><em>Figura 3.3.2: Impact Mapping del segmento de Empresario pesquero.</em></p>

### 3.4. Product Backlog

<table border="1">
  <tr>
    <th>#Order</th>
    <th>User Story ID</th>
    <th>Titúlo</th>
    <th>Descripción</th>
    <th>Story Points</th>
  </tr>
  <tr>
    <td align="center">1</td>
    <td>E3-US11</td>
    <td>Sección de búsqueda</td>
    <td>Como Empresario pesquero quiero poder realizar búsquedas por distritos para así poder filtrar la búsqueda de empresas de transportes</td>
    <td align="center">8</td>
  </tr>
  <tr>
    <td align="center">2</td>
    <td>E3-US13</td>
    <td>Solicitar el servicio a la empresa prestadora de vehículos</td>
    <td>Como Empresario pesquero quiero poder seleccionar la empresa de transporte adecuada para así poder brindar la información necesaria para que realice mi servicio</td>
    <td align="center">8</td>
  </tr>
  <tr>
    <td align="center">3</td>
    <td>E3-US14</td>
    <td>Gestionar solicitudes enviadas</td>
    <td>Como Empresario pesquero quiero tener un apartado en el cual pueda ver las solicitudes que hice para poder gestionar los precios que me ofrecieron por el servicio que deseo</td>
    <td align="center">8</td>
  </tr>
  <tr>
    <td align="center">4</td>
    <td>E4-US18</td>
    <td>Gestión de pagos</td>
    <td>Como Empresa de transportes quiero realizar un seguimiento de quien realizo el pago o cancelo el servicio para poder continuar con el proceso del servicio a prestar</td>
    <td align="center">8</td>
  </tr>
  <tr>
    <td align="center">5</td>
    <td>E4-US19</td>
    <td>Enviar información del vehículo hacia el emprendedor pesquero</td>
    <td>Como Empresa de transportes quiero enviar informacion necesaria del vehículo para que el emprendedor pesquero pueda gestionar la entrega</td>
    <td align="center">8</td>
  </tr>
  <tr>
    <td align="center">6</td>
    <td>E2-US08</td>
    <td>Registro para de la empresa prestadora de vehículos</td>
    <td>Como Empresa de transportes quiero llenar mi información para así darme a conocer</td>
    <td align="center">5</td>
  </tr>
  <tr>
    <td align="center">7</td>
    <td>E2-US09</td>
    <td>Registro para de el emprendedor pesquero</td>
    <td>Como Empresario pesquero quiero llenar mi información para luego tener comunicación con la empresa prestadora de vehículos</td>
    <td align="center">5</td>
  </tr>
  <tr>
    <td align="center">8</td>
    <td>E3-US15</td>
    <td>Pagar a la empresa seleccionada</td>
    <td>Como Empresario pesquero quiero pagar el servicio que haya seleccionado para así confirmarle a la empresa de transporte que estoy de acuerdo con su cotización</td>
    <td align="center">5</td>
  </tr>
  <tr>
    <td align="center">9</td>
    <td>E3-US16</td>
    <td>Obtener información del vehículo repartidor</td>
    <td>Como Empresario pesquero quiero tener la información del vehículo que enviarán mi producto para así poder tener un seguimiento de sus datos</td>
    <td align="center">5</td>
  </tr>
  <tr>
    <td align="center">10</td>
    <td>E4-US17</td>
    <td>Gestión de solicitudes recibidas</td>
    <td>Como Empresa de transportes quiero observar los detalles de la información de los emprendedores pesqueros para poder aceptar y gestionar una cotización o rechazar la solicitud</td>
    <td align="center">5</td>
  </tr>
  <tr>
    <td align="center">11</td>
    <td>E1-US01</td>
    <td>Barra de Navegación en la Landing Page</td>
    <td>Como Empresario pesquero o Empresa de transportes quiero ver una página web en la cual tenga información del servicio que voy a utilizar para tener una vista más clara del servicio que nos proporcionarán</td>
    <td align="center">3</td>
  </tr>
  <tr>
    <td align="center">12</td>
    <td>E1-US02</td>
    <td>Información sobre el servicio brindado</td>
    <td>Como Empresario pesquero o Empresa de transportes quiero que al ingresar a la página web me muestre la información de los servicios que me van a brindar para entender qué beneficios obtendré al usar la aplicación web</td>
    <td align="center">3</td>
  </tr>
  <tr>
    <td align="center">13</td>
    <td>E1-US05</td>
    <td>Conocer las ventajas de la aplicación web</td>
    <td>Como Empresario pesquero o Empresa de transportes quiero conocer las ventajas que tiene la aplicación frente a otras aplicaciones similares para tomar la decisión de tomar o no el servicio</td>
    <td align="center">3</td>
  </tr>
  <tr>
    <td align="center">14</td>
    <td>E3-US12</td>
    <td>Información de la empresa</td>
    <td>Como Empresario pesquero quiero observar información de la empresa de transporte luego de la búsqueda para así poder elegir la que mejor me convenga</td>
    <td align="center">3</td>
  </tr>
  <tr>
    <td align="center">15</td>
    <td>E5-US20</td>
    <td>Agregar una empresa prestadora de vehículos</td>
    <td>Como desarrollador quiero agregar una empresa de transporte a través del backend para que esté disponible para la empresa pesquera</td>
    <td align="center">3</td>
  </tr>
  <tr>
    <td align="center">16</td>
    <td>E5-US21</td>
    <td>Agregar solicitud del emprendedor pesquero</td>
    <td>Como desarrollador quiero agregar los datos de la solicitud de la empresa pesquera mediante el backend para que la empresa de transporte pueda utilizar esos datos</td>
    <td align="center">3</td>
  </tr>
  <tr>
    <td align="center">17</td>
    <td>E5-US22</td>
    <td>Gestionar usuarios</td>
    <td>Como desarrollador quiero gestionar usuarios a través del backend para poder controlar el acceso y permisos de cada usuario en el sistema</td>
    <td align="center">3</td>
  </tr>
  <tr>
    <td align="center">18</td>
    <td>E1-US04</td>
    <td>Conocer los testimonios de clientes pasados</td>
    <td>Como Empresario pesquero o Empresa de transportes quiero leer algunos testimonios de clientes anteriores para evaluar la experiencia de otras personas</td>
    <td align="center">2</td>
  </tr>
    <tr>
    <td align="center">19</td>
    <td>E1-US06</td>
    <td>Contacto</td>
    <td>Como Empresario pesquero o Empresa de transportes quiero enviar una solicitud a los dueños de la aplicación web para poder conocer más sobre su trabajo y/o que me den más detalles de la misma</td>
    <td align="center">2</td>
  </tr>
  <tr>
    <td align="center">20</td>
    <td>E2-US10</td>
    <td>Ingreso a la aplicación</td>
    <td>Como Empresario pesquero o Empresa de transportes quiero ingresar mis datos para empezar a hacer uso de la aplicación web</td>
    <td align="center">2</td>
  </tr>
  <tr>
    <td align="center">21</td>
    <td>E1-US03</td>
    <td>Información sobre el procedimiento de uso de la aplicación web</td>
    <td>Como Empresario pesquero o Empresa de transportes quiero visualizar el procedimiento que tendría que hacer para usar este servicio para así conocer el grado de satisfacción que tendre al momento de usar la aplicación web</td>
    <td align="center">1</td>
  </tr>
    <tr>
    <td align="center">22</td>
    <td>E1-US07</td>
    <td>Cambiar idiomas</td>
    <td>Como Empresario pesquero o Empresa de transportes quiero cambiar el idioma de la página web de Inglés al Español para así poder comprender el contenido</td>
    <td align="center">1</td>
  </tr>
</table>