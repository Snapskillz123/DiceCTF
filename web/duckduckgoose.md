# Duckduckgoose

The link provided shows a game with a dice and a goose(a black square for some reason). I experimented with the game and randomly started moving the dice with
the 'wasd' keys and I won the game but it was fucking useless.

I then went through the js code and saw that the goose moves randomly when the dice is moved.

![image](https://github.com/Snapskillz123/DiceCTF/assets/149099858/c87fde27-6206-4ab2-ae90-54bdbf3d99ea)

![image](https://github.com/Snapskillz123/DiceCTF/assets/149099858/b4306811-ccf4-4ee3-bbf9-994911b61a01)

On further examination of the code i found this snippet of code that tells it would print the flag if the game is won with a score of exactly 9 points, which
is impossible with the goose moving randomly.

![image](https://github.com/Snapskillz123/DiceCTF/assets/149099858/1be284db-a6fe-4a37-8e1a-67961f1c630e)

I then overrided(or overid whatever) the js code and changed the random fucntion to a hard codede value for predictable movement of the duck.
I won the game in 9 moves and the flag was printed in the console log.

![image](https://github.com/Snapskillz123/DiceCTF/assets/149099858/1fdb85d8-c2fe-4839-b868-3b3a866d7ee8)

  # Flag

  dice{pr0_duck_gam3r_AAEJCQEBCQgCAQkHAwEJBgQBCQUFAQkEBgEJAwcBCQIIAQkB}


