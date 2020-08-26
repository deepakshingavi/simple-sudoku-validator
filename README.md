# simple-sudoku-validator
Validates the user input sudoku board(9x9)

### Pre-Requisites
* Java 8+
* Maven 3.6

#### Project Details
* src/main/java - Contains Java source code
* src/test/java - Contains Java test source code  
* scripts - Contains support shell script to build and run the project

#### Unit tests
```shell script
./scripts/execUnitTests.sh
```
#### Build 
```shell script
./scripts/build.sh
```
It should compile and generate a new jar with dependencies at 
`target/simple-sudoku-validator-1.0-jar-with-dependencies.jar`


#### Run
```shell script
./scripts/validate.sh "{input file path}"
```
e.g.
``` 
./scripts/run.sh "src/test/resources/validInput.txt"
``` 
and the program should return a result message of the validation. 

NOTE : File ending with _rename needs to be renamed to actual file name and 
need to have/assign executable permissions.


