CCNA 2

1. Los usuarios se quejan de un acceso esporádico a Internet cada tarde. ¿Qué se debe hacer o verificar?
```
    Compruebe las estadísticas de la ruta predeterminada para la sobresaturación.
```
2. Consulte la ilustración. ¿Qué hará el router R1 con 
un paquete que tiene una dirección IPv6 de destino 2001:db8:cafe:5::1?
```
    Reenviará el paquete por Serial0/0/0.
 ```  
3. Haga coincidir el número de paso con la secuencia de etapas que se producen durante el proceso de 
conmutación por error de HSRP. (No se utilizan todas las opciones).
```
	ACB
```
4. Seleccione los tres modos de establecimiento de canales PAgP. (Escoja tres opciones).
```
    auto
    deseado
    on
```
5. Consulte la exhibición. Un switch de capa 3 se encarga del routing para tres VLAN y se conecta a un router para obtener conectividad a Internet. 
¿Cuáles son las dos configuraciones que se aplicarían al switch? (Elija dos).
```
	(config)# interface gigabitethernet 1/1
	(config-if)# no switchport
	(config-if)# ip address 192.168.1.2 255.255.255.252

	(config)# ip routing
```
6. El enrutamiento entre VLAN exitoso ha estado funcionando en una red con varias VLAN a través de varios switches durante algún tiempo. Cuando falla un vínculo troncal entre switch y el protocolo de árbol de expansión muestra un vínculo troncal de copia de seguridad, se informa de que los hosts de dos VLAN pueden acceder a algunos recursos de red, pero no a todos los que se podía acceder anteriormente. Los hosts de todas las demás VLAN no tienen este problema. ¿Cuál es la causa más probable de este problema?
```
    Las VLAN permitidas en el vínculo de copia de seguridad no se configuraron correctamente.
``` 	
7. Consulte la ilustración. El administrador de red configura ambos switches como se muestra. Sin embargo, el host C no puede hacer ping al host D y el host E no puede hacer ping al host F. ¿Qué debe hacer el administrador para habilitar esta comunicación?
```
    Configurar cualquier puerto de enlace troncal en el modo dinámico deseado.
```
8. Consulte la ilustración. Según la configuración y el resultado que se muestran, ¿por qué falta la VLAN 99?

9. ¿Cuáles son los tres pares de modos de enlace troncal que establecen un enlace troncal funcional entre dos switches Cisco? (Elija tres).
```
    Dinámico deseado y enlace troncal   
    Dinámico deseado y dinámico automático
    Dinámico deseado y dinámico deseado
```
10. Se ha configurado una ruta estática en un router. Sin embargo, la red de destino ya no existe. ¿Qué debe hacer un administrador para eliminar la ruta estática de la tabla de enrutamiento?
```
    Elimine la ruta usando el comando no ip route .
```
11. Consulte la ilustración. Un administrador de redes agregó una nueva subred a la red y necesita que los hosts de dicha subred reciban direcciones IPv4 del servidor DHCPv4.
¿Qué dos comandos permiten que los hosts de la nueva subred reciban las direcciones del servidor DHCP4? (Elija dos opciones.)
```
	R1(config-if)# ip helper-address 10.2.0.250
	R1(config)# interface G0/0
```
12. Consulte la exhibición. Se configuró el R1 tal como se muestra. Sin embargo, la PC1 no puede recibir ninguna dirección IPv4. ¿Cuál es el problema?

	El comando ip helper-address se aplicó en una interfaz incorrecta.
	
13. Consulte la ilustración. ¿Qué se puede concluir acerca de la configuración mostrada en R1?

	R1 está configurado como un agente de retransmisión DHCPv4.
	
14. ¿Cuáles dos funciones son realizadas por un WLC cuando se usa el control de acceso de medios divididos (MAC)? (Escoja dos opciones).

    Traducción de tramas a otros protocolos
    asociación y re-asociación de clientes itinerantes

15. Una compañía está implementando una red inalámbrica en la instalación de distribución en la periferia de Boston. El depósito es muy grande y necesita utilizar varios puntos de acceso. Debido a que algunos de los dispositivos de la compañía aún operan a 2.4 GHz, el administrador de red decide implementar el estándar 802.11 g. ¿Qué asignación de canales en varios puntos de acceso garantizará que los canales inalámbricos no se superpongan?

    **Canales 1, 6 y 11**
 
16. ¿Qué protocolo debe deshabilitarse para ayudar a mitigar los ataques de VLAN?

    DTP

17. Una política de seguridad de la compañía requiere que todas las direcciones MAC se aprendan y agreguen dinámicamente a la tabla de direcciones MAC y a la configuración en ejecución en cada switch. ¿Qué configuración de seguridad de puertos logrará esto?

    direcciones MAC seguras persistentes

18. ¿Qué ataque de red se mitiga al habilitar la guardia BPDU?

    Switches no fiables en una red

19. Un nuevo switch de capa 3 está conectado a un router y se está configurando para el enrutamiento InterVLAN. ¿Cuáles son tres de los cinco pasos necesarios para la configuración? (Escoja tres opciones).
 
    habilitar el routing IP
    creando interfaces SVI 
    asignando puertos a VLANs

Caso 2:

    habilitar el routing IP
    ingresando «sin switchport» en el puerto conectado al router
    asignando puertos a VLANs

Caso 3:

    habilitar el routing IP
    ingresando «sin switchport» en el puerto conectado al router
    asignar puertos a las VLAN
 
Caso 4:

    creando VLANs
    asignando puertos a VLANs
    creando interfaces SVI

20. Un administrador de red esta configurando una WLAN. ¿Por qué cambiaría el administrador las direcciones IPv4 DHCP predeterminadas en un AP?

    para reducir la interceptación de datos o el acceso a la red inalámbrica mediante un rango de direcciones conocido

21. ¿Qué método de asignación de prefijo IPv6 se basa en el prefijo contenido en los mensajes RA?

    SLAAC
  
22. ¿Qué prefijo IPv6 está diseñado para la comunicación local de enlace?

    fe80::/10

23. ¿Qué dos tipos de protocolos de árbol pueden provocar flujos de tráfico subóptimos asumen porque solamente una instancia de árbol de expansión para la red puenteada entero? (Elija dos).

    STP
    RSTP
	
24. Consulte la ilustración. Todos los switches que se muestran son switches Cisco 2960 con la misma prioridad predeterminada y funcionan en el mismo ancho de banda. ¿Cuáles son los tres puertos que serán los puertos designados de STP? (Elija tres).

    fa0/20
    fa0/11
    fa0/21
    fa0/13
    fa0/9
    fa0/10

25. Para obtener una descripción general del estado del árbol de una red conmutada, un ingeniero de red publica el comando show spanning-tree en un switch. ¿Qué dos elementos de información este comando display? (Elija dos.)

    El rol de los puertos en todas las VLAN.
    El BID de Root Bridge.
	
26. Una la característica de reenvío con su tipo. (No se utilizan todas las opciones.)

27. ¿Qué afirmación describe un resultado después de interconectar varios switches LAN de Cisco?

    El dominio de difusión se amplía a todos los switches.
 
28. ¿Qué información usa un switch para completar la tabla de direcciones MAC?

    la dirección MAC de origen y el puerto de entrada
	
29. ¿Qué es un método para lanzar un ataque de salto de VLAN?

    Introducir un switch falso y habilitar el enlace troncal
   
30. Durante el proceso de AAA, ¿cuándo se implementará la autorización?

    Inmediatamente después de la correcta autenticación en relación con una fuente de datos de AAA

31. ¿Qué protocolo o tecnología desactiva las rutas redundantes para eliminar los bucles de capa 2?

    STP
	
32. Consulte la ilustración. ¿Qué ruta se configuró como ruta estática en una red específica con la dirección del próximo salto?

    S 10.17.2.0/24 [1/0] via 10.16.2.2

33. ¿De qué manera cambia la forma en que un router administra el routing estático si se inhabilita Cisco Express Forwarding?

    Las interfaces Ethernet de accesos múltiples requieren rutas estáticas especificadas completamente para evitar incoherencias de routing.

34. Consulte la ilustración. El router R1 tiene una relación de vecino OSPF con el router ISP a través de la red 192.168.0.32. El enlace de red 192.168.0.36 debe funcionar como respaldo cuando deja de funcionar el enlace OSPF. Se emitió el comando de ruta estática flotante ip route 0.0.0.0 0.0.0.0 S0/0/1 100 en el R1, y ahora el tráfico usa el enlace de respaldo, aun cuando el enlace OSPF está activo y en funcionamiento. ¿Qué modificaciones se deben realizar al comando de ruta estática a fin de que el tráfico use solo el enlace OSPF cuando este se encuentre activo?

    Cambiar la distancia administrativa a 120.

35. En una página Resumen del WLC 3504 de Cisco (Avanzado > Resumen ), ¿qué pestaña permite a un administrador de red configurar una WLAN determinada con una directiva WPA2?

    Redes de área local inalámbrica (WLAN)

36. ¿Cuál es el término común que se da a los mensajes de registro SNMP generados por dispositivos de red y enviados al servidor SNMP?

    trampas

37. Un administrador de red de una pequeña empresa publicitaria está configurando la seguridad WLAN mediante el método PSK WPA2. ¿Qué credenciales necesitan los usuarios de oficina para conectar sus portátiles a la WLAN?

    una frase de contraseña de usuario

Explique: Cuando se configura una WLAN con WPA2 PSK, los usuarios inalámbricos deben conocer la clave previamente compartida para asociarse y autenticarse con el AP.

38. ¿Qué tipo de ruta estática se configura con una mayor distancia administrativa a fin de proporcionar una ruta de respaldo a una ruta descubierta por un protocolo de routing dinámico?

    Ruta estática flotante

39. Consulte la ilustración. El R1 se configuró con el comando de ruta estática ip route 209.165.200.224 255.255.255.224 S0/0/0 y, en consecuencia, los usuarios en la red 172.16.0.0/16 no pueden acceder a los recursos de Internet. ¿Cómo se debe modificar esta ruta estática para permitir que el tráfico de usuarios de la LAN llegue a Internet?

    Cambiar la red y la máscara de destino a 0.0.0.0 0.0.0.0.

40. Consulte la ilustración. El router R1 actualmente utiliza una ruta de EIGRP obtenida de la Sucursal2 para acceder a la red 10.10.0.0/16. ¿Qué ruta estática flotante creará una ruta de respaldo a la red 10.10.0.0/16 en caso de que el enlace entre el R1 y la Sucursal2 deje de funcionar?

    ip route 10.10.0.0 255.255.0.0 209.165.200.225 100
	
41. ¿Qué comando crea una ruta estática en el R2 para llegar a la PC B?

    R2(config)# ip route 172.16.2.0 255.255.255.0 172.16.3.1

42. Consulte la ilustración. ¿Cuáles de las siguientes son tres conclusiones que se pueden extraer a partir del resultado que se muestra? (Elija dos).

    El canal de puerto ID es 2.
    El grupo EtherChannel no funciona.

43. ¿Cuál es el efecto de ingresar el comando de configuración ip dhcp snooping en un switch?

    Habilita el DHCP snooping globalmente en un Switch.

44. Consulte la exhibición. ¿Qué dirección MAC de destino se utiliza cuando las tramas se envían de la estación de trabajo al gateway predeterminado?

    La dirección MAC del router virtual

45. ¿Cuáles son tres técnicas de mitigación de ataques de VLAN? (Elija tres opciones.)

    Habilitar manualmente los enlaces troncales.
    Desactivar el DTP.
    Configurar la VLAN nativa en una VLAN sin usar.

46. Consulte la exhibición. Además de las rutas estáticas que direccionan el tráfico a las redes 10.10.0.0/16 y 10.20.0.0/16, el router HQ también está configurado con el siguiente comando:

ip route 0.0.0.0 0.0.0.0 serial 0/1/1

	Los paquetes con una red de destino que no sea 10.10.0.0/16 ni 10.20.0.0/16 ni una red conectada directamente serán reenviados a Internet.
	
47. ¿Qué método de cifrado inalámbrico es la manera más segura?

    WEP
    WPA
    WPA2 con AES
    WPA2 con TKIP
	
48. Consulte la ilustración. Un administrador de red ha conectado dos switches juntos con la tecnología EtherChannel. Si STP se está ejecutando, ¿cuál será el resultado final?

    El STP bloqueará uno de los enlaces redundantes.

49. Consulte la ilustración. ¿Qué ruta estática introduciría un técnico de TI para crear una ruta de respaldo a la red 172.16.1.0 que solo se utiliza si la ruta principal aprendida a través de RIP falla?

    ip route 172.16.1.0 255.255.255.0 s0/0/0 121

50. Después de conectar cuatro PC a los puertos del switch, configurar el SSID y establecer las propiedades de autenticación para una red de oficina pequeña, un técnico prueba correctamente la conectividad de todos los PC conectados al switch y a la WLAN. A continuación, se configura un firewall en el dispositivo antes de conectarlo a Internet. ¿Qué tipo de dispositivo de red incluye todas las características descritas?

    Router inalámbrico

51. Un administrador intenta eliminar configuraciones de un switch. Luego de usar el comando erase startup-config y de volver a cargar el switch, el administrador advierte que aún existen las VLAN 10 y 100 en el switch. ¿Por qué no se eliminaron estas VLAN?

    Porque estas VLAN se almacenan en un archivo denominado vlan.dat que está ubicado en la memoria flash y se debe eliminar de forma manual.

52. Consulte la ilustración. ¿Cuáles son los posibles roles de puerto para los puertos A, B, C y D en esta red con el protocolo RSTP habilitado?
 
    Alternativo, designado, raíz, raíz

53. ¿Cuál es una opción de configuración segura para el acceso remoto a un dispositivo de red?

    Configurar SSH.

54. Una el estado de enlace con el estado de la interfaz y el protocolo. (No se utilizan todas las opciones.)

55. Consulte la ilustración. El host A envió un paquete al host B. ¿Cuáles serán las direcciones MAC e IP de origen en el paquete cuando este llegue al host B?

	MAC de origen: 00E0.FE91.7799
	IP de origen: 10.1.1.10

56. Una la descripción el tipo de VLAN correcto. (No se utilizan todas las opciones.)

57. Consulte la exhibición. Un administrador de red configura el routing entre VLAN en una red. De momento, solo se usa una VLAN, pero pronto se agregarán más. ¿Cuál es el parámetro que falta y que se muestra como signo de interrogación destacado en el gráfico?

    El que identifica el número de VLAN nativa.
    El que identifica el tipo de encapsulación que se utiliza.
    El que identifica el número de VLAN.
    El que identifica la cantidad de hosts que se permiten en la interfaz.
    El que identifica la subinterfaz.

58. Consulte la exhibición. ¿Cómo se reenvía una trama desde la PCA hacia la PCC si la tabla de direcciones MAC en el switch SW1 está vacía?

    SW1 satura todos los puertos en SW1 con la trama, a excepción del puerto a través del cual la trama ingresó al switch.

59. Una los tipos de mensaje DHCP con el orden del proceso de DHCPv4. (No se utilizan todas las opciones).

60. Después de que un host ha generado una dirección IPv6 usando el proceso de DHCPv6 o SLAAC, como puede el host verificar que la dirección es única y por lo tanto utilizable?

    El host envía un mensaje de solicitud de vecino ICMPv6 a la direccion aprendida por DHCPv6 o SLAAC y si no recibe anuncio de vecino de vuelta , la direccion se considera unica.

61. ¿Qué acción se lleva a cabo cuando la dirección MAC de origen de una trama que ingresa a un switch no está en la tabla de direcciones MAC?
  
    El switch agrega la dirección MAC y el número de puerto entrante a la tabla.
    
62. Un técnico está solucionando problemas con una WLAN lenta y decide utilizar el enfoque de división del tráfico. ¿Qué dos parámetros tendrían que configurarse para hacer esto? (Escoja dos opciones).

    Configure la banda de 2.4 GHz para el tráfico básico de Internet que no es sensible al tiempo.

63. Un administrador de red está agregando una nueva WLAN en un WLC de la serie 3500 de Cisco. ¿Qué pestaña debe usar el administrador para crear una nueva interfaz VLAN que se utilizará para la nueva WLAN?

    CONTROLADOR
	
64. ¿Qué dos configuraciones de router inalámbrico predeterminadas pueden afectar la seguridad de la red? (Elija dos opciones).

    Se difunde el SSID.
    Se configura una contraseña de administrador ampliamente conocida.

65. En comparación con las rutas dinámicas, ¿cuáles son las dos ventajas de utilizar rutas estáticas en un router? (Elija dos opciones.)

    Mejoran la seguridad de la red.
    Utilizan menos recursos del router.

66. Consulte la exhibición. ¿Cuál es la métrica para reenviar un paquete de datos con la dirección de destino IPv6 2001:DB8:ACAD:E:240:BFF:FED4:9DD2?

    2682112

67. ¿Qué protocolo o tecnología es un protocolo propietario de Cisco que se habilita automáticamente en switches 2960?

    DTP

68. Un administrador de red esta configurando una WLAN. ¿Por qué el administrador usaría un controlador WLAN?

    para facilitar la configuración de grupos y la administración de varias WLAN a través de un WLC

69. Consulte la exhibición. Un ingeniero de red está configurando un routing IPv6 en la red. ¿Qué comando emitido en el router HQ configurará una ruta predeterminada a Internet para reenviar paquetes a una red de destino IPv6 que no se enumera en la tabla de routing?
 
    ipv6 route ::/0 serial 0/1/1

70. Un administrador de red ha encontrado a un usuario que envía una trama 802.1Q de doble etiqueta a un switch. ¿Cuál es la mejor solución para prevenir este tipo de ataque?

    Las VLAN para los puertos de acceso de usuario deben ser distintas de las VLAN nativas utilizadas en los puertos troncal.

71. Consulte la ilustración. El administrador de red está configurando la función de seguridad del puerto en el switch SWC. El administrador emitió el comando show port-security interface fa 0/2 para verificar la configuración. ¿Qué se puede concluir a partir de la salida que se muestra? (Escoja tres opciones).

    Las infracciones de seguridad harán que este puerto se cierre inmediatamente.
    Este puerto está activo actualmente.
    El modo de puerto del switch para esta interfaz es el modo de acceso.

72. ¿Cuáles son las dos afirmaciones que describen características de los puertos enrutados en un switch multicapa? (Elija dos opciones).

    En una red conmutada, se configuran principalmente entre los switches de las capas núcleo y de distribución.
    No se asocian a una VLAN determinada.

73. Un administrador de red utiliza el modelo de router-on-a-stick para configurar un switch y un router para el routing entre VLAN. ¿Qué configuración se debe aplicar al puerto del switch que se conecta al router?

    Configurar el puerto como puerto de enlace troncal 802.1q.

74. ¿Cuál es el prefijo IPv6 que se utiliza para direcciones de enlace local?

    FE80::/10

75. ¿Cuál es el efecto de ingresar el comando de configuración ip dhcp snooping limit rate 6 en un switch?

    Restringe el número de mensajes de detección, por segundo, que se recibirán en la interfaz.

76. ¿Qué acción realiza un cliente DHCPv4 si recibe más de un DHCPOFFER de varios servidores DHCP?

    Envía un DHCPREQUEST que identifica qué oferta de arrendamiento está aceptando el cliente.

77. Consulte la ilustración. ¿Qué enlace troncal no enviará tráfico después de que el proceso de elección de puente raíz se complete?

    Enlace troncal2

78. Un ingeniero WLAN implementa un WLC y cinco puntos de acceso inalámbricos utilizando el protocolo CAPWAP con la función DTLS para asegurar el plano de control de los dispositivos de red. Durante la prueba de la red inalámbrica, el ingeniero de WLAN nota que el tráfico de datos se está intercambiando entre el WLC y los AP en texto sin formato y no se está cifrando. ¿Cuál es la razón más probable para esto?

    Aunque DTLS está habilitado de manera predeterminada para asegurar el canal de control CAPWAP, está deshabilitado de manera predeterminada para el canal de datos.

79. ¿Qué método de autenticación inalámbrica depende de un servidor de autenticación RADIUS?

    WPA2 comercial
   
80. ¿Cuáles son los dos modos VTP que permiten la creación, modificación y eliminación de las VLAN en el switch local? (Elija dos opciones.)

    Transparente
    Servidor

81. Consulte la ilustración. ¿Qué hosts recibirán solicitudes de ARP desde el host A, considerando que el puerto Fa0/4 en ambos switches está configurado para llevar tráfico a varias VLAN? (Elija tres opciones.)

    host D
    host C
    host F
	
82. ¿Cuál sería el motivo principal por el que un atacante podría lanzar un ataque de sobrecarga de la dirección MAC?

    Para que el atacante pueda ver las tramas con destino a otros hosts

83. Un analista de ciberseguridad está utilizando la herramienta macof para evaluar configuraciones de switches implementados en la red troncal de una organización. ¿A qué tipo de ataque LAN se dirige el analista durante esta evaluación?

    Desbordamiento de tabla de direcciones MAC

84. ¿Qué declaración es correcta acerca de cómo un switch de Capa 2 determina cómo reenviar fotogramas?

    Las decisiones de reenvío de tramas se basan en la asignación de puertos y la dirección MAC en la tabla CAM.

85. ¿Qué tres estándares de Wi-Fi funcionan en el rango de frecuencias 2.4 GHz? (Elija tres).

    802.11g
    802.11b
    802.11n

86. Un administrador de red esta configurando una WLAN. ¿Por qué el administrador usaría varios AP ligeros?
   
    para facilitar la configuración de grupos y la administración de varias WLAN a través de un WLC

87. Un administrador de redes configura un nuevo switch de Cisco para el acceso de administración remota. ¿Qué tres elementos se deben configurar en el switch para realizar esta tarea? (Elija tres opciones.)

    Líneas vty
    Gateway predeterminado
    Dirección IP
	
88. Consulte la exhibición. Después de intentar introducir la configuración que se muestra en el router RTA, un administrador recibe un error, y los usuarios en la VLAN 20 informan que no pueden llegar a los usuarios en la VLAN 30. ¿Qué está causando el problema?

    RTA usa la misma subred para la VLAN 20 y la VLAN 30.

89. Un administrador de red ha configurado un router para la operación DHCPv6 sin estado. Sin embargo, los usuarios informan de que las estaciones de trabajo no reciben información del servidor DNS. ¿Qué dos líneas de configuración del router deben verificarse para garantizar que el servicio DHCPv6 sin estado esté configurado correctamente? (Escoja dos opciones).

    La línea dns-server se incluye en la sección ipv6 dhcp pool .
    Se introduce el indicador ipv6 nd other-config-flag para la interfaz que se enfrenta al segmento LAN.
 
90. Un administrador de redes configura la función de seguridad de puertos en un switch. La política de seguridad especifica que cada puerto de acceso debe permitir hasta dos direcciones MAC. Cuando se alcanza al número máximo de direcciones MAC, se descarta una trama con la dirección MAC de origen desconocida y se envía una notificación al servidor de syslog. ¿Qué modo de violación de seguridad se debe configurar para cada puerto de acceso?

    restrict

91. Un administrador de red utiliza }el comando de configuración global predeterminado portfast bpduguard del árbol de expansión para habilitar la protección BPDU en un switch. Sin embargo, la protección BPDU no está activada en todos los puertos de acceso. ¿Cuál es la causa del problema?

    PortFast no está configurado en todos los puertos de acceso.

92. ¿Cuáles son los dos protocolos que se usan para proporcionar autenticación de AAA basada en servidor? (Elija dos opciones.)

    Basado en MAC
    TACACS+

93. ¿Qué ataque a la red intenta crear un DoS para los clientes al evitar que obtengan un arrendamiento de DHCP?

    Ataque de tabla CAM
    Suplantación de dirección IP
    Suplantación de identidad de DHCP
    Inanición DHCP

94. Un administrador de red está preparando la implementación PVST+ rápido en una red de producción. ¿Cómo determinan los tipos de links rápidos PVST+ en las interfaces del switch?

    Determinan los tipos de link automáticamente.
   
95. ¿Cuáles de los siguientes son dos motivos para que un administrador de red divida una red con un switch de capa 2? (Elija dos).

    Para aumentar el ancho de banda de usuario.
    Para aislar el tráfico entre segmentos.
    
96. ¿Qué acción se lleva a cabo cuando una trama que ingresa a un switch tiene una dirección MAC de destino de unidifusión que aparece en la tabla de direcciones MAC?

    El switch actualiza el temporizador de actualización para la entrada.
    El switch purga toda la tabla de direcciones MAC.
    El switch reemplaza la entrada anterior y usa el puerto más actual.
    El switch reenvía la trama fuera del puerto especificado.

97. Consulte la ilustración.¿Qué comando static route se puede ingresar en R1 para reenviar tráfico a la LAN conectada a R2?

    ruta ipv6 2001:db 8:12:10: :/64 S0/0/1 fe80: :2

98. Consulte la ilustración. Un administrador de red revisa la configuración del switch S1. ¿Qué protocolo se implementó para agrupar varios puertos de físicos en un único enlace lógico?

    DTP
    Protocolo de control de agregación de enlaces (LACP)
    PAgP
    STP

99. Consulte la ilustración. ¿Qué afirmación que se muestra en el resultado permite que el router R1 responda a las solicitudes de DHCPv6 sin información de estado?

    ipv6 nd other-config-flag​

100. ¿Cuál es el efecto de ingresar el comando shutdown configuration en un switch?

    Deshabilita un puerto no utilizado.

101. ¿Qué protocolo o tecnología requiere que los switches estén en modo servidor o modo cliente?

    VTP

102. ¿Por qué se requiere la indagación DHCP cuando se utiliza la función de inspección dinámica de ARP?

    Utiliza la base de datos de enlace de dirección MAC a dirección IP para validar un paquete ARP.
 
103. ¿Cuáles son las tres afirmaciones que describen con precisión las configuraciones de dúplex y de velocidad en los switches Cisco 2960? (Elija tres).

    La configuración de dúplex y de velocidad de cada puerto del switch se puede establecer manualmente.
    Cuando la velocidad se establece en 1000 Mb/s, los puertos del switch funcionan en modo full-duplex.
    Una falla de autonegociación puede ocasionar problemas de conectividad.

104. ¿Cuál es una de las desventajas del método de base de datos local para proteger el acceso a dispositivos que se puede resolver usando AAA con servidores centralizados?

    Las cuentas de usuario deben configurarse localmente en cada dispositivo, por lo que la solución de autenticación no es escalable.

105. Una empresa acaba de cambiar a un nuevo ISP. El ISP ha completado y comprobado la conexión desde su sitio a la empresa. Sin embargo, los empleados de la empresa no pueden acceder a Internet. ¿Qué se debe hacer o verificar?

    Asegúrese de que la antigua ruta predeterminada se haya eliminado de los routers perimetrales de la empresa.

106. ¿Cuál es el efecto de ingresar el comando show ip dhcp snooping binding configuration en un switch?

    Muestra las asociaciones de direcciones IP a Mac para interfaces de switch.

107. ¿Qué comando inicia el proceso para agrupar dos interfaces físicas para crear un grupo EtherChannel mediante el LACP?

    interface range GigabitEthernet 0/4-5

108. ¿En qué situación un técnico usaría el comando de switch show interfaces ?

    Cuando los paquetes se eliminan de un host en particular conectado directamente.
   
109. Consulte la ilustración. Un administrador de red configura R1 para el enrutamiento entre VLAN entre VLAN 10 y VLAN 20. Sin embargo, los dispositivos de VLAN 10 y VLAN 20 no pueden comunicarse. Basado en la configuración de la exposición, ¿cuál es una posible causa del problema?

    La interfaz de comando GigabitEthernet 0/0.1 es incorrecta.

110. Consulte la ilustración. Considere que se acaba de restaurar la alimentación principal. La PC3 emite una solicitud de DHCP IPv4 de difusión. ¿A qué puerto reenvía esta solicitud SW1?

    Solo a Fa0/1, Fa0/2 y Fa0/3
 
111. Consulte la exhibición. Si las direcciones IP del router de gateway predeterminado y del servidor DNS son correctas, ¿cuál es el problema de configuración?

    No se incluye la dirección IP del router de gateway predeterminado en la lista de direcciones excluidas.

112. ¿Qué opción muestra una ruta estática predeterminada IPv4 correctamente configurada?

    ip route 0.0.0.0 0.0.0.0 S0/0/0

113. Los usuarios de una LAN no pueden acceder a un servidor web de la empresa, pero pueden llegar a otro lugar. ¿Qué se debe hacer o verificar?

    Compruebe que la ruta estática al servidor está presente en la tabla de enrutamiento.

114. ¿Qué protocolo o tecnología permite que los datos se transmitan a través de enlaces de switch redundantes?

    STP
 
115. ¿Qué acción se lleva a cabo cuando un fotograma que ingresa a un switch tiene una dirección MAC de destino de unidifusión que no está en la tabla de direcciones MAC?

    El switch reenviará la trama a todos los puertos excepto el puerto entrante.

116. ¿Qué acción se lleva a cabo cuando la dirección MAC de origen de una trama que ingresa a un switch aparece en la tabla de direcciones MAC asociada a un puerto diferente?

    El switch reemplaza la entrada anterior y usa el puerto más actual.

117. ¿Cuáles son los tres pasos que se deben seguir antes de mover un switch de Cisco a un nuevo dominio de administración VTP? (Elija tres opciones).

    Seleccionar el modo y la versión del VTP.
    Configurar el switch con el nombre del dominio de administración nuevo.
    Reiniciar el switch.
    
118. Un administrador de red esta configurando una WLAN. ¿Por qué el administrador utilizaría servidores RADIUS en la red?

    para facilitar la configuración de grupos y la administración de varias WLAN a través de un WLC
    para supervisar el funcionamiento de la red inalámbrica
    para restringir el acceso a la WLAN sólo por usuarios autorizados y autenticados
    para centralizar la administración de varias WLAN

119. ¿Qué protocolo o tecnología utiliza IP de origen a IP de destino como mecanismo de equilibrio de carga?

    EtherChannel
   
120. ¿Qué acción se lleva a cabo cuando la dirección MAC de origen de una trama que ingresa a un switch está en la tabla de direcciones MAC?

    El switch actualiza el temporizador de actualización para la entrada.

121. Consulte la exhibición. Un administrador de red configura un router como servidor de DHCPv6. El administrador emite un comando show ipv6 dhcp pool para verificar la configuración. ¿Cuál de estas afirmaciones explica el motivo por el que el número de clientes activos es 0?

    El servidor de DHCPv6 no mantiene el estado cuando se implementa DHCPv6 sin estado.
  
122. ¿Cuál es el efecto de ingresar el comando de configuración ip arp inspection validate src-mac en un switch?

    Comprueba la dirección de origen L2 en el encabezado de Ethernet contra la dirección del remitente L2 en el cuerpo ARP.
 
123. ¿Qué acción se lleva a cabo cuando una trama que ingresa a un switch tiene una dirección MAC de destino de multidifusión?

    El switch reenviará la trama a todos los puertos excepto el puerto entrante.

124. ¿Qué técnica de mitigación evitaría que los servidores no autorizados proporcionen parámetros de configuración IP falsos a los clientes?

    activar la indagación DHCP

125. Los usuarios de la sucursal pudieron acceder a un sitio por la mañana, pero no han tenido conectividad con el sitio desde la hora del almuerzo. ¿Qué se debe hacer o verificar?

    Utilice el comando «show ip interface brief» para ver si una interfaz está inactiva.

126. Una el paso con cada descripción de la secuencia de arranque del switch. (No se utilizan todas las opciones).

127. Consulte la ilustración. Un administrador intenta instalar una ruta estática IPv6 en el router R1 para llegar a la red conectada al router R2. Después de introducir el comando de ruta estática, la conectividad a la red sigue fallando. ¿Qué error se cometió en la configuración de la ruta estática?

    La interfaz es incorrecta.

128. ¿Cuál es el efecto de ingresar el comando de configuration switchport mode access en un switch?

    Deshabilita DTP en una interfaz que no sea troncal.

129. Consulte la ilustración. Un administrador de red está configurando el router R1 para la asignación de direcciones IPv6. En función de la configuración parcial, ¿qué esquema de asignación de direcciones de unidifusión global IPv6 piensa implementar el administrador?

    Con información de estado
 
130. Consulte la ilustración. Un administrador de red configuró los routers R1 y R2 como parte del grupo 1 de HSRP. Después de volver a cargar los routers, un usuario en el Host1 se quejó de la falta de conectividad a Internet. El administrador de redes emitió el comando show standby brief en ambos routers para verificar las operaciones de HSRP. Además, el administrador observó la tabla ARP en el Host1. ¿Qué entrada de la tabla ARP del Host1 se debe observar para obtener conectividad a Internet?

    La dirección IP Virtual y la dirección MAC virtual para el grupo 1 de HSRP

131. Un técnico junior estaba agregando una ruta a un router LAN. Un traceroute a un dispositivo en la nueva red reveló una ruta incorrecta y un estado inalcanzable. ¿Qué se debe hacer o verificar?

    Compruebe la configuración de la interfaz de salida en la nueva ruta estática.
  
132. Un administrador de red esta configurando una WLAN. ¿Por qué el administrador aplicaría WPA2 con AES a la WLAN?

    para proporcionar privacidad e integridad al tráfico inalámbrico mediante el encriptado

133. ¿En qué puertos del switch se debe habilitar la protección BPDU para mejorar la estabilidad del STP?

    todos los puertos habilitados para Portfast

134. ¿Cuál es el efecto de ingresar el switchport port-security switchport port-security en un switch?

    Permite la seguridad del puerto en una interfaz.

135. Un ingeniero de red está resolviendo una red inalámbrica recientemente implementada que esté utilizando las últimas normas de 802.11. Cuando los usuarios acceden los servicios de ancho de banda alto como transmisión de video, el rendimiento inalámbrico es pobre. Para mejorar el rendimiento que el ingeniero de red decide configurar una banda de frecuencia SSID de 5 Ghz y capacitar a los usuarios para usar ese SSID para servicios de transmisión de medios. ¿Qué podría esta solución mejorar el rendimiento inalámbrico para ese tipo de servicio?

    Banda dual y 5 GHz tiene más canales y se fortalece menos que la banda de 2.4 GHz, lo que facilita más adecuado a fluir multimedia.
    
136. Un administrador de red esta configurando una WLAN. ¿Por qué el administrador usaría un hub WLAN?

    para facilitar la configuración de grupos y la administración de varias WLAN a través de un WLC

137. ¿Qué comando habilita un router para que este comience a enviar mensajes que le permiten configurar una dirección de enlace local sin utilizar un servidor DHCP IPv6?

    Comando ipv6 unicast-routing

138. ¿Cuál es el efecto de ingresar el comando de configuración ip arp inspection vlan 10 en un switch?

    Habilita DAI en interfaces específicas de un switch previamente configuradas con DHCP snooping.

139. ¿Qué protocolo o tecnología administra las negociaciones troncales entre switches?

    DTP

140. ¿Qué protocolo o tecnología utiliza un router en espera para asumir la responsabilidad de reenvío de paquetes si falla el router activo?

    HSRP

141. ¿Qué protocolo o tecnología define un grupo de routeres, uno de ellos definido como activo y otro como en espera?

    HSRP

142. Un administrador de red esta configurando una WLAN. ¿Por qué el administrador deshabilitaría la función de difusión para el SSID?

    para eliminar a los usuarios externos que escanean los SSID disponibles en el área

143. Los empleados no pueden conectarse a servidores en una de las redes internas. ¿Qué se debe hacer o verificar?

    Utilice el comando «show ip interface brief» para ver si una interfaz está inactiva.

144. Un técnico está configurando un router para una pequeña empresa con varias WLAN y no necesita la complejidad de un protocolo de enrutamiento dinámico. ¿Qué se debe hacer o verificar?

    Cree rutas estáticas a todas las redes internas y una ruta predeterminada a Internet.

_33. ¿Cuál es el efecto de ingresar el comando de configuración de spanning-tree portfast en un switch?

    Habilita portfast en una interfaz de conmutador específica.

_74. Consulte la ilustración. ¿Qué enlace troncal no reenviará el tráfico después de que se complete el proceso de elección del puente raíz?

    Trunk2

_88. ¿Qué plan de mitigación es mejor para frustrar un ataque DoS que está creando un desbordamiento de la tabla de direcciones MAC?

    Habilite la seguridad del puerto.

_90. ¿Qué mensaje DHCPv4 enviará un cliente para aceptar una dirección IPv4 ofrecida por un servidor DHCP?

    transmite DHCPREQUEST
 
93. Una coincidir el propósito con su tipo de mensaje DHCP. (No se utilizan todas las opciones).

_94. ¿Qué protocolo agrega seguridad a las conexiones remotas?

    SSH

_95. Consulte la ilustración. Un administrador de red está verificando la configuración del enrutamiento InterVLAN. Los usuarios se quejan de que la PC2 no puede comunicarse con la PC1. Según el resultado, ¿cuál es la posible causa del problema?

    El comando encapsulation dot1Q 5 contiene la VLAN incorrecta.
	
_97. Una coincidir cada tipo de mensaje DHCP con su descripción. (No se utilizan todas las opciones).

Coloque las opciones en el siguiente orden:

    un cliente que inicia un mensaje para encontrar un servidor DHCP – DHCPDISCOVER
    un servidor DHCP que responde a la solicitud inicial de un cliente: DHCPOFFER
    el cliente acepta la dirección IP proporcionada por el servidor DHCP – DHCPREQUEST
    el servidor DHCP confirmando que la concesión ha sido aceptada – DHCPACK
	
_129. Se agregará un nuevo conmutador a una red existente en una oficina remota. El administrador de la red no quiere que los técnicos de la oficina remota puedan agregar nuevas VLAN al switch, pero el conmutador debe recibir actualizaciones de VLAN desde el dominio VTP. ¿Qué dos pasos se deben realizar para configurar VTP en el nuevo conmutador para cumplir con estas condiciones? (Elija dos opciones.)

    Configure el nuevo conmutador como cliente VTP.
    Configure el nombre de dominio del VTP existente en el nuevo conmutador.
    
_134. Un administrador se da cuenta de que se están cayendo grandes cantidades de paquetes en uno de los enrutadores de sucursal. ¿Qué se debe hacer o verificar?

    Verifique la tabla de enrutamiento para ver si falta una ruta estática.

_135. ¿Cuáles son las dos características del switch que podrían ayudar a aliviar la congestión de la red? (Elija dos opciones.)

    cambio interno rápido
    búferes de marcos grandes

_136. ¿Cuál es el resultado de conectar dos o más conmutadores juntos?

    Se aumenta el tamaño del dominio de transmisión.
	
_141. Consulte la ilustración. La PC-A y la PC-B están en la VLAN 60. La PC-A no puede comunicarse con la PC-B. ¿Cuál es el problema?

    La VLAN que utiliza la PC-A no está en la lista de VLAN permitidas en el tronco.

_145. Un administrador de red está configurando una WLAN. ¿Por qué el administrador deshabilitaría la función de transmisión para el SSID?

    para eliminar a los forasteros que buscan SSID disponibles en el área
 
_155. Un administrador de red está configurando una WLAN. ¿Por qué el administrador cambiaría las direcciones DHCP IPv4 predeterminadas en un AP?

    para reducir que personas externas intercepten datos o accedan a la red inalámbrica mediante el uso de un rango de direcciones conocido

_158. ¿Qué dirección y longitud de prefijo se utiliza al configurar una ruta estática predeterminada IPv6?

    ::/0

_159. ¿Cuáles son dos características de Cisco Express Forwarding (CEF)? (Elija dos opciones.)

    Este es el mecanismo de reenvío más rápido en los enrutadores y conmutadores multicapa de Cisco.
    Los paquetes se reenvían según la información de la FIB y una tabla de adyacencia.

_160. ¿Qué término describe la función de un switch Cisco en el control de acceso basado en puertos 802.1X?

    autenticador
 
_161. ¿Qué solución de Cisco ayuda a prevenir la suplantación de ARP y los ataques de envenenamiento de ARP?

    Inspección dinámica de ARP

_162. ¿Cuál es una ventaja de PVST +?

    PVST + optimiza el rendimiento en la red mediante el uso compartido de la carga.

_166. Una pequeña empresa editorial tiene un diseño de red tal que cuando se envía una transmisión en la LAN, 200 dispositivos reciben la transmisión transmitida. ¿Cómo puede el administrador de red reducir la cantidad de dispositivos que reciben tráfico de transmisión?

    Segmente la LAN en LAN más pequeñas y enrute entre ellas. *

167. ¿Qué define una ruta de host en un router Cisco?

    Una configuración de ruta de host estática IPv4 utiliza una dirección IP de destino de un dispositivo específico y una máscara de subred /32.

_168. ¿Qué más se requiere al configurar una ruta estática IPv6 usando una dirección local de enlace de siguiente salto?

    número y tipo de interfaz

_169. Un técnico está configurando una red inalámbrica para una pequeña empresa utilizando un enrutador inalámbrico SOHO. ¿Qué dos métodos de autenticación se utilizan si el enrutador está configurado con WPA2? (Elija dos opciones.)

    personal
    empresa

_170. ¿Qué técnica de mitigación evitaría que los servidores no autorizados proporcionen parámetros de configuración de IPv6 falsos a los clientes?

    habilitando DHCPv6 Guard

_171. Una PC ha enviado un mensaje RS a un enrutador IPv6 conectado a la misma red. ¿Qué dos datos enviará el enrutador al cliente? (Elija dos opciones.)

    longitud del prefijo
    prefijo

_172. Mientras asisten a una conferencia, los participantes utilizan computadoras portátiles para conectarse a la red. Cuando un orador invitado intenta conectarse a la red, la computadora portátil no muestra ninguna red inalámbrica disponible. ¿El punto de acceso debe estar funcionando en qué modo?

    activo

_173. ¿Qué tres componentes se combinan para formar un ID de puente?

    ID de sistema extendido
    prioridad de puente
    dirección MAC

174. ¿Cuál es el efecto de ingresar el comando de configuración de spanning-tree portfast en un switch?

    Habilita portfast en una interfaz de conmutador específica.
