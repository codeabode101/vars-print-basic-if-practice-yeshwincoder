# **🚀 Monday: Launch Your Rocket**  
**Prompt:**  
Create a space explorer profile!  
1. Use variables to store:  
   - Your astronaut's name
   - Your rocket's fuel level (any number between 0 and 100)
   - Your starting planet

2. Print a message like:  
   `🌎 [Your Name] blasts off from [Planet]!`  

3. Use an `if` statement to check if the fuel is 100. If it is, print:  
   `Fuel tank is full! Ready for launch!`  
   Otherwise, print:  
   `Fuel tank is not full. Check before launch!`


# **🪐 Tuesday: Planet Approach**  
**Prompt:**  
Your rocket is approaching a new planet!  
1. Change the `planet` variable to a new planet
2. Print a message like:  
   `ALERT! Approaching [Planet]!`  

3. Use an `if`/`else` statement to check the planet:  
   - If the planet is `"Mars"`, print:  
     `You see craters!`  
   - Else, print:  
     `You see clouds!`  

4. Use another `if` statement to check if the fuel is above 50. If it is, print:  
   `Fuel level is good for landing.`  
   Otherwise, print:  
   `Warning: Low fuel for landing!`

---

# **☄️ Wednesday: Asteroid Field**  
**Prompt:**  
An asteroid field is blocking your path!  
1. Create a variable called `choice` and set it to either `"shoot"` or `"dodge"`.  
2. Use an `if`/`else` statement:  
   - If `choice` is `"shoot"`, subtract 30 from `fuel` and print:  
     `💥 Lasers fired! Fuel -30%`  
   - Else, subtract 10 from `fuel` and print:  
     `🌀 Dodged! Fuel -10%`  

3. Use an `if` statement to check if the fuel is below 20. If it is, print:  
   `CRITICAL WARNING: Fuel very low!`  
   Otherwise, print:  
   `Fuel level is stable.`

---

# **👽 Thursday: Alien Encounter**  
**Prompt:**  
You’ve encountered aliens!  
1. Create a variable called `alien_mood` and set it to either `"friendly"` or `"angry"`.  
2. Use an `if`/`else` statement:  
   - If `alien_mood` is `"friendly"`, add 20 to `fuel` and print:  
     `🎁 Got space crystals! +20% fuel!`  
   - Else, subtract 25 from `fuel` and print:  
     `💣 Alien attack! -25% fuel!`  

3. Use an `if` statement to check if the fuel is above 75. If it is, print:  
   `Fuel tank is almost full!`  
   Otherwise, print:  
   `Fuel tank is not full yet.`

---

# **🎇 Friday: Mission Success**  
**Prompt:**  
Time to check if your mission was successful!  
1. Use an `if`/`else` statement to check the `fuel` level:  
   - If `fuel` is greater than 50, print:  
     `🌟 [Your Name] reaches [Planet] safely! 🌟`  
   - Else, print:  
     `💥 [Your Name] needs rescue from [Planet] orbit!`  

2. Use another `if` statement to check if the planet is `"Mars"`. If it is, print:  
   `You made it to the Red Planet!`  
   Otherwise, print:  
   `You explored a new world!`  

3. Print the final fuel level.

# **Next Steps:**  
Check out `input()` and replace the choices you make in the code.

For example, instead of:

```py
choice_cat = "dog"
```

You can change it to:

```py
choice_cat = input("Are you a cat or a dog? ")
```
