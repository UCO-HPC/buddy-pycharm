# Buddy OnDemand - PyCharm Community

[![GitHub Release](https://img.shields.io/github/v/release/UCO-HPC/buddy_pycharm?style=flat-square)](https://github.com/UCO-HPC/buddy_pycharm/blob/devel/CHANGELOG.md)
[![GitHub License](https://img.shields.io/github/license/UCO-HPC/buddy_pycharm?style=flat-square)](https://opensource.org/licenses/MIT)

An app designed for UCO's OnDemand that launches PyCharm Community Edition. 

## Prerequisites

The following should be made available on the compute nodes
- [PyCharm] 2019.3.1+
- [Xfce Desktop] 4+
- [TurboVNC] 2.2.3+
- [websockify] 0.6.0+

To get PyCharm running:

- [Python] 3.7.2+ (Use 2to3 for any Python2 code)
- [Anaconda3] 5.3.0+

For module support:

- [Lmod] 8.1.0+

[PyCharm]: https://www.jetbrains.com/pycharm/
[Xfce Desktop]: https://xfce.org/
[TurboVNC]: http://www.turbovnc.org/
[websockify]: https://github.com/novnc/websockify
[Python]: https://www.python.org/
[Anaconda3]: https://www.anaconda.com/
[Lmod]: https://www.tacc.utexas.edu/research-development/tacc-projects/lmod

## Installation

You can either use the "New App" feature in the Open OnDemand development tab, or clone this app directly to the /var/www/ood/apps/sys folder. 

## Contributing

Please note that this application is specific to our university. Please feel free to copy and use as needed according to the associated license. IF you discover a big during use, please feel free to create a new branch and submit a pull request. 

## License

* Code, documentation, and content are licensed under MIT (see LICENSE.txt) at this time. License is subject to change without notice. 
*PyCharm, JetBrains and all JetBrains s.r.o. brand, product, service and feature names, logos and slogans are trademarks or registered trademarks of JetBrains s.r.o. or its subsidiaries located in the United States or other countries.
*Anaconda and all Anaconda Inc. brand, product, service and feature names, logos and slogans are trademarks or registered trademarks of Anaconda Inc. or its subsidiaries located in the United States or other countries.
* OnDemand and it's source code are copyrighted by Ohio Supercomputer Center
