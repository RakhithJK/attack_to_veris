# VERIS Vocabulary Mappings

This folder contains mappings of the VERIS framework to MITRE ATT&CK along with parsers and supporting data.

| Mappings Version | Last Updated | VERIS Version | ATT&CK Version | ATT&CK Domain |
|---|---|---|---|---|
| 1.4 | 7 June 2021 | [VERIS v1.3.5](http://veriscommunity.net/index.html) | [ATT&CK v9.0](https://attack.mitre.org/resources/versions/) | Enterprise |

| Data | Description |
|---|---|
| [spreadsheet](veris-mappings.xlsx) | Lists all of the mappings for this control framework. |
| [json](veris-mappings.json) | Lists all of the mappings for this control framework in JSON format. |
| [layers](layers) | [ATT&CK Navigator](https://github.com/mitre-attack/attack-navigator) layers showing the mappings in the context of the ATT&CK Matrix. |
| [stix](stix) | The STIX 2.0 representation of the data in JSON format. See the README in that folder for more information. |
| [input](input) | 	Input spreadsheets from which the STIX is built. To rebuild the STIX data from the input spreadsheets, run `python parse.py`. See the README in that folder for more information. |
