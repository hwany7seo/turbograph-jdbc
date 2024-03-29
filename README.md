## HOW TO BUILD TurboGraph JDBC Driver
### TurboGraph JDBC Driver Source Build Guide (ANT Build Project)
- Windows
  ```
  build.bat 
  ```
    
- Linux

  ```
  ./build.sh 
  ```

### TurboGraph JDBC Driver 
- implements an interface to enable access 
  from applications in Java to TurboGraph DBMS.
  The driver has been developed based on the CUBRID JDBC source (the JDBC 2.0 specification)
  and the default driver provided is complied with JDK 1.6.

### Maven Repository Infomation
'''
<dependency> 
    <groupId>turbograph</groupId> 
    <artifactId>turbograph-jdbc</artifactId> 
    <version>release</version> 
</dependency> 
'''

