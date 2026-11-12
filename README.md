# Harry-Potter-Trivia-Game
A modular Harry Potter trivia game featuring 3 difficulty tiers, multiple-choice &amp; direct-input questions, a House Points scoring system, life tracking, and a password-protected Admin CRUD mode.


1. Magical Question Vault & Admin Controls (CRUD Module)
A collection of 15–20 Harry Potter–themed trivia questions will be stored in an array, with a corresponding answer array aligned in sequence.
 To prevent unauthorized access, an admin mode will require a secure 12-character alphanumeric password.
 Inside the admin panel, authorized users can create new questions, edit existing ones, remove questions that are no longer needed, and adjust settings such as scoring rules and the number of player lives.
Assigned to: Developer 1

2. Question Format & Difficulty Structure (Question Engine)
The game will feature mixed question types such as:
Multiple-choice questions (e.g., “What is Harry’s Patronus?”)


Direct-input questions (e.g., spell names, numerical answers, Yes/No)


Questions will be organized into three ascending levels of difficulty:
 Easy → Moderate → Hard, covering basic facts, deeper lore, and advanced magical knowledge.
Assigned to: Developer 2

3. Feedback Messaging System (User Response Handler)
After each attempt, the player will instantly receive feedback through customized messages like:
“Brilliant! You answered correctly.”


“Alas! That was incorrect.”


This module handles all correct/incorrect response displays and manages invalid inputs.
Assigned to: Developer 3

4. House Points & Life Counter System (Life/Attempt Manager)
Players begin the quiz with 3 lives, representing their magical stamina.
 Each incorrect answer reduces the life count.
 If the number of lives reaches zero, the game ends immediately.
 Admins can modify the initial number of lives through the settings panel.
Assigned to: Developer 4

5. Sequential Question Navigation (Array Looping Logic)
The trivia flows automatically from one question to the next using loop structures that iterate through the question arrays.
 Once the final question in one difficulty tier is completed, the system seamlessly transitions to the next level.
Assigned to: Developer 5

6. Scoring & Final Results Display (Score Manager)
Every correct answer awards House Points based on question difficulty:
Easy = 1 point


Moderate = 2 points


Hard = 3 points


At the end of the quiz, the player’s total score is shown alongside a themed message (e.g., “You’ve earned 18 points for your House!”).
 The scoring values can be adjusted by the admin.
Assigned to: Developer 6
