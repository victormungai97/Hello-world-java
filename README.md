# Hello-world-java
Brief introduction to setting up Java and running first program

Hi guys! 
So today, we shall we setting up Java for use as our programming language.
Please follow the steps carefully to avoid any mistakes along the way

1. ABOUT JAVA
   Java is a general-purpose computer programming language that is concurrent, class-based, object-oriented,[14] and specifically designed to have as few implementation dependencies as possible. It is intended to let application developers "write once, run anywhere" (WORA), meaning that compiled Java code can run on all platforms that support Java without the need for recompilation Java applications are typically compiled to bytecode that can run on any Java virtual machine (JVM) regardless of computer architecture. As of 2016, Java is one of the most popular programming languages in use particularly for client-server web applications, with a reported 9 million developers.[21] Java was originally developed by James Gosling at Sun Microsystems (which has since been acquired by Oracle Corporation) and released in 1995. (Courtesy of Wikipedia.com)

  A term that we will be using is the jdk. The Java Development Kit (JDK) is a software development environment used for developing Java applications and applets. It includes the Java Runtime Environment (JRE), an interpreter/loader (java), a compiler (javac), an archiver (jar), a documentation generator (javadoc) and other tools needed in Java development(Techpedia)
  
2. WHY JAVA
  a. It's widely used.
  b. It's open source meaning it's development kit is available and free
    for developers to use.
  c. It's platform independent hence can run on any computer regardless of
     hardware and software dependencies.
   d. It's portable as the program will run on an program's JRE once it has 
     
3. DOWNLOADING JAVA (as of 14/03/2017)
  a. Go to http://www.oracle.com/technetwork/java/javase/downloads/jdk8-downloads-2133151.html so as to get Java SE (Standard              Edition) dowload page.
  b. Click on the radio button saying "Accept License Agreement" in the Java SE Development Kit 8u121
  c. Look for the file description that matches your computer and select it's corresponding JDK. If you are on Windows, visit http://support.wdc.com/knowledgebase/answer.aspx?ID=9405#top to determine your type of Windows.
  d. Once the jdk has been downloaded, click on the "Run" option or go to the folder where it was downloaded (probabl Downloads)
     and double click on it.
  e. A wizard will appear. Complete the steps given while keeping the default options to complete the Java       installation process.

4. SETTING UP JAVA PATH
   For us to fully access the Java compiler, we need to set the path to it so that the computer can know where to find it.
   a. Click Start Menu -> Computer/This PC -> Local Disk (C:) -> Program Files -> Java -> jdk1.8.xxxx -> bin.
   b. Right click on any of the contents in bin folder and select Properties.
   c. Look for location, select all of location, right click it and copy it. Ensure you start from C: and INCLUDE BIN. If
      you don't see bin, do this tutorial again. This location is where your compiler is.
   d. Close File Explorer. Right click on Start and select System.
   e. On the left hand side of the screen, select "Advanced system settings'.
   f. Under the Advanced tab of the System Properties that appear, select 'Environment Variables'.
   g. Under 'User variables' select New.
   h. For variable name, write Path and for variable value, right click and paste the location of your compiler.
   i. Click OK on everything to exit.
   j. Click on Start Menu and type 'cmd' to open the command prompt. A black display screen should appear. Go ahead and type 'javac'. If a bunch of stuff appears, then you have succesfully set up the Java compiler. You can now write java programs on your computer. If a message saying 'javac is not recognised' appears, please repeat this tutorial.


5. SETTING UP ECLIPSE
   Eclipse is an IDE (Integrated Development Environment) which is free for use to make Java programs.
   a.Go to www.eclipse.org/downloads and select the latest Eclipse version (Neon 64 bit). Go on to download the available .exe
      file.
   b.On download completion, navigate to the folder containing the download and double click the exe file to run.
   c.An installation wizard will appear. Select "Eclipse IDE for Java Developers" and follow the steps to complete installation.
