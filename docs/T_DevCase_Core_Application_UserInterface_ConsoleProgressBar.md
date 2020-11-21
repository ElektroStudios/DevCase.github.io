# ConsoleProgressBar Class
 

A personalizable colorful ASCII progress bar for console applications.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.UserInterface.ConsoleProgressBar<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class ConsoleProgressBar : AestheticObject, 
	IDisposable, IProgress<double>
```

**VB**<br />
``` VB
Public NotInheritable Class ConsoleProgressBar
	Inherits AestheticObject
	Implements IDisposable, IProgress(Of Double)
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleProgressBar
```

**C++**<br />
``` C++
public ref class ConsoleProgressBar sealed : public AestheticObject, 
	IDisposable, IProgress<double>
```

**F#**<br />
``` F#
[<SealedAttribute>]
type ConsoleProgressBar =  
    class
        inherit AestheticObject
        interface IDisposable
        interface IProgress<float>
    end
```

The ConsoleProgressBar type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleProgressBar__ctor">ConsoleProgressBar</a></td><td>
Initializes a new instance of the ConsoleProgressBar class.</td></tr></table>&nbsp;
<a href="#consoleprogressbar-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_Animation">Animation</a></td><td>
Gets or sets the characters used to draw the animation secuence at the very end of the progress bar. 

 Default value is: {"|"c, "|"c, "/"c, "/"c, "-"c, "-"c, "\"c, "\"c} ( that is: "||//--\\" )</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_AnimationBackColor">AnimationBackColor</a></td><td>
Gets or sets the ConsoleColor used to paint the background of the animation secuence.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_AnimationForeColor">AnimationForeColor</a></td><td>
Gets or sets the ConsoleColor used to paint the foreground of the borders of the animation secuence.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_AnimationSpeed">AnimationSpeed</a></td><td>
Gets or sets the speed (framerate) of the animation secuence defined in <a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_Animation">Animation</a>. 

 Default value is: 125 milliseconds.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_AnimationVisible">AnimationVisible</a></td><td>
Gets or sets a value indicating whether the animation secuence is visible in the progress bar.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BlockActiveBackColor">BlockActiveBackColor</a></td><td>
Gets or sets the ConsoleColor used to paint the background of an active progress bar block.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BlockActiveChar">BlockActiveChar</a></td><td>
Gets the character used to draw an active progress bar block. 

 Default value is: "#"</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BlockActiveForeColor">BlockActiveForeColor</a></td><td>
Gets or sets the ConsoleColor used to paint the foreground of an active progress bar block.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BlockCount">BlockCount</a></td><td>
Gets the amount of blocks to display in the progress bar. 

 Default value is: 20</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BlockInactiveBackColor">BlockInactiveBackColor</a></td><td>
Gets or sets the ConsoleColor used to paint the background of a inactive progress bar block.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BlockInactiveChar">BlockInactiveChar</a></td><td>
Gets the character used to draw an inactive progress bar block. 

 Default value is: "·"</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BlockInactiveForeColor">BlockInactiveForeColor</a></td><td>
Gets or sets the ConsoleColor used to paint the foreground of a inactive progress bar block.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BorderBackColor">BorderBackColor</a></td><td>
Gets or sets the ConsoleColor used to paint the background of the borders of the progress bar.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_BorderForeColor">BorderForeColor</a></td><td>
Gets or sets the ConsoleColor used to paint the foreground of the borders of the progress bar.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_CurrentProgress">CurrentProgress</a></td><td>
Gets the current progress value. From 0.0 to 1.0</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_ProgressTextBackColor">ProgressTextBackColor</a></td><td>
Gets or sets the ConsoleColor used to paint the background of the progress text.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_ProgressTextForeColor">ProgressTextForeColor</a></td><td>
Gets or sets the ConsoleColor used to paint the foreground of the borders of the progress text.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_UserInterface_ConsoleProgressBar_ProgressTextFormat">ProgressTextFormat</a></td><td>
Gets or sets the format of the progress text, where: 

 {0} = Percentage Value 

 {1} = Current Value 

 {2} = Maximum Value 

 Default value is: "{0}%"</td></tr></table>&nbsp;
<a href="#consoleprogressbar-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleProgressBar_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_UserInterface_ConsoleProgressBar_Report">Report</a></td><td>
Reports a progress update.</td></tr></table>&nbsp;
<a href="#consoleprogressbar-class">Back to Top</a>

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
<a href="#consoleprogressbar-class">Back to Top</a>

## Remarks
Based on: <a href="https://gist.github.com/DanielSWolf/0ab6a96899cc5377bf54" target="_blank">https://gist.github.com/DanielSWolf/0ab6a96899cc5377bf54</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Module Module1

    Public Sub Main()
        Console.CursorVisible = False
        Console.Write("Performing some task... ")

        Using progress As New ConsoleProgressBar(blockCount:=20) With {
            .Animation = "||//--\\".ToCharArray(),
            .AnimationSpeed = TimeSpan.FromMilliseconds(125),
            .AnimationBackColor = Console.BackgroundColor,
            .AnimationForeColor = ConsoleColor.Yellow,
            .BlockActiveChar = "█"c,
            .BlockInactiveChar = "·"c,
            .BlockActiveBackColor = Console.BackgroundColor,
            .BlockActiveForeColor = ConsoleColor.Green,
            .BlockInactiveBackColor = Console.BackgroundColor,
            .BlockInactiveForeColor = ConsoleColor.DarkGray,
            .BorderBackColor = Console.BackgroundColor,
            .BorderForeColor = ConsoleColor.White,
            .ProgressTextFormat = "{1} of {2} ({0}%)",
            .ProgressTextBackColor = Console.BackgroundColor,
            .ProgressTextForeColor = ConsoleColor.Gray
        }

            For i As Integer = 0 To 100
                progress.Report(i / 100)
                Thread.Sleep(100)
            Next i
        End Using

        Console.WriteLine()
        Console.WriteLine("Done.")
        Console.ReadKey()
    End Sub

End Module
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />