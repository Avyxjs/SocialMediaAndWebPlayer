***This repository is a personal website where you can add your social media links and also has a music player that plays music, very configurable.***

----------------------

Example: to add music

```music.js
title = [
        "Yellow",  // Self explanotory right? //
        "Be More",
        "Escapism.-Sped Up",
      ],
      artist = [
        "Coldplay - Yellow",
        "Stephen Sanchez -  Be More",
        "RAYE, 070 Snake - Escapism.-Sped Up",
        "???",
      ],
      albumArtworks = ["_1", "_2", "_3", "_4",],  // These songs are from my github repo "AT-Assets"
      trackUrl = [                         // To replace, add songs to any public link that allows mp3 uploads like your github and just grab link!
        "https://raw.githubusercontent.com/artificial-development/AT-Assets/main/Coldplay - Yellow (Official Video).mp3",
        "https://raw.githubusercontent.com/artificial-development/AT-Assets/main/Stephen Sanchez - Be More (Lyric Video).mp3",
        "https://raw.githubusercontent.com/artificial-development/AT-Assets/main/RAYE - Escapism (sped up).mp3",
        "Song link ??",
      ],
```

Example: This is how you add album art for your music.

```index.html
<div id="player-content"> <!-- For song image, discord works, github works. -->
          <div id="album-art">
            <img src="https://cdn.discordapp.com/attachments/1138847987934695485/1141203103052476547/ab67616d0000b2733d92b2ad5af9fbc8637425f0.jpg" class="active" id="_1">
            <img src="https://media.discordapp.net/attachments/1138847987934695485/1141204928736530533/StephenSanchezAngelFace.png?width=671&height=671" id="_2">
            <img src="https://cdn.discordapp.com/attachments/1138847987934695485/1141205058130825307/41igUB7t1uL._UXNaN_FMjpg_QL85_.jpg" id="_3">
            <div id="buffer-box" _msttexthash="163943" _msthash="7">Buffering ...</div>
          </div>
```

----------------------

Example: Want to add more social accounts and icons? for icons please do go to https://fontawesome.com/search

```index.html
<!-- Social links -->
    <div class="social">
      <a href="https://github.com/artificial-development" target="_blank">
        <i class="fa-brands fa-github fa-bounce fa-lg"></i>
        <p _msttexthash="76492" _msthash="8">Github</p>
      </a>
      <a href="https://discord.gg/artificialdev" target="_blank">
        <i class="fa-brands fa-discord fa-bounce"></i>
        <p _msttexthash="93990" _msthash="9">Discord</p>
      </a>
    </div>
```

## Thanks, want to donate? you can buy me a coffee here: <a href='https://ko-fi.com/X8X3N0AZX' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi1.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>🙏
