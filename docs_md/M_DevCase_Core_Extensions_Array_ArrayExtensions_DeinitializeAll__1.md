# ArrayExtensions.DeinitializeAll(*T*) Method (*T*[])
 

Deinitializes all the elements of the specified Array. 

 This method just turns to a null reference (`Nothing` in Visual Basic) all the elements, 

 if you also need to dispose them, call <a href="M_DevCase_Core_Extensions_IDisposable_IDisposableExtensions_DisposeAll__1">DisposeAll(T)(T[])</a> method instead.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void DeinitializeAll<T>(
	this T[] sender
)
where T : new()

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub DeinitializeAll(Of T As New) ( 
	sender As T()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As T()

sender.DeinitializeAll()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : gcnew()
static void DeinitializeAll(
	array<T>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DeinitializeAll : 
        sender : 'T[] -> unit  when 'T : new()

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: *T*[]<br />The source Array.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The type.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Class Form1 : Inherits Form

    Private Sub Test(ByVal sender As Object, ByVal e As EventArgs) Handles MyBase.Shown

        Dim myCol As MyDisposableType() = {New MyDisposableType}
        myCol.DeinitializeAll()

        Try
            MsgBox(myCol(0).MyField)

        Catch ex As NullReferenceException
            MsgBox(ex.Message)

        End Try

    End Sub

End Class

Public Class MyType

    Public MyField As String

    Public Sub New()
        Me.MyField = "Default field initialization value"
    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Array_ArrayExtensions">ArrayExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Array_ArrayExtensions_DeinitializeAll">DeinitializeAll Overload</a><br /><a href="N_DevCase_Core_Extensions_Array">DevCase.Core.Extensions.Array Namespace</a><br />