# blockable
An user-experience API with a radical new vision for human-information interaction. 

### fundamental element of abstraction
The primary object of abstraction is a block. All kinds of interactions with an information system are represented as blocks.

<img src=https://i.ibb.co/DrL7znQ/Screen-Shot-2019-01-30-at-3-45-35-PM.png>

A block represents an action or a sequence of actions. Fundamentally speaking, a block encapsulates arbitrary computer codes. 

### fundamental properties of blocks

Each block in their empty state are identical with each other and can be modified to have properties in 5 degrees of depth. Each degree of depth introduces more complexity. 

**DEGREE 1: color**

The most simple degree of property is the color of the block. For example, in a system focused on simplifying complex data analytics workflows, the color may represent a type of process (e.g. data transformation). 

**DEGREE 2: iconography**

More properties can be added to each individual color through embedding glyphs on a single surface of the block (the top surface). Using the previous example, an icon may represent a specific kind of data transformation (e.g. normalization). 

**DEGREE 3: attributes**

Attributes allow introduction of more granular properties to blocks, and are presented on one or both sides of block. An example would be repeating a process represented by a block several times. 

**DEGREE 4: arguments**

Arguments behave in the same way as say python function arguments. An example of an attribute would be to allow changing default values, or provide other specifics (e.g. normalize data to max 1). An arbitrary number of arguments is supported for each block. Arguments live inside the block and do not change the physical appearance of the block.

**DEGREE 5: code**

Complete transparency and arbitrary configurability is provided for builders and advanced users through providing access to the underlying source codes of a block. Note that the codes reflect the functionality associated with the block.

### block movement

Each block has the additional properties of moving. Blocks can move in a 2-dimensional cordinates. Blocks can't rotate or turn. Blocks can be placed adjacent (to left or right) of other blocks, or on top of other blocks. Blocks can't overlay another block, and movement a block or a set of blocks can be restricted in any way, for example to prevent end-states that 

### execution 

Blocks are first arranged by the user, as well as configured, in the desired way much like a user would go through the process of completing a web form in a typical modern user interface. Once a desired end-state is reached, the resulting implicit computer codes are computed. 

## credits

Blockable is an [Eka foundation](http://eka.to) information interaction project. And is inspired by [SugarOS](https://sugarlabs.org/) and [Scratch](https://scratch.mit.edu/). Blockable leverage [Draggable](https://shopify.github.io/draggable/) as an UI geometric API.
