# Sitko.Grpc.Tools.Php

![Nuget](https://img.shields.io/nuget/v/Sitko.Grpc.Tools.Php)

MSBuild Target for generate php files from gRPC

# Installation

```
dotnet add package Sitko.Grpc.Tools.Php
```

# Basic usage

Add PhpProtobuf target next to Protobuf

```xml
<ItemGroup>
    <Protobuf Include="**/*.proto" GrpcServices="Both"/>
    <PhpProtobuf Include="**/*.proto" ProtoRoot="Proto" OutputDir="Php"/>
</ItemGroup>
```

# Limitations

Works only on Linux x64 for now


