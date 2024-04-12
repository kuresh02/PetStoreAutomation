# PetStoreAutomation
Pet Store Automation with RestAssured
Certainly! Below is an example of a README file for a Pet Store automation project using RestAssured. This README provides an overview of the project, how to set it up, and how to run the tests.

---

# Pet Store Automation with RestAssured

This project demonstrates automated testing of the Pet Store API using RestAssured.

## Getting Started

### Prerequisites

- Java Development Kit (JDK) installed
- Maven installed
- IDE (Eclipse, IntelliJ, etc.) for Java development

### Installing

1. Clone this repository to your local machine.
   ```
   git clone https://github.com/yourusername/PetStoreAutomation.git
   ```

2. Open the project in your preferred IDE.

3. Ensure all dependencies are resolved by running Maven.
   ```
   mvn clean install
   ```

## Running the Tests

1. Navigate to the `src/test/java` directory.

2. Run the test classes individually or the test suite as a whole.

   To run individual test classes, execute:
   ```
   mvn test -Dtest=TestClass
   ```

   To run the entire test suite, execute:
   ```
   mvn test
   ```

## Test Cases

The test cases cover various scenarios for interacting with the Pet Store API, including:

- Retrieving pet information
- Adding a new pet
- Updating existing pet information
- Deleting a pet

## Configuration

The base URL for the Pet Store API is configured in `src/test/java/config/Config.java`. Modify this file if the API URL changes.

## Reporting

Test reports can be found in the `target/surefire-reports` directory after running the tests.

## Built With

- Java
- Gherkin
- RestAssured
- Maven

## Authors

- [Kuresh02](https://github.com/kuresh02)

## License

This project is opensources.



