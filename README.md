
Snowfall Animation with CSS3
============================

I created this little holiday card over a year ago with CSS3, luckily now I use Less,
but here is the code for a snowfall animation using CSS transitions and keyframes.
Use it however you like, including the image which I created using Adobe Illustrator.

Details
-------

Basically all you need to do is create some empty divs in your HTML 
and create circles in the css

        <div class="snowOne"></div>
        <div class="snowTwo"></div>
        <div class="snowThree"></div>
        <div class="snowFour"></div>
        <div class="snowFive"></div>
        <div class="snowSix"></div>
        <div class="snowTwo" id="moveTwo"></div>
        <div class="snowOne" id="moveOne"></div>
        <div class="snowThree" id="moveThree"></div>
        <div class="snowFive" id="moveFive"></div>
        <div class="snowOne" id="slowOne"></div>
        <div class="snowSix" id="moveSix"></div>
The trick is to start the animations at different times and angles 
yet they need to come from the same direction so it looks natural.


