# ImgurStatus Enumeration
 

Specifies one of the possible Imgur's server status result when uploading an image.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum ImgurStatus
```

**VB**<br />
``` VB
Public Enumeration ImgurStatus
```

**VB Usage**<br />
``` VB Usage
Dim instance As ImgurStatus
```

**C++**<br />
``` C++
public enum class ImgurStatus
```

**F#**<br />
``` F#
type ImgurStatus
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.ThirdParty.Imgur.ImgurStatus.UnknownError">**UnknownError**</td><td>0</td><td>Indicates an unknown status.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Imgur.ImgurStatus.Success">**Success**</td><td>200</td><td>Indicates a success status.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Imgur.ImgurStatus.BadImageFormat">**BadImageFormat**</td><td>400</td><td>Indicates a bad image file-format.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Imgur.ImgurStatus.AuthorizationFailed">**AuthorizationFailed**</td><td>401</td><td>Indicates that the authorization to upload the image has failed. Note: It's unsure that this status code could raise in an anonym upload.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Imgur.ImgurStatus.AccessForbidden">**AccessForbidden**</td><td>403</td><td>Indicates that the access is forbidden.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Imgur.ImgurStatus.PageIsNotFound">**PageIsNotFound**</td><td>404</td><td>Indicates that the page is not found.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Imgur.ImgurStatus.UploadRateLimitError">**UploadRateLimitError**</td><td>429</td><td>Indicates that the user (Anonym IP) raised the image upload limit. Note: It's unsure that this status code could raise in an anonym upload.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Imgur.ImgurStatus.InternalServerError">**InternalServerError**</td><td>500</td><td>Indicates an internal imgur service error.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Imgur">DevCase.ThirdParty.Imgur Namespace</a><br />