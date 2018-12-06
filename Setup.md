# Requirements
* [Java JDK 1.8](https://www.google.com/#q=download+jdk+8) (not OpenJDK)
* Instructions on how to install JDK 8 on your system: [[Installing-JDK1.8]]

# Downloads
Download the latest **JMusicBot-X.Y.Z.jar** (and optionally, example **config.txt** file) from the [releases](https://github.com/jagrosh/MusicBot/releases/latest) page (or, get the URL from the releases page and then use wget or similar command-line tool to download).

# Setup
* Download the **JMusicBot-X.Y.Z.jar** file (and the **config.txt**, optional) from the [releases](https://github.com/jagrosh/MusicBot/releases/latest) page. Your folder should look like this:<br>
![View](http://i.imgur.com/14x9uDy.png)
* Do not run this from the 'Downloads' or 'Desktop'. Use a folder within 'Documents'
* Fill in the config file (if you downloaded it). If you didn't download it, you will be prompted when you run for the first time. An example `config.txt` is provided below (See [[Getting a Bot Token]] and [[Finding Your User ID]] if you need help with the config).<br>
```
token=MJHJkljflksdjfCoolTokenDudeILikeItkasdk
owner=113156185389092864
prefix="!"
```
* Double-click the jar file, or run `java -Dnogui=true -jar JMusicBot-X.Y.Z.jar` from the command line. (replace X, Y, and Z with the release numbers)
* Provide the requested information, if prompted.
* Wait for the "Finished Loading" message.
* Add the bot to your server. From the [bot application page](https://discordapp.com/developers/applications/me) (where you got the token), find the Client ID and insert it in this link, replacing APP_ID: `​https://discordapp.com/oauth2/authorize?client_id=APP_ID&scope=bot`. If your bot has not been added to any guilds, a link will be provided in the console for you.