
#  MCP Server

A Model Context Protocol (MCP) server built for the ENST Bot, enabling seamless integration between LLM agents and external tools.

##  Tech Stack

- Java
- Spring Boot
- MCP Protocol
- Maven

##  Project Structure

```bash
mcp-server/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   └── org/
│   │   │       └── example/
│   │   │           ├── tools/
│   │   │           
│   │   │
│   │   └── resources/
│   │       └── application.properties
│   │
│   └── test/
│
├── pom.xml
└── README.md
```

##  Features

-  MCP protocol implementation
-  Tool registration for LLM agents
-  Server-side request handling
-  Easy tool integration
-  High-performance communication

##  Prerequisites

- Java 11+
- Maven

##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/HajarBoulmane/mcp-server.git
cd mcp-server
```

### 2. Build the project

```bash
./mvnw clean install
```

### 3. Run the server

```bash
./mvnw spring-boot:run
```



## 🔗 Integration with ENST Bot

This server is designed to work with the [ENST Bot](https://github.com/HajarBoulmane/enst-bot) as its MCP backend.

