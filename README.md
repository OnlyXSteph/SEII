# A2: Spotbugs

**Code Smell Detecting Tool:** SonarLint

**Target:** [spotbugs-4.8.3.zip](https://spotbugs.readthedocs.io/en/stable/installing.html)

Initially I had some trouble getting the spotbugs plug-in to work on both Eclipse and IntelliJ. I also had trouble getting the AltoroJ project to build on my system. I thought it would be a little interesting to view what bugs could be found within the first few .jar files in spotbugs-4.8.3. Interestingly, Spotbugs found a lot of bugs within it's own files, including 255 "Malicious Code Vulnerability" bugs. I was unable to fix any of the bugs since I had trouble getting Spotbugs to work for me right away. However, I was surprised at how intuitive it can be and I understand it could be a great help to developers looking to find bugs within their programs. 

## Total Bugs Found: 783

### Launching Spotbugs
<img src='/Screenshots/spotbugsjar.png' width=''/>

### Adding files to analyze
<img src='/Screenshots/addingfiles.png' width=''/>


### View of analysis
<img src='/Screenshots/analysis.png' width=''/>


### Bug breakdown
<img src='/Screenshots/breakdown.png' width=''/>

