Create inital webapi project
```
mkdir RestApiDemo
cd RestApiDemo
dotnet new webapi
```
Use VS Code (https://code.visualstudio.com/)
```
code .
```
or
```
dotnet run
```
App will start on localhost (on default 5000 and 5001 ports) with initial cocntroller ValuesController

```
...
Now listening on: https://localhost:5001
Now listening on: http://localhost:5000
Application started. Press Ctrl+C to shut down.
```
Go to https://localhost:5001/api/values
or 
```
curl -k https://localhost:5001/api/values/2
curl -k https://localhost:5001/api/values
```
-k is to ignore 