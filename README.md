# Where-to-Meet

You might have heard of When-to-Meet, an app that allows you to enter your time preferences and align when to meet your group or your friends. Now introducing *Where-to-Meet*, a way to meet your friends based on both time and distance. Let's say you live in Westwood, your friend Joe in WeHo, Gloria in the Fashion District, and Frank in Marina Del Rey. You want to meet for a beer, but don't want to make anyone schlep too much. So you try and find the point where everyone drives the same amount of time since we are good friends.

<img width="1570" height="1164" alt="image" src="https://github.com/user-attachments/assets/af4e90a9-4580-472f-8bf7-7944e896d08e" />


*Where-to-Meet* uses a graph of the main pick-up/drop-off in LA and the time between based on Uber Data from 2019 Q4. It then employs a minimax search over possible meeting points based on distance heuristics in order to find the best meeting location in terms of distance and time.
