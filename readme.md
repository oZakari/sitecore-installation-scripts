# Sitecore Installation Scripts
This repository contains various scripts that might be required for sitecore installation

## Sitecore 9.0
### Sitecore 9.0.1
#### Sitecore Experience Commerce 9.0 Update 1 (Sitecore.Commerce.2018.03-2.1.55)
Scripts allow configuration of a commerce engine on a single machine. 
Out of the box sitecore scripts are modified to allow more granular control over installation including
* **hosts** - possible to set desired host names to each commerce role
* **ports** - possible to set desired ports to each commerce role
* **locations** - possible to set desired location to each commerce role
* **certificates** - certificates are generated for each role, or could be shared (using wildcard certificate)

_IMPORTANT: SXA installation is currently removed from scripts (but will be added later)_

##### TODO list:
* [ ] Automate archives extraction, except SIF itself
* [ ] Try to leverage `Microsoft.Web.XmlTransform.dll` from SIF or download automatically from NuGet
* [ ] Enable SXA

## Contributing
Any feedback, [issues](https://github.com/asmagin/sitecore-installation-scripts/issues) or pull requests [pull requests](https://github.com/asmagin/sitecore-installation-scripts/pulls) are welcome and greatly appreciated.