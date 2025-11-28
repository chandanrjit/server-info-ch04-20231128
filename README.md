# Mule Application - Server Info

This is a Mule 4 application that provides server information and GPS walker functionality.

## Project Structure

```
.
├── META-INF/              # Application metadata and Maven info
├── docroot/               # Static web content and resources
├── repository/            # Application dependencies
├── utilities/             # Utility files
├── application-types.xml  # Application type configurations
├── gpswalker.properties   # GPS walker properties
├── gpswalker.xml          # GPS walker configuration
├── log4j2.xml             # Logging configuration
├── properties.yaml        # Application properties
└── serverinfo.xml         # Server information configuration
```

## Configuration Files

- **serverinfo.xml** - Main server information flow configuration
- **gpswalker.xml** - GPS walker flow configuration
- **properties.yaml** - Application-level properties
- **log4j2.xml** - Log4j2 logging configuration

## Requirements

- Mule Runtime 4.x
- Java 8 or higher

## Running the Application

1. Deploy to Mule Runtime or CloudHub
2. Access the endpoints defined in the configuration files

## Development

This application was extracted from a packaged Mule application JAR file and is ready for development and deployment.

## License

See LICENSE file for details.
