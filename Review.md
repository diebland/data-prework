# Review Prework

Hi Antonia 🙋🏻‍♀️!! I am writing to give you some feedback on your prework! 🚀

### 1. Snail-and-Well

Great that you got the Bonus! This exxercise it's perfect!!! Nothing to say!

### 2. 🧙🏽‍♂️🧙🏽 Duel-of-Sorcerers 🧙🏽‍♂️🧙🏽

The first part of this exercise it's perfect, congratulations!!! I should like to highlight two things, I hope they add value to you:

- In the exercise 3 *Using the lists of spells of both sorcerers, update variables gandalf_wins and saruman_wins to count the number of times each sorcerer wins a clash*. When you create a `for` loop, if you have two options note that it's not necessary to include the elif condition, you can use `else`: 
    ```python
    for i in range(spells):
        if saruman [i] > gandalf[i]:
            saruman_wins +=1
        else:
            gandalf_wins +=1
    ```
    But, as I said before, it's just a detail. The exercise it it's really good 💪 

- Let's go with the bonus!   
  
    I give you some tips to solve this exercise, but if you have any question we can ask me by slack at any time 😉. 

    - Assign spell power lists to variables, one for each sorcerer
    ```python
        gandalf_power = []
        for spell in gandalf:
            gandalf_power.append(POWER[spell])
    ```
    -  Execution of spell clashes, exactly the same as what you have in the previous exercise
    -  Check for 3 wins in a row
        ```python
        if ((total_gandalf_wins >= 3) or (total_saruman_wins >= 3)):
            print ("We have a winner!")
        else:
            print ("No wizard won 3 spell clashes in a row. There are no winners.")
        ```
    - Finally, check the winner

In any case Antonia, you did a good job in this part of the prework! keep on doing it 🚀!!!


### 3. Bus

This exercise it's really perfect, good job!!! 

### 4. Robin-Hood

Good job using `list comprehension` 👏🏽. It is a advance coding method that could help us a lot to atomize our code.
Again, you did a perfect work in this exercise. Congratulations!!!!

### 5. Temperature-Processor

Again...well done. Not only execute the code in the best way possible, but you have explained each steop you have take very weel with a very good logic. 

Only, as a detail, in python yoy have the `mean` function that give us the mean of a given list of numbers. We only need to import `statistics` library. Here is an example in case you find it usefull:

```python
import statistics
numbers = [1, 3, 4, 5, 7, 9, 2]
  
x = statistics.mean(numbers)
  
print("Mean is :", x)
```
### 6. Rock–Paper–Scissors

The last exercise, perfect Antonia! Really, really good job! 
In the last exercise: 

*Now it's time to code the execution of the game using the functions and variables you defined above.*

You are rewriting the functions that you define above (i.e. `computer`, `choices`, `round_result` and `round_result`). However, it's no necessary. When you define a function, you can "call" that function anywhere in the code without having to rewrite it, and save the return value in a variable. For example:

```python
while cpu_score<rounds_to_win and player_Score<rounds_to_win and playedrounds<n_rounds:
    #Computer chooses
    cpu = computer(gestures)

    # Player chooses
    player = choices(gestures)

    ...the rest of the code
```

Overall, really great job Antonia!!! You are ready to start and enhance you python knownledge!  See you soon! 🔥🚀💪
