# DwmPreviewManager.PeekImage Property 
 

Gets or sets the image that will be used to display a peek preview of the current Window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual Bitmap PeekImage { get; set; }
```

**VB**<br />
``` VB
Public Overridable Property PeekImage As Bitmap
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As DwmPreviewManager
Dim value As Bitmap

value = instance.PeekImage

instance.PeekImage = value
```

**C++**<br />
``` C++
public:
virtual property Bitmap^ PeekImage {
	Bitmap^ get ();
	void set (Bitmap^ value);
}
```

**F#**<br />
``` F#
abstract PeekImage : Bitmap with get, set
override PeekImage : Bitmap with get, set
```


#### Property Value
Type: Bitmap<br />The image that will be used to display a peek preview of the current Window.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_DwmPreviewManager">DwmPreviewManager Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />