# DevFileSystemWatcher Class
 

A extended FileSystemWatcher component.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;System.MarshalByRefObject<br />&nbsp;&nbsp;&nbsp;&nbsp;System.ComponentModel.Component<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;System.IO.FileSystemWatcher<br />&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.IO.DevFileSystemWatcher<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ToolboxBitmapAttribute(typeof(Component), "Component.bmp")]
[DefaultEventAttribute("Changed")]
[IODescriptionAttribute("DevFileSystemWatcherDesc")]
public class DevFileSystemWatcher : FileSystemWatcher
```

**VB**<br />
``` VB
<ToolboxBitmapAttribute(GetType(Component), "Component.bmp")>
<DefaultEventAttribute("Changed")>
<IODescriptionAttribute("DevFileSystemWatcherDesc")>
Public Class DevFileSystemWatcher
	Inherits FileSystemWatcher
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevFileSystemWatcher
```

**C++**<br />
``` C++
[ToolboxBitmapAttribute(typeof(Component), L"Component.bmp")]
[DefaultEventAttribute(L"Changed")]
[IODescriptionAttribute(L"DevFileSystemWatcherDesc")]
public ref class DevFileSystemWatcher : public FileSystemWatcher
```

**F#**<br />
``` F#
[<ToolboxBitmapAttribute(typeof(Component), "Component.bmp")>]
[<DefaultEventAttribute("Changed")>]
[<IODescriptionAttribute("DevFileSystemWatcherDesc")>]
type DevFileSystemWatcher =  
    class
        inherit FileSystemWatcher
    end
```

The DevFileSystemWatcher type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_DevFileSystemWatcher__ctor">DevFileSystemWatcher()</a></td><td>
Initializes a new instance of the DevFileSystemWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_DevFileSystemWatcher__ctor_1">DevFileSystemWatcher(String)</a></td><td>
Initializes a new instance of the DevFileSystemWatcher class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_IO_DevFileSystemWatcher__ctor_2">DevFileSystemWatcher(String, String)</a></td><td>
Initializes a new instance of the DevFileSystemWatcher class.</td></tr></table>&nbsp;
<a href="#devfilesystemwatcher-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_IO_DevFileSystemWatcher_Path">Path</a></td><td>
Gets or sets the path of the directory to watch.</td></tr></table>&nbsp;
<a href="#devfilesystemwatcher-class">Back to Top</a>

## Events
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_DevFileSystemWatcher_Error">Error</a></td><td>
Occurs when this instance is unable to continue monitoring changes or when the internal buffer overflows.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_DevFileSystemWatcher_PathAvailable">PathAvailable</a></td><td>
Occurs when the path specified in <a href="P_DevCase_Core_IO_DevFileSystemWatcher_Path">Path</a> property becomes available after <a href="E_DevCase_Core_IO_DevFileSystemWatcher_PathUnavailable">PathUnavailable</a> event is raised.</td></tr><tr><td>![Public event](media/pubevent.gif "Public event")</td><td><a href="E_DevCase_Core_IO_DevFileSystemWatcher_PathUnavailable">PathUnavailable</a></td><td>
Occurs when the path specified in <a href="P_DevCase_Core_IO_DevFileSystemWatcher_Path">Path</a> property becomes unavailable.</td></tr></table>&nbsp;
<a href="#devfilesystemwatcher-class">Back to Top</a>

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
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Component_ComponentExtensions_GetEventHandlers">GetEventHandlers</a></td><td>
Gets all the delegates associated to the specified event raised by the source Component.
 (Defined by <a href="T_DevCase_Core_Extensions_Component_ComponentExtensions">ComponentExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#devfilesystemwatcher-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />System.IO.FileSystemWatcher<br />