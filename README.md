## (Fluids 9808) Scientific Computation with Julia 

### **Step 1:** Download Julia

First, let's download the Julia programming language.

1. Go to the JuliaLang website: https://julialang.org/
2. Click on Download, and download the appropriate version of Julia for your computer (note for Mac users, make sure you install the correct version between Intel or Apple Silicon, depending on your machine) 

### Step 2: Download Pluto Notebooks 

Pluto is a notebook/cell-based IDE for Julia. Although we _can_ write + run Julia code in Jupyter Notebooks, many Julia users prefer Pluto because it takes advantage of powerful Julia features and actually encourages you to write clean and safe code. 

1. Open the Julia REPL (read-eval-print-loop) by opeing the Julia “app” you’ve downloaded in the previous step. This should open a terminal/command-prompt-esque window with the following prompt:
   ~~~
   julia>
   ~~~
   
2. Input the `]` character in the prompt (don’t need to press the “enter” key), this will change the prompt to `pkg>` and we are now in Julia’s built-in package manager. You should see the following:
   ~~~
   pkg> 
   ~~~
   
3. Now type:
   ~~~
   pkg> add Pluto
   ~~~
   and press enter. This will download Pluto and all of it’s dependencies. This might take about 1-2 mins, and you'll return to an empty `pkg>` prompt when it's complete.
   
4. Once the download/install is completely finished, pressing the backspace key in the package manager will bring you back to the Julia REPL.

And you’re done! That’s all you need to do to prepare for the Oct 16th class, but here’s how to open Pluto notebooks if you’re interested in exploring a bit:

* Open Pluto notebooks:
    * Type `using Pluto` in the Julia REPL and press enter (this imports the Pluto package to your current working environment) 
    * Type `Pluto.run()` and press enter. This will launch Pluto in your browser. If it doesn't automatically launch, type the url given to you in the terminal window
* After Pluto has launched, scroll down and explore/browse some of the featured notebooks :)
