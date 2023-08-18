# Datos:

**Planes**
1. `messages_included` - SMS incluidos por mes.
2. `mb_per_month_included` - datos incluidos por mes (en megabytes, 1 GB = 1,024 MB).
3. `minutes_included` - minutos incluidos por mes.
4. `usd_monthly_pay` - pago mensual en dólares estadounidenses.
5. `usd_per_gb` - precio por gigabyte de los datos extra tras exceder los límites del plan.
6. `usd_per_message` - precio por SMS tras exceder los límites del plan.
7. `usd_per_minute` - precio por minuto tras exceder los límites del plan.
8. `plan_name` - nombre del plan.

**Usuarios**
1. `user_id` - identificador único de usuario.
2. `firs_name` - nombre del usuario.
3. `last_name` - apellido del usuario.
4. `age` - edad del usuario (en años).
5. `city` - ciudad de residencia del usuario.
6. `reg_date` - fecha de suscripción (aaaa-mm-dd).
7. `plan` - nombre del plan contratado.
8. `churn_date` - fecha en la que el usuario dejó de usar el servicio (si el valor es ausente, la tarifa se estaba usando cuando se recuperaron los datos).

**Llamadas**
1. `id` - identificador único de llamada.
2. `user_id` - identificador del usuario que realizó la llamada.
3. `call_date` - fecha de la llamada.
4. `duration` - duración de la llamada (en minutos).

**Mensajes**
1. `id` - identificador único del SMS.
2. `user_id` - identificador del usuario que envió el SMS.
3. `message_date` - fecha en la que se envió el SMS.

**Internet**
1. `id` - identificador único de la sesión.
2. `user_id` - identificador del usuario.
3. `session_date` - fecha en la que se utilizaron los megabytes.
4. `mb_used` - cantidad de datos gastados durante la sesión (en megabytes).

# Objetivo:

Determinar cuál de dos planes teléfonicos de una empresa de telecomunicaciones genera más ingresos para ajustar el presupuesto de publicidad.

# Librerías usadas:

pandas
matplotlib
numpy
scipy
math