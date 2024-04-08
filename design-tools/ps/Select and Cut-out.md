---
Title: Select and Cut-out
Type: D
tags:
  - PS
DateStarted: 2023-10-20
DateModified: 2023-11-13
status: 
mindmap-plugin: basic
---

# Select and Cut-out

## ⭐Selection

### Basics
- *Add* and *Subtract* to a selection
- Inverse selection (*Select > Inverse*)
    - `Ctrl + i`
- Deselect *Select > Deselect*
    - `Ctrl D`
- ✅Select the shape/ object on a layer
    - `Ctrl Click` the layer
- Select multiple layers
    - `Ctrl` select the layers to resize
- Select layer on click
    - *Move* Tool
        - Check *Auto-Select* Layer

### Quick select
- *Quick selection, object selection, magic wand* tool
- *Lasso* tool
- ✅Fine tune quick selection
    - Right click on the selection > *feather: 0.5 pixels*
    - Quick Selection Tool > *Color aware* / *Object aware*
        - ![[z-Assets/Paste image 1697526614539image.png]]

### Vector Select (*Pen Tool*)
- Select the mask to adjust property options > *density* / *feather*
- *Path* panel > *Alt click* Bottom icon to *Make work path* > Set tolerance to 8
- *Direct selection tool* select path points > Choose *curvature pen tool* and click *Backspace* to delete the points but remain the path

### Fine tune a selection
- *Select > Select and Mask*
    - *View > Overlay*
    - ![[z-Assets/Paste image 1697243016458image.png]]
- *Output > Selection*

## Fine tune in a colorful background

### Duplicate the subject layer > *layer style > Blending Options*
- ![[z-Assets/Paste image 1697526929081image.png]]

### Prevent blending on the subject body
- Hold *Alt* and *Drag and drop* the subject mask to the copied background

## Select hair #TODO

### Work on hair (⚠️Outdated and Slow)
- *Shift click* on the mask to disable the mask
- *Lasso Tool* to select the hair area
- Click on the layer thumbnail and *Ctrl J* to duplicate the selected hair layer
- Select *Channel* Panel and Choose the channel that reveals the hair with the highest contrast (blue channel) > duplicate the channel
- *Ctrl i* to inverse the channel
    - ![[z-Assets/Paste image 1697525062672image.png|200]]
- *Image > Adjustments > Levels* to increase the black white contrast
    - ![[z-Assets/Paste image 1697525148970image.png|200]]
- *Burn Tool* > *Range: Shadows* to make shadows darker or *Dodge Tool > Range: Highlight* to make highlight brighter
    - ![[z-Assets/Paste image 1697525352315image.png|250]]
- *Ctrl click* the blue copy to select > Select all other RGB channels
- Go to the layer panel to select the hair layer and click *mask icon*
- Fine tune the hair
    - Select the hair layer > Apply *layer style > Inner Glow* > *Blend mode > normal / multiply* Pick the hair color and adjust the glow size
        - ![[z-Assets/Paste image 1697525827149image.png|250]]