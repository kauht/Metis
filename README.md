<div align="center">
  <h1>Metis</h1>
  <h3>Advanced, customizable chess engine</h3>
  <br>
  <p>
    <a href="#"><img src="https://img.shields.io/badge/license-MIT-blue" alt="License"></a>
    <a href="#"><img src="https://img.shields.io/badge/platform-x64-lightgrey" alt="Platform"></a>
  </p>
  <p><em>Think a thousand moves ahead.</em></p>
</div>

<hr>

<div align="center">
  <p>
    <b><a href="#overview">Overview</a></b> •
    <b><a href="#community">Community</a></b> •
    <b><a href="#features">Features</a></b> •
    <b><a href="#roadmap">Roadmap</a></b> •
    <b><a href="#research">Research</a></b> •
    <b><a href="#license">License</a></b>
  </p>
</div>

---

# Overview

Metis will be a modern chess engine written in C++. This project is for personal research, I aim to develop more advanced and unique features over time.

---

# Community

Metis is a personal project - Though I'd appreciate any contributions and feedback.

- Discord: **@kauht** or **@yuhbayn**  
- Discord Server: https://discord.gg/WVMHUgrgeH  
- GitHub: https://github.com/kauht/Metis  

---

# Features

## Engine Core
- Standard chess rules and move generation
- Bitboard board representation
- Move ordering, pruning, and optimizations

## Modes
- Classic: standard, rating based play
- Stalemate seeker: attempts to draw as fast as possible
- Suicide mode: attempts to lose as fast as possible
- Human-like: human clock response, blunders

## Testing & Benchmarking
- Performance and speed benchmarking
- Perft tests (move generation validation)
- Search correctness verification
- Profiling utilities

## Future?
- Custom UI or visualization engine
- AI features like Maia

---

# Roadmap

## Core Engine
- [ ] Leagal move generation
- [ ] Implement search algorithms (Minimax, Alpha-Beta)
- [ ] Transposition tables
- [ ] Zobrist hashing

## Modes
- [ ] Classic mode
- [ ] Stalemate mode
- [ ] Suicide mode
- [ ] Human-like engine (rating-based)
- [ ] AI?

## Benchmarking
- [ ] Perft testing framework
- [ ] Performance profiling
- [ ] Integration tests

---

# Research

See `RESEARCH.md` for a structured learning roadmap and resources, feel free to check it out and learn along with me!

---

# License

Metis is licensed under the MIT License.  
See the `LICENSE` file for full terms.
