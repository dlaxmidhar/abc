set projectLocation=C:\Users\dlaxmidhar\eclipse-workspace1\TestNgProject
cd %projectLocation%
set classpath=%projectLocation%\bin;%projectLocation%\lib\*
java org.testng.TestNG %projectLocation%\testng.xml
pause