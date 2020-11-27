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
- [Max Size Codec](https://github.com/mjj29/apama-maxsize-codec) - A simple outbound threshold check for message size to avoid sending anything larger than the transport can handle.

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
- [L10N](https://github.com/mjj29/apama-epl-l10n-plugin) - Translation of EPL apps using GNU gettext
- [JEMalloc](https://github.com/mjj29/apama-jemalloc-plugin) - JEMalloc memory stats for a JEMalloc-enabled correlator

### Java

### Python
- [Configuration Plugin](https://github.com/mjj29/apama-configuration-plugin) - Allow EPL access to correlator configuration properties
- [MachineInformation](https://github.com/imog63/MachineInformation) - Exposes system information to EPL
- [Kasa](https://github.com/mjj29/apama-kasa-plugin) - EPL plugin for talking to TP Link Kasa smart plugs

## Hybrid Plug-Ins (C++ based mixed EPL & Connectivity Plug-Ins)
- [CSV Plugin](https://github.com/mjj29/apama-csv-plugin) - Translation of CSV format messages, with escaping and contentType checking for both plugins and connectivity codec

## Frameworks and Libraries
- [RxEPL](https://github.com/SoftwareAG/apama-rxepl) - The ReactiveX framework (Observables) implemented entirely in EPL
- [Action Binding](https://github.com/rpeach-sag/apama-action-binding) - JavaScript-esque action binding in EPL
- [Lambdas](https://github.com/SoftwareAG/apama-lambdas) - Lambdas for EPL
- [Industry Analytics Kit](https://github.com/SoftwareAG/apama-industry-analytics-kit) - A set of analytic microservices used to accelerate the development of Industry/IoT applications
- [Complex numbers](https://github.com/mjj29/apama-epl-complex) - EPL event for complex number operations in EPL.
- [Container types](https://github.com/mjj29/apama-epl-containers) - EPL containers including Heap, Stack, Queue etc.
- [Functional operators](https://github.com/mjj29/apama-epl-functional) - EPL libraries for map/reduce and other functional operators, generators and partial function evalution

## Utilities and Tools
- [GitHub Actions workflow for Apama](https://github.com/ApamaCommunity/.github) - A starter workflow (and associated setup-apama action) for building and testing Apama applications and plugins using GitHub Actions. 
- [PySys](https://pysys-test.github.io/pysys-test/) - Cross platform system/unit testing, recommended for use when testing Apama applications. Many Apama centric extensions available. Included in install.
- [Apama log Analyzer](https://github.com/ApamaCommunity/apama-log-analyzer) - A script for analyzing Apama correlator log files, and graphing key metrics.
- [Aunit](https://github.com/antoinewaugh/aunit) - EPL annotation-based unit testing. Leverages PySys framework.

## Docker
- [Correlator Images](https://hub.docker.com/_/apama-correlator) - Official images of the Apama Correlator hosted on Docker Store.
- [Correlator Builder Image](https://hub.docker.com/_/softwareag-apama-builder) - Official image for building Apama projects into new images via multi-stage builds.
- [AWS Marketplace](https://aws.amazon.com/marketplace/pp/B07KBHJ5NL?qid=1547210773784&sr=0-1&ref_=srh_res_product_title) - Images on Amazon Marketplace.

## IDE Extensions
- [Notepad++](https://github.com/rpeach-sag/apama-notepad-syntax).
- [VSCode](https://marketplace.visualstudio.com/items?itemName=CaribouJohn.apama-extensions) - Visual Studio Code extension to editing EPL files.

## Tutorials

## Misc.
- [Game of Life](https://github.com/nmfa/apama_life.git) - A basic Game of Life using the Dashboards for display.
- [Sample Grafana Dashboards](https://github.com/ChrisF999/Apama-Dashboard) - A demonstration of both system and application dashboards via Grafana and Prometheus


------------------------------
These tools are provided as-is and without warranty or support. They do not constitute part of the Software AG product suite. Users are free to use, fork and modify them, subject to the relevant license agreement(s). While Software AG welcomes contributions, we cannot guarantee to include every contribution in the master project.
