
1. Complie hadoop code with

$ hadoop com.sun.tools.javac.Main LinkCount.java


2. Tranform it to .jar format

$ jar cf LinkCount.jar LinkCount*.class


3. Run hadoop with your input

$ hadoop jar LinkCount.jar LinkCount web-Google.txt output102

The running time have shown in hadoopProb6_time.png
