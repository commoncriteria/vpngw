
PP-Module for Virtual Private Network (VPN) Clients
===============
![Build](https://github.com/commoncriteria/vpnclient/workflows/Build/badge.svg)
![Validate](https://github.com/commoncriteria/vpnclient/workflows/Validate/badge.svg)
[![GitHub issues Open](https://img.shields.io/github/issues/commoncriteria/vpnclient.svg?maxAge=2592000)](https://github.com/commoncriteria/vpnclient/issues) 
![license](https://img.shields.io/badge/license-Unlicensed-blue.svg)

This repository hosts the draft version of the PP-Module for Virtual Private Network (VPN) Clients based on the 
[Essential Security Requirements (ESR)](https://commoncriteria.github.io/pp/vpnclient/vpnclient-esr.html) for this technology class of 
products. This repository is used to facilitate collaboration and development on the draft document. 
See the [release](#Release-Version) section if you are looking for the officially released version for evaluations. 
A list of products that have passed evaluation against this Protection Profile can be found [here](https://www.niap-ccevs.org/Product/PCL.cfm?ID624=34).

## Draft Version

* [PP-Module for Virtual Private Network (VPN) Gateways](https://commoncriteria.github.io/pp/vpnclient/vpngw-release.html) (html)
* [PP-Module for Virtual Private Network (VPN) Gateways](https://commoncriteria.github.io/pp/vpnclient/vpngw-release.pdf) (pdf)
* [Supporting Documents for Virtual Private Network (VPN) Gateways](https://commoncriteria.github.io/pp/vpngw/vpnclient-sd.html) (html)
* [Supporting Documents for Virtual Private Network (VPN) Gateways](https://commoncriteria.github.io/pp/vpngw/vpnclient-sd.pdf) (pdf)

## Combined Module/SD Version
* [PP-Module for Virtual Private Network (VPN) Gateways](https://commoncriteria.github.io/pp/vpnclient/vpngw.html) (html)

## Release Version
* [PP-Module for Virtual Private Network (VPN) Gateways](VPN Module)

## Contributing

If you are interested in contributing directly to future versions the this Protection Profile, please consider joining the NIAP technical community.
* [How to join the NIAP Technical Community (Mailing list and updates)](https://www.niap-ccevs.org/NIAP_Evolution/tech_communities.cfm)

## Feedback

Questions, comments, and fixes can be submitted to the [repository issue tracker](https://github.com/commoncriteria/vpngw/issues)

## Quickstart
To clone this project along with its _transforms_ submodule run:

````
  git clone --recursive git@github.com:commoncriteria/vpngw.git
````
To pull updates from the upstream _transforms_ submodule and commit them run:
````
 git submodule update --remote transforms
 git add transforms
 git commit
````

### Development Info
[Help working with Transforms Submodule](https://github.com/commoncriteria/transforms/wiki/Working-with-Transforms-as-a-Submodule)

## Repository Content
* input - Contains the 'meat' of the project. It's the input content (in XML form) that gets transformed to readable html.
* output - The output directory where the html is placed after transformation.
* output/images - The directory where images are stored
* transforms - Points to the transform subproject which is really a repository for resources shared amongst many Common Criteria projects.

## Links 
* [National Information Assurance Partnership (NIAP)](https://www.niap-ccevs.org/)
* [Common Criteria Portal](https://www.commoncriteriaportal.org/)

## License
See [License](./LICENSE)
