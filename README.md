# CTF-linux

## Welcome to Linux CTF Challenge

- This is a Docker-based Linux CTF (Capture The Flag) challenge.

- It’s designed to help you learn Linux concepts, security, and system administration in a fun and hands-on way.

- Each level is packaged inside its own Docker container.
  
- Solve the challenge inside one container, grab the flag, and move to the next level 🚀


![CTF Poster](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSVIf8rbpraq5MXlGvG2zc0Q4DytweNf2wFDR8Vr3kSv4bkrbM2XX3Me6wk3oBiZeIL50A&usqp=CAU)


# 📦 Requirements

- Docker installed on your system → Get Docker

- Basic Linux knowledge (shell, users, permissions, etc.)

# Curiosity + patience 😎

▶️ How to Play
```
Each level is a separate container image:

Level 1 → abhaydandgedocker/ctf-linux:lvl1

Level 2 → abhaydandgedocker/ctf-linux:lvl2

Level 3 → abhaydandgedocker/ctf-linux:lvl3

Level 4 → abhaydandgedocker/ctf-linux:lvl4

Level 5 → abhaydandgedocker/ctf-linux:lvl5
```
## Run a container for the level you want to play:

# Example: Start Level 1
```
docker run -it --rm abhaydandgedocker/ctf-linux:lvl1
```

- You’ll be dropped into the challenge environment.
- Your mission → Find the flag file or secret string 🎯

# 🏆 Rules

- Don’t brute force the container (use your brain, not your CPU 😅).

- Each level has exactly one flag.

- Once you capture the flag, move to the next level.

- Share your learnings, not the flags (don’t spoil the fun for others 🔒).

# 📖 Example (Level 1 Walkthrough)

Start Level 1:
```
docker run -it --rm abhaydandgedocker/ctf-linux:lvl1

```
- Explore the container (ls, cat, find, etc.).

- Solve the puzzle and capture the flag.

- Example flag format:

- FLAG{congrats_you_solved_lvl1}

# 🎮 Levels
```
Level 1: Basic Linux commands

Level 2: File permissions

Level 3: Hidden processes

Level 4: Networking basics

Level 5: Privilege escalation
```
# 💡 Tips

- Use commands like cat, grep, find, strings, ls -la.

- Sometimes permissions matter more than content.

 😉

# 🔗 Connect

Created by: Abhay Dandge

If you’re interested in collaborating or have suggestions, let’s connect:

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/abhaydandge/)
