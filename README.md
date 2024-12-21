<!--
 * @Author: AidenYangX
 * @Email: xscs709560271@gmail.com
 * @Date: 2024-12-21 23:30:55
 * @Description: Mapbox MCP Server
-->

# Mapbox MCP Server

MCP Server for the Mapbox API.

## Tools

1. `directions api`
   - Get directions between points
   - Inputs:
     - `coordinates` ({latitude: number, longitude: number}[])
     - `profile` (optional): "driving-traffic", "driving", "walking", "cycling"
   - Returns: route details with steps, distance, duration

## Setup

### API Key

Get a Mapbox API key by following the instructions [here](https://console.mapbox.com/account/access-tokens/).

Make the API key available as `MAPBOX_ACCESS_TOKEN` environment variable.

## Deployment

### Structure

In mapbox-mcp-server, we use the following structure to manage the server's handlers:

---

**Class Diagram**:
![mapbox-mcp-server-class-diagram](./assets/MapboxMCPServerClass.png)

---

**Process Diagram**:
![mapbox-mcp-server-process-diagram](./assets/MapboxMCPServerProcess.png)

## License

This MCP server is licensed under the MIT License. This means you are free to use, modify, and distribute the software, subject to the terms and conditions of the MIT License. For more details, please see the LICENSE file in the project repository.
