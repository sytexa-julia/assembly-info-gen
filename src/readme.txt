
The AssemblyInfo.cs file is generated via an AssemblyInfo.tt T4 template file that is transformed during the pre-build 
event. It requires that the <Version> property be set within a <PropertyGroup> element within the project's .csproj 
file. The AssemblyInfo.tt T4 template file will look in the .csproj file for the <Version> property in order to 
determine the major, minor version numbers to use when generating the version-specific Assembly attributes. 