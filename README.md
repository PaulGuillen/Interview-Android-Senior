# Preguntas de Entrevista para Desarrollador Android Senior
¡Bienvenido al repositorio de Preguntas de Entrevista para Desarrollador Android Senior! Esta colección de preguntas está diseñada para ayudar a los desarrolladores senior de Android a prepararse para entrevistas técnicas, cubriendo una amplia gama de temas esenciales para dominar la plataforma Android. Ya sea que estés preparándote para una entrevista a nivel senior o simplemente buscando perfeccionar tus habilidades en desarrollo Android, estas preguntas pondrán a prueba tus conocimientos y comprensión de los conceptos clave.

## Kotlin Scopes
- ¿Cuál es la diferencia entre let y apply?
- ¿En qué caso usarías run en lugar de let?
- ¿Cuál es el propósito de apply y cuándo lo usarías?
- ¿Cuáles son los principales beneficios de usar let?
- Explica una situación donde also sería más adecuado que apply.
- ¿Qué sucede si el bloque dentro de let lanza una excepción?
- ¿Cómo puede apply mejorar la inicialización de un objeto en Kotlin?
- ¿Cuándo utilizarías with en lugar de run o apply?
- ¿Cómo elegirías entre let, run y apply en una situación donde todas parecen viables?
- ¿Por qué let es útil cuando se trabaja con objetos encadenados en Kotlin?

## Lazy vs lateinit
- ¿Cuál es la diferencia entre lazy y lateinit en términos de inicialización?
- ¿Cuándo usarías lazy sobre lateinit?
- ¿Qué pasa si intentas acceder a una propiedad lateinit antes de inicializarla?
- ¿Qué significa que lazy es thread-safe?
- ¿Por qué lateinit no se puede usar con tipos primitivos?
- ¿Qué sucede si intentas reasignar una propiedad lazy?

## Inline vs Infix
- ¿Cuál es el propósito de inline en Kotlin?
- ¿Cuándo deberías usar inline?
- ¿Qué es una función infix y cuándo se usa?
- ¿Qué limitaciones tiene una función infix?
- ¿Cuál es la diferencia entre una función inline y una infix?

## Coroutines
- ¿Qué es una coroutine en Kotlin?
- ¿Cuál es la diferencia entre launch y async?
- ¿Qué es una función suspend y cuándo la usarías?
- ¿Qué son los dispatchers en coroutines y cuáles son los más comunes?
- ¿Qué es structured concurrency y por qué es importante en Kotlin Coroutines?
- ¿Cómo manejarías una excepción dentro de una coroutine?
- ¿Qué es CoroutineScope y cuál es su importancia en el manejo de coroutines?
- ¿Cómo se cancela una coroutine y por qué es útil?

## Gradle
- ¿Qué es Gradle y cuál es su propósito en un proyecto Android?
- ¿Cuál es la diferencia entre el archivo build.gradle de nivel de proyecto y el de nivel de módulo?
- ¿Cómo se manejan las dependencias en Gradle?
- ¿Qué es minifyEnabled en Gradle?
- ¿Qué son los buildTypes y para qué se usan?
- ¿Cómo puedes crear una tarea personalizada en Gradle?
- ¿Qué es Proguard y cómo se integra en un proyecto Android?
- ¿Cómo manejarías múltiples variantes de compilación con Gradle?

## Patrones de diseño
- https://refactoring.guru/es/design-patterns/java

## LeetCode
- https://leetcode.com/problemset/
  
## Seguridad
_Rooting_
- ¿Qué es el rooting en Android y qué implica?
- ¿Cuáles son los riesgos principales del rooting en un dispositivo Android?
- ¿Qué es SafetyNet y cómo protege a las aplicaciones de dispositivos rooteados?
- ¿Qué medidas implementa Android para detectar o bloquear dispositivos rooteados?
- ¿Qué es SELinux y cuál es su papel en la seguridad de Android?
- ¿Qué es Verified Boot y cómo protege el sistema operativo?
- ¿Qué tipos de aplicaciones pueden dejar de funcionar en dispositivos rooteados?
- ¿Por qué los fabricantes y Google desaconsejan el rooting?

_SSL PINNING_
- ¿Qué es SSL Pinning y por qué es importante?
- ¿Cuál es la diferencia entre pinning de certificado y pinning de clave pública?
- ¿Qué sucede si cambia el certificado del servidor en una aplicación con SSL Pinning?
- ¿Cómo implementas SSL Pinning en Android utilizando OkHttp?
- ¿Cuáles son las limitaciones del SSL Pinning?
- ¿Cómo puedes implementar SSL Pinning de manera declarativa en Android?
- ¿Qué es un ataque MITM y cómo protege SSL Pinning contra este tipo de ataque?

_Anti Emuladores_
- ¿Por qué es importante detectar emuladores en aplicaciones Android?
- ¿Cómo puedes detectar un emulador en Android verificando las características del dispositivo?
- ¿Qué archivos del sistema puedes verificar para detectar la presencia de un emulador?
- ¿Cómo la arquitectura de la CPU puede ayudar a identificar si el dispositivo es un emulador?
- ¿Qué direcciones IP típicas pueden indicar que una aplicación está ejecutándose en un emulador?
- ¿Cómo puede el número de serie de un dispositivo ayudar a detectar un emulador?
- ¿Cuáles son los riesgos de los falsos positivos al detectar emuladores y cómo los puedes evitar?

_Protocolos de comunicacion segura mobile_
- ¿Qué es HTTPS y por qué es importante en las aplicaciones móviles?
- ¿Qué es TLS y por qué se recomienda usar TLS 1.2 o superior?
- ¿En qué tipo de aplicaciones se utiliza DTLS y por qué?
- ¿Qué es IPsec y en qué tipo de aplicaciones móviles se usa?
- ¿Qué protocolo es comúnmente utilizado en aplicaciones de VoIP para asegurar las transmisiones de audio y video?

## Jetpack Compose
- ¿Qué diferencia hay entre una UI imperativa (XML) y una UI declarativa (Jetpack Compose)?
- ¿Cómo se gestiona el estado en Jetpack Compose?
- ¿Qué es remember y cuándo se debe utilizar?
- ¿Cuál es la diferencia entre remember y rememberSaveable?
- ¿Cómo descomponerías una interfaz compleja en Jetpack Compose?
- ¿Qué es un Modifier en Jetpack Compose y cuál es su propósito?
- ¿Cómo se maneja la navegación entre pantallas en Jetpack Compose?
- ¿Qué son las animaciones en Jetpack Compose y cómo las implementas?
- ¿Cómo se integran las vistas clásicas de Android (como TextView) en Jetpack Compose?
- ¿Cómo se realizan pruebas de UI en Jetpack Compose?
- ¿Cómo optimizarías el rendimiento de composables que se recomponen con frecuencia?
- ¿Qué es viewModel() en Jetpack Compose y cómo se utiliza?

## Material Design
- ¿Qué es Material Theming en Android?
- ¿Cómo implementas un tema oscuro en una aplicación Android?
- ¿Qué son los componentes de Material Design y por qué son importantes?
- ¿Qué función cumple MaterialTheme en Jetpack Compose?
- ¿Cómo puedes manejar el espaciado y la tipografía en Material Design?
- ¿Cómo implementas transiciones y animaciones en Jetpack Compose siguiendo Material Design?
- ¿Qué es el sistema de diseño responsivo de Material Design y cómo lo aplicas en Android?

## Patrones de arquitectura
_MVVM_
- Qué es MVVM y cómo se diferencia de otros patrones como MVP o MVC?
- ¿Cuál es el papel del ViewModel en el patrón MVVM?
- ¿Qué es LiveData y por qué es útil en MVVM?
- ¿Cómo sobrevive un ViewModel a los cambios de configuración, como la rotación de pantalla?
- ¿Qué beneficios ofrece StateFlow sobre LiveData en el patrón MVVM?
- ¿Cómo se prueba un ViewModel en el patrón MVVM?
- ¿Qué problemas se pueden encontrar si no se sigue correctamente el patrón MVVM?

_MVI_
- ¿Qué es el patrón MVI y en qué se diferencia de MVVM?
- ¿Qué es un Intent en el patrón MVI?
- ¿Por qué el estado en MVI es inmutable?
- ¿Cómo se implementa el manejo de eventos en MVI?
- ¿Qué ventajas ofrece MVI en aplicaciones con estados complejos?
- ¿Qué herramientas de Jetpack puedes usar para implementar MVI en Android?
- ¿Cuándo no es recomendable utilizar MVI?

## Base de datos
_Room || SQLITE || DataStore_
- ¿Cuál es la diferencia entre SQLite y Room?
- ¿Cuándo usarías Room en lugar de SQLite?
- ¿Para qué se utiliza DataStore y cómo mejora respecto a SharedPreferences?
- ¿Qué es un DAO en Room?
- ¿Qué ventajas ofrece Room sobre SQLite para la migración de esquemas?
- ¿Qué tipos de DataStore existen y cuándo usarías cada uno?
- ¿Cómo se implementa el manejo de migraciones en Room?
- ¿Qué desventajas tiene SQLite frente a Room?

## Google Services
- ¿Qué es Google Play Services y cuál es su propósito en Android?
- ¿Cuál es la diferencia entre Google Sign-In y OAuth tradicional?
- ¿Para qué se utiliza Firebase Cloud Messaging (FCM)?
-  ¿Cómo funciona la API de Fused Location Provider y qué ventajas ofrece?
- ¿Qué es Google Analytics para Firebase y qué ventajas ofrece para los desarrolladores?
- ¿Qué restricciones hay para utilizar Google Play Services en dispositivos Android?
- ¿Qué es la Google Maps API y cómo se integra en una aplicación Android?


  
