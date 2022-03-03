<p align="center">
  <a href="https://www.dyne.org">
    <img alt="{project_name}" src="https://via.placeholder.com/150.png?text=LOGO" width="150" />
  </a>
</p>

<h1 align="center">
  {project_name}</br>
  <sub>{tagline}</sub>
</h1>

<p align="center">
  <a href="https://travis-ci.com/DECODEproject/{project_name}">
    <img src="https://travis-ci.com/DECODEproject/{project_name}.svg?branch=master" alt="Build Status">
  </a>
  <a href="https://dyne.org">
    <img src="https://img.shields.io/badge/%3C%2F%3E%20with%20%E2%9D%A4%20by-Dyne.org-blue.svg" alt="Dyne.org">
  </a>
</p>

<br><br>

<h4 align="center">
  <a href="#-install">💾 Install</a>
  <span> • </span>
  <a href="#-quick-start">🎮 Quick start</a>
  <span> • </span>
  <a href="#-docker">🐋 Docker</a>
  <span> • </span>
  <a href="#-api">🐝 API</a>
  <span> • </span>
  <a href="#-configuration">🔧 Configuration</a>
  <span> • </span>
  <a href="#-testing">📋 Testing</a>
  <span> • </span>
  <a href="#-troubleshooting--debugging">🐛 Troubleshooting & debugging</a>
  <span> • </span>
  <a href="#-acknowledgements">😍 Acknowledgements</a>
  <span> • </span>
  <a href="#-links">🌐 Links</a>
  <span> • </span>
  <a href="#-contributing">👤 Contributing</a>
  <span> • </span>
  <a href="#-license">💼 License</a>
</h4>


Abstract description like: 🚧 Zenroom is a software in **ALPHA stage** and are part of the [DECODE project](https://decodeproject.eu) about data-ownership and [technological sovereignty](https://www.youtube.com/watch?v=RvBRbwBm_nQ). Our effort is that of improving people's awareness of how their data is processed by algorithms, as well facilitate the work of developers to create along [privacy by design principles](https://decodeproject.eu/publications/privacy-design-strategies-decode-architecture) using algorithms that can be deployed in any situation without any change.


<details id="toc">
 <summary><strong>🚩 Table of Contents</strong> (click to expand)</summary>

* [Install](#-install)
* [Quick start](#-quick-start)
* [Docker](#-docker)
* [API](#-api)
* [Configuration](#-configuration)
* [Testing](#-testing)
* [Troubleshooting & debugging](#-troubleshooting--debugging)
* [Acknowledgements](#-acknowledgements)
* [Links](#-links)
* [Contributing](#-contributing)
* [License](#-license)
</details>


## Objective

1. Scope of Testing.

The scope of the testing is the Zenbridge end to end functionalities and features, tested in a lab testing environment

2. What is out of scope of Testing.

This does not want to cover the integration with EPIC nor the EBSI infrastructure for now that is out of scope in the 2a phase

3. What are the test objectives.

To proof solidity and reliability of the solution, the integration of the components, performance auditing ans assessments of the Zenbridge solution in particular

    1. Find the defects
    2. Verify that the software meets the requirements
    3. Improve software quality
    4. Minimize the maintenance and software support costs and infrastructure
    5. Avoid post deployment risks
    6. Compliance with processes

5. What are the project deadlines.
This is the plan for the coming next 4 months

6. What is the test execution schedule.
Execution is drafted in detail in the document

7. What are the project risks.
Risky parts of the product rely on:

  * faulty data injection handling
  * performance
  * interoperability of the blockchains
  * swarm of oracles
  * consensus
  * data sharding and replication

8. Deliverables
For each component the following deliverable are considered (based on the type of component some deliverable will not be valid)
 * Test cases Documents
 * Test Plan for each component
 * Testing Strategy
 * Test Scripts
 * Test Results/reports
 * Test summary report
 * Defect Report

## Masterlpan

Our masterplan involves a first run of testin gin [White-Box Testing](https://en.wikipedia.org/wiki/White-box_testing) mode, which lead to the firs two levels of testing:
 1. Unit testing
 2. Integration testing

most of our software components, already have them in place (with high percentage of code coverage)

Each component (depending of the tech stack) uses different testing tools that will be covered in deep in the following sections.

The second step of our plan involves [Non-functional testing](https://en.wikipedia.org/wiki/Non-functional_testing) that focuses more on proof the reliability of Zenbridge. In detail:

* Load testing
* Stress Testing
* Performance Testing
* Security testing

The third phase of the masterplan is the report generation of the results, by writing each Result reports of the executed tests and a summary report of the previous that includes all the defects and resolutions adopted.

### Methodology

The methodology is binded to to our SDLC (Softeare development lifecycle) that is an iterative approach:
 1. Testplanning
 1. test case and scenarios
 1. reporting
 1. verification/validation
 1. automated test
 1. restart the cycle from point 3

## Zenbrige components

As previously described all the componente of the zenbridge stack will be tested.
The testing tools for the automated tests are covered in detail as below.

### Consensusroom

The oracle swarm prototype:
  * Ansible tests (checking complitaion sanity and integration tests and unit tests)
  * Shell script tests to cover the zencode
  * and Rest API validation with http mock servers

### Fabchain

ganache
/
truffle


### Zenswarm
The  zenswarm prototype:
  * Ansible tests (checking complitaion sanity and integration tests and unit tests)
  * Shell script tests to cover the zencode
  * and Rest API validation with http mock servers

***
## 💾 Install
```pip install / yard add {project_name}```


***
## 🎮 Quick start

To start using {project_name} just (fill with real documentation)

***
## 🐋 Docker

```bash
docker build -t {project_name} .
docker run --rm -it {project_name}
```

**[🔝 back to top](#toc)**

***
## 🐝 API

**[🔝 back to top](#toc)**

***
## 🔧 Configuration

**[🔝 back to top](#toc)**

***

## 📋 Testing

**[🔝 back to top](#toc)**

***
## 🐛 Troubleshooting & debugging

**[🔝 back to top](#toc)**

***
## 😍 Acknowledgements

[![software by Dyne.org](https://files.dyne.org/software_by_dyne.png)](http://www.dyne.org)

Copyleft (ɔ) 2021 by [Dyne.org](https://www.dyne.org) foundation, Amsterdam

Designed, written and maintained by Puria Nafisi Azizi.

Special thanks to Mr. W. White for his special contributions.

**[🔝 back to top](#toc)**

***
## 🌐 Links

https://www.somelink.io/

https://dyne.org/

**[🔝 back to top](#toc)**

***
## 👤 Contributing

Please first take a look at the [Dyne.org - Contributor License Agreement](CONTRIBUTING.md) then

1.  🔀 [FORK IT](../../fork)
2.  Create your feature branch `git checkout -b feature/branch`
3.  Commit your changes `git commit -am 'Add some fooBar'`
4.  Push to the branch `git push origin feature/branch`
5.  Create a new Pull Request
6.  🙏 Thank you


**[🔝 back to top](#toc)**

***
## 💼 License
    {project_name} - {tagline}
    Copyleft (ɔ) 2021 Dyne.org foundation, Amsterdam

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU Affero General Public License as
    published by the Free Software Foundation, either version 3 of the
    License, or (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU Affero General Public License for more details.

    You should have received a copy of the GNU Affero General Public License
    along with this program.  If not, see <http://www.gnu.org/licenses/>.

**[🔝 back to top](#toc)**
