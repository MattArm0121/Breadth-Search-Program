Today in class we began to talk about implementing AI. Mainly, enemy AI.

We went over an example of a shooter game. What is the shortest path an enemy AI can track to your location when accounting for walls and slopes? 
We then began talking in a 2D game, going over different search algorithms. After that, we began building the fundamentals of our window but after that was done it was time for us to handle coding a search algorithm with one of the examples we were taught earlier.

I decided to code using the breadth search program as it felt like it made the most sense to me. I had a vector of vector nodes. The inner vector was the four direct neighbours (or fewer if at a boundary or against a wall). The outer vector kept all nodes that were searched. It would keep looping each step until the end was found, in which case using a parent list I would draw the yellow line showing the shortest path.

There are a few things I can do to make it look visually better, such as drawing the yellow line one node at a time. Not all at once. For now, here is an example.

<img width="1980" height="1034" alt="Recording 2026-08-26 081207 (1)" src="https://github.com/user-attachments/assets/bd002e02-c241-457c-befd-c0f9c51f5ce6" />
