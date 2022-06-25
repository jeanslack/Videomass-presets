Creator: @jeanslack

Please copy 'AV1 Video Encoding.prst' in the "presets" folder of Videomass.

These presets are based on AV1 Video Encoding (specifically for the FFmpeg 
libraries libsvtav1 and libaom-av1). Before using these AV1 based presets make 
sure your FFmpeg version supports 'libaom-av1' and 'libsvtav1', otherwise you 
will get an `Unknown encoder` error.

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