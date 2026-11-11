# Cascade — a movie player

An immersive movie browser built around a 3D cascade of movie posters.

- 51 new and classic films from 29 directors
- Filter the cascade by genre, **New** (2023+) or **Classics** (pre-2000)
- Movie and director pages, playlists, a library, search and a queue
- Playback is simulated: each movie is split into 5 scenes

Posters and director photos are loaded from Wikipedia/Wikimedia. Movie posters are copyrighted by their owners.

## Run locally

It's a static site. Serve the folder and open it in a browser:

```sh
python3 -m http.server 8000
# then open http://localhost:8000
```
