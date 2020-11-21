# LogfileWriter Class
 

A simple logging system assistant that helps to create a log for the current application.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Diagnostics.LogfileWriter<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class LogfileWriter : AestheticObject, 
	IDisposable
```

**VB**<br />
``` VB
Public NotInheritable Class LogfileWriter
	Inherits AestheticObject
	Implements IDisposable
```

**VB Usage**<br />
``` VB Usage
Dim instance As LogfileWriter
```

**C++**<br />
``` C++
public ref class LogfileWriter sealed : public AestheticObject, 
	IDisposable
```

**F#**<br />
``` F#
[<SealedAttribute>]
type LogfileWriter =  
    class
        inherit AestheticObject
        interface IDisposable
    end
```

The LogfileWriter type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_LogfileWriter__ctor">LogfileWriter</a></td><td>
Initializes a new instance of the LogfileWriter class.</td></tr></table>&nbsp;
<a href="#logfilewriter-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Diagnostics_LogfileWriter_Encoding">Encoding</a></td><td>
Gets the logfile encoding.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Diagnostics_LogfileWriter_EntryFormat">EntryFormat</a></td><td>
Gets or sets the format of a log entry. {0}=Date, {1}=Time, {2}=Event, {3}=Message.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Diagnostics_LogfileWriter_Filepath">Filepath</a></td><td>
Gets the log filepath.</td></tr></table>&nbsp;
<a href="#logfilewriter-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_LogfileWriter_Clear">Clear</a></td><td>
Clears the logfile content.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_LogfileWriter_Dispose">Dispose</a></td><td>
Releases all the resources used by this instance.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_LogfileWriter_WriteEntry">WriteEntry</a></td><td>
Writes a new entry on the logfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_LogfileWriter_WriteNewLine">WriteNewLine</a></td><td>
Writes an empty line on the logfile.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Diagnostics_LogfileWriter_WriteText">WriteText</a></td><td>
Writes any text on the logfile.</td></tr></table>&nbsp;
<a href="#logfilewriter-class">Back to Top</a>

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
<a href="#logfilewriter-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Private logfile As New LogfileWriter(String.Format("{0}.log", My.Application.Info.AssemblyName)) With
        {
            .EntryFormat = "[{1}] | {2,-11} | {3}"
        } ' {0}=Date, {1}=Time, {2}=Event, {3}=Message.

    Private Sub Form1_Load() Handles MyBase.Load

        With Me.logfile
            .Clear()
            .WriteText("#########################################")
            .WriteNewLine()
            .WriteText(String.Format("          Log Date {0}          ", Date.Now.Date.ToShortDateString))
            .WriteNewLine()
            .WriteText("#########################################")
            .WriteNewLine()
            .WriteEntry(TraceEventType.Information, "Application is being initialized.")
        End With

        Try
            Dim setting As Integer = Integer.Parse(" Hello World! :D ")

        Catch ex As Exception
            Me.logfile.WriteEntry(TraceEventType.Critical, "Cannot parse 'setting' object in 'Sub Form1_Load()' method.")
            Me.logfile.WriteEntry(TraceEventType.Information, "Exiting...")
            Application.Exit()

        End Try

    End Sub

End Class
```


## See Also


#### Reference
<a href="N_DevCase_Core_Diagnostics">DevCase.Core.Diagnostics Namespace</a><br />