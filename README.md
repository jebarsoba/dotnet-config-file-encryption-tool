# dotnet-config-file-encryption-tool
Command-line tool to encrypt/decrypt .NET console application configuration files, based on *__NAnt__*.

Usage:
Change the following properties inside *dotnet-config-file-encryption-tool.build* file:
* bin-dir: console application binaries location.
* config-filename: console application configuration filename.
* framework-dir: .NET framework location.

To encrypt:
dotnet-config-file-encryption-tool.bat encrypt

To decrypt:
dotnet-config-file-encryption-tool.bat decrypt
