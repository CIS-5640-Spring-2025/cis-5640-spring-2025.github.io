---
type: assignment
date: 2025-1-30T10:15:00-5:00
title: 'Lab #2 - Game Loop Modification'
pdf: /static_files/assignments/Lab2.pdf
due_event: 
    type: due
    date: 2025-01-30T23:59:59-5:00
    description: 'Lab #2'
hide_from_announcments: true
---

This is the second lab of our game design class\! In this session, we will be modifying a classic dice game called **Pig**. The focus of this lab is to make meaningful modifications to the game loop. Unlike the previous lab, where you could experiment with random ideas, this time let’s try to constrain our modifications: we want to enhance and support the core game loop, not break it. We’re stepping into the shoes of a real game designer—time to embrace the challenge\!

---

## Pig

**Objective**: Be the first player to reach 100 points.

**Setup**: The game is played with two players and a single six-sided dice. Each player has their own score, which starts at zero.

**Gameplay**:

* On their turn, a player rolls the dice to add to their **turn score**  
  * Rolling a **1** ends their turn, and their turn score resets to zero (a "pig out").  
  * Rolling a **2-6** allows the player to choose:  
    * **Roll again** to add another number to their turn score (risking a roll of 1), or  
    * **Hold** to add their turn score to their total score and pass the die to the next player.  
* Turns alternate between players until one reaches 100 points.

**Winning**: The first player to reach or exceed 100 points wins the game.

---

**Task Details**

1. **Play the Original Pig Game**  
   * Play one round of the original Pig game and record how long it takes to complete the round.  
2. **Analyze the Game Loop**  
   * Reflect on Pig’s core game loop. Is it effective? Consider these four criteria:  
     1. **Clarity**: Does the player know what to do next?  
     2. **Motivation**: Does the player have a reason to act?  
     3. **Feedback**: Are the player’s actions acknowledged by the game?  
     4. **Satisfaction**: Does the player’s action feel rewarding on some level?  
3. **Modify the Original Pig Game**  
* Given what we’ve learned about game loops, create a modified version of Pig where the game ends at 200 points instead of 100\. Since the goal is further away, this puts more pressure on the core game loop to maintain player interest. Here are some potential strategies for your version:  
  1. **Variety in player actions**: offer players new ways to interact with the game.  
     * What if players could bet some of their points for a potential reward?  
     * What if players could use their points to purchase special abilities, like a reroll or protection from a "pig out"?  
  2. **Progression**: to prevent the game from feeling too repetitive, change something about how the game progresses towards the goal over time  
     * What if players had the opportunity to earn a larger number of points in later rounds?  
     * What if players could become “more powerful” in some way as the game progresses?  
  3. **Heightened Risk**: Add mechanics that make players feel more at risk while allowing those falling behind to **catch up**. For instance:  
     * Introduce alternative high-stakes choices, like risking all accumulated points for a big reward.  
     * Add penalties or rewards based on streaks (e.g., rolling three 6s in a row gives a bonus).  
     * Create a "catch-up mechanic," such as letting a trailing player double their score with a risky roll.  
* As you test modifications, consider how your changes will affect the core game loop.  
* If one of your rule changes breaks the game, note down how and why the game broke (so we can share with the class\!)  
4. **Playtest Your Modifications**  
* Play the modified game with your classmates and observe the outcome. Consider the following:  
  * How does your modification affect the core game loop of the original?  
  * Does the modification make the game feel less repetitive?  
  * Does it increase the sense of risk and excitement?  
  * Do players falling behind feel they have a chance to catch up?  
5. **Test Others’ Modifications**  
   * After hearing about your classmates’ modifications, pick a few interesting ones and test them yourself. Determine if these modifications successfully achieve their design goals.  
6. **Share the experience**  
   * Towards the end of the class, we will be swapping groups and testing out your modification with others\! So please note down your modifications.
