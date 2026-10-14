# practica-wifi-segura

1. ¿Qué protocolo utiliza el sitio?

El protocolo que utiliza la pagina neverssl.com es HTTP significa que el sitio no es seguro, ya que transmite toda la informacion sin ningun tipo de cifrado.

2. ¿Qué información puede observarse durante la solicitud?

Se puede observar el host, GET, user-agent, URL.

3. ¿Qué riesgos existen al navegar mediante HTTP desde una red Wi-Fi pública?

Los riesgos que existen es que un atacante pueda interceptar todo el trafico que no esta protegido, como robar las cookies o inyectar un malware. 

4. ¿Cómo cambiaría este escenario utilizando una VPN?

Al utilizarse una VPN esta misma crea un tunel para que viaje seguro el dispositivo y ayudaria a ocultar la direccion IP, de esta manera un atacante no podria hacer nada ya que ve datos ilegibles.

El tunel seguro: para que no viajen mezclados con todos los datos de los demas usuario, es como que encapsula solamente tu trafico.

El cifrado: antes de que un mensaje o contraseña salga del dispositivo crea una cadena de caracteres caoticas y sin sentido.

La proteccion del trafico: esta misma no puede ser alterada, manipulada o redirigida en el camino por algun tercero.

La privacidad: hace que te vuelvas invisible, como que oculta tu identidad real en los sitios que se visitan. 

¿Qué son SSL/TLS y cómo protegen la información?

SSL (Secure Sockets Layer) y TLS (Transport Layer Security) son para proteger las comunicaciones a través de una red. SSL es un protocolo antiguo que se encuentra obsoleto, actualmente se utiliza TLS.

Cuando un usuario ingresa a un sitio HTTPS, el navegador y el servidor establecen una conexión segura.

Durante este proceso ocurren los siguientes pasos:

1. Negociación: el navegador y el servidor acuerdan los parámetros criptográficos que utilizarán para comunicarse.
2. Autenticación: el servidor presenta un certificado digital que permite al navegador verificar su identidad y comprobar que corresponde al dominio visitado.
3. Establecimiento de claves: ambos extremos establecen las claves criptográficas que utilizarán para proteger los datos.
4. Cifrado de la comunicación: una vez establecida la conexión, los datos se transmiten cifrados mediante algoritmos criptográficos, de modo que terceros no autorizados no puedan leer fácilmente su contenido.
5. Integridad: TLS también permite detectar modificaciones no autorizadas de los datos transmitidos.

TLS proporciona tres propiedades principales:

Confidencialidad: evita que terceros no autorizados lean el contenido de la comunicación.
Integridad: permite detectar si los datos fueron modificados durante la transmisión.
Autenticación: permite comprobar la identidad del servidor mediante su certificado digital.

Diferencia entre HTTP, HTTPS y VPN

HTTP transmite los datos sin cifrarlos por sí mismo. HTTPS utiliza HTTP protegido mediante TLS, mientras que una VPN establece un túnel cifrado entre el dispositivo y un servidor VPN.
Una VPN no reemplaza HTTPS y que el candado del navegador no garantiza que un sitio sea legítimo: también debo comprobar que el dominio sea el correcto.

5. Escribe tus 3 Reglas de Oro para navegar en redes Wi-Fi públicas.

Regla 1: Debo comprobar que el sitio utilice HTTPS y verificar que el dominio sea el correcto. HTTPS utiliza TLS para cifrar la comunicación, proteger su integridad y permitir la autenticación del servidor, reduciendo el riesgo de que terceros lean o modifiquen los datos transmitidos.

Regla 2: Cuando me conecte a una red pública que no controlo, puedo utilizar una VPN confiable y correctamente configurada. El túnel cifrado ayuda a proteger el tráfico frente a otros usuarios de la red local, aunque no sustituye la protección que proporciona HTTPS.

Regla 3: Debo verificar el nombre de la red antes de conectarme, evitar los puntos de acceso desconocidos y desactivar la conexión automática a redes públicas. También debo utilizar contraseñas únicas, activar la autenticación de dos factores y mantener actualizados mis dispositivos para reducir el riesgo de robo de cuentas e información personal.
