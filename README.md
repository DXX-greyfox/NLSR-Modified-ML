# NLSR-Modified-ML: NLSR Enhanced with Basic Machine Learning Algorithms

![Latest version](https://img.shields.io/github/v/tag/DXX-greyfox/NLSR-Modified-ML?label=Latest%20version)
![Language](https://img.shields.io/badge/C%2B%2B-17-blue)
![Status](https://img.shields.io/badge/Status-Testing%20%26%20Debugging-orange)
![ML Enhancement](https://img.shields.io/badge/Enhancement-Machine%20Learning-green)

> [!TIP]
> This is a modified version of NLSR with machine learning enhancements. For the original NLSR documentation, visit the [NLSR homepage](https://docs.named-data.net/NLSR/current/).

## Overview

NLSR-Modified-ML is an enhanced version of the Named Data Link State Routing (NLSR) protocol that incorporates basic machine learning algorithms for dynamic network optimization. This project is built upon the original [NLSR implementation](https://github.com/named-data/NLSR) developed by the Named Data Networking Project.

**Original NLSR Functionality:**
The original NLSR is a routing protocol for Named Data Networking (NDN) that populates the Routing Information Base (RIB) of an NDN router, such as [NFD](https://github.com/named-data/NFD). NLSR calculates the routing table using link-state or hyperbolic routing and produces multiple faces for each reachable name prefix in a single authoritative domain.

**Key Modifications and Enhancements:**

This modified version introduces significant enhancements to the original NLSR implementation:

- **Link Cost Manager Module**: Integration of a `link-cost-manager` function module that enables dynamic adjustment of link costs based on real-time network conditions
- **Machine Learning Integration**: Implementation of basic machine learning algorithms to intelligently optimize link cost calculations and routing decisions  
- **Dynamic Network Adaptation**: Enhanced capability for the routing protocol to adapt to changing network conditions through learned patterns and predictive modeling

**Current Development Status:**

This project is currently in the **testing and debugging phase**. The implemented features are being thoroughly evaluated in controlled virtual machine environments to ensure stability and performance improvements over the baseline NLSR implementation.

## Source releases

The source code and installation instructions are available at the following locations:

- [Installation](https://docs.named-data.net/NLSR/current/INSTALL.html) *(Original NLSR installation guide)*
- [Getting started with NLSR](https://docs.named-data.net/NLSR/current/GETTING-STARTED.html) *(Original NLSR getting started guide)*
- [Original NLSR GitHub repository](https://github.com/named-data/NLSR)
- [This Modified Version Repository](https://github.com/DXX-greyfox/NLSR-Modified-ML)

## Reporting bugs

For bugs related to the machine learning modifications, please submit bug reports or feature requests to this repository's [Issues page](https://github.com/DXX-greyfox/NLSR-Modified-ML/issues).

For bugs related to the original NLSR functionality, please submit them to the [Original NLSR issue tracker](https://redmine.named-data.net/projects/nlsr/issues).

## Additional resources

**Original NLSR Resources:**
- [Contributor's Guide](https://github.com/named-data/.github/blob/main/CONTRIBUTING.md)
- [NLSR Wiki](https://redmine.named-data.net/projects/nlsr/wiki)
- [NLSR Issue Tracker](https://redmine.named-data.net/projects/nlsr/issues)
- [NLSR Mailing List Sign Up](https://listserv.memphis.edu/scripts/wa.exe?GETPW1)
- [NLSR Mailing List](https://listserv.memphis.edu/scripts/wa.exe?SUBED1=NLSR-HELP-L&A=1)
- [NLSR Mailing List Archives](https://listserv.memphis.edu/scripts/wa.exe?A0=NLSR-HELP-L)
- [NLSR Developer's guide](https://github.com/named-data/NLSR/blob/developers-guide/NLSR-Developers-Guide.pdf)

## Acknowledgments

This project is built upon and respectfully modifies the original NLSR implementation developed by the Named Data Networking Project team. We express our sincere gratitude to the original developers and contributors for their foundational work.

**Original Project Credits:**
- Named Data Networking Project: [https://named-data.net/](https://named-data.net/)
- Original NLSR Repository: [https://github.com/named-data/NLSR](https://github.com/named-data/NLSR)
- NLSR was mainly developed by members of the NSF-sponsored [NDN project](https://named-data.net/project/participants/). See [`AUTHORS.md`](https://github.com/named-data/NLSR/blob/master/AUTHORS.md) for details.

**Important Disclaimer:**
- This is a **modified and experimental version** developed for **research and educational purposes**
- The modifications are experimental and include machine learning enhancements still under development and testing
- All improvements are built respectfully upon the original NLSR codebase
- This work aims to contribute to the advancement of adaptive routing protocols in NDN environments

## License

NLSR-Modified-ML inherits the same license as the original NLSR project.

NLSR is free software distributed under the GNU General Public License version 3.
See [`COPYING.md`](COPYING.md) for details.

NLSR contains third-party software, licensed under the following licenses:

- The *waf* build system is licensed under the [3-clause BSD license](waf)

## Citation

If you use this modified version in your research, please cite both the original NLSR work and acknowledge this modification:

```
Original NLSR Project:
Named Data Networking Project. "NLSR: Named Data Link State Routing Protocol."
https://github.com/named-data/NLSR

Modified Version:
NLSR-Modified-ML: NLSR Enhanced with Basic Machine Learning Algorithms.
https://github.com/DXX-greyfox/NLSR-Modified-ML
```
