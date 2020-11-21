# ResXManager Class
 

Manages a .NET managed resource (ResX) file.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Application.Data.ResXManager<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public class ResXManager : AestheticObject
```

**VB**<br />
``` VB
Public Class ResXManager
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResXManager
```

**C++**<br />
``` C++
public ref class ResXManager : public AestheticObject
```

**F#**<br />
``` F#
type ResXManager =  
    class
        inherit AestheticObject
    end
```

The ResXManager type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager__ctor">ResXManager</a></td><td>
Initializes a new instance of the ResXManager class.</td></tr></table>&nbsp;
<a href="#resxmanager-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_ResXManager_FilePath">FilePath</a></td><td>
Gets the .NET managed resource file path.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Application_Data_ResXManager_Resources">Resources</a></td><td>
Gets the resources contained in the .NET managed resource file.</td></tr></table>&nbsp;
<a href="#resxmanager-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_AddResource">AddResource(String, Object, String)</a></td><td>
Adds a resource into the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_AddResource__1">AddResource(T)(Resource(T))</a></td><td>
Adds a resource into the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_AddResource__1_1">AddResource(T)(String, T, String)</a></td><td>
Adds a specified resource of the specified type into the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_Create">Create</a></td><td>
Creates the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_FindResource">FindResource(String, StringComparison)</a></td><td>
Finds a resource by the specified name inside the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_FindResource__1">FindResource(T)(String, StringComparison)</a></td><td>
Finds a resource by the specified name of specified type inside the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_FindResources__1">FindResources(T)</a></td><td>
Finds the resources of the specified type inside the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_RemoveResource">RemoveResource</a></td><td>
Removes a resource by the specified name from the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_ReplaceResource">ReplaceResource(String, Object, String)</a></td><td>
Replaces a resource by the specified name inside the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_ReplaceResource__1">ReplaceResource(T)(Resource(T))</a></td><td>
Replaces a resource by the specified name inside the .NET managed resource file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Application_Data_ResXManager_ReplaceResource__1_1">ReplaceResource(T)(String, T, String)</a></td><td>
Replaces a resource by the specified name of the specified type inside the .NET managed resource file.</td></tr></table>&nbsp;
<a href="#resxmanager-class">Back to Top</a>

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
<a href="#resxmanager-class">Back to Top</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
    Dim resX As New ResXManager(Path.Combine(Application.StartupPath, "MyResources.ResX"))
    With resX

        ' Create or overwrite the ResX file.
        .Create(overwrite:=True)

        ' Add a string resource.            
        Dim resStr As New Resource(Of String)("String Resource", "Hello World!", "String Comment")
        .AddResource(Of String)(resStr)

        ' Add a bitmap resource.
        Dim resBmp As New Resource(Of Bitmap)("Bitmap Resource", SystemIcons.Information.ToBitmap, "Bitmap Comment")
        .AddResource(Of Bitmap)(resBmp)

        ' Add a binary resource.
        Dim resBin As New Resource(Of Byte())("Binary Resource", File.ReadAllBytes("C:\File.mp3"), "Binary Comment")
        .AddResource(Of Byte())(resBin)

    End With

    ' *******************************************************************************************************

    ' Get the string resource.
    Dim stringResource As Resource(Of String) =
        resX.FindResource(Of String)("String Resource", StringComparison.OrdinalIgnoreCase)

    ' Get the bitmap resource.
    Dim bitmapResource As Resource(Of Bitmap) =
        resX.FindResource(Of Bitmap)("Bitmap Resource", StringComparison.OrdinalIgnoreCase)

    ' Get the binary resource.
    Dim binaryResource As Resource(Of Byte()) =
        resX.FindResource(Of Byte())("Binary Resource", StringComparison.OrdinalIgnoreCase)

    ' *******************************************************************************************************

    ' Get the string data.
    Dim stringData As String = stringResource.Data

    ' Get the bitmap data.
    Dim bitmapData As Bitmap = bitmapResource.Data

    ' Get the binary data.
    Dim binaryData As Byte() = binaryResource.Data

    ' *******************************************************************************************************

    ' Get all the resources at once.
    Dim resources As IEnumerable(Of Resource) = resX.Resources

    ' Get all the resources of specific Type at once.
    Dim stringResources As IEnumerable(Of Resource(Of String)) = resX.FindResources(Of String)()

    ' *******************************************************************************************************

    ' Get all the resource datas at once from Resource collection.
    Dim resourceDatas As IEnumerable(Of Object) =
        From res As Resource In resX.Resources
        Select res.Data

    ' Get all the resource datas of specific Type at once from Resource collection.
    Dim stringResourceDatas As IEnumerable(Of String) =
        From res As Resource In resX.Resources
        Where res.Type Is GetType(String)
        Select DirectCast(res.Data, String)

    ' *******************************************************************************************************

    ' Treat the string data as you like.
    MessageBox.Show(stringData, String.Empty, MessageBoxButtons.OK, MessageBoxIcon.Information)

    ' Treat the bitmap data as you like.
    Me.Icon = Icon.FromHandle(bitmapData.GetHicon)

    ' Treat the binary data as you like.
    File.WriteAllBytes("C:\new file.mp3", binaryData)

    ' *******************************************************************************************************

    ' Iterate all the resources.
    For Each res As Resource In resX.Resources

        Dim sb As New Global.System.Text.StringBuilder

        sb.AppendLine(String.Format("Name...: {0}", res.Name))
        sb.AppendLine(String.Format("Comment: {0}", res.Comment))
        sb.AppendLine(String.Format("Type...: {0}", res.Data.GetType().FullName))
        sb.AppendLine(String.Format("Data...: {0}", res.Data.ToString()))

        MsgBox(sb.ToString())

    Next res

    ' Iterate all the resources of specific Type.
    For Each res As Resource(Of String) In resX.FindResources(Of String)()

        Dim sb As New Global.System.Text.StringBuilder

        sb.AppendLine(String.Format("Name...: {0}", res.Name))
        sb.AppendLine(String.Format("Comment: {0}", res.Comment))
        sb.AppendLine(String.Format("Type...: {0}", res.Type.ToString()))
        sb.AppendLine(String.Format("Data...: {0}", res.Data.ToString()))

        MsgBox(sb.ToString())

    Next res

    ' *******************************************************************************************************

    ' Remove a resource.
    resX.RemoveResource("Binary Resource")

    '  GC.Collect()

End Sub
```


## See Also


#### Reference
<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />