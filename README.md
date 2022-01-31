Open XML Package Editor Power Tool for Modern Visual Studios
===
This is a Visual Studio extension that provides an easy way to parse and edit Open Packaging Conventions files, including Word, Excel, PowerPoint and Visio documents. 

## Supported features:

* Open any Open XML Package file or XPS Package file directly by drag and drop in Visual Studio 
* Browse the contents of Package files in a tree view
* Open any XML part directly in Visual Studio's rich XML editor
* Edit and save the XML parts
* Detect when a Package file that is opened in Visual Studio is modified externally. The extension prompts the user to reload the file without having to close any open XML part editors
* Add or remove parts and relationships directly in the user interface
* Import and export part contents to and from files
* Create new Office Packages from a set of templates using Visual Studio's File > New dialog

## Availability

The extension is available on the Visual Studio Marketplace here: [Open XML Package Editor Power Tool for Modern Visual Studios](https://marketplace.visualstudio.com/items?itemName=bsivanov.OpenXMLPackageEditorforVisualStudio).

## Compatibility
The marketplace version currently supports Visual Studio 2022, 2019, and 2017. 

The latest version supporting Visual Studio 2015, 2013, and 2012, is [v1.1.0](https://github.com/bsivanov/Open-XML-Package-Editor-Power-Tool-for-Visual-Studio/releases/tag/v1.1.0). It is available in [Releases](https://github.com/bsivanov/Open-XML-Package-Editor-Power-Tool-for-Visual-Studio/releases), and could be manually installed using the `.vsix` file.

## Building 

To build the extension yourself, you need Visual Studio 2022 with 'Visual Studio extension development' workload installed.

## Tribute

This extension is fork of the original [Open XML Package Editor Power Tool for Visual Studio](https://github.com/OfficeDev/Open-XML-Package-Editor-Power-Tool-for-Visual-Studio) (also available on the Visual Studio Marketplace [here](https://marketplace.visualstudio.com/items?itemName=ChrisRae.OpenXMLPackageEditorforVisualStudio)), adding support for latest versions of Visual Studio and some small features.
