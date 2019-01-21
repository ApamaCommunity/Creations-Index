# Apama Community Creations Index
A curated index of community creations for the [Apama Streaming Analytics](http://www.apamacommunity.com/) platform.
## Contributing to the Index
If you would like to link to a resource (hosted on GitHub or externally), please create a pull request containing your changes to the README.md file. 

- Please try to find an existing category under which it can be placed, else insert under 'Misc.' or suggest a new category
- Please prettify links such that the link text is a descriptive title rather than a URL

## Connectivity Plug-Ins
### C++
- [CSV Codec](https://github.com/himanshunandeshwar/apama-streaming-analytics-connectivityPlugin-CSVCodec-cpp) - Translation of CSV format messages
- [Batching Codec](https://github.com/mjj29/apama-batching-codec) - Convert a batch of messages into a single message containing a list of messages and vice-versa

### Java
- [CSV Codec](https://github.com/SoftwareAG/apama-streaming-analytics-connectivity-CSVCodec) - Translation of CSV format messages
- [File Transport](https://github.com/SoftwareAG/apama-streaming-analytics-connectivity-FileTransport) - Ingestion of files from disk
- [RegEx Codec](https://github.com/SoftwareAG/apama-streaming-analytics-connectivity-RegExCodec) - RegEx operations on messages
- [Apache Pulsar Plugin](https://github.com/prabal77/ApachePulsarConnecitivityPlugin) - Connectivity Plugin for Apache Pulsar pub-sub system.

## EPL Plug-Ins
### C++
- [RaspberryPi GPIO](https://github.com/CallumAttryde/apama_GPIO) - For interfacing with the RaspberryPi on board GPIO
- [Random Plugin](https://github.com/mjj29/apama-random-plugin) - Random number generation plugin for statistical use (wraps STL random header)
- [Filesystem](https://github.com/CallumAttryde/apama_file_plugin) - Filesystem operations (r,w,ls,mv,cp,rm,etc.)

### Java

### Python
- [Configuration Plugin](https://github.com/mjj29/apama-configuration-plugin) - Allow EPL access to correlator configuration properties
- [MachineInformation](https://github.com/imog63/MachineInformation) - Exposes system information to EPL

## Hybrid Plug-Ins (C++ based mixed EPL & Connectivity Plug-Ins)
- [CSV Plugin](https://github.com/mjj29/apama-csv-plugin) - Translation of CSV format messages, with escaping and contentType checking for both plugins and connectivity codec
- [Base64 Codec](https://github.com/mjj29/apama-base64-plugin) - Translation of Base64-encoded data for both plugins and connectivity codec

## Frameworks and Libraries
- [RxEPL](https://github.com/SoftwareAG/apama-rxepl) - The ReactiveX framework (Observables) implemented entirely in EPL
- [Action Binding](https://github.com/rpeach-sag/apama-action-binding) - JavaScript-esque action binding in EPL
- [Lambdas](https://github.com/SoftwareAG/apama-lambdas) - Lambdas for EPL

## Utilities and Tools
- [PySys](https://sourceforge.net/projects/pysys/) - Cross platform system/unit testing, recommended for use when testing Apama applications. Many Apama centric extensions available. Included in install.
- [Aunit](https://github.com/antoinewaugh/aunit) - EPL annotation-based unit testing. Leverages PySys framework.

## Docker
- [Correlator Images](https://hub.docker.com/_/apama-correlator) - Official images of the Apama Correlator hosted on Docker Store.
- [Correlator Builder Image](https://hub.docker.com/_/softwareag-apama-builder) - Official image for building Apama projects into new images via multi-stage builds.
- [AWS Marketplace](https://aws.amazon.com/marketplace/pp/B07KBHJ5NL?qid=1547210773784&sr=0-1&ref_=srh_res_product_title) - Images on Amazon Marketplace.

## IDE Extensions
- [Notepad++](https://github.com/rpeach-sag/apama-notepad-syntax)
- [vscode](https://github.com/CaribouJohn/vscode-apama-extensions) - Install from vscode (search extensions for 'EPL') 

## Tutorials

## Misc.
- [Game of Life](https://github.com/nmfa/apama_life.git) - A basic Game of Life using the Dashboards for display.


------------------------------
These tools are provided as-is and without warranty or support. They do not constitute part of the Software AG product suite. Users are free to use, fork and modify them, subject to the license agreement. While Software AG welcomes contributions, we cannot guarantee to include every contribution in the master project.
