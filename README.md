# Java FileReader Example

A simple Java program demonstrating how to read character data from a text file using the `FileReader` class.

## Features

- Reads text files using Java's FileReader
- Automatic resource management with try-with-resources
- Command-line argument support for flexible file selection
- Proper error handling and user feedback

## Prerequisites

- Java Development Kit (JDK) 8 or higher

## Usage

1. **Compile the program:**
```bash
   javac FileReaderExample.java
```

2. **Run the program:**
```bash
   java FileReaderExample <filename>
```

   Example:
```bash
   java FileReaderExample sample.txt
```

## Example

Create a sample text file named `sample.txt`:
```
Hello, this is a sample file!
Reading files in Java is easy.
```

Run the program:
```bash
java FileReaderExample sample.txt
```

Output:
```
Data in the file:
Hello, this is a sample file!
Reading files in Java is easy.
```

## Notes

- The program reads up to 100 characters from the file
- For larger files, consider using `BufferedReader` for better performance
- Only text files are supported

## License

This project is open source and available under the MIT License.
```

**Suggested filename:** `FileReaderExample.java` (matches the class name - Java convention)

**Optional: Create a sample file** (`sample.txt`):
```
Hello, this is a sample file!
Reading files in Java is easy.
