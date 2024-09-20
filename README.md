# AREP_PARCIAL1_BONO


## Getting Started

These instructions will get you a copy of the project up and running on your local machine.

### Prerequisites

Before install and run the project you will need:

1. **Java** (version 21)

2. **Maven**
    - Download Maven from [here](http://maven.apache.org/download.html)
    - Follow the installation instructions [here](http://maven.apache.org/download.html#Installation)

3. **Git**
    - Install Git by following the instructions [here](http://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Installing

1. **Clone the repository and navigate into the project directory**:
    ```sh
    git clone https://github.com/JuanDavidGarciaPulido/AREP_PARCIAL1_BONO.git

    cd AREP_PARCIAL1_BONO
    ```

2. **Compile the project**:
   ```sh
   mvn clean install
   ```

3. **Run CalcReflexFacade and CalcReflexBEServer**:
   ```sh
   java -cp target/classes co.edu.escuelaing.arep.app.CalcReflexFacade
   ```

   ```sh
   java -cp target/classes co.edu.escuelaing.arep.app.CalcReflexBEServer
   ```

4. **Access the web application**:
`http://localhost:35000`

## Usage

To use the operations from Java Math library, you have to write the command and the values. For example: abs(-50) max(50,100) . To use the bubble sort algorithm, change the command to bbl. For example, bbl(100,50,25,10,1).


![image](https://github.com/user-attachments/assets/64156403-de5f-415b-bed1-497ac618ed44)


![image](https://github.com/user-attachments/assets/bccc6a2b-db33-4222-a588-7b753e5690d3)


![image](https://github.com/user-attachments/assets/c32e9ce1-8ea1-418c-b4e2-454603901f2d)


## Author
This project was developed by Juan David García Pulido.

## Date

Thursday, September 19 - 2024

## License

This project is licensed under the GNU license; See the [LICENSE.txt](LICENSE.txt) file for details.
