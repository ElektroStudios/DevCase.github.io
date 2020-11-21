# NativeUtil.GetNativeFunction(*TDelegate*) Method 
 

Gets a function exported in a native dll.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TDelegate GetNativeFunction<TDelegate>(
	string filepath,
	string functionName
)

```

**VB**<br />
``` VB
Public Shared Function GetNativeFunction(Of TDelegate) ( 
	filepath As String,
	functionName As String
) As TDelegate
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim functionName As String
Dim returnValue As TDelegate

returnValue = NativeUtil.GetNativeFunction(filepath, 
	functionName)
```

**C++**<br />
``` C++
public:
generic<typename TDelegate>
static TDelegate GetNativeFunction(
	String^ filepath, 
	String^ functionName
)
```

**F#**<br />
``` F#
static member GetNativeFunction : 
        filepath : string * 
        functionName : string -> 'TDelegate 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path of the native dll.</dd><dt>functionName</dt><dd>Type: System.String<br />The name of the function to be retrieved.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TDelegate</dt><dd>The Type of the source Delegate that will represent the signature of the native function.</dd></dl>

#### Return Value
Type: *TDelegate*<br />The resulting Delegate which represents a pointer to the method invoker.

## Examples
This is a code example. 
**VB**<br />
``` VB
Public Module Module1

    ''' ----------------------------------------------------------------------------------------------------
    ''' <summary>
    ''' A delegate to call DllRegisterServer or DllUnregisterServer functions in a native dll.
    ''' </summary>
    ''' ----------------------------------------------------------------------------------------------------
    ''' <returns>
    ''' The result of calling DllRegisterServer or DllUnregisterServer functions in a native dll.
    ''' </returns>
    ''' ----------------------------------------------------------------------------------------------------
    <UnmanagedFunctionPointer(CallingConvention.StdCall)>
    Friend Delegate Function PointerToRegistrationMethodInvoker() As Integer

    Public Sub Main()

        Dim methodInvoker As PointerToRegistrationMethodInvoker =
            GetNativeFunction(Of PointerToRegistrationMethodInvoker)("C:\native.dll", "DllRegisterServer")

        Dim result As Integer = methodInvoker.Invoke()
        If (result <> 0) Then
            ' To-Do: Handle specific errors...
        End If

    End Sub

End Module
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />