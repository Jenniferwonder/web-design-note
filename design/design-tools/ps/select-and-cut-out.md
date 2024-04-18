---
title: Select and Cut-out
type: D
tags:
  - PS
DateStarted: 2023-10-20
DateModified: 2023-11-13
status:
---

# Select and Cut-out

## ⭐Selection

### Basics

- _Add_ and _Subtract_ to a selection
- Inverse selection (_Select > Inverse_)
  - `Ctrl + i`
- Deselect _Select > Deselect_
  - `Ctrl D`
- ✅Select the shape/ object on a layer
  - `Ctrl Click` the layer
- Select multiple layers
  - `Ctrl` select the layers to resize
- Select layer on click
  - _Move_ Tool
    - Check _Auto-Select_ Layer

### Quick select

- _Quick selection, object selection, magic wand_ tool
- _Lasso_ tool
- ✅Fine tune quick selection
  - Right click on the selection > _feather: 0.5 pixels_
  - Quick Selection Tool > _Color aware_ / _Object aware_
    - ![[https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/web-design/Paste image 1697526614539image.png]]

### Vector Select (_Pen Tool_)

- Select the mask to adjust property options > _density_ / _feather_
- _Path_ panel > _Alt click_ Bottom icon to _Make work path_ > Set tolerance to 8
- _Direct selection tool_ select path points > Choose _curvature pen tool_ and click _Backspace_ to delete the points but remain the path

### Fine tune a selection

- _Select > Select and Mask_
  - _View > Overlay_
  - ![[https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/web-design/Paste image 1697243016458image.png]]
- _Output > Selection_

## Fine tune in a colorful background

### Duplicate the subject layer > _layer style > Blending Options_

- ![[https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/web-design/Paste image 1697526929081image.png]]

### Prevent blending on the subject body

- Hold _Alt_ and _Drag and drop_ the subject mask to the copied background

## Select hair #TODO

### Work on hair (⚠️Outdated and Slow)

- _Shift click_ on the mask to disable the mask
- _Lasso Tool_ to select the hair area
- Click on the layer thumbnail and _Ctrl J_ to duplicate the selected hair layer
- Select _Channel_ Panel and Choose the channel that reveals the hair with the highest contrast (blue channel) > duplicate the channel
- _Ctrl i_ to inverse the channel
  - ![[https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/web-design/Paste image 1697525062672image.png|200]]
- _Image > Adjustments > Levels_ to increase the black white contrast
  - ![[https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/web-design/Paste image 1697525148970image.png|200]]
- _Burn Tool_ > _Range: Shadows_ to make shadows darker or _Dodge Tool > Range: Highlight_ to make highlight brighter
  - ![[https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/web-design/Paste image 1697525352315image.png|250]]
- _Ctrl click_ the blue copy to select > Select all other RGB channels
- Go to the layer panel to select the hair layer and click _mask icon_
- Fine tune the hair
  - Select the hair layer > Apply _layer style > Inner Glow_ > _Blend mode > normal / multiply_ Pick the hair color and adjust the glow size
    - ![[https://cdn.jsdelivr.net/gh/jenniferwonder/bimg/web-design/Paste image 1697525827149image.png|250]]
