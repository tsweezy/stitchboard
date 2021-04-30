# stitchboard
Stitchboard is a web-based vector graphic art application built with Fabric.js.

[Click here to start drawing!](http://35.231.135.49/index/project/stitchboard/stitchboard.html)

![image](https://user-images.githubusercontent.com/45302428/116645872-ba18f480-a944-11eb-93c3-1418424b736b.png)

*This was a project created for my Computer Graphics course at Grand Valley State University Winter 2021.*

## Tools
We'll start with the toolbar on the left side of the screen. At present, Stitchboard has five main tools artists can use at their disposal to create graphics:

![image](https://user-images.githubusercontent.com/45302428/116643763-c51d5600-a93f-11eb-8bf8-c96fa1a160b6.png)

### Select
*hotkey: 1*

Select can be used either by clicking directly on an object (or multiple objects while holding Shift) or dragging a selection marquee over the object(s) to be selected. Once an object is selected, objects can be easily transformed via a conventional free transform overlay.

![select](https://user-images.githubusercontent.com/45302428/116643469-22fd6e00-a93f-11eb-9e9e-eb3aa31434a7.gif)

### Brush
*hotkey: 2*

Brush is a free-drawing vector brush where the user can simply draw on the canvas with their mouse. The brush size can also be changed in the right side properties panel, or by using the bracket keys '[' and ']' to decrease and increase the brush size, respectively.

![brush](https://user-images.githubusercontent.com/45302428/116644030-4ffe5080-a940-11eb-8501-21a562dadff6.gif)

### Rectangle, Ellipse, and Triangle
*hotkeys: 3, 4, 5*

The first of our shape tools, Rectangle will add a rectangle to the canvas. At present, each shape will spawn at (50, 50) on the canvas. From there, all shapes can be transformed to the intended size and location.

![shapes](https://user-images.githubusercontent.com/45302428/116644319-0f530700-a941-11eb-82d7-15fb1083cdc1.gif)

## Extra Tools

### Color Picker
The color picker is used to change the color of your next object. At the moment, the color picker does not change the color of objects already placed on the canvas :(

### Undo and Redo
*hotkeys: z, x*

Stitchboard supports undo and redo functionality though a [library](https://github.com/lyzerk/fabric-history) created by Alim Özdemir.

## Properties Panel
On the right side of the screen, Stitchboard has a properties panel which provides some more granular control over the canvas.

### Pivot Box
The Pivot box is a useful tool for changing the transformation point around which the user can rotate their shape. By default, the rotational point is at the center of the object/selection.

![pivot](https://user-images.githubusercontent.com/45302428/116645006-dd42a480-a942-11eb-910d-487fd452a5cf.gif)

### Transform Panel
The Transform panel is where the user can directly enter values for the X,Y coordinates, the width and height of the object, its rotation angle, and the angle of horizontal shearing. These values are also automatically updated when the user is using the free transform widget, so this panel can be also be useful for the information it provides to the user.

![transform](https://user-images.githubusercontent.com/45302428/116645276-74a7f780-a943-11eb-9b5a-bfd25ee3ecdf.gif)
