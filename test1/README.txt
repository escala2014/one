REM Download scala from http://www.scala-lang.org/files/archive/scala-2.10.4.tgz
REM Unpackage in some place you'll remember, e.g. C:\Apps
REM Set Windows environment variables SCALA_HOME=C:\Apps\scala-2.10.4 and add to PATH %SCALA_HOME%\bin
REM Go to your scala sources directory using CMD.exe, e.g. `cd c:\Users\miqui\git\escalator2014\one\samples\src`
REM Downloaded https://raw.githubusercontent.com/scala/scala-dist/master/tool-support/src/notepad-plus/userDefineLang.xml
REM            into E:\PortableApps\PortableApps\Notepad++Portable\App\Notepad++\plugins\APIs\
REM            and renamed to scala.xml
REM            and imported with "Language > User defined language > Import..."
REM            and rebooted Notepad++
REM Test the examples running following commands:

scala upper1-script.scala

scala upper2-script.scala

scalac -d ..\bin upper3.scala
scala -cp ..\bin Upper Hello world

scalac -d ..\bin shapes.scala shapes-actor.scala
scala -cp ..\bin shapes-actor-script.scala

REM scala semicolon-example-script.scala

scala string-util-v1-script.scala

scala string-util-v2-v28-script.scala

scala user-profile-v28-script.scala

scala factorial-script.scala

scala count-to-script.scala

scalac -d ..\bin string-util-v3.scala string-util-client.scala
scala -cp ..\bin StringUtilClient "Programming Scala"

scala tuple-example-script.scala

scala state-capitals-subset-script.scala

REM scala package-example1.scala
REM scala package-example2.scala
REM scala import-example1.scala

scala import-example2-script.scala

REM scala relative-imports.scala

scala abstract-types-script.scala

scala one-plus-two-script.scala

scala -language:postfixOps no-dot-script.scala

scala no-dot-better-script.scala

scala specs-script.scala
REM specs-script.scala:3: error: value should is not a member of String
REM "nerd finder" should {
REM               ^
REM one error found






