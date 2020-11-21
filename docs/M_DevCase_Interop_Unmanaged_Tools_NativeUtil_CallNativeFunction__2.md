# NativeUtil.CallNativeFunction(*TResult*, *TDelegate*) Method 
 

Executes a function exported in a native dll and returns the result value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static TResult CallNativeFunction<TResult, TDelegate>(
	string filepath,
	string functionName,
	TDelegate functionSignature,
	params Object[] parameters
)

```

**VB**<br />
``` VB
Public Shared Function CallNativeFunction(Of TResult, TDelegate) ( 
	filepath As String,
	functionName As String,
	functionSignature As TDelegate,
	ParamArray parameters As Object()
) As TResult
```

**VB Usage**<br />
``` VB Usage
Dim filepath As String
Dim functionName As String
Dim functionSignature As TDelegate
Dim parameters As Object()
Dim returnValue As TResult

returnValue = NativeUtil.CallNativeFunction(filepath, 
	functionName, functionSignature, 
	parameters)
```

**C++**<br />
``` C++
public:
generic<typename TResult, typename TDelegate>
static TResult CallNativeFunction(
	String^ filepath, 
	String^ functionName, 
	TDelegate functionSignature, 
	... array<Object^>^ parameters
)
```

**F#**<br />
``` F#
static member CallNativeFunction : 
        filepath : string * 
        functionName : string * 
        functionSignature : 'TDelegate * 
        parameters : Object[] -> 'TResult 

```


#### Parameters
&nbsp;<dl><dt>filepath</dt><dd>Type: System.String<br />The file path of the native dll.</dd><dt>functionName</dt><dd>Type: System.String<br />The name of the function to be executed.</dd><dt>functionSignature</dt><dd>Type: *TDelegate*<br />A Delegate that will represent the signature of the native function.</dd><dt>parameters</dt><dd>Type: System.Object[]<br />An argument list for the invoked function. This is an array of objects with the same number, order, and type as the parameters of the function to be invoked. 

 If there are no parameters, parameters should be null.If the method Any object in this array that is not explicitly initialized with a value will contain the default value for that object type. 

 For reference-type elements, this value is a null reference (`Nothing` in Visual Basic). For value-type elements, this value is 0, 0.0, or false, depending on the specific element type.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>TResult</dt><dd>The Type of the value returned by the native function.</dd><dt>TDelegate</dt><dd>The Type of the source Delegate that will represent the signature of the native function.</dd></dl>

#### Return Value
Type: *TResult*<br />The result of calling the native function.

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

        Dim result As Integer = 
            CallNativeFunction(Of Integer, PointerToRegistrationMethodInvoker)(filepath, "DllRegisterServer", Nothing)

        Dim result As Integer = methodInvoker.Invoke()
        If (result <> 0) Then
            ' To-Do?: Handle specific errors...
        End If

    End Sub

End Module
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />