1Setup
    Github shenanigans.
2 Gather gifs/images/etc.

1 Coding

<!--2 Create a bootstrap display container - set the background.
    Bootstrap inner layout
        area for a Question / start button (timer) / category / difficulty
        area for 4 seperate answers as buttons?
            Who wants to be a millionaire style?
            onHover element opacity change? -- button with danger class.-->

<!--2.5 Create a Start/Start over function
    Clears all global variables
    clears ajax array
    Generate a question object/array using Ajax
            Waits for array to be created before running display function.-->

<!--3 Create Question display function
    checks to see if game is ended
        if game is over - calls game end function and then return to end display function.
        if not, adds 1 to question counter variable continues function.
    calls to ajax array pulls out Question/category/difficulty by index, and 4 choices,
        randomizes where answer is put
        displays major elements-->

    Begins interval timer
        calls a display timer as it updates
        if it reaches 0 adds 1 to unanswered question value.
            calls clear interval timer function



<!--4 Create onClick functions.
    1Start button (put it into the html)
    2Answer button -check to see if answer or not and counts it to a variable
    Calls clear interval timer function-->


5 Create Clear interval timer function
    Clears interval timer
    displays image associated with last category
    Calls interuption timer
        at end of time it calls display function.

6 End game function
    Displays stats over image area
        number: right/wrong/unanswered
        Start Over button


7 Clean up
    Make a whitespace clear funtion if enough time?
    Use it to allow proper spacing and editing of non initial layouts?
