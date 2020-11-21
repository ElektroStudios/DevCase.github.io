# IDisposableExtensions.DisposeAll(*T*) Method 
 

Disposes all the disposable elements of the specified Array.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_IDisposable">DevCase.Core.Extensions.IDisposable</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void DisposeAll<T>(
	this T[] sender
)
where T : IDisposable

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub DisposeAll(Of T As IDisposable) ( 
	sender As T()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As T()

sender.DisposeAll()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : IDisposable
static void DisposeAll(
	array<T>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member DisposeAll : 
        sender : 'T[] -> unit  when 'T : IDisposable

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
        myCol.DisposeAll()

        Try
            MsgBox(myCol(0).MyField)

        Catch ex As NullReferenceException
            MsgBox(ex.Message)

        End Try

    End Sub

End Class

Public Class MyDisposableType : Implements IDisposable

    Public MyField As String

    Public Sub New()
        Me.MyField = "Default field initialization value"
    End Sub

    Private disposedValue As Boolean

    Public Sub Dispose() Implements IDisposable.Dispose
        Dispose(True)
    End Sub

    Protected Sub Dispose(disposing As Boolean)
        If Not Me.disposedValue Then
            If disposing Then
                Me.MyField = ""
            End If
        End If
        Me.disposedValue = True
    End Sub

End Class
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_IDisposable_IDisposableExtensions">IDisposableExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_IDisposable">DevCase.Core.Extensions.IDisposable Namespace</a><br />