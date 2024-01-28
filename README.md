# A1: Code Smell

**Code Smell Detecting Tool:** SonarLint

**Target Project:** [aircompany](https://github.com/vitalliuss/aircompany/tree/master/Java)

SonarLint was able to detect a number of code smells within the target project. While going through the code, I had to consider what changes were necessary to improve readability and cleanliness while keeping functionality. Overall, the code smells were simple fixes so I managed to fix each one without having to make compromises on how the project worked. As a developer, it would be important to detect smells in a project in order to maintain a clean and healthy codebase. Detecting and dealing with code smells is a good measure to ensure success in development.

## Code Smells Found


### 1. SonarLint: Sections of code should not be commented out (java:S125)
<img src='/ss/commentedoutcode.png' width=''/>
Fix: by deleting commented out code.

### 2. SonarLint: The default unnamed package should not be used (java:S1220)
<img src='/ss/defaultunnamed.png' width=''/>
Fix: by moving the class and stating the package name.

### 3. SonarLint: Class names should comply with a naming convention (java:S101)
<img src='/ss/class.png' width=''/>
Fix: by renaming "experimentalPlane" class to "ExperimentalPlane" in order to match naming convention.

### 4. SonarLint: Method names should comply with a naming convention (java:S100)
<img src='/ss/method.png' width=''/>
Fix: by renaming "Get_Max_Flight_Distance" method to "getMaxFlightDistance" in order to match naming convention.

### 5. SonarLint: Package names should comply with a naming convention (java:S120)
<img src='/ss/package.png' width=''/>
Fix: by renaming "Planes" package to "planes" in order to match naming convention.

### 6. SonarLint: Modifiers should be declared in the correct order (java:S1124)
<img src='/ss/wrongorder.png' width=''/>
Fix: by changing the order.

### 7. SonartLint: Constructors of an "abstract" class should not be declared "public" (java:S5993)
<img src='/ss/constructor.png' width=''/>
Fix: "protected" instead of "public".

### 8. SonartLint: Local variables should not be declared and then immediately returned or thrown (java:S1488)
<img src='/ss/temporaryvariable.png' width=''/>
Fix: use inline expression "return this.maxLoadCapacity".

### 9. SonartLint: Standard outputs should not be used directly to log anything (java:S106)
<img src='/ss/sysout.png' width=''/>
Fix: replace "System.out" with "logger".

### 10. SonartLint: Nested blocks of code should not be left empty (java:S108)
<img src='/ss/empty.png' width=''/>
Fix: by removing empty else block.

### 11. SonartLint: Anonymous inner classes containing only one method should become lambdas (java:S1604)
<img src='/ss/anoninnerclass.png' width=''/>
Fix: make annoymous inner class a lambda.

### 12. SonartLint: Unused "private" methods should be removed (java:S1144)
<img src='/ss/unused.png' width=''/>
Fix: by removing the unused method.

### 13. SonartLint: Track uses of "TODO" tags (java:S1135)
<img src='/ss/todo.png' width=''/>
Fix: by completing task. (removed in this case)

### 14. SonartLint: Package declaration should match source file directory (java:S1598)
Fix: by changing the name of "Planes" directory to "planes" after package name was changed to "planes".
