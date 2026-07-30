# BeatStack

A small music-player demo built to practice core data structures:

- **Array** — the song library / playlist
- **Queue (FIFO)** — upcoming songs
- **Stack (LIFO)** — listening history
- **Search / Sort / Shuffle** — classic array algorithms

This repo has two versions of the same idea:

```
web/        HTML + CSS + JS version (browser UI)
cpp/        C++ console version (main.cpp)
```

## Running the C++ version

```bash
g++ -std=c++17 -O2 -o beatstack main.cpp
./beatstack
```

Menu options let you play a song, queue one up, search, sort, shuffle,
and step forward/backward through your history.

## Running the web version

Just open `index.html` in a browser — no build step needed.
