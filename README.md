# RimWorld XML Catalogs

This repository hosts schemas used to validate XML files for the game RimWorld.

It's intended to be used when creating mods for RimWorld.

## Getting Started

1. Setup your IDE, editor, terminal, whatever... to reference the catalog files `catalog.xml` in this repository.\
  (If someone know how to reference a GitHub URL as a catalog in Visual Studio Code, please let me know.)
2. Add the corresponding namespace (`xmlns`) to the XML node you want to validate.

## Supported XML Nodes

```xml
<ModMetaData xmlns="rimworld.schemas.modMetaData">
```

## Contributing

You can contribute to this project by submitting a pull request.\
Please ensure that your pull request follows the guidelines listed below.

1. **Schema files should use the `.xsd` extension**:\
  To keep things consistent, all schema files should use the `.xsd` extension.
2. **One schema per file**:\
  Each schema should be in its own file. The filename should match the schema name.
3. **One node per schema**:\
  Each schema should validate one node. The node name should match the schema name.
4. **One namespace per schema**:\
  Each schema should have its own namespace. The namespace should match the schema name.
5. **Schema namespaces should be prefixed with `rimworld.schemas`**:\
  This is to avoid conflicts with other schemas.
6. **Schema files should be placed in the `schemas` directory**:\
  This is to avoid cluttering the root directory.
7. **Schema files should be added to the `catalog.xml` file**:\
  This is to ensure that the schema files are included in the catalog.
8. **Keep the catalog file sorted alphabetically**:\
  This is to make it easier to find a specific schema.

For reporting bugs or suggesting features, please open an issue.

## Disclaimers

1. **Usage Limitations**: This project is intended for use with the game RimWorld.

2. **No Warranty**: This project is provided "as is", without warranty of any kind. Use at your own risk.

3. **Not Affiliated**: This project is not officially affiliated with, endorsed by, or connected to the creators of RimWorld or Ludeon Studios. All product names, logos, and brands are property of their respective owners.

4. **Updates and Maintenance**: This project is maintained on a voluntary basis. As such, updates and bugfixes may not be immediate.

Please ensure you understand these disclaimers before using the project.
