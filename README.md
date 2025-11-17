# Bean Merger Game

**Bean Merger** is an interactive learning game that promotes mathematical thinking and logical reasoning through play. In this specific mission, players must combine numbers to crack the safe!.Players select two numbered “beans,” combine them using a mathematical operation (**+**, **−**, **×**, or **÷**), and merge them into a new result.The Challenge: You win the Jackpot only if the final remaining bean has the value 0.

<img src="https://github.com/robomustib/BeanMerger/blob/main/img/bohnenverschmelzen_logo.jpg?raw=true" alt="The Blackbox Simulator Logo" width="50%"/>

---

## Learning Objectives
- Strengthen mathematical reasoning and planning skills  
- Practice the four basic arithmetic operations in a playful way  
- Develop problem-solving and combination strategies  
- Foster motivation through visual and interactive feedback
- Learning strategies to eliminate numbers (e.g., subtracting equal numbers: 5−5=0).
- Planning moves ahead to ensure the final operation results in zero.

---

## General Educational Context
The game and tool can be used in mathematics or technology lessons to support logical thinking, decision-making and visualize computational thinking. 
It’s particularly suitable for:
- Elementary students (grades 3–5)  
- Inclusive classrooms (low entry barrier, visual feedback)  
- Self-guided learning or station-based activities
- Introducing the concept of inverse operations.

---

## AI Connection (Game as a Problem Solver)

Conceptually, the game can be extended to highlight its AI relevance:

- Children plan their moves to achieve a goal (merging beans into zero).  
  → This corresponds to **state-space search** in AI (e.g. AI Search Algorithms):  
    Each state (arrangement of beans) can be transformed by an action (operation).

- Every combination of beans represents a **node in the solution tree**. Some branches lead to dead ends (e.g., ending with a 5), while others lead to the goal (0).
  → Children choose heuristically (intuitively) “good moves” — similar to how an AI selects optimal actions. 

- If a calculation doesn't lead to 0, the player realizes they need a different strategy—similar to how an algorithm backtracks to find the optimal path (Backtracking).
  → the specific target: State = 0
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
1. Start: The game generates 5 random numbered beans. The sum of these numbers is the Jackpot.
2. Merge: Click two beans and select an arithmetic operator (+, −, ×, ÷). 
3. Strategize: Try to create pairs of equal numbers so you can subtract them to get 0.
4. Win: If your very last bean is 0, you win the Jackpot!

---

## Features
- Automatic save and load of game progress  
- Reset option for a fresh start  
- Animated “You Win” confetti  
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
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---
