# az-function-timer

This guide will walk you through creating a Python-based Timer Trigger using Azure Functions in VS Code.

### Step 0: Create a GitHub Repository
- Start by creating a new GitHub repository to host your project.

### Step 1: Install Azure Tools in VS Code
- Ensure you have the Azure Tools extension installed in Visual Studio Code.

### Step 2: Create a New Azure Function Project
- Install the Azure Functions extension in VS Code.
- Open the command palette (`Ctrl+Shift+P` or `Cmd+Shift+P` on macOS) and select **Azure Functions: Create New Project**.
- Choose **Timer Trigger** as the template when prompted.

### Step 3: Modify the `function_app.py` File
- The `function_app.py` file serves as the entry point for your Azure Functions app. This is where the program begins.
- Modify the file according to your needs.
- For detailed information, refer to the [Azure Functions Python documentation](https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-python?tabs=get-started%2Casgi%2Capplication-level&pivots=python-mode-decorators).

### Step 4: Connect Azure Functions to GitHub
- Set up continuous integration by connecting your Azure Functions app to your GitHub repository.

### Step 5: Verify Deployment via Logs
- After deploying your function, you can monitor its activity by checking the logs in the **Stream Logs** section of Azure Functions.

## More information
1) CosmosDB (with az functions)
- https://learn.microsoft.com/en-us/azure/azure-functions/functions-reference-python?tabs=get-started%2Casgi%2Capplication-level&pivots=python-mode-decorators
- https://learn.microsoft.com/ko-kr/azure/cosmos-db/throughput-serverless
2) key-vault (envs params)
- https://medium.com/@dssc2022yt/-accessing-azure-key-vault-secrets-with-azure-functions-2e651980f292
