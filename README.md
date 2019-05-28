# Tomcat Notes

## Issues

### `startup.bat` stops itself

Change `call "%EXECUTABLE%" start %CMD_LINE_ARGS%` to `call "%EXECUTABLE%" run %CMD_LINE_ARGS%`.

http://www.coderanch.com/t/83600/Tomcat/startup-bat-stops

