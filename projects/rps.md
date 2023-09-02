---
layout: project
type: project
image: img/rps-square.jpg
title: "Rock Paper scissors"
date: 2021
published: true
labels:
  - Java
  - Java Swing
  - Player vs Computer
  - Game
summary: "A GUI game of Rock Paper Scissors play with the computer. Using Java AWT and Java Swing libraries for the graphical user interface develope in Java"
---

<p>Rock Paper Scissors is one of the projects I developed in my ICS 211 class. By implementing Java Swing, a toolkit that helps us create user interfaces on the Java platform, this project helped us practice with event handlers to implement Action listeners, allowing users to directly manipulate the software through buttons, text, and user feedback. In this game, the user plays against the computer, and they can choose between rock, paper, or scissors. The results are saved as a .txt file in the same directory.</p>
<h3>Project detail</h3>
<p>Starting the game, we will see the game interface as shown below. On the left side of the panel, we will see four options: instructions, rock, paper, and scissors. In the middle of the panel, the player's selection will appear. To the right of the panel, there are two options: play again and exit. Finally, below the panel, there will be the player's score and the computer's score.
After the player chooses one of the three options, the system will randomly choose the computer's choice. Based on the rules of the classic rock, paper, scissors game, it will be determined who wins. A new panel will then pop up to announce whether the player has won or lost.</p>
<p>After the player exits the game, the system will store the scores in the "scores.txt" file before shutting down the application completely. The user can review the game scores in the same folder as the project launch file.</p>
<img class="img-fluid" style="display: block;
  margin-left: auto;
  margin-right: auto; src="../img/rps2.jpg">
