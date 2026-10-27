# WeatherAppOne

COPY THE FOLLOWING COMMANDS IN ORDER TO OPEN:

FIRST: Copy the ENTIRE text body below, beginning from "javac " to ".txt)", into the terminal of VS Code or your chosen platform. This is to ensure all necessary code is compiled.

javac --module-path "C:\Users\aishw\OneDrive\Javaproject\weatherAppOne\Java\javafx-sdk-25.0.1\lib" --add-modules javafx.controls,javafx.fxml -d out (Get-Content .\sources.txt)  

SECOND: Copy the ENTIRE text body below, beginning from "java " to "AppLauncher", into the terminal of VS code or your chosen platform. This is to make the app open.

java --module-path "C:\Users\aishw\OneDrive\Javaproject\weatherAppOne\Java\javafx-sdk-25.0.1\lib" --add-modules javafx.controls,javafx.fxml -cp out AppLauncher

Environmental Variable Checker:
Environmental variable
JAVA_HOME=C:\Users\aishw\.jdks\openjdk-25.0.1
PATH=%JAVA_HOME%\bin
Make sure powershell.exe on the terminal settings
Java -version in the terminal- should show 25.0.1
