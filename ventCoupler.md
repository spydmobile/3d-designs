# Building a truck part for functional print prototyping

## Designing the sub-components

### Prototype #1

#### The sprocket hole (Fusion 360)

The first challenge is to build the sprocket part that will be come the sprocket hole.
Measuring the original part for dimensions, 

![The original part and D hole](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.11.38 AM.png)

![SHowing the tab hole and the sprocket hole](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.12.37 AM.png)

I made the sprocket in 2d.

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-17%20at%203.06.22 PM.png)

![The first tooth](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-17%20at%203.23.11 PM.png)

![All teeth](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-17%20at%206.28.49 PM.png)

 ![Extrude the part](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-17%20at%2011.19.59 PM.png)

#### The D-shaft hole (fusion 360)

Now i construct the D-shaft that will become the shaft hole.

![make the circle for the d-shaft](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%206.52.18 AM.png)

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%206.53.33 AM.png)

And extrude that

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%206.54.44 AM.png)

We now have the 2 complex parts needed to make holes in the 3d construct that will become 3d printed prototype.

#### main part body (Bambu Studio)

From here we move from the Fusion 360 CAD into the Bambu Studio Slicer environment so we can complete our prototype and print it.

#### Adding The D-shaft hole

We create the bulk of the part body into which we will put a our Dshaft part as a negative, generating a hole, then we do the same for the sprocket.



![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.00.17 AM.png)

#### Adding The Sprocket hole

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.00.25 AM.png)

#### Creating the Tab

Now we will construct the tab and attach it to the main body


![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.02.54 AM.png)

#### Tab assembly

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.06.09 AM.png)

We position the tab correctly.
![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.06.58 AM.png)

#### The rounded hole

now we must contruct the tab hole:
![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.45.35 AM.png)

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.46.57 AM.png)

And make it a negative part (hole)

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.49.25 AM.png)

and place it in the tab

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.51.29 AM.png)

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.51.43 AM.png)

#### Slicing into G-CODE

We then slice it for printing.

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.11.50 AM.png)

now we are ready to print our first prototype.

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%207.12.09 AM.png)

Away we go:

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.05.03 AM.png)

#### 3d printing results

Here is our first printed prototype

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.17.14 AM.png)

#### Removing supports and interfaces

because we cannot print molten plastic in thin air, we build supports (Like a scaffold), as well as support interfaces (Go between the actual part and the support scaffold), so when printing above the bed that there is something to print on, the supports and interface must be manually removed when the print is complete.


![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.23.19 AM.png)

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.23.30 AM.png)

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.23.36 AM.png)

![Part Image](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.23.43 AM.png)

![Original vs Prototype 1](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.23.50 AM.png)

![Original vs Prototype 1](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.23.57 AM.png)

![Original vs Prototype 1](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.24.02 AM.png)

![Original vs Prototype 1](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%208.24.08 AM.png)

### Prototype 2

### the curved recess (fusion 360)

First we had to make a 3d part in fusion 360 to use as a cutting template.


![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%202.21.15 PM.png)

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%202.21.03 PM.png)

### Implementing the part in Bambu Studio

Here we must import the 3d part into bambu studio and place it correctly and make it a negative cut from the main body.

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%202.30.36 PM.png)

### Slicing V2

Now we slice it into G-CODE

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%202.45.47 PM.png)

And finally we send the gcode to the printer to print.

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%202.49.25 PM.png)

### Printing V2

Printing V2 on the Bambu Labs X1-Carbon + AMS

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%203.04.28 PM.png)


### V2 final print complete

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%203.28.00 PM.png)

### V2 support removal

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%203.28.13 PM.png)

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%203.28.27 PM.png)

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%203.28.39 PM.png)

### The finished V2 Prototype.

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%203.29.18 PM.png)

### V2 and OG comparison.

![partx](./fusion360/neil/vent%20coupler/images/Screenshot%202023-12-18%20at%203.28.58 PM.png)

## Additional possible complications we may need to revisit in future versions:

* the thickness of the outer wall around the D hole may be up to .5 mm too big. Only a test fit will confirm.
* The original part has the outward sprocket hole opening with a slight bevel to make it easier to slide the coupler on to the sprocket post. our part has none, but again only a test fit can confirm this.


