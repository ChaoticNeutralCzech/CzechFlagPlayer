# CzechFlagPlayer &#x1F1E8;&#x1F1FF; &#x23EF;&#xFE0F;

Plays audio (*Jožin z bažin* by default) when clicking the Czech flag as if the triangle is a play button  
By [u/CheoticNeutralCzech](https://www.reddit.com/user/ChaoticNeutralCzech/)

## [Try it online!](https://chaoticneutralczech.github.io/CzechFlagPlayer/)
Pressing the "a" key on the site will reveal a link to this page.

If you find a better source for the *Jožin z Bažin* audio (directly hosted MP3/M4A/OPUS/... file) or can rewrite the code to sneakily embed a YouTube video, feel free to make a pull request! You can obviously make a fork of this for the Philippines or any other extension.

## Download
Right-click [this link](https://github.com/ChaoticNeutralCzech/CzechFlagPlayer/raw/main/index.html) and choose "Save link as..."  
If you want to have everything offline including the music, you can follow the steps below:

## Change music or background color

Add the following text to the URL. This works whether the page is online or offline.

    ?m=<yourMusic>&bg=<yourColor>

- `<yourMusic>` is the [URL-encoded](https://cdpn.io/benjamincharity/fullpage/wzyNqQ?anon=true&editors=1000&view=) URL of your music file. When the page is saved on your device (see [above](https://github.com/ChaoticNeutralCzech/CzechFlagPlayer#download)), relative paths are supported, which means that if the sound file is in the same folder, you can just put its filename here and it will work! You still need to URL-encode it, which means that `Jožin z bažin.mp3` will become `Jo%C5%BEin+z+Ba%C5%BEin.mp3`. Example (you're using Windows, you saved the file in your Downloads folder as `flag.html` and `Jožin z bažin.mp3` is in your Music folder): `file:///C:/Users/[...]/Downloads/flag.html?m=../Music/Jo%C5%BEin+z+ba%C5%BEin.mp3`
- `<yourColor>` is the [HTML color name](https://www.w3.org/wiki/CSS/Properties/color/keywords) of your color or `rgb(<r>,<g>,<b>)` for any custom color.

[Example](https://chaoticneutralczech.github.io/CzechFlagPlayer?m=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F0%2F08%2FBedrich_Smetana_-_ma_vlast_-_i._vltava_%2527the_moldau%2527.ogg&bg=black) (*Vltava*, black background):

    https://chaoticneutralczech.github.io/CzechFlagPlayer?m=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F0%2F08%2FBedrich_Smetana_-_ma_vlast_-_i._vltava_%2527the_moldau%2527.ogg&bg=black
