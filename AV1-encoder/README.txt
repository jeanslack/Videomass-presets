Creator: @jeanslack

WARNING:
The handling of the `libaom-av1` codec was problematic with at least
my ffmpeg 4.3.5 version on Devuan chimaera 4. The conversion is very long 
and having thus decided to terminate the subprocess, I have not succeeded. 
I think this codec is not ready for Videomass yet. As for the `libsvtav1` 
codec I haven't had the chance to test it with Videomass yet.

Please copy 'Video Encoding AV1.prst' in the "presets" folder of Videomass.

These presets are based on AV1 Video Encoding (specifically for the FFmpeg
libraries libaom-av1). Before using these AV1 based presets make
sure your FFmpeg version supports latest 'libaom-av1' and 'libsvtav1' libraries, 
otherwise you will get an `Unknown encoder` error or at least slow conversions.

-------
libaom:
-------
To install FFmpeg with support for 'libaom-av1', look at
<https://trac.ffmpeg.org/wiki/CompilationGuide>
and compile FFmpeg with the --enable-libaom option.

--------
SVT-AV1:
--------
To install FFmpeg with support for 'libsvtav1', look at
<https://trac.ffmpeg.org/wiki/CompilationGuide>
and compile FFmpeg with the --enable-libsvtav1 option.

------------------------------------------------------------
For more resources and references, please visit
<https://trac.ffmpeg.org/wiki/Encode/AV1>
------------------------------------------------------------
