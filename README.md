# A1: Code Smell

**Code Smell Detecting Tool:** SonarLint

**Target Project:** [aircompany](https://github.com/vitalliuss/aircompany/tree/master/Java)

I used [code-smells.com](https://code-smells.com/) to define smells found in the target.

### Code Smell: "Dead Code" 
**SonarLint:** Sections of code should not be commented out (java:S125)
Fixed by deleting commented out code.

**Where?** PassengerPlane.java
<img src='/commentedoutcode.png' width=''/>

**SonarLint:** Package names should comply with a naming convention (java:S120)
Fixed by renaming "Planes" package to match naming convention. Now both packages are lowercase.




