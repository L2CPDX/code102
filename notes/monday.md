Open VS Code Terminal: CTRL + `

TIL:

JavaScript is hard, it hurts my brain.

I have made progress. I figured out Function parameters, which pretty much suck and made my brain leak out my ears for the first twenty minutes that I looked at the exercise. 

Basically, It's a (somewhat counterintuitive) way to condense variables into functions. And it sucks.
Observe. 

Before:

var drawMole = function() {
    var moleX = 248;
    var moleY = 185;
    
   //pretend there's code in here
};

drawMole();

After:

var drawMole = function(moleX,moleY) {
  
  //pretend there's code in here
};

drawMole(248,185);




