# Debugging  Hacking with Swift.
Some debugging tips.
Everyone hits problems sooner or later, so learning to find and fix them is an important skill.


# Topics 
print(), assert(), breakpoints, and view debugging


 # Challenge
One of the best ways to learn is to write your own code as often as possible, so here are three ways you should try your new knowledge to make sure you fully understand what’s going on:

1.Temporarily try adding an exception breakpoint to project 1, then changing the call to instantiateViewController() so that it uses the storyboard identifier “Bad” – this will fail, but your exception breakpoint should catch it.

2.In project 1, add a call to assert() in the viewDidLoad() method of DetailViewController.swift, checking that selectedImage always has a value.

3.Go back to project 5, and try adding a conditional breakpoint to the start of the submit() method that pauses only if the user submits a word with six or more letters.

# Screenshots 

<img width="1280" alt="Screenshot 2023-01-06 at 09 53 12" src="https://user-images.githubusercontent.com/79315087/210968361-d522cf9d-5198-467b-aa6f-a8590657b161.png">
<img width="1280" alt="Screenshot 2023-01-06 at 09 57 55" src="https://user-images.githubusercontent.com/79315087/210968370-65122228-339d-4f5d-a299-52c855821904.png">
<img width="1280" alt="Screenshot 2023-01-06 at 10 03 20" src="https://user-images.githubusercontent.com/79315087/210968376-4cae7ce4-fd5f-443c-a756-b861bb040144.png">


