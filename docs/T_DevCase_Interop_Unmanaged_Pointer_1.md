# Pointer(*T*) Structure
 

Provides a wrapper class for compatibility between translation of C# pointers to VB.NET. 

 A pointer is a variable that holds the memory address of another type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public struct Pointer<T>
where T : IConvertible

```

**VB**<br />
``` VB
Public Structure Pointer(Of T As IConvertible)
```

**VB Usage**<br />
``` VB Usage
Dim instance As Pointer(Of T)
```

**C++**<br />
``` C++
generic<typename T>
where T : IConvertible
public value class Pointer
```

**F#**<br />
``` F#
[<SealedAttribute>]
type Pointer<'T when 'T : IConvertible> =  struct end
```


#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "T:DevCase.Interop.Unmanaged.Pointer`1"\]</dd></dl>&nbsp;
The Pointer(T) type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Pointer_1__ctor">Pointer(T)</a></td><td>
Initializes a new instance of the Pointer struct.</td></tr></table>&nbsp;
<a href="#pointer(*t*)-structure">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Interop_Unmanaged_Pointer_1_Value">Value</a></td><td>
Gets or sets the value in the pointer.</td></tr></table>&nbsp;
<a href="#pointer(*t*)-structure">Back to Top</a>

## Operators
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Pointer_1_op_Addition">Addition</a></td><td>
Implements the sum operator.</td></tr><tr><td>![Public operator](media/puboperator.gif "Public operator")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Interop_Unmanaged_Pointer_1_op_Subtraction">Subtraction</a></td><td>
Implements the minus operator.</td></tr></table>&nbsp;
<a href="#pointer(*t*)-structure">Back to Top</a>

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
<a href="#pointer(*t*)-structure">Back to Top</a>

## Remarks
Credits to: <a href="http://social.msdn.microsoft.com/Forums/en-US/b07e8ad5-3de2-419c-9e18-f24f4165989f/c-pointers-to-vb-net?forum=vbgeneral" target="_blank">http://social.msdn.microsoft.com/Forums/en-US/b07e8ad5-3de2-419c-9e18-f24f4165989f/c-pointers-to-vb-net?forum=vbgeneral</a>

## Examples
This is a code example that demonstrates how to adapt a C# code that uses pointers to VB.NET language. 
**VB**<br />
``` VB
' C# original source code that use pointers to invert the colors of a image:
'
' private static Image InvertImageColorsUnsafe(Image img) {
' 
'     Bitmap bmp = new Bitmap(img);
' 
'     //Format is BGRA, NOT ARGB.
'     BitmapData bmData = bmp.LockBits(new Rectangle(0, 0, bmp.Width, bmp.Height),
'                                      ImageLockMode.ReadWrite,
'                                      PixelFormat.Format32bppArgb);
' 
'     int stride = bmData.Stride;
'     IntPtr Scan0 = bmData.Scan0;
' 
'     unsafe {
'         byte* p = (byte*)(void*)Scan0;
' 
'         int nOffset = stride - bmp.Width * 4;
'         int nWidth = bmp.Width;
' 
'         for (int y = 0; y < bmp.Height; y++) {
'             for (int x = 0; x < nWidth; x++) {
'                 p[0] = (byte)(255 - p[0]); // Red
'                 p[1] = (byte)(255 - p[1]); // Green
'                 p[2] = (byte)(255 - p[2]); // Blue
'                 //p[3] is alpha, don't want to invert alpha
'                 p += 4;
'             }
'             p += nOffset;
'         }
'     }
' 
'     bmp.UnlockBits(bmData);
'     return (Image)bmp;
' }

' VB.NET equivalency using the Pointer class:
Private Shared Function InvertImageColorsUnsafe(originalImg As Image) As Image

    Dim bmp As New Bitmap(originalImg)

    ' Format is BGRA, NOT ARGB.
    Dim bmData As BitmapData =
        bmp.LockBits(New Rectangle(0, 0, bmp.Width, bmp.Height),
                     ImageLockMode.ReadWrite, PixelFormat.Format32bppArgb)

    Dim stride As Integer = bmData.Stride
    Dim p As New Pointer(Of Byte)(bmData.Scan0)

    Dim nOffset As Integer = stride - bmp.Width * 4
    Dim nWidth As Integer = bmp.Width

    For y As Integer = 0 To (bmp.Height - 1)
        For x As Integer = 0 To (nWidth - 1)
            p(0) = CByte(255 - p(0)) ' Red
            p(1) = CByte(255 - p(1)) ' Green
            p(2) = CByte(255 - p(2)) ' Blue
            'p(3) is alpha, don't want to invert alpha
            p += 4
        Next
        p += nOffset
    Next
    bmp.UnlockBits(bmData)

    Return DirectCast(bmp, Image)
End Function
```


## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged">DevCase.Interop.Unmanaged Namespace</a><br />