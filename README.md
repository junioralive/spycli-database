# SPY MOVIES

A dataset for latest MOVIES, SERIES. UPDATED REGULARLY !!

Last Updated: `15 November 2023 00:05:49 UTC`

FOR NON CODER: [DOWNLOAD EXE](https://github.com/junioralive/spymovies/releases/tag/1.0)

## ⚠️  The intension of the project is not piracy, i'm just scraping from a website openly available on the internet

## API

You can fetch the data using HTTP.

### Movies and Series

This file contains JSON object:

`title` - Name of the Movie,
`image_source` -  Direct Image linkl,
`link` - Direct Links.



```json
[
   {
    "title": "Crackdown (Season 2) [Episode 1-7 Added] Hindi JioCinema Original Web Series 480p | 720p | 1080p WEB-DL",
    "image_source": "https://assets.gadgets360cdn.com/pricee/assets/product/202305/Crackdown-2_1684930990.jpg",
    "link": "https://rentry.co/7akx4"
  },
  {
    "title": "City of Dreams (2019) Season 1 Hindi Complete Hotstar Specials WEB Series 480p & 720p",
    "image_source": "https://m.media-amazon.com/images/M/MV5BMDE1NTk4NzctZGExYi00MzIwLTlhNmEtNmViZDllOTIxN2U1XkEyXkFqcGdeQXVyODE5NzE3OTE@._V1_.jpg",
    "link": "https://rentry.co/chv5v"
  },
  {
    "title": "Download Abbar Kanchanjangha (2022) Bengali Full Movie HDRip 480p [330MB] | 720p [960MB] | 1080p [2.1GB]",
    "image_source": "https://m.media-amazon.com/images/M/MV5BNmYzNTU1OWItN2RmMC00MGE2LTg0MDktYWI5ZDFjNGI1MmJlXkEyXkFqcGdeQXVyMTQ3OTA2MTM5._V1_.jpg",
    "link": "https://rentry.co/6w58r"
  },
  {
    "title": "[18+] Download Lady Voyeur (Season 1) Dual Audio {Hindi-English} WEB Series 480p | 720p | 1080p WEB-DL",
    "image_source": "https://assets.gadgets360cdn.com/pricee/assets/product/202212/Lady-Voyeur_1672051883.jpg",
    "link": "https://rentry.co/cr876"
  }
]
```

You can fetch the data contained in this file by sending a `GET` request to:

```
https://raw.githubusercontent.com/junioralive/spymovies/main/src/spymovies_data.json
```
For example:

```python
import requests

url = 'https://raw.githubusercontent.com/junioralive/spymovies/main/src/spymovies_data.json'
resp = requests.get(url=url)
data = resp.json() 
```

## Disclaimer

The Spy Movies Repository emphasize that this project is for educational and entertainment purposes only. They state a clear stance against piracy and express their respect for the intellectual property rights of filmmakers and production companies. The project is positioned as a way to bypass third-party money-making schemes rather than to engage in any form of illegal activity. For any issue or queries discord at @junioralive or email thejuniortest@gmail.com.

## Usage

It's a commendable effort to make spy movies more accessible while respecting legal boundaries. However, users and contributors should remain vigilant about the legal and ethical implications of such projects, ensuring they stay within the bounds of copyright laws and fair use policies.

## Join Now

Telegram : https://t.me/spytvmoviesofficial

## License

Licensed under [MIT](./LICENSE). Do what you will.


