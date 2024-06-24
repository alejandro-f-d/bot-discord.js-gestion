# 》 Proyecto: 

- Este proyecto consta de la realización de un bot para la gestión de un sistema de reservas y diversas funcionalidades en discord.
- Este bot trabaja mediante [Slash Commands](https://support.discord.com/hc/en-us/articles/1500000368501-Slash-Commands-FAQ#:~:text=With%20Slash%20Commands%2C%20all%20you,using%20Slash%20Commands%20right%20now.)
- Es un proyecto realizado en tiempo libre, puede ser optimizado.
- Utilización de la API de discord.js y la api de google Sheets.

## 》》 Funcionalidades en discord:
- [x] Slash Commands.
- [x] Modmail.

	❓ Un modmail es un sistema de contacto con los administradores y moderadores del servidor mediante el mensaje directo del bot, este chat solo será visible por los moderadores y administradores.
	
	✅ Permite contactar con los usuarios siempre y cuando tengan el md habilitado en el servidor. (Opción de privacidad de discord)
	
	✅ Permite bloquear y desbloquear usuarios de este servicio para evitar el uso indebido.
- [x] Tempchannel.
	❓ Puedes configurar el bot para cree canales en una determinada categoría de discord con un número determinado de miembros que será eliminado cuando el último participante en ese canal lo abandone.
- [x] Sistema de sugerencias.
	
	- Funcionamiento con tres estados:
	  
		1. La sugerencia se encuentra en votación.

		2. La sugerencia se encuentra denegada.

	        3. La sugerencia se encuentra implementada.
- [x] Sistema de reservas. (Al ser un modelo inventado se realiza para un sistema de gestión de mesas de ping pong)

	✅ Este sistema actualiza un google sheet en tiempo real con las reservas realizadas. Cuenta con la opción de establecer un margen máximo de antelación de la reserva.
	
	✅ Los administradores pueden hacer varias un mismo día.
	
	✅ Los usuarios base solo pueden reservar un número limitado de horas y de días.
- [x] Creación de Torneos. 

	✅ Esta gestión también te generá un google sheet con la información de los participantes:

	   - Modalidad individual.

	   - Modalidad parejas.

	✅ Comandos de crear y cerrar torneo.
- [x] Reaction Role.

	❓ Creas un mensaje con reacciones que si un usuario reacciona a un determinado emoji el bot automáticamente le asigna un determinado role.

	⚠️ Es importante que el role sea asignable con los permisos del bot. [Discord Support Docs](https://support.discord.com/hc/es/articles/10388356626711-Conexiones-y-roles-vinculados-Admins#:~:text=Dir%C3%ADgete%20a%20Ajustes%20del%20canal,acceso%20al%20canal%20en%20cuesti%C3%B3n.)

- [x] Comando _Status_ con la información de uso de los recursos y datos del sistema.
# 》 Datos de la implementación: 

- [x] "discord.js": "^14.14.1",

- [x] "fs": "^0.0.1-security",

- [x] "google-auth-library": "^9.5.0",

- [x] "google-spreadsheet": "^4.1.1",

- [x] "os": "^0.1.2",

- [x] "os-utils": "^0.0.14"	