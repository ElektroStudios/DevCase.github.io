# DriveFormatResult Enumeration
 

Specifies a result status code of a drive format operation.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IO">DevCase.Core.IO</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum DriveFormatResult
```

**VB**<br />
``` VB
Public Enumeration DriveFormatResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As DriveFormatResult
```

**C++**<br />
``` C++
public enum class DriveFormatResult
```

**F#**<br />
``` F#
type DriveFormatResult
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.Success">**Success**</td><td>0</td><td>No error. Drive is formatted successful.</td></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.UnsupportedFileSystem">**UnsupportedFileSystem**</td><td>1</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.IncompatibleMediaInDrive">**IncompatibleMediaInDrive**</td><td>2</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.AccessDenied">**AccessDenied**</td><td>3</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.CallCanceled">**CallCanceled**</td><td>4</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.CallCancellationRequestTooLate">**CallCancellationRequestTooLate**</td><td>5</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.VolumeWriteProtected">**VolumeWriteProtected**</td><td>6</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.VolumeLockFailed">**VolumeLockFailed**</td><td>7</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.UnableToQuickFormat">**UnableToQuickFormat**</td><td>8</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.IOerror">**IOerror**</td><td>9</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.InvalidVolumeLabel">**InvalidVolumeLabel**</td><td>10</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.NoMediaInDrive">**NoMediaInDrive**</td><td>11</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.VolumeIsTooSmall">**VolumeIsTooSmall**</td><td>12</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.VolumeIsTooLarge">**VolumeIsTooLarge**</td><td>13</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.VolumeIsNotMounted">**VolumeIsNotMounted**</td><td>14</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.ClusterSizeIsTooSmall">**ClusterSizeIsTooSmall**</td><td>15</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.ClusterSizeIsTooLarge">**ClusterSizeIsTooLarge**</td><td>16</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.ClusterSizeIsBeyond32Bits">**ClusterSizeIsBeyond32Bits**</td><td>17</td><td /></tr><tr><td /><td target="F:DevCase.Core.IO.DriveFormatResult.UnknownError">**UnknownError**</td><td>18</td><td /></tr></table>

## See Also


#### Reference
<a href="N_DevCase_Core_IO">DevCase.Core.IO Namespace</a><br />