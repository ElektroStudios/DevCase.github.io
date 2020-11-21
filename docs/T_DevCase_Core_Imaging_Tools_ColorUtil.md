# ColorUtil Class
 

Contains color related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Imaging.Tools.ColorUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ColorUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class ColorUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ColorUtil
```

**C++**<br />
``` C++
public ref class ColorUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ColorUtil =  
    class
        inherit AestheticObject
    end
```

The ColorUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_ConsoleColorToWinFormsColor">ConsoleColorToWinFormsColor</a></td><td>
Converts a ConsoleColor to its equivalent Color.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_ConsoleColorToWpfColor">ConsoleColorToWpfColor</a></td><td>
Converts a ConsoleColor to its equivalent Color.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelBrush">GetPixelBrush(Point)</a></td><td>
Gets the color of a pixel at the specified coordinates and returns a Brush.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelBrush_1">GetPixelBrush(Int32, Int32)</a></td><td>
Gets the color of a pixel at the specified coordinates and returns a Brush.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelColor">GetPixelColor(Point)</a></td><td>
Gets the color of a pixel at the specified coordinates.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelColor_1">GetPixelColor(Int32, Int32)</a></td><td>
Gets the color of a pixel at the specified coordinates.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelPen">GetPixelPen(Point)</a></td><td>
Gets the color of a pixel at the specified coordinates and returns a Pen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetPixelPen_1">GetPixelPen(Int32, Int32)</a></td><td>
Gets the color of a pixel at the specified coordinates and returns a Pen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomBrush">GetRandomBrush(Boolean)</a></td><td>
Generates a random SolidBrush.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomBrush_1">GetRandomBrush(Byte, Byte, Byte, Byte, Byte, Byte, Byte, Byte)</a></td><td>
Generates a random SolidBrush between the specified range of values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomColor">GetRandomColor(Boolean)</a></td><td>
Generates a random A-RGB color.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomColor_1">GetRandomColor(Byte, Byte, Byte, Byte, Byte, Byte, Byte, Byte)</a></td><td>
Generates a random A-RGB color between the specified range of values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomConsoleColor">GetRandomConsoleColor</a></td><td>
Generates a random ConsoleColor.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomPen">GetRandomPen(Boolean)</a></td><td>
Generates a random Pen.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomPen_1">GetRandomPen(Byte, Byte, Byte, Byte, Byte, Byte, Byte, Byte)</a></td><td>
Generates a random Pen between the specified range of values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_GetRandomQbColor">GetRandomQbColor</a></td><td>
Generates a random QB color.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_IsColorSimilar">IsColorSimilar(Color, Color, Byte)</a></td><td>
Determines whether two colors are similar. 

 It compares the RGB channel difference to match inside the range of the specified tolerance threshold value.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_IsColorSimilar_1">IsColorSimilar(Color, Color, Byte, Byte, Byte)</a></td><td>
Determines whether two colors are similar. 

 It compares the RGB channel differences to match inside the range of the specified tolerance threshold values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_IsColorSimilar_2">IsColorSimilar(Color, Color, Byte, Byte, Byte, Byte)</a></td><td>
Determines whether two colors are similar. 

 It compares the ARGB channel differences to match inside the range of the specified tolerance threshold values.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_WinFormsBrushToWpfBrush">WinFormsBrushToWpfBrush</a></td><td>
Converts a WinForms brush (Brush) to WPF brush (Brush).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_WinFormsColorToWpfBrush">WinFormsColorToWpfBrush</a></td><td>
Converts a WinForms color (Color) to WPF brush (Brush).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_WinFormsColorToWpfColor">WinFormsColorToWpfColor</a></td><td>
Converts a WinForms color (Color) to WPF color (Color).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_WpfBrushToWinFormsBrush">WpfBrushToWinFormsBrush</a></td><td>
Converts a WPF brush (Brush) to WinForms brush (Brush).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_WpfColorToWinFormsBrush">WpfColorToWinFormsBrush</a></td><td>
Converts a WPF brush (Color) to WinForms brush (Brush).</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Imaging_Tools_ColorUtil_WpfColorToWinFormsColor">WpfColorToWinFormsColor</a></td><td>
Converts a WPF color (Color) to WinForms color (Color).</td></tr></table>&nbsp;
<a href="#colorutil-class">Back to Top</a>

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
<a href="#colorutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Imaging_Tools">DevCase.Core.Imaging.Tools Namespace</a><br />