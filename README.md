# asuka
A simple Blazor wasm app.

## Usage:
为方便 Pages 类服务使用，应用基路径被设置为为 `asuka`，直接运行需使用：

    dotnet run --pathbase=/asuka

发布静态文件：

    dotnet publish -c Release

生成文件默认位于 `.\bin\Release\netstandard2.1\publish\wwwroot`