:nth
====

:nth is a modular system designed to help explore, design, prototype, build grids and layouts for online content.

As the web evolves at an impressive pace it wants to be everywhere. All those "everywheres" come in different shapes and sizes.
:nth is an experimental tool inspired by new methodologies, processes and frameworks that are trying to address ever changing requirements.

--


#The Grid
:nth uses a twelve column grid as a base, which allows a variety of divisions and multiple combinations for the space to be organised. :nth uses some of those combinations as region types that determine how individual modules are rendered.
-

#Region
Any html element can be turned into a region by adding .reg class. :nth will render it's immidiate children using the region's type. For example, .r2 class will divide the region in half, while .r3 into thirds.
-

#Module
Any element renders as a module if it's direct parent is a region. It's size and position is determined by the type of the region. For example, all immidiate children of an .r4 region will use ~25% of the region's width.
-

#Staticfluid
The grid can be fluid or static. Additionally, max-width, min-width and % based width can be used to determine 'staticfluid' properties within a specified range. Magic!
-

#Media queries
Media queries can be used to change the grid's 'staticfluid' properties and/or change the type of any region depending on device or any other context.
-

#Left to right
Responsive design demands a different approach to information architecture. With :nth, thinking left to right aids design decisions.
-

#Fold / unfold
Fluid alone is not enough to build responsive layouts. Switching in between 2, 3 or 4 columns is easy when information flows from left to right.
-

#Nest
It's possible to nest regions within modules. This can be very helpful when creating more complex grids and when precise folding / unfolding is required.
-

#Stack
There's no real limit to how many modules can be stored within a region. They will all render as defined by the region's type in multiple rows.
stack
-

#In. Not out.
:nth encourages IE 5 box-model. All :nth elements use CSS box-sizing:border-box; which handles a module's paddings & borders without disturbing the order. It's :nth's way of adding % with pixels.
-

#Use less

:nth is distributed as a less file. Using less allows more control over layouts and all mentioned properties of :nth.


Stay tuned @nthcss
