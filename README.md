VOIDPACKET
Making games, websites, and tools with a security mindset.

---

### **Quick Facts**
- PWPA Certified (TCM's Practical Web Pentest Associate).
- 30+ private program invites on Intigriti & Ex-QA at BugForge.
- I used to be a video editor and animator.
- Hobbies: Chess, Cycling and Rocket League.

### **What I’m Working On**
- The VOID Engine: Building my own game engine using C++.
- The VOID Plugin: A physics plugin for DaVinci Resolve so editors can use gravity and collisions.
- Web Arcade: A website full of games made with C++ and Raylib that run right in your browser.
- 2D Game: Just applying what I know (and plenty of Googling) to make a fun 2D game.

### **Learning Journey**
Mastering C++ (Manual memory management and all the hard stuff).
Learning how to build physics into games.
Figuring out how to make C++ and Web Dev work together.

### **VOIDPACKET's Challenge: Spot the Bug!**
I can't turn off my QA brain. Can you find the memory mistake in this C++ snippet?
```
#include <iostream>
int* getPlayerScore() {
    int score = 100; 
    return &score; // This is a trap! 
}
int main() {
    int* myScore = getPlayerScore();
    std::cout << "Player Score: " << *myScore << std::endl;
    return 0;
}
```
(Hint: What happens to 'score' when the function finishes?)

### **Let’s Chat About**
Game engines, DaVinci Resolve tools, or how to keep web apps secure without making them boring.
You can find my Socials in my Bio
