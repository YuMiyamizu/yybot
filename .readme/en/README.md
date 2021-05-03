### yBot Project
yBot is a bot in Portuguese created and kept up to date by Yuri and has more than 200 commands.

### Personal Note
This software works under the [MIT] license (http://escolhaumalicenca.com.br/licencas/mit/), the withdrawal of credits is prohibited, and remember, I spend A LOT of time helping everyone who has doubts and improving the BOT, but without earning anything from it, please do not remove the credits.
If you see someone stealing or who has stolen, show the truth, tell them that this is plagiarism, this is the only request I have.

`` bash
> wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
> sudo apt install ./google-chrome-stable_current_amd64.deb
``

### Functions (+200)

| Function | Contains |
| ------------- | ------------- |
| Run WA-Automate / Functions within WhatsApp | ✅ |
| Manage Groups | ✅ |
| Betting / Casino / Other Games | ✅ |
| Anti Porno & Imagem + 18 / Chat Link | ✅ |
| SMS / CALL / EMAIL attacks | ✅ |
| Welcome / Goodbye / Anti-Fake / Blacklist | ✅ |
| Block / Unblock / Track people | ✅ |
| Search Anime / Lyrics / Twitter / Instagram | ✅ |
| Send messages to other groups | ✅ |
| Chat by text / voice Sim-Simi / Local (unlimited) | ✅ |
| Delete BOT Messages | ✅ |
| Downloads (Social-Networks and YouTube) | ✅ |
| Speak 51 languages ​​/ Translator | ✅ |
| Generation of Texts / Diary | ✅ |
| Google / Google Play / Pinterest | ✅ |
| Group / Profile Information | ✅ |
| Mark All / Remove All | ✅ |
| Memes / Make Memes | ✅ |
| NASA, Brainly, Wikipedia | ✅ |
| Pause / Exit All / Stream / Delete All | ✅ |
| Search Photos / Data / Covid | ✅ |
| Print Screen / Sites | ✅ ||
| GIF Sticker / Without Background / Link / Words | ✅ |
| Photo Uploads | ✅ |
| Use CMD / Terminal via WhatsApp | ✅ |
| XP / Ranking / Level / Polls | ✅ |
| Other | ✅ |

### Requirements

- Two WhatsApp numbers, one for the owner and one for the BOT.
- [NodeJS] (https://nodejs.org) - I recommend LTS.
- [Git] (https://git-scm.com) - For Unix-Tools - Be careful.
- [FFmpeg] (https://ffmpeg.org) - For the GIF command.
- [Libwebp] (https://developers.google.com/speed/webp/download) - Help at the top and stuff.
- For a tutorial on installing FFmpeg on Windows, see [WikiHow] (https://pt.wikihow.com/Instalar-o-FFmpeg-no-Windows), to install Libwebp follow the same steps, but changing the name from the folder for libwebp, doing the same in the "setx" command.

For the installation of everything above on Linux, you can use the command below:

`` bash
> sudo apt install nodejs git ffmpeg libwebp -y
``

If you get errors with the version of the node in your Linux repository, use [Node Source] (https://github.com/nodesource/distributions), remember to use LTS (14).

### Installation
You need to have this repository, it's simple, run the commands below, in case of errors, run as sudo / administrator.

`` bash
> git clone https://github.com/YuMiyamizu/ybot.git
> ybot cd
> npm i
``
### MANDATORY Changes
EDIT the API's found at:

- [Language] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#2)
- [Owner] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#3)
- [DDI] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#4)
- [Prefix] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#5)
- [API 1 - API-Flash] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#6)
- [API 2 - RemoveBG] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#7)
- [API 3 - WallHaven] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#8)
- [API 4 - Deep-AI] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#9)
- [Group Limit] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#10)
- [Member Limit] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#11)
- [Sticker-Author] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#12)
- [Sticker-Pack] (https://github.com/YuMiyamizu/ybot/blob/main/lib/config/Bot/config.json#13)
- They refer to the sites [RemoveBG] (https://www.remove.bg/pt-br), [API-Flash] (https://apiflash.com), [WallHaven] (https: // wallhaven. cc / settings / account) & [Deep-AI] (https://deepai.org).
- DDI and Language are necessary only if you are from outside Brazil, the available languages ​​are "en" in English, "pt" in Portuguese and "es" in Spanish and affect all dialogues and akinator.

### Start
After editing the necessary files, run the command below and wait to start, after that, scan the QR Code.

`` bash
> npm start
``

### See all commands
Type in your chat the message, if you edited your prefix, change the '.' for the character you will use.

`` bash
> .menu
``.


### Alerts on WhatsApp
To also receive yBot error messages via WhatsApp, remove the "//" from the [Catch] line (https://github.com/YuMiyamizu/ybot/blob/main/config.js#L3855).

### Donate and Support
- [Donations] - This project is maintained only by me for free and without charging anything, if you can, donate something ❤️
- [PIX] - 129b7bb8-bdb6-4f37-a025-f2e2c7f75592
- [Owner] - If you need to talk to me (I always answer as quickly as possible) - [Talk] (https://wa.me/+5511960930541)
