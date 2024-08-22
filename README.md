# <a name="en"></a>word-to-html-settings

Schema and oXygen framework for Antenna House Formatter 'HTML on Word' settings files.

**word-to-html-settings** version numbers correspond to the HTML on Word version current at the time of the release.

Each release includes schema files in Relax NG, Relax NG compact syntax, W3C XML Schema, and DTD formats.

## Disclaimer

**word-to-html-settings** is a work in progress.

Pull requests and new issues are welcome.

## Installing

* If you want to keep up-to-date with **word-to-html-settings** releases, then you can install **word-to-html-settings** as an add-on Oxygen framework.
* Alternatively, you can download a static copy of the Oxygen framework from GitHub.
* If you want to easily keep up-to-date with changes, then you can clone this repository and 'pull' the latest version whenever you want.
* If you want to hack on **word-to-html-settings** or submit pull requests, then you can fork this repository and clone that onto your local machine.

### Installing as add-on Oxygen framework

Follow the instructions in the Oxygen manual at https://www.oxygenxml.com/doc/ug-editor/topics/installing-and-updating-add-ons.html

The **word-to-html-settings** update site URL is https://raw.githubusercontent.com/AntennaHouse/word-to-html-settings/master/add-on.xml

Note that Oxygen will require you to restart the editor after installing the add-on framework.

### Installing a ZIP archive to Oxygen `frameworks` directory

1. Download the ZIP archive from the latest release on the 'Releases' page.
2. Extract the folder in the ZIP archive to the Oxygen `frameworks` directory.
  - On Windows, this is `C:\Program Files\Oxygen XML Editor 24.1\frameworks`, or something similar.
  - If you don't have permission to copy the folder to the `frameworks` directory, then you can use an alternative location as described below.
3. Restart Oxygen.

### Installing a ZIP archive to an alternative frameworks location

If you don't have permission to modify the Oxygen installation – for example, if Oxygen is installed on Windows under `C:\Program Files\` and you are not an Administrator – you can set Oxygen to also use an alternative frameworks location.

1. Click on the "Download ZIP" button on this project's main page to download the files.
2. Extract the folder in the ZIP archive to a folder where you can create the new folder.
3. In your Oxygen preferences, add the **word-to-html-settings** folder as an alternative frameworks location.
  - See https://www.oxygenxml.com/doc/ug-editor/topics/framework-location.html
4. Restart Oxygen.

### Installing a repository clone

1. Clone the repository into either the Oxygen `frameworks` directory or another directory.
2. If necessary, add the **word-to-html-settings** folder as an alternative frameworks location.
3. Restart Oxygen.

## Using **word-to-html-settings**

### oXygen XML Editor

When you open an `word-to-html-settings.xml` file – where the document element is `word-to-html-settings` in no namespace – oXygen will automatically validate the document against the Relax NG schema.

If the file includes a DOCTYPE declaration, Oxygen will validate the file using the DTD. If the DOCTYPE declaration is absent or is commented out, Oxygen will use the Relax NG schema from the framework, which provide more fine-grained validation than is possible with a DTD.

The Oxygen framwork provides template `word-to-html-settings.xml` files.

### Standalone validation

Each release includes schema files in Relax NG, Relax NG compact syntax, W3C XML Schema, and DTD formats.

## License

Copyright 2024 Antenna House, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

