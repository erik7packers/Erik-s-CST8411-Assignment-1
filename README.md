# Erik-s-CST8411-Assignment-1
School project


Hello and welcome to my project. It is a simple calculator. It will prompt you to pick a number with an associated operator, then 2 numbers to be subject to the math operation displaying a result. Done on a while loop so you can use it until you decide to quit. The jar file in my Github repository was uploaded through the web but you can see my published package there too. If you wish to install it onto your maven project go to pom.xml and add the package link like so:
```
<repositories>
    <repository>
        <id>github</id>
        <url>https://maven.pkg.github.com/erik7packers/Erik-s-CST8411-Assignment-1</url>
    </repository>
</repositories>
```
My dependencies were:
```
<dependencies>
    <dependency>
        <groupId>ca.menhart.erik.cst8411assignment1</groupId>
        <artifactId>cst8411-assignment1-calculator</artifactId>
        <version>3.8.1</version>
    </dependency>
</dependencies>
```
There were no real prerequisites, I had to rebuild my project as a maven project to get the xml file. I specifically chose github to avoid making sure I lined up with maven centrals requirements, like uploading all my source code which I was worried would clutter and some of the verified namespace things. Having an easy way to share code like this can save time by allowing people to build using others contributions something bigger from smaller parts.
