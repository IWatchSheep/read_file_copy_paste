the program reads a file to find out if the file is empty.

if the file is not empty then the file is copied to the clipboard, then the mouse moves over a text file, then the clipboard is pasted into a second text file and saved.

then the original text file is emptied.

then you can put more text into the original file, save it, then that will automatically be put into the second text file while erasing the text in the second text file.

then to stop this you press the escape key on the keyboard.

the text below is only an idea not related to this repository.
/////////////////////

see picture of blue square in middle top, two stacked blue squares bottom left, two stacked pink squares bottom right.
the box with text is below the top middle blue square, in the text box is line 1 = "condition" line 2 = "true" line 3 = "false".

the top blue box has a arrow pointing down to the word "condition".
the word "true" has an arrow pointing left to the top blue box on the left.
the word "false" has an arrow pointing right to the top pink box on the right.

the top blue box goes to another color either pink or blue and tests a color equality condition 
- the top blue box goes to the top pink stacked box. 
- the top pink stacked box goes to the bottom pink stacked box = 1 color blue, 2 color pink stacked boxes

- the top blue box goes to the top blue stacked box. 
the top blue stacked box goes to the bottom blue stacked box = 1 color blue, 2 color blue stacked boxes

description: 

- C++ inheritance.
The original class is labelled "Base". 
Additional classes are labelled "Derived". 

Derived class name appends the Base class name like this: 
Derived : Base
{
public:
};

- C++ polymorphism.
There is the same virtual function in the Base and Derived class.
Base* base = new Derived;
base->function(); // shows function in Derived class

- C++ casting.
There is a function in the Derived class not in the Base class. To use that function use dynamic_cast.

Base* base = new Derived;

// base->test(); // = error

Derived* derived = dynamic_cast<Derived*>(base);

if(derived)
{
    derived->test(); // shows function in Derived class
}

/////////////////////

see picture of square in middle top, two stacked squares bottom left, two stacked squares bottom right.
the box with text is below the top middle blue square, in the text box is:
condition
true
false

the top box minus sign has a arrow pointing down to the word "condition".
the word "true" has an arrow pointing to the top left box plus sign.
the word "false" has an arrow pointing to the top right box minus sign.

the top box has the plus and minus signs arranged with the plus on top and the minus on the bottom.
the two stacked bottom boxes on the left also have the plus and minus signs arranged with the plus on top and the minus on the bottom.
the two stacked bottom boxes on the right also have the plus and minus signs arranged with the plus on bottom and the minus on the top.

(the magnet_1 [positive to negative]) goes to condition - condition goes to (the flipped magnet2 [negative to positive]). (the flipped magnet2 [negative to positive]) goes to (the flipped magnet_3 [negative to positive]) = (1 repelled magnet = magnet 1), (2 attracted magnets: flipped magnets 2 and 3)

condition goes to (the magnet2 [positive to negative]). (the magnet2 [positive to negative]) goes to (the magnet3 [positive to negative]) = 0 repelled magnets, (3 attracted magnets: magnet1, magnet2, magnet3)
description: dynamic cast works if the classes have magnetic polarity. the magnets attract if inheritance is true.


/////////////////////


see picture of square in middle top, two stacked squares bottom left, two stacked squares bottom right.
the box with text is below the top middle blue square, in the text box is:
condition
true
false

the top box minus sign has a arrow pointing down to the word "condition".
the word "true" has an arrow pointing to the top left box plus sign.
the word "false" has an arrow pointing to the top right box minus sign.

the top box has the plus and minus signs arranged with the plus on top and the minus on the bottom.
the two stacked bottom boxes on the left also have the plus and minus signs arranged with the plus on top and the minus on the bottom.
the two stacked bottom boxes on the right also have the plus and minus signs arranged with the plus on bottom and the minus on the top.

to the left of the two stacked boxes on the left  is another box that has the plus and minus signs arranged with the plus on bottom and the minus on the top = top box left.
to the right of the two stacked boxes on the right is another box that has the plus and minus signs arranged with the plus on bottom and the minus on the top = top box right.
each of these two boxes plus sign has an arrow pointing down to the word "condition".
top box right box word "true" has an arrow pointing to the top right stacked box minus sign.
top  box left box word "false" has an arrow pointing to the top left stacked box plus sign.


(the magnet_1 [positive to negative]) goes to two magnets with polarity [positive to negative] and tests a magnetic attraction condition (the flipped magnet_1 [negative to positive]) goes to two magnets with polarity [positive to negative] and tests a magnetic attraction condition

(the magnet_1 [positive to negative]) goes to two magnets with polarity [negative to positive] and tests a magnetic attraction condition (the flipped magnet_1 [negative to positive]) goes to two magnets with polarity [negative to positive] and tests a magnetic attraction condition

description: the parent class might be false using magnets to decide, but not if the parent flips their magnetic polarity, then the polarity begins at the parent.

/////////////////////

{ 
( the magnet [positive to negative] ) 
divided by 
( 2 multiplied by ( the magnet [positive to negative] ) ) 
}

*

{
( 2 * ( the magnet [negative to positive] ) )
divided by 
( 2 * ( the magnet [negative to positive] ) ) 
}

=

{
( the magnet [positive to negative] ) 
divided by 
( 2 * ( the magnet [negative to positive] ) )  
}

description: using fraction multiplication to cancel like terms to simplify the math to get a ratio of 1 to 2.

////////////////////

the ratio (1 to 2) = the ratio (1 to 1) 
if, the divisor 2 being attracted magnets that sum up to 1 magnet.
[(-, +), (-, +)] = (-, +)

{[(-, +), (-, +)] * 2 } = {(-, +) * 2} 
= 
{(-, +), (-, +), (-, +), (-, +)} = {(-, +), (-, +)}

the multiplication product dividend parents are C++ virtual parents, they inherit the original factor dividend,
{(-, +) : virtual (-, +), (-, +) : virtual (-, +)}.
child (multiplication product) class : inherits parent ((multiplication factor) class

meaning (the dividend parents = 2) have opposite magnetic polarity to (the dividend parent = 1). 
the dividend 2 is the opposite polarity to the dividend 1.

meaning the {(-, +) : virtual (-, +), (-, +) : virtual (-, +)} = the child class divisor, so flip the polarity for the child;
{(+, -) : virtual (-, +), (+, -) : virtual (-, +)}.

the divisor of 2 inherits from virtual parents dividend, 
{(-, +) : (-, +) = (+, -), (-, +) : (-, +) = (+, -)}



/////////////////////

Energy = parent class with (Positive Negative) polarity + false condition Mass at rest = child class with (Positive Negative) polarity + true condition Mass at rest = child class with (Negative Positive) polarity + false condition

Energy = parent class with (Negative Positive) polarity + true condition Mass at rest = child class with (Positive Negative) polarity + false condition Mass at rest = child class with (Negative Positive) polarity + true condition

The energy changes when comparing attracting vs repelling magnets.

The mass at rest is the child class 2, the speed/velocity of light is from moving downwards to child class 3, so is child class 3 c? I think so. Child class 3 is using the velocity from child class 2 as a square. c is squared by the speed from child class 2 so child class 2 serves as both mass and c, c for when the third class uses it as another child class 3 for speed/velocity.

And that is how special relativity works into the theory.

/////////////////////

the mass at rest is in the fraction (1/2), because the energy 1, does not add to the velocity/speed of c that is child class 3.
imagine lack of energy in the wave slit experiment is the empty space between the wave marks on the wall.

(I add C++ NOT operator to the text above to show the visible lines in the double slit experiment)
NOT
 (the mass at rest is in the fraction (1/2), because the energy 1, does not add to the velocity/speed of c that is child class 3.
imagine lack of energy in the wave slit experiment is the empty space between the wave marks on the wall.)

this is the wave pattern.

(I add C++ NOT operator to the text above to show the visible lines in the double slit experiment)
NOT
(the mass at rest is in the fraction (1/2), because the energy 1, does not add to the velocity/speed of c that is child class 3.
imagine lack of energy in the wave slit experiment is the empty space between the wave marks on the wall.)

(I add C++ NOT operator to the text above to show the visible lines in the double slit experiment)
NOT NOT
 (the mass at rest is in the fraction (1/2), because the energy 1, does not add to the velocity/speed of c that is child class 3.
imagine lack of energy in the wave slit experiment is the empty space between the wave marks on the wall.)

this is the particle pattern.

/////////////////////

gravity = 9.8 meters per second divided by second 

{
- time = 0 (seconds)
- velocity = 0 (meters per second)
- position y = 0 (meters)
}

{
- time = 1 (seconds)
- velocity = 9.8 (meters per second)
- position y = 9.8 (meters)
}

{
- time = 2 (seconds)
- velocity = 19.6 (meters per second)
- position y = 29.4 (meters)
}

the math trick is:
- the top of the fall = 0 velocity
- and on the ground = 0 velocity

you go from:
- 0 in the air
- to 0 on the ground
- to 0 in the air

the velocity is dragging the first class magnet through the second and third classes magnetic polarities, creating repel and attract.

reaching the positive polarity of the third class = attraction, the velocity stops, so the attraction goes from the third class back to positive in the first class magnet.

the velocity moving through magnetic polarity means stretching the polarity of one magnet through the polarities of two other magnets.
then the stretching is stopped and the first magnet no longer moves its negative polarity through the second and third class magnetic polarities.

now the dynamic casting has a zero that is the magnetic polarity of positive on the first class parent.
then you have a positive on the bottom of the child class polarity, just like zero = zero.

from zero in the air to zero on the ground to zero in the air, you stretch. start the stretch from the parent to child, then release the stretch back to parent.

growin the length travelled each time, because of velocity.

stretching = adult age at some point of velocity, now the particle can be changed to a wave. the velocity is spent on a attraction to the third class positive polarity instead of the first class positive polarity.

this switches the attraction from the first class magnet that has (positive to negative) polarity, to the first class magnet that has the (negative to positive) polarity.

/////////////////////

starting with (a particle = the three classes) start stretching.

the velocity hitting the ground creates a bounce off the ground, the bounce flips velocity to move upwards.

the positive polarity from the child on the ground reaches up to the positive polarity of the parent in the air. the parent in the air (condition true) being ignored in favor of the parent in the air (condition false).
because (condition false) attracts the magnet on the ground which goes to the positive polarity of the second parent as a result, converting the particle to a wave in the process.

because the bounce has to stop, the particle in the air cannot stretch downwards anymore.
but the neighbouring magnetic polarity in the first class parent position also have a positive polarity the first class parent can go to. 
so the magnet goes to one of these neighbouring particles instead, creating a link with a new particle to take the role of the first class parent.

/////////////////////

the linked particle starts from zero velocity, but this time the particle in the air is negative, and the particle on the ground is negative.
the negative polarity from the child on the ground reaches up to the negative polarity of the parent in the air.
the parent in the air (condition true) being ignored in favor of the parent in the air (condition false).
because (condition false) attracts the magnet on the ground which goes to the negative polarity of the second parent as a result, converting the particle to a wave in the process.

magnetic attraction leads to going from [(condition false) = negative in the air = zero velocity], to [(condition false) = negative on the ground = zero velocity], which happens to be the other particle being stretched.
now both particles are being stretched in the wave as the result of only one particle being stretched.

/////////////////////


after thinking about this i think i can relate the movement logic to the diagrams of c++ code using dynamic casting, polymorphism, and virtual classes. but i will look at this one step or section at a time. then re-edit my document for clarification one section at a time.
