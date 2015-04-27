#Present Value
###IBM SPSS Modeler Predictive Extensions

This node enables you to compute the present value of cash-flow by specifying the desired year and annual rate. 

![Map](https://github.com/IBMPredictiveAnalytics/Present-Value/blob/master/Screenshot/Illustration1.png?raw=true)



---
Requirements
----
- IBM SPSS Modeler v16.0 or later
- IBM SPSS Modeler 'R Essentials'
- R 2.15.x or R 3.1

More information here: [IBM Predictive Extensions][2]


---
Installation intructions
----
1. Download the extension: [Download][3] 
2. Close IBM SPSS Modeler. Save the .cfe file in the CDB directory, located by default on Windows in "C:\ProgramData\IBM\SPSS\Modeler\16\CDB" or under your IBM SPSS Modeler installation directory.
3. Restart IBM SPSS Modeler, the node will now appear in the Model palette.

---
R Packages used
----
The R packages will be installed the first time the node is used as long as an Internet connection is available.
- [stringr][4]

---
Documentation and samples
----
- Find a PDF with the documentation of this extension in the [Documentation][5] directory
- There is a sample available in the [example][6] directory
- [Video-tutorial][20]

---
License
----

[Apache 2.0][1]


Contributors
----

  - Armand Ruiz ([armand_ruiz](https://twitter.com/armand_ruiz))


[1]: http://www.apache.org/licenses/LICENSE-2.0.html
[2]:https://developer.ibm.com/predictiveanalytics/downloads/#tab2
[3]:https://github.com/IBMPredictiveAnalytics/Present-Value/raw/master/Source%20code/PresentValue.cfe
[4]:http://cran.r-project.org/web/packages/stringr
[5]:https://github.com/IBMPredictiveAnalytics/Present-Value/blob/master/Documentation/PresentValue-SPSSModelerExtension.pdf
[6]:https://github.com/IBMPredictiveAnalytics/Present-Value/tree/master/Example
[20]:https://www.youtube.com/watch?v=mq4zOGdO4Jw
