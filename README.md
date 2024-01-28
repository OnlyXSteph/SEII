# A1: Code Smell

**Code Smell Detecting Tool:** SonarLint

**Target Project:** [aircompany](https://github.com/vitalliuss/aircompany/tree/master/Java)


## Code Smells Found

### SonarLint: Sections of code should not be commented out (java:S125)
<img src='/ss/commentedoutcode.png' width=''/>
**Fix:** by deleting commented out code.

### SonarLint: The default unnamed package should not be used (java:S1220)
<img src='/ss/defautunnamed.png' width=''/>
**Fix:** by moving the class and stating the package name.

### SonarLint: Class names should comply with a naming convention (java:S101)
<img src='/ss/class.png' width=''/>
**Fix:** by renaming "experimentalPlane" class to "ExperimentalPlane" in order to match naming convention.

### SonarLint: Method names should comply with a naming convention (java:S100)
<img src='/ss/method.png' width=''/>
**Fix:** by renaming "Get_Max_Flight_Distance" method to "getMaxFlightDistance" in order to match naming convention.

### SonarLint: Package names should comply with a naming convention (java:S120)
<img src='/ss/package.png' width=''/>
**Fix:** by renaming "Planes" package to "planes" in order to match naming convention.

### SonarLint: Modifiers should be declared in the correct order (java:S1124)
<img src='/ss/wrongorder.png' width=''/>
**Fix:** by changing the order.

### SonartLint: Constructors of an "abstract" class should not be declared "public" (java:S5993)
<img src='/ss/constructor.png' width=''/>
**Fix:** "protected" instead of "public".

### SonartLint: Local variables should not be declared and then immediately returned or thrown (java:S1488)
<img src='/ss/temporaryvariable.png' width=''/>
**Fix:** use inline expression "return this.maxLoadCapacity".

### SonartLint: Standard outputs should not be used directly to log anything (java:S106)
<img src='/ss/sysout.png' width=''/>
**Fix:** replace "System.out" with "logger".

### SonartLint: Nested blocks of code should not be left empty (java:S108)
<img src='/ss/empty.png' width=''/>
**Fix:** by removing empty else block.

### SonartLint: Anonymous inner classes containing only one method should become lambdas (java:S1604)
<img src='/ss/anoninnerclass.png' width=''/>
**Fix:** make annoymous inner class a lambda.

### SonartLint: Unused "private" methods should be removed (java:S1144)
<img src='/ss/unused.png' width=''/>
**Fix:** by removing the unused method.

### SonartLint: Track uses of "TODO" tags (java:S1135)
<img src='/ss/todo.png' width=''/>
**Fix:** by completing task. (removed in this case)