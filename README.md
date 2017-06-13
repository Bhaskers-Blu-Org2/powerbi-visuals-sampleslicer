# PowerBI Slicer custom visual sample
[![Build Status](https://travis-ci.org/Microsoft/powerbi-visuals-sampleslicer.svg?branch=master)](https://travis-ci.org/Microsoft/powerbi-visuals-sampleslicer)

Demostrates the use of the Advanced Filtering API introduced in the revision 1.7 of [PowerBI Visuals Tools](https://github.com/Microsoft/PowerBI-visuals-tools). 

This PowerBI Custom Visual relies on the Advanced Filter API for bulk data-point selection and [InteractivityUtils](https://github.com/Microsoft/powerbi-visuals-utils-interactivityutils) for discrete data-point selection.

### Understanding the visual
![]("doc/images/SampleSlicer.PNG")

### Setting Up Environment

Before starting creating your first custom visual follow by [this](https://github.com/Microsoft/PowerBI-visuals/blob/master/Readme.md#setting-up-environment)
setting up environment instruction.


### Install dev dependencies:

Once you have cloned this example, run these commands to install dependencies and to connect the visual into powerbi.

```
npm install # This command will install all necessary modules
```

### Start dev app
```
pbiviz start
```

### Building Bar Chart
1. [Building a Visual with Static Data](Tutorial/StaticVisual.md)
2. [Adding Databinding to the Bar Chart](Tutorial/DataBinding.md)
3. [Adding Color to the Bar Chart](Tutorial/ColorPalette.md)
4. [Adding Selection and Interaction with Other Visuals](Tutorial/Selection.md)
5. [Adding Static Objects to Property Pane](Tutorial/StaticObjects.md)
6. [Adding Databound Objects to Property Pane](Tutorial/DataBoundObjects.md)
7. [Adding Powerbi Extensibility Utils](Tutorial/ExtensibilityUtils.md)
8. [Finally Package for Distribution ... Done](https://github.com/Microsoft/PowerBI-visuals/blob/master/tools/usage.md#packaging-your-visual-for-distribution)
