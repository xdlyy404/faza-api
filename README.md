<center><img src="https://i.postimg.cc/kGH1D0kZ/fafa.jpg" alt="fadlyid" width="500" />
</p></center>
<p align="center">
<a href="#"><img title="faza-api" src="https://img.shields.io/badge/faza-api-green?colorA=%23ff0000&colorB=%23017e40&style=for-the-badge"></a>

<p align="center">
<a href="https://github.com/xdlyy404/faza-api"><img title="Followers" src="https://img.shields.io/github/followers/xdlyy404?color=blue&style=flat-square"></a>
<a href="https://github.com/xdlyy404/faza-api"><img title="Stars" src="https://img.shields.io/github/stars/xdlyy404/faza-api?color=red&style=flat-square"></a>
<a href="https://github.com/xdlyy404/faza-api/network/members"><img title="Forks" src="https://img.shields.io/github/forks/xdlyy404/faza-api?color=red&style=flat-square"></a>
<a href="https://github.com/xdlyy404/faza-api/watchers"><img title="Watching" src="https://img.shields.io/github/watchers/xdlyy404/faza-api?label=Watchers&color=blue&style=flat-square"></a>
</p>

## Penginstalan
> npm install faza-api
>
> npm uninstall faza-api

## ```Downloader```
```js
const fz = require('faza-api');

const url_youtube = 'https://youtu.be/zXiSTrOQhxM'
const url_tiktok = 'https://vt.tiktok.com/ZSehyjVW9/'
const url_instagram = 'https://www.instagram.com/p/CJFsOsKJMHa6FCRkbjn0mR3jJ0KwHOCCMaW7_Q0/?utm_medium=copy_link'
const url_facebook = 'http://www.facebook.com/groups/526909968570398/permalink/571916620736399/'
const url_twitter = 'https://twitter.com/LucuLucuVideo/status/1454834787382816775?s=20'
const url_soundcloud = 'https://soundcloud.com/enggak-tau-829795349/tri-suaka-aku-bukan-jodohnya?utm_campaign=social_sharing&utm_source=mobi&utm_terms=social_sharing_on_mobi.control%2Ctop_curators.top_curators'
const url_imgur = 'https://imgur.com/gallery/rK8ppvC'
const url_imdb = 'https://www.imdb.com/video/vi146981657?listId=ls053181649'
const url_telesticker = 'https://t.me/addstickers/c1129234339_by_HarukaAyaBot'

// youtube
fz.Youtube(url_youtube)
    .then(data => {console.log(data)
});

// tiktok
fz.Tiktok(url_tiktok)
    .then(data => {console.log(data)
});

// instagram
fz.Instagram(url_instagram)
    .then(data => {console.log(data)
});

// facebook
fz.Facebook(url_facebook)
    .then(data => {console.log(data)
});

// twitter
fz.Twitter(url_twitter)
    .then(data => {console.log(data)
});

// soundcloud
fz.SoundCloud(url_soundcloud)
    .then(data => {console.log(data)
});

// imgur
fz.Imgur(url_imgur)
    .then(data => {console.log(data)
});

// imdb
fz.Imdb(url_imdb)
    .then(data => {console.log(data)
});

// telesticker
fz.Telesticker(url_telesticker)
    .then(data => {console.log(data)
});
```

## ```Anime```
```js
const fz = require('faza-api');

const query = 'naruto'

// anime
fz.Anime(query)
    .then(data => {console.log(data)
});

// manga
fz.Manga(query)
    .then(data => {console.log(data)
});

// character
fz.Character(query)
    .then(data => {console.log(data)
});
```

## ```Search```
```js
const fz = require('faza-api');

const query_pinterest = 'elaina'
const query_film = 'love'
const query_wattpad = 'love'
const query_webtoons = 'love'
const query_mangatoons = 'love'
const query_drakor = 'love'
const query_stickersearch = 'patrick'

// pinterest
fz.Pinterest(query_pinterest)
    .then(data => {console.log(data)
});

// film
fz.Film(query_film)
    .then(data => {console.log(data)
});

// wattpad
fz.Wattpad(query_wattpad)
    .then(data => {console.log(data)
});

// webtoons
fz.Webtoons(query_webtoons)
    .then(data => {console.log(data)
});

// mangatoons
fz.Mangatoons(query_mangatoons)
    .then(data => {console.log(data)
});

// drakor
fz.Drakor(query_drakor)
    .then(data => {console.log(data)
});

// stickersearch
fz.StickerSearch(query_stickersearch)
    .then(data => {console.log(data)
});
```

## ```Islami```
```js
const fz = require('faza-api');

const query = 'luqman'

// listsurah
fz.ListSurah()
    .then(data => {console.log(data)
});

// surah
fz.Surah(query)
    .then(data => {console.log(data)
});

// tafsirsurah
fz.TafsirSurah(query)
    .then(data => {console.log(data)
});
```

## ```Information && News```
```js
const fz = require('faza-api');

const username = 'WattpadRomanceIN'

// jadwalbola
fz.JadwalBola()
    .then(data => {console.log(data)
});

// jadwaltv
fz.JadwalTv()
    .then(data => {console.log(data)
});

// jadwalsholat
fz.JadwalSholat()
    .then(data => {console.log(data)
});

// kompasnews
fz.KompasNews()
    .then(data => {console.log(data)
});

// inews
fz.Inews()
    .then(data => {console.log(data)
});

// wattpaduser
fz.WattpadUser(username)
     .then(data => {console.log(data)
});
```

# THANKS TO 🎉
<a href="https://github.com/providerxploit"><img src="https://github.com/providerxploit.png?size=100" width="100" height="100"></a> | [![Fajar](http://github.com/Zynfinity.png?size=100)](http://github.com/Zynfinity) | [![Hexa](http://github.com/hexagonz.png?size=100)](http://github.com/hexagonz)
----|----|----
[ProviderXploit](https://github.com/providerxploit) | [Fajar](http://github.com/Zynfinity) | [Hexa](http://github.com/hexagonz)
My team (pedo) | Fajar insana | Hexagonz (pedo)
