# GIF Class
 

Represents a GIF image.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Imaging.GIF<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class GIF : AestheticObject
```

**VB**<br />
``` VB
Public Class GIF
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As GIF
```

**C++**<br />
``` C++
public ref class GIF : public AestheticObject
```

**F#**<br />
``` F#
type GIF =  
    class
        inherit AestheticObject
    end
```

The GIF type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_GIF__ctor">GIF(Image)</a></td><td>
Initializes a new instance of the GIF class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_GIF__ctor_1">GIF(FileInfo)</a></td><td>
Initializes a new instance of the GIF class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_GIF__ctor_2">GIF(String)</a></td><td>
Initializes a new instance of the GIF class.</td></tr></table>&nbsp;
<a href="#gif-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GIF_ActiveFrame">ActiveFrame</a></td><td>
Gets the active frame.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GIF_ActiveFrameIndex">ActiveFrameIndex</a></td><td>
Gets the index in the frame count of the current active frame.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GIF_EndOfFrames">EndOfFrames</a></td><td>
Gets a value indicating whether the frame count is at EOF, this means there is no more frames to advance in the GIF image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GIF_FrameCount">FrameCount</a></td><td>
Gets the frame count of the GIF image.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GIF_Frames">Frames</a></td><td>
Gets the frame at the specified index.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Imaging_GIF_Image">Image</a></td><td>
Gets the GIF image.</td></tr></table>&nbsp;
<a href="#gif-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_GIF_GetFrames">GetFrames</a></td><td>
Gets a List(T) containing all the frames in the image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Imaging_GIF_NextFrame">NextFrame</a></td><td>
Advances one position in the frame count and returns the next frame.</td></tr></table>&nbsp;
<a href="#gif-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#gif-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim pcb As PictureBox = Me.PictureBox1
Dim gif As New GIF("C:\File.gif")

Do Until gif.EndOfFrames ' Iterate frames until the end of frame count.

    ' Free previous Bitmap object.
    If (pcb.Image IsNot Nothing) Then
        pcb.Image.Dispose()
        pcb.Image = Nothing
    End If

    pcb.Image = gif.NextFrame()
    Thread.Sleep(60) ' Simulate the FPS animation.
    Application.DoEvents()

    If (gif.EndOfFrames) Then
        ' Set active frame to 0 for infinite loop:
        gif.ActiveFrameIndex = 0
    End If

Loop
```


## See Also


#### Reference
<a href="N_DevCase_Core_Imaging">DevCase.Core.Imaging Namespace</a><br />