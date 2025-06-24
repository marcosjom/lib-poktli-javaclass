
# poktli

Poktli ("aroma" in Nahuatl) is a library for parsing, loading and saving compiled JAVA files (.class). It can be used as a basis for the development of decompilers, (de)obfuscators, code injectors and other tools for JAVA projects.

# Licence

MIT, see LICENSE file

# Origin

Published on 09/Feb/2013.

This library was initially developed by [Marcos Ortega](https://mortegam.com/) from the CLASS file specifications document published by Oracle: http://docs.oracle.com/javase/specs/jvms/se5.0/html/ClassFile.doc.html

# Utility

This implementation is intended to be an alternative to "javap", aiming to have versions in C, Java and other languages of interest available. In such a way that developers can create software with the functionality of loading, manipulating and saving ".class" files.

Possible practical implementations of this library include the development of the following type of software:

a) for code compilation (produce class)

b) for decompilation of binaries (interpret class)

c) for obfuscation in binaries (manipulate class)

d) deobfuscation of binaries (interpret class and opcodes)

e) injection or extraction of opcodes, members, methods or method invocations (manipulate class)

f) plugins, builders or wizards that facilitate the process of integrating third-party libraries into a Java project.

Others...

# Test binaries

ClassSnifSnif.jar is a binary that allows you to test the loading and saving of class files. The following are examples of console usage:

Simple and silent test:

$ java -jar ClassSnifSnif.jar -class ./myFile.class 

Test describing the contents of the file:

$ java -jar ClassSnifSnif.jar -v -class ./myFile.class 

Load and file save test:

$ java -jar ClassSnifSnif.jar -test -class ./myFile.class 

# Contact

Visit [mortegam.com](https://mortegam.com/) to see other projects.

May you be surrounded by passionate and curious people. :-)

