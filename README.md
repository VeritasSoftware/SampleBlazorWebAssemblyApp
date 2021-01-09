# Blazor Web Assembly Demo Application

## Robot Pipetter

A robot for pipetting can be operated by the below commands:

* PLACE - Positions the pipetter at the start.
* DROP - Places a drop in the current well. The pipette marks the well with a drop.
* MOVE - Moves the pipetter one position North, South, East, West.

### Sample

```
PLACE 2,2
DROP
MOVE N
DROP
MOVE E
```

These commands will move the robot pipetter as shown below:

![Screenshot](https://github.com/VeritasSoftware/SampleBlazorWebAssemblyApp/blob/master/Screenshot.JPG)

[Try it out!](https://robotpipetting-sample-blazor-webassembly-app.azurewebsites.net/)