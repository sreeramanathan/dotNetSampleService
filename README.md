.NET sample service
======================

* Install NuGet.

* Register with NuGet to get an api-key and run 'nuget SetApiKey \<api-key\>'.

* Run 'nuget spec' from the directory containing .csproj. This generates a spec file.

* Run 'nuget pack \<proj_name\>.csproj' to generate the nuget package.

* Run 'nuget push \<package_name\>.nupkg' to push to the repo.

* Run 'nuget install <package_name>' to install package in the system.
