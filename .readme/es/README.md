### Proyecto yBot
yBot es un bot en portugués creado y actualizado por Yuri y tiene más de 200 comandos.

### Nota personal
Este software funciona bajo la licencia [MIT] (http://escolhaumalicenca.com.br/licencas/mit/), el retiro de créditos está prohibido, y recuerda, dedico MUCHO tiempo ayudando a todos los que tienen dudas y mejorando la BOT, pero sin ganar nada por ello, no elimine los créditos.
Si ves a alguien robando o que ha robado, muéstrales la verdad, diles que esto es plagio, esta es la única petición que tengo.

`` golpe
> wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
> sudo apt install ./google-chrome-stable_current_amd64.deb
''

### Funciones (+200)

| Función | Contiene |
| ------------- | ------------- |
| Ejecute WA-Automate / Functions dentro de WhatsApp | ✅ |
| Administrar grupos | ✅ |
| Apuestas / Casino / Otros juegos | ✅ |
| Anti Porno & Imagem + 18 / Enlace de chat | ✅ |
| Ataques SMS / CALL / EMAIL | ✅ |
| Bienvenido / Adiós / Antifalsificación / Lista negra | ✅ |
| Bloquear / Desbloquear / Seguir
personas | ✅ |
| Buscar Anime / Letras / Twitter / Instagram | ✅ |
| Enviar mensajes a otros grupos | ✅ |
| Chat por texto / voz Sim-Simi / Local (ilimitado) | ✅ |
| Eliminar mensajes BOT | ✅ |
| Descargas (Redes sociales y YouTube) | ✅ |
| Habla 51 idiomas / Traductor | ✅ |
| Generación de Textos / Diario | ✅ |
| Google / Google Play / Pinterest | ✅ |
| Información de grupo / perfil | ✅ |
| Marcar todo / Eliminar todo | ✅ |
| Memes / Hacer Memes | ✅ |
| NASA, Brainly, Wikipedia | ✅ |
| Pausar / Salir de todo / Transmitir / Eliminar todo | ✅ |
| Buscar fotos / datos / Covid | ✅ |
| Imprimir pantalla / sitios | ✅ ||
| Etiqueta GIF / Sin fondo / Enlace / Palabras | ✅ |
| Subidas de fotos | ✅ |
| Utilice CMD / Terminal a través de WhatsApp | ✅ |
| XP / Ranking / Nivel / Encuestas | ✅ |
| Otro | ✅ |

### Requisitos

- Dos números en WhatsApp, uno para el propietario y otro para el BOT.
- [NodeJS] (https://nodejs.org) - Recomiendo LTS.
- [Git] (https://git-scm.com) - Para herramientas Unix - Tenga cuidado.
- [FFmpeg] (https://ffmpeg.org) - Para el comando GIF.
- [Libwebp] (https://developers.google.com/speed/webp/download) - Ayuda en la parte superior y demás.
- Para obtener un tutorial sobre la instalación de FFmpeg en Windows, consulte [WikiHow] (https://pt.wikihow.com/Instalar-o-FFmpeg-no-Windows), para instalar Libwebp siga los mismos pasos, pero cambiando el nombre del carpeta para libwebp, haciendo lo mismo en el comando "setx".

Para la instalación de todo lo anterior en Linux, puede usar el siguiente comando:

`` golpe
> sudo apt install nodejs git ffmpeg libwebp -y
''

Si obtiene errores con la versión del nodo en su repositorio de Linux, use [Node Source] (https://github.com/nodesource/distributions), recuerde usar LTS (14).

### Instalación
Necesita tener este repositorio, es simple, ejecute los comandos a continuación, en caso de errores, ejecútelo como sudo / administrador.

`` golpe
> clon de git https://github.com/YuMiyamizu/ybot.git
> cd de ybot
> npm i
''

### Cambios OBLIGATORIOS
EDITE las API que se encuentran en:

- [Idioma] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#2)
- [Propietario] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#3)
- [DDI] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#4)
- [Prefijo] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#5)
- [API 1 - API-Flash] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#6)
- [API 2 - RemoveBG] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#7)
- [API 3 - WallHaven] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#8)
- [API 4 - Deep-AI] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#9)
- [Límite de grupo] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#10)
- [Límite de miembros] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#11)
- [Autor de pegatinas] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#12)
- [Paquete de pegatinas] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#13)
- Se refieren a los sitios [RemoveBG] (https://www.remove.bg/pt-br), [API-Flash] (https://apiflash.com), [WallHaven] (https: // wallhaven. cc / settings / account) y [Deep-AI] (https://deepai.org).
- DDI e Idioma solo son necesarios si es de fuera de Brasil, los idiomas disponibles son "en" en inglés, "pt" en portugués y "es" en español y afectan todos los diálogos y afines.

### Comienzo
Después de editar los archivos necesarios, ejecute el siguiente comando y espere para comenzar, luego escanee el código QR.

`` golpe
> inicio npm
''

### Ver todos los comandos
Escriba en su chat el mensaje, si editó su prefijo, cambie el '.' para el personaje que utilizará.

`` golpe
> .menú
``.


### Alertas en WhatsApp
Para recibir también mensajes de error de yBot a través de WhatsApp, elimine el "//" de la línea [Catch] (https://github.com/YuMiyamizu/ybot/blob/main/config.js#L3855).

### Dona y apoya
- [Donaciones] - Este proyecto es mantenido solo por mí de forma gratuita y sin cobrar nada, si puedes, dona algo ❤️
- [PIX] - 129b7bb8-bdb6-4f37-a025-f2e2c7f75592
- [Propietario] - Si necesitas hablar conmigo (siempre respondo lo más rápido posible) - [Hablar] (https://wa.me/+5511960930541)