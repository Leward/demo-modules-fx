Built with Java 14.

## Build and Run

### Run
```bash
mvn javafx:run
```

## As Image

```bash
mvn compile && javafx:jlink
target/hellofx/bin/launcher
```

(Note: Unlike `javafx:run`, `javafx:jlink` does not automatically trigger `mvn compile`)