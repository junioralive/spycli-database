# SPYCLI-DATABASE, HOW IT WORKS?

## **Data Structure** 

Please note: As new data is appended at the end of the dataset, reversing the order of the output will ensure you access the most recent additions first.

The dataset is structured in JSON format, This file contains JSON object: `name` `title` `poster` `genre` `rating` `plot` `link`

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

## **Fetching Data**

Users can fetch the data using HTTP requests to the provided URL.

```
https://raw.githubusercontent.com/junioralive/spymovies/main/src/spymovies_data.json
```
## **Examples:**

- Load json:

```python
import requests

url = 'https://raw.githubusercontent.com/junioralive/spymovies/main/src/spymovies_data.json'
resp = requests.get(url=url)
spymovies_data = resp.json() 
```

- Filter by genre:

```python
#same as above code...

for movie in reversed(spymovies_data):
    if 'Action' in movie.get('genre', ''): #Change genre here
        print(movie.get('title', 'No title available'))
```

- Filter by year:

```python
#same as above code...

for movie in reversed(spymovies_data):
    if '2023' in movie.get('title', ''): #Change year here
        print(movie.get('title', 'No title available'))
```
