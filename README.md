# A1: Code Smell

**Code Smell Detecting Tool:** SonarLint

**Target Project:** [aircompany](https://github.com/vitalliuss/aircompany/tree/master/Java)



### Code Smells Found

**SonarLint:** Sections of code should not be commented out (java:S125)
<img src='/commentedoutcode.png' width=''/>
**Fix:** by deleting commented out code.

**SonarLint:** Method names should comply with a naming convention (java:S100)
<img src='/method.png' width=''/>
**Fix:** by renaming "Get_Max_Flight_Distance" method to "getMaxFlightDistance" in order to match naming convention.

**SonarLint:** Package names should comply with a naming convention (java:S120)
<img src='/package.png' width=''/>
**Fix:** by renaming "Planes" package to "planes" in order to match naming convention.

**SonarLint:** Modifiers should be declared in the correct order (java:S1124)
<img src='/wrongorder.png' width=''/>
**Fix:** by changing the order.

**SonartLint:** Constructors of an "abstract" class should not be declared "public" (java:S5993)
<img src='/constructor.png' width=''/>
**Fix:** "protected" instead of "public".

**SonartLint:** Local variables should not be declared and then immediately returned or thrown (java:S1488)
<img src='/temporaryvariable.png' width=''/>
**Fix:** use inline expression "return this.maxLoadCapacity"






