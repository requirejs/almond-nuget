This is the package for publishing [almond](https://github.com/jrburke/almond) to
[NuGet](http://docs.nuget.org/) for Visual Studio users.

* Update the almond.js version in content/Scripts using `volo add -nostamp -f jrburke/almond`
* Update Package.nuspec to rev version number.
* NuGet.exe Pack Package.nuspec
* NuGet.exe Push almond.0.0.0.nupkg

## License

MIT

## Code of Conduct

[jQuery Foundation Code of Conduct](https://jquery.org/conduct/).
