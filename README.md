# Lem-in – Ant Colony Pathfinding Simulator

Lem-in is a Go program that simulates the movement of ants in an ant farm.  
The goal is to find the fastest possible path from a start room to an end room using efficient pathfinding algorithms.

---

## ⚙️ How It Works

1. **Clone the repository**
   ```bash
   git clone <repository_url>
   ```

2. **Build the program**
   ```bash
   go build
   ```

3. **Prepare an input file describing:**
   - Number of ants  
   - Rooms and tunnels (connections)  
   - Start and end rooms  

   **Example input:**
   ```
   4
   0 2 4
   ##start
   2 5 2
   9 6 7
   ##end
   5 4 8
   0-2
   2-9
   2-5
   0-5
   ```

4. **Run the program with your input file**
   ```bash
   ./lem-in <input_file>
   ```

---

## 👥 Contributors
| Name | GitHub |
|------|---------|
| Gülbeyza Cüce | [gcuce](https://github.com/gcuce) |
| Cavit Karakuş | [cavit-karakus](https://github.com/cavit-karakus) |
| Sude Naz Demir | [sudenazdemir](https://github.com/sudenazdemir) |

---

## 💡 Notes
This project was completed as part of a team assignment at 01Edu.  
My main contributions focused on pathfinding logic, debugging input parsing, and improving performance in Go.
