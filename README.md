# Sitko.Grpc.Tools.Php

MSBuild Target for compiling proto-files to php 

# Installation

```
dotnet add package Sitko.Grpc.Tools.Php
```

# Basic usage

```xml
<ItemGroup>
    <PhpProtobuf Include="**/*.proto" OutputDir="Php" />
</ItemGroup>
```

# Limitations

Works only on Linux x64 for now


