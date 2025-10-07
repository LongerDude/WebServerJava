# WebServerJava

A lightweight HTTP server implemented in Java. This project demonstrates the fundamentals of handling HTTP requests and serving static content without relying on external frameworks.

## Features

- Basic HTTP request parsing
- Serves static HTML files
- Handles multiple client connections using threads
- Simple logging of incoming requests

## Technologies Used

- Java SE
- Socket programming
- Threading
- Basic I/O and file handling

## Project Structure

```
WebServerJava/
├── src/
│   ├── WebServer.java
│   └── ClientHandler.java
├── www/
│   └── index.html
├── .idea/
├── WebServerJava.iml
└── .gitignore
```

## How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/LongerDude/WebServerJava.git
   cd WebServerJava
   ```

2. Compile the source files:
   ```bash
   javac src/*.java
   ```

3. Start the server:
   ```bash
   java src.WebServer
   ```

4. Open a browser and navigate to:
   ```
   http://localhost:8080
   ```

## Notes

- The server serves files from the `www/` directory.
- Default port is `8080`; you can change it in `WebServer.java`.
- Only basic GET requests are supported.

## Future Improvements

- Add support for POST requests
- Implement MIME type detection
- Add routing and templating support
- Improve error handling and logging

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
