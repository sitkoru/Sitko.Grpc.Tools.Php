# Sitko.Grpc.Tools.Php

[![Nuget](https://img.shields.io/nuget/v/Sitko.Grpc.Tools.Php)](https://www.nuget.org/packages/Sitko.Grpc.Tools.Php/)

MSBuild Target for generate php files from gRPC

# Installation

```
dotnet add package Sitko.Grpc.Tools.Php
```

# Basic usage

Add PhpOutputDir property to Protobuf Item

```xml
<ItemGroup>
    <Protobuf Include="**/*.proto" GrpcServices="Both" PhpOutputDir="Php"/>
</ItemGroup>
```

# Limitations

Works only on Linux x64 for now


