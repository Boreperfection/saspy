# A Python interface to MVA SAS
## Overview
This module creates a bridge between Python and SAS 9.4. This module enables a Python developer, familiar with Pandas dataframes or SAS datasets,
to leverage the power of SAS by connecting a Python process to a SAS 9.4 installation, where it will run SAS code. The SAS code is generated by the
supplied Python object and Python methods or explicitly user written. Results from SAS are returned as text, HTML5 documents (via SAS ODS), or as
Pandas Data Frames. This module supports running analytics and returning the resulting graphics and result data to the Python process. It can convert
data representations between SAS Data Sets and Pandas Data Frames. 

This module has multiple access methods which allow it to connect to local or remote Linux SAS, IOM SAS on Windows, Linux (Including Grid Manager),
or MVS, and local PC SAS. It can run within Jupyter Notebooks, in interactive line mode python or in python batch scripts. 

It is expected that the user community can, and will, contribute enhancements. 

# Prerequisites
- Python3.x or above
- SAS 9.4 or above

# Connecting offering
- Linux SAS: local or remote, including Grid Manager
- Windows SAS: local or remote
- MVS SAS: remote
- Jupyter Notebooks
- Interactive Line mode
- Batch Python scripts

# Installation

This module can be installed via pip. This will pull down the latest PyPI package and install it.

    pip install saspy

However, if that's too easy, you can also download a specific release from
[SASpy project releases page](https://github.com/sassoftware/saspy/releases), or just clone
the repo and and instll from that. To install a given release, use the following, 
where the X.X.X is the release version you want.

    pip install https://github.com/sassoftware/saspy/archive/vX.X.X.tar.gz

# Getting Started     

All of the doc, including install and configuration information can be found at
[sassoftware.github.io/saspy](https://sassoftware.github.io/saspy/).

Also, example Notebooks and use cases can be found at
[sassoftware/saspy-examples](https://github.com/sassoftware/saspy-examples/).   

# Contributing
The [Contributing](https://github.com/sassoftware/saspy/blob/master/CONTRIBUTING.md) file explains the rules and conventions to follow while
Contributing to this project. It also contains the **Contributor Agreement** instructions.

# Licensing 
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of
the License at [LICENSE.txt](https://github.com/sassoftware/saspy/blob/master/LICENSE) 

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES
OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

# Additional Resources
- [Python Website](http://www.python.org/)
- [SASPy Documentation](https://sassoftware.github.io/saspy/).
- [SASPy Examples](https://github.com/sassoftware/saspy-examples) 
