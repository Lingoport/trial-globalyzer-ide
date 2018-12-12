# trial-globalyzer-ide
## Introduction
Lingoport's products facilitate internationalization (i18n) and localization (L10n) automation for software application source code. 

Globalyzer in IDE is one of the deployments for the i18n issue detection. It helps developers identify i18n issues within an IDE by scanning source code.

Videos and documentation are available on the Lingoport Wiki at 
https://wiki.lingoport.com/Globalyzer_Lite

## Installing Globalyzer Lite
### The Scanning Engine
Unzip the globalyzer-lite-6.1.1_11.0.zip file and follow the simple instructions in the README.md.
We recommend unzipping under a 'lingoport' directory under your home directory.
 

## IDE Configuration
Depending on your IDE, configure the external tool as per the README unzipped above.

### The License
This setup is for a quick and easy trial. To get your license, please contact 'support@lingoport.com'. The license will be generated for a 30 days trial period.
Place Globalyzer.license in your Lingoport directory:
* C:\Lingoport on Windows
* $HOME/lingoport on Linux
* /Applications/Lingoport on Mac

## Project Specifics
Right under the root directory of your source code, add a 'lingoport' directory and place the rule set and the project definition files:
* /source code project root/lingoport/JavaScript_i18n.trial.com.zip
* /source code project root/lingoport/Java_Rule_Set_i18n.trial.com.zip
* /source code project root/lingoport/LiteProjectDefinition.xml

## Running Globalyzer in IDE
Select a file or a directory and run the external tool as per the "Running Globalyzer Lite" section of the https://www.globalyzer.com/gzserver/help/referenceLite/globalyzer-lite-IDE-usage.html documentation.

## Email Support
Send your questions to support@lingoport.com
