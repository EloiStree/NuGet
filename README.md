# NuGet
Reminder of how you can create a NuGet pacakge.

[![image](https://github.com/user-attachments/assets/ad63cf0f-6fba-483d-974f-3403073fa068)](https://youtu.be/E0rPteTWxYQ?t=84)  
https://youtu.be/E0rPteTWxYQ?t=84  
https://www.nuget.org/  

Best Pratice
[![image](https://github.com/user-attachments/assets/ea6eb01b-6fac-4b99-8ddd-fe74ef973eef)](https://youtu.be/R2Smy3bi_rM?t=92)  
https://youtu.be/R2Smy3bi_rM?t=92  

[![image](https://github.com/user-attachments/assets/e3ed6e98-9715-45c3-a89c-51aee13c970c)](https://youtu.be/R2Smy3bi_rM?t=370)  
https://youtu.be/R2Smy3bi_rM?t=370  



``` xml
<Project Sdk="Microsoft.NET.Sdk">

  <!--DOC:  https://learn.microsoft.com/en-us/nuget/create-packages/package-authoring-best-practices#readme-->
  <PropertyGroup>
    <TargetFramework>net8.0</TargetFramework>
    <ImplicitUsings>enable</ImplicitUsings>
    <Nullable>enable</Nullable>
    <PackageId>be.elab.iid</PackageId>
    <Version>1.0.0</Version>
    <Authors>Eloi Stree</Authors>
    <Description>IID is an Index Integer Date format used for network</Description>
    <Product>IID</Product>
    <Company>eLab</Company>
    <PackageReadmeFile>README.md</PackageReadmeFile>
    <RepositoryUrl>https://github.com/EloiStree/NuGet_IID</RepositoryUrl>
    <PackageLicenseFile>LICENSE.md</PackageLicenseFile>
  </PropertyGroup>
  <ItemGroup>
    <None Include="LICENSE.md" Pack="true" PackagePath="" />
    <None Include="README.md" Pack="true" PackagePath="" />
  </ItemGroup>
</Project>


```

```
dotnet new classlib
dotnet build
dotnet pack

```
https://www.nuget.org

https://www.nuget.org/packages/be.elab.iid
