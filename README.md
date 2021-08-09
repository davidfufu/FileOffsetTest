# FileOffsetTest

Following the documentation here:
https://www.renderheads.com/content/docs/AVProVideo/articles/inline-file-offset.html


Using AVPro 2.1.8 Ultra
Using Unity 2019.4.16

Attempted Steps:

1. Open command line from folder with the two video clips
2. run command "copy /b dummy.mp4 + %1 %~n1-hidden.mp4"
3. import the created file "%~n1-hidden.mp4" into unity and put it in Streaming Assets folder
4. go to AVpro demo scenes Open Demo_Mediaplayer scene
5. set File Offset to 54321 in Platform Specific Settings 
6. Create media reference and set it as the media on the media player component
7. Player plays the dummy video file, instead of the hidden media file
