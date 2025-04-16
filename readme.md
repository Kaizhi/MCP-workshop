# Setup

Follow these steps to set up the project:

1.  Install project dependencies:
    ```bash
    npm install
    ```
2.  Install `ts-node` globally to help run Cursor run server:
    ```bash
    npm install -g ts-node
    ```
3.  Configure Cursor MCP:
    *   Open Cursor settings.
    *   Navigate to the MCP settings.
    *   Update the relevant path setting to point to the root directory of this project.
    *   Replace {project-path} with the path to your MCP-workshop project
    ```json
    "MCP-Workshop": {
      "command": "ts-node",
      "args": ["{project-path}/src/index.ts"],
    }
    ```
