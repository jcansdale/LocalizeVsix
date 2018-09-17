# LocalizeVsix
An example localizable VSIX project that uses [XliffTasks](https://github.com/dotnet/xliff-tasks)

### How to test

1. Update the `ButtonText` in `LocalizeCommandPackage.vsct`
2. Solution compile should fail
3. Run `msbuild /t:UpdateXlf` to update .xlf files
4. Translate the updated .xlf files
5. Build and install VSIX 

Your extension has been localized! 🎉
