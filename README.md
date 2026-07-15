\## Item 1 - Implementación de la PBX con Asterisk



\### Infraestructura



\- \[x] Creación de la instancia EC2 para la PBX.

\- \[x] Configuración de los Security Groups.

\- \[x] Instalación de Ubuntu Server.



\### Instalación de Asterisk



\- \[x] Instalación de Asterisk.

\- \[x] Configuración inicial de la PBX.

\- \[x] Configuración del servicio PJSIP.

\- \[x] Creación de las extensiones SIP.



\### Configuración de extensiones



\- \[x] Extensión 1001 creada.

\- \[x] Extensión 1002 creada.

\- \[x] Registro exitoso de ambas extensiones.



\### Dialplan



\- \[x] Configuración del dialplan.

\- \[x] Pruebas de llamadas entre extensiones.

\- \[x] Verificación del funcionamiento de la PBX.



\### Automatización



\- \[x] Integración del script AGI (`confirmar\\\_cita.agi`).

\- \[x] Validación del funcionamiento del script.



\---



\##  Item 2 - Implementación del SBC y Aseguramiento de la Plataforma VoIP



\### Implementación del SBC



\- \[x] Creación de la instancia EC2 para Kamailio.

\- \[x] Configuración de Security Groups.

\- \[x] Instalación de Kamailio 5.7.

\- \[x] Configuración de `kamailio.cfg`.

\- \[x] Configuración de la dirección pública (Advertise Address).



\### RTPengine



\- \[x] Instalación de RTPengine.

\- \[x] Integración con Kamailio.

\- \[x] Verificación del servicio RTPengine.

\- \[x] Validación del flujo RTP.



\### Seguridad



\- \[x] Implementación de Topology Hiding.

\- \[x] Instalación del módulo TLS.

\- \[x] Generación de certificados autofirmados.

\- \[x] Configuración de `tls.cfg`.

\- \[x] Habilitación de SIP sobre TLS (Puerto 5061).



\### Validación



\- \[x] Pruebas de llamadas entre extensiones a través del SBC.

\- \[x] Verificación del handshake TLS mediante OpenSSL.

\- \[x] Captura del tráfico SIP/TLS utilizando Wireshark.

\- \[x] Captura del flujo RTP.

\- \[x] Validación del funcionamiento del SBC mediante `tcpdump` y Wireshark.

