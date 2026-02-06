#Restablecer contraseña a un usuario windows

#Síntomas
-Usuario no puede iniciar sesión en Windows con su cuenta corporativa.
-Mensajes como “ El nombre de usuario o la contraseña son incorrectos” o “La contraseña ha expirado”.
-La cuenta está bloqueada tras varios intentos fallidos

#Solución paso a paso (5–8 pasos)

El administrador abre Usuarios y equipos de Active Directory.
Busca el departamento y la cuenta del usuario afectado.
Clic derecho > Restablecer contraseña.
Ingresa una contraseña temporal segura.
Marcar “El usuario debe cambiar la contraseña al iniciar sesión”.
Comunicar la contraseña temporal al usuario.

#Validación
1. Confirmar que el usuario puede iniciar sesión correctamente.
2. Verificar en Active Directory que la cuenta ya no aparece como bloqueada.

#Escalamiento (si no funciona)

* El equipo maneja problemas avanzados como cuentas corruptas, problemas en los controladores de Dominio o políticas de grupo conflictivas.
* Escalar al departamento de Infraestructura de servidores.

#Nota de seguridad
No compartir contraseñas por canales no seguros y/o públicos y cambiarla inmediatamente después del primer inicio de sesión
