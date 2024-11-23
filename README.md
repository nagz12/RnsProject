# AzureFunctionExample

This is a simple Azure Function using an HTTP Trigger, written in Python. 
It returns a personalized greeting if a name is provided via query parameters or the request body.

## How to Use
1. Clone this repository.
2. Install the Azure Functions Core Tools and Python runtime.
3. Run the function locally using `func start`.
4. Deploy to Azure using Visual Studio Code or the Azure CLI.

## Example Usage
- **GET Request**: `http://localhost:7071/api/HttpTrigger1?name=John`
- **POST Request** (JSON body): `{ "name": "John" }`

## Requirements
- Python 3.8 or higher
- Azure Functions Core Tools
