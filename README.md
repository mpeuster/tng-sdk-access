[![Join the chat at https://gitter.im/5gtango/tango-sdk](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/5gtango/tango-sdk)


# tng-sdk-access

This repository contains the `tng-sdk-sccess` component that is part of the European H2020 project [5GTANGO](http://www.5gtango.eu) NFV SDK. This component is responsible to upload 5GTANGO packages and to access 5GTANGO catalogs, service platforms, and V&Vs.

The seed code of this component is based on the `son-cli` toolbox that was developed as part of the European H2020 project [SONATA](http://sonata-nfv.eu).

## Installation

```bash
$ git clone https://github.com/sonata-nfv/tng-sdk-access.git
```

## Usage

```bash
# 5GTANGO
tng-onboard <url> <package_file>

# OSM
tng-onboard-osm <url> <package_file>
```

## Examples

```bash
# on-board to 5GTANGO
tng-onboard https://sta-vnv-ath-v4-0.5gtango.eu eu.5gtango.ns-squid-haproxy.0.1.tgo

# on-board to OSM
tng-onboard-osm http://osm-host.de eu.5gtango.ns-squid-haproxy.0.1.tgo
```

## Development

To contribute to the development of this 5GTANGO component, you may use the very same development workflow as for any other 5GTANGO Github project. That is, you have to fork the repository and create pull requests.


### CI Integration

All pull requests are automatically tested by Jenkins and will only be accepted if no test is broken.


## License

This 5GTANGO component is published under Apache 2.0 license. Please see the LICENSE file for more details.

---
#### Lead Developers

The following lead developers are responsible for this repository and have admin rights. They can, for example, merge pull requests.

- Kostantinos Douloudis (?)
- Manuel Peuster ([@mpeuster](https://github.com/mpeuster))
- Stefan Schneider ([@StefanUPB](https://github.com/StefanUPB))

#### Feedback-Chanel

* Please use the GitHub issues to report bugs.
