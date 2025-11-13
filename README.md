# Bean Merger Game

**Bean Merger** is an interactive learning game that promotes mathematical thinking and logical reasoning through play.Players select two numbered “beans,” combine them using a mathematical operation (**+**, **−**, **×**, or **÷**), and create a new bean showing the result. The goal: end up with **just one bean**!

<img src="https://github.com/robomustib/BeanMerger/blob/main/img/bohnenverschmelzen_logo.jpg?raw=true" alt="The Blackbox Simulator Logo" width="50%"/>

---

## Learning Objectives
- Strengthen mathematical reasoning and planning skills  
- Practice the four basic arithmetic operations in a playful way  
- Develop problem-solving and combination strategies  
- Foster motivation through visual and interactive feedback  

---

## General Educational Context
The game can be used in mathematics or technology lessons to support logical thinking and decision-making.  
It’s particularly suitable for:
- Elementary students (grades 3–5)  
- Inclusive classrooms (low entry barrier, visual feedback)  
- Self-guided learning or station-based activities  

---

## AI Connection (Game as a Problem Solver)

Conceptually, the game can be extended to highlight its AI relevance:

- Children plan their moves to achieve a goal (merging beans into one).  
  → This corresponds to **state-space search** in AI:  
    Each state (arrangement of beans) can be transformed by an action (operation).

- Every combination of beans represents a **node in the solution tree**.  
  → Children choose heuristically (intuitively) “good moves” — similar to how an AI selects optimal actions.

---

##  Educational AI Connection (Unplugged Thinking)

The game can serve as a stepping stone to AI concepts, especially:

- **Rule-based systems:** Making decisions according to fixed rules.  
- **Heuristics:** “Which combination brings me closer to the goal faster?”  
- **State evaluation:** Which step brings the system closer to the target state?

Children practice **algorithmic thinking and strategy development**, which are fundamental skills for understanding AI.

---

## Technical Overview
- **HTML** – provides the game’s structure  
- **CSS** – defines the design, animations, and layout  
- **JavaScript** – controls the game logic (creating, merging, and storing beans)  
- **LocalStorage** – saves the player’s progress in the browser  

---

## How to Play
1. Click on two beans to select them.  
2. Choose an arithmetic operation.  
3. The two beans merge into a new one with the calculated result.  
4. Repeat until only one bean remains — you win!  

---

## Features
- Automatic save and load of game progress  
- Reset option for a fresh start  
- Animated “You Win” popup  
- Clean and responsive design  

---

## Demo
Click here to try out:
[BeanMerger Demo](https://www.mustafa-bilgin.de/bohnenschatzkiste)

---

## Author
Developed by **Mustafa Bilgin** as part of the *FUTURE-STEM-HUB* project.  
The game is designed to combine **computional thinking** with **inclusive and playful educational approaches**.

---

## License
This project can be shared and adapted for **educational and non-commercial use** under the [CC BY-NC-SA 4.0 License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

---
