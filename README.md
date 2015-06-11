### Maual create .fsproj for fsharp-atom.

```
<Project ToolsVersion="4.0" DefaultTargets="Builid" xmlns="http://schemas.microsoft.com/developer/msbuild/2003">
    <ItemGroup>
        <Reference Include="System"/>
    </ItemGroup>
    <ItemGroup>
        <Compile Include="Library.fs"/>
        <Compile Include="Main.fs"/>
    </ItemGroup>
</Project>

```
