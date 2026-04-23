# xklaim-bpmn-project-xpds29n2

This XKlaim project was automatically generated using the B2XKlaim tool.

## Project Structure

- `src/main/java/xklaim/`: Contains the XKlaim source files
  - `Collaboration.xklaim`: Main collaboration coordination code (if collaboration exists)
  - `processes/`: Contains all participant process implementations
  - `activities/`: Contains all call activity implementations
  - `tasks/`: Contains all script tasks and event sub-processes
- `src-gen/`: Generated Java code (populated when building)

## Package Organization

The project follows a clean package structure:
- `xklaim`: Root package containing the collaboration
- `xklaim.processes`: All main process implementations
- `xklaim.activities`: All call activities
- `xklaim.tasks`: All script tasks and event sub-processes

This structure ensures proper separation of concerns and makes imports straightforward.

## Building the Project

To build the project:

```
mvn clean package
```

## Running the Application

```
java -jar target/xklaim-bpmn-project-xpds29n2-1.0-SNAPSHOT-jar-with-dependencies.jar
```

## Generated from BPMN

This code was generated from a BPMN model using B2XKlaim.
