Build:
  dotnet build -c Release

Run:
  .\EfiMiniExplorer\bin\Release\net8.0-windows\EfiMiniExplorer.exe

Publish single-file:
  dotnet publish -c Release -r win-x64 --self-contained true /p:PublishSingleFile=true
