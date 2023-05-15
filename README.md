# CzechFlagPlayer
Plays audio (Jožin z bažin by default) when clicking the Czech flag as if the triangle is a play button  
By [u/CheoticNeutralCzech](https://www.reddit.com/user/ChaoticNeutralCzech/)

## [Try it online!](https://chaoticneutralczech.github.io/CzechFlagPlayer/index.html)
If you find a better source for the audio (directly hosted MP3/M4A/OPUS/... file) or can rewrite the code to sneakily embed a YouTube video, feel free to make a pull request!

## Download
Right-click [this link](https://github.com/ChaoticNeutralCzech/CzechFlagPlayer/raw/main/index.html) and choose "Save link as..." 

## Change music or background color
(the latter is useful for OLED screens or to match surroundings when embedded\)

Add the following text to the URL. This works whether the page is online or offline.

    ?m=<yourMusic>&bg=<yourColor>

`<yourMusic>` is the URL-encoded URL of your music file, `<color>` is the [HTML color name](https://html-color-codes.info/color-names/) of your color or `rgb(<r>,<g>,<b>)` for any custom color

[Example](https://chaoticneutralczech.github.io/CzechFlagPlayer?m=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F0%2F08%2FBedrich_Smetana_-_ma_vlast_-_i._vltava_%2527the_moldau%2527.ogg&bg=black)

    https://chaoticneutralczech.github.io/CzechFlagPlayer?m=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F0%2F08%2FBedrich_Smetana_-_ma_vlast_-_i._vltava_%2527the_moldau%2527.ogg&bg=black

Pressing the "a" key on the site will now reveal a link to this page.
