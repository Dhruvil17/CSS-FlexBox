# CSS-Flexbox
This repo contains all the code that I wrote for practicing the CSS Flexbox and its various properties. 

# Notes of CSS-Flexbox
There are 2 major parts of Flexbox
1. Flexbox Axes
2. Understanding that everything in the Flexbox contains of Parent element and Child elements. 

Parent Element - Flex Container
Child Element - Flex Items

Flexbox Axes:
1. Main Axis (Main of the Flex Container)
2. Cross Axis (Perpendicular to Main Axis)

If the Flex-Direction: Row, then the Main Axis is Horizontal and Cross Axis is Vertical
If the Flex-Direction: Column, then the Main Axis is Vertical and Cross Axis is Horizontal
Content always goes along the Main Axis. (Unless any changes)


# Parent Element-Flex Container

Flex Container properties:

1. Flex Direction
Can be Row or Column.
It has values like row, row-reverse, column, column-reverse.
By default Flex Direction is row. 

2. Justify-Content
By default is is flex-start.
Is used to align the flex items along the main axis.
It has values like flex-start, flex-end, center, space-around, space-between

3. Align Items
It is used to align the flex items along the cross axis.
It has values like flex-start, flex-end, center, stretch, baseline.
By default it has value stretch.

4. Flex Wrap and Flex Flow
Specifies whether the flex items should wrap or not
It has values like nowrap, wrap, wrap-reverse
By default it has value of nowrap.

5. Align Content
It is used to align the flex lines
It has values like flex-start, flex-end, center, space-around, space-between
It aligns across the cross axis. 


# Child Elements-Flex Items

Flex Items Properties:

1. Order
Used to increase or decrease the order of the element to control its position. 
If order of an element is increased, then it will move ahead. 
If order of an element is decreased, then it will move backwards.

2. Align Self
Alignment is across the cross axis. 
It can be used to align a specific element (Flex Child) with some value and not all as in the case of align items.
It has values like flex-start, flex-end, center, stretch.
By default, it has value of flex-start. 

3. Flex Grow
Help the elements to grow or shrink the elements in the parent container.
It will grow relative to the rest of the Flex items.
The growth will be relative to the space available and allocated to that of the parent container. 

4. Flex Shrink
It defines how much a Flex item will shrink relative to the rest of the flex items.
All items have Flex shrink of 1 (Default value)
The more the flex-shrink, the more the elements will shrink.

5. Flex Basis
It specifies the initial length of a flex item.

6. Flex
Flex property is a shorthand property for the flex-grow, flex-shrink and flex-basis properties. 
Default values of everything in order are:
flex: 0 1 auto 
