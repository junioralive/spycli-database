# SPYCLI-DATABASE

A dataset for latest MOVIES, SERIES. UPDATED REGULARLY! (MADE FOR [SPY-CLI](https://github.com/junioralive/spy-cli))

Last Updated: `18 January 2024 14:27:45 UTC`

Data Update: `1772 - 2 NEWLY ADDED`

## ⚠️ IT IS ONLY FOR EDUCATIONAL PURPOSES.

Neither I Say Nor I Promote To Do Anything Illegal. I am scraping data from various open-source websites that are publicly accessible on the internet.

## API

You can fetch the data using HTTP.

### USAGE

This file contains JSON object:

`name` `title` `poster` `genre` `rating` `plot` `link`

Example:

```json
[
  {
    "name": "Annhi Dea Mazaak Ae(2023)",
    "title": "Download Annhi Dea Mazaak Ae (2023) Punjabi HDRip Full Movie 480p [480MB] | 720p [1.3GB] | 1080p [2.8GB]",
    "poster": "https://m.media-amazon.com/images/M/MV5BYTIwODAxYjUtYWIxOC00MWZkLTkyMWMtMzRmY2U1YjYzNmNkXkEyXkFqcGdeQXVyODE5NzE3OTE@._V1_FMjpg_UX1000_.jpg",
    "genre": "Comedy",
    "rating": "5.8",
    "plot": "Raja, a blind man, falls in love with Roop. Will their love overcome all family barriers?",
    "link": "https://rentry.co/8cq6a"
  },
  {
    "name": "Young Adult Matters(2020)",
    "title": "Download Young Adult Matters (2020) BluRay {Korean With Subtitles} Full Movie 480p [400MB] | 720p [1GB] | 1080p [2.4GB]",
    "poster": "https://m.media-amazon.com/images/M/MV5BZmU2MTAyNmUtNWU0OC00YWMxLWE3ZjktMTYxZDhhZGVkNGFkXkEyXkFqcGdeQXVyNTYzMDM2MzI@._V1_.jpg",
    "genre": "Drama",
    "rating": "5.9",
    "plot": "The wanderings of teenagers and the process of getting to know the world.",
    "link": "https://rentry.co/9erf3"
  },
  {
    "name": "The Perfect Find(2023)",
    "title": "Download The Perfect Find (2023) Netflix Original Dual Audio {Hindi-English} 480p [350MB] | 720p [900MB] | 1080p [2GB] WEB-DL",
    "poster": "https://m.media-amazon.com/images/M/MV5BZDFiNjQ0NWMtZjgwZC00MjRlLThlMjAtMDg4YWIzY2QzNmMxXkEyXkFqcGdeQXVyMDc5ODIzMw@@._V1_FMjpg_UX1000_.jpg",
    "genre": "Comedy, Drama, Romance",
    "rating": "5.2",
    "plot": "After a high-profile firing, Jenna's fashion career comeback hits a snag when she falls for a charming, much younger coworker - who happens to be her boss's son. As sparks fly, Jenna must decide if she'll risk it all on a secret romance.",
    "link": "https://rentry.co/p3zbb"
  }
]
```

You can fetch the data contained in this file by sending a `GET` request to:

```
https://raw.githubusercontent.com/junioralive/spycli-database/main/src/spycli-database_data.json
```
For example:

```python
import requests

url = 'https://raw.githubusercontent.com/junioralive/spycli-database/main/src/spycli-database_data.json'
resp = requests.get(url=url)
data = resp.json() 
```

To understand data structure, read [documentation](./DOC.md)


## Disclaimer

The SPY-CLI Database Repository emphasize that this project is for educational and entertainment purposes only. We state a clear stance against piracy and express their respect for the intellectual property rights of filmmakers and production companies. The project is positioned as a way to bypass third-party money-making schemes rather than to engage in any form of illegal activity. For any issue or queries email at thejuniortest@gmail.com.

## Join Now

Discord : https://discord.gg/zuAR4txdqT

## License

Licensed under [MIT](./LICENSE). Do what you will.

## NOTES

Please Give Credits, Stars, And Follow If You use SPY-CLI Database.
