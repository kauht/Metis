# Metis Research

---

## 1. Fundamentals

### Topics
- Board representations (Array, Bitboards)  
- Move generation and legality checks  
- Standard chess rules and edge cases  

### Resources
- https://www.chessprogramming.org/Main_Page  
- https://www.chessprogramming.org/Bitboards  
- https://www.chessprogramming.org/Move_Generation  

### Test Project
- Implement a board with bitboards. Generate all legal moves for a position. Verify against perft(3) or perft(4) positions.

---

## 2. Search Algorithms

### Topics
- Minimax  
- Alpha-Beta pruning  
- Iterative deepening  
- Quiescence search  

### Resources
- https://www.chessprogramming.org/Minimax  
- https://www.chessprogramming.org/Alpha-Beta  
- https://www.chessprogramming.org/Iterative_Deepening  

### Test Project
- Build a search that selects the best move given a simple evaluation function. Verify with mini positions.

---

## 3. Evaluation Functions

### Topics
- Material evaluation  
- Piece-square tables  
- Positional heuristics  
- Dynamic evaluation (king safety, mobility)  

### Resources
- https://www.chessprogramming.org/Evaluation  
- https://www.chessprogramming.org/Piece-Square_Tables  

### Test Project
- Write a function that scores a board position. Compare against known evaluations for test positions.

---

## 4. Transposition Tables & Hashing

### Topics
- Zobrist hashing  
- Transposition tables  
- Move ordering using history heuristics  

### Resources
- https://www.chessprogramming.org/Zobrist_Hashing  
- https://www.chessprogramming.org/Transposition_Table  

### Test Project
- Implement Zobrist hashing for your board. Integrate transposition table into search. Verify cache hits improve performance.

---

## 5. Custom Modes & AI Personalities

### Topics
- Human-like timing and blunders  
- Rating-based move selection  
- Novel mode experimentation (suicide mode, stalemate mode)  

### Resources
- Maia Engine paper: https://arxiv.org/abs/1812.07039  
- UCI engine protocol: https://en.wikipedia.org/wiki/Universal_Chess_Interface  

### Test Project
- Create a “human-mode” AI that blunders occasionally and respects a simulated clock.

---

## 6. Advanced / Experimental

### Topics
- Neural network evaluation (optional)  
- Custom pruning/search heuristics  
- Novel move generation strategies  

### Resources
- https://www.chessprogramming.org/Neural_Networks  
- Open-source engines for inspiration: Stockfish, Lc0  

### Test Project
- Implement a simple neural eval (optional) or experiment with a unique pruning method. Benchmark against classical search.

---

## Tools & Languages

- **C++17/20** – main engine implementation  
- **Lean/Typst** – optional for math/proofs or visualizations  
- **Zig/Odin** – inspiration for clean modern language features  
- **Testing Frameworks** – Catch2, GoogleTest for C++ testing  
- **Benchmarking** – chrono timers, performance counters, profiling  

---

# Checklist

- [ ] Legal move generation
- [ ] Search + pruning
- [ ] Evaluation function
- [ ] Transposition table + hashing
- [ ] Custom modes
- [ ] Benchmarking & testing
