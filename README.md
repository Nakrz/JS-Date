# Método Date en JavaScript





El método date  **almacena la fecha, la hora, y brinda métodos para administrarlas**. Por ejemplo, podemos usarlo para almacenar horas de creación o  modificación, medir tiempo, o simplemente mostrar en pantalla la fecha  actual.



Aqui estan algunas de sus funciones y sus significados



- `Date.prototype.getDate()` 

   Retorna el día del mes (1–31) para la fecha especificada acorde a la hora local.

  

- Date.prototype.getDay()  Retorna el día de la semana (0–6) para la fecha especificada acorde a la hora local.

  

- Date.prototype.getFullYear()  Retorna el año (4 dígitos para años de 4 dígitos) para la fecha especificada acorde a la hora local.

  

- Date.prototype.getHours()  Retorna la hora (0–23) para la fecha especificada acorde a la hora local.

  

- Date.prototype.getMilliseconds()  Retorna los milisegundos (0–999) para la fecha especificada acorde a la hora local.

  

- Date.prototype.getMinutes()  Retorna los minutos (0–59) para la fecha especificada acorde a la hora local.

  

- `Date.prototype.getMonth()` Retorna el mes (0–11) para la fecha especificada acorde a la hora local.

  

- `Date.prototype.getSeconds()` Retorna los segundos (0–59) para la fecha especificada acorde a la hora local.

  

- `Date.prototype.getTime()`  Retorna el valor numérico de la fecha especificada como el número de  milisegundos transcurridos desde el 1 de Enero de 1970, 00:00:00 UTC.  (Retorna valores negativos para fechas previas.)

  

- `Date.prototype.getTimezoneOffset()`  Retorna la diferencia horaria en minutos para la hora local.

  

- `Date.prototype.getUTCDate()`  Retorna el día (fecha) del mes (1–31) para la fecha especificada acorde a la hora local.

  

- `Date.prototype.getUTCDay()` Retorna el día de la semana (0–6) para la fecha especificada en hora universal.

  

- `Date.prototype.getUTCFullYear()`  Retorna el año (4 dígitos para años de 4 dígitos) para la fecha especificada acorde a la hora universal.

  

- `Date.prototype.getUTCHours() ` Retorna la hora (0–23) para la fecha especificada acorde a la hora universal.

  

- `Date.prototype.getUTCMilliseconds()`  Retorna los milisegundos (0–999) para la fecha especificada acorde a la hora universal.

  

- `Date.prototype.getUTCMinutes() ` Retorna los minutos (0–59) para la fecha especificada acorde a la hora universal.

  

- `Date.prototype.getUTCMonth()`  Retorna el mes (0–11) para la fecha especificada acorde a la hora universal.

  

- `Date.prototype.getUTCSeconds()`  Retorna los segundos (0–59) para la fecha especificada acorde a la hora universal.

  

- `Date.prototype.getYear()`  Retorna el año (usualmente de 2 a 3 dígitos) para la fecha especificada acorde a la hora local. Usa getFullYear() en su lugar.

  

- `Date.prototype.setDate() ` Establece el día del mes para la fecha especificada acorde a la hora local.

  

- `Date.prototype.setFullYear()`  Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha específica acorde a la hora local.

  

- `Date.prototype.setHours()`  Establece la hora para una fecha específica acorde a la hora local.

  

- `Date.prototype.setMilliseconds() ` Establece los milisegundos para una fecha específica acorde a la hora local.

  

- `Date.prototype.setMinutes() ` Establece los minutos para una fecha específica acorde a la hora local.

  

- `Date.prototype.setMonth()`  Establece el mes para una fecha específica acorde a la hora local.

- `Date.prototype.setSeconds()`  Establece los segundos para una fecha específica acorde a la hora local.

  

- `Date.prototype.setTime()`   Establece el objeto Date al tiempo representado por un número de  milisegundos desde el 1 de Enero de 1970, 00:00:00 UTC. Usa números  negativos para fechas previas.

  

- `Date.prototype.setUTCDate()`  Establece el día del mes para la fecha especificada acorde a la hora universal.

  

- `Date.prototype.setUTCFullYear()`  Establece el año completo (ej. 4 dígitos para años de 4 dígitos) para una fecha específica acorde a la hora universal.

  

- `Date.prototype.setUTCHours()`   Establece la hora para una fecha específica acorde a la hora universal.

  

- `Date.prototype.setUTCMilliseconds()`  Establece los milisegundos para una fecha específica acorde a la hora universal.

  

- `Date.prototype.setUTCMinutes()` Establece los minutos para una fecha específica acorde a la hora universal.

  

- `Date.prototype.setUTCMonth()` Establece el mes para una fecha específica acorde a la hora universal.

  

- `Date.prototype.setUTCSeconds()`  Establece los segundos para una fecha específica acorde a la hora universal.

  

- `Date.prototype.setYear()`  Establece el año (usualmente de 2 a 3 dígitos) para una fecha específica acorde a la hora local. Usa setFullYear() en su lugar.

  

- `Date.prototype.toDateString()`  Retorna la "fecha" del objeto Date como una cadena fácil de leer por humanos 'Thu Apr 12 2018'.

  

- `Date.prototype.toISOString()`  Convierte una fecha a una cadena siguiendo el ISO 8601 de Formato Extendido.

  

- `Date.prototype.toJSON() ` Retorna una cadena representando el objeto Date usando toISOString(). Destinado a ser usado por JSON.stringify().

  

- `Date.prototype.toGMTString()`  Retorna una cadena representando el objeto Date basado en la zona horaria GMT (UTC). Usa toUTCString() en su lugar.

  

- `Date.prototype.toLocaleDateString() ` Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

  

- `Date.prototype.toLocaleString()`  Retorna una cadena con una representación sensible a la localización de esta fecha.

  

- `Date.prototype.toLocaleTimeString()`  Retorna una cadena con una representación sensible a la localización de la fecha basada en la configuración del sistema.

  

- `Date.prototype.toString()`  Retorna una cadena representando el objeto especificado Date. Sobrescribe el método Object.prototype.toString().

  

- `Date.prototype.toTimeString()`  Retorna la porción de "tiempo" del objeto Date a una cadena legible para humanos.

  

- `Date.prototype.toUTCString()` Convierte una fecha a una cadena usando la zona horaria UTC.

  

- `Date.prototype.valueOf()`  Retorna el valor primitivo de un objeto Date. 