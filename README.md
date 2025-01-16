<p align="center">
  <img src="https://i.imgur.com/LtUGnF3.png" width=500 />
</p>

<div align="center">
  <a href="https://github.com/sundowndev/PhoneInfoga/actions">
    <img src="https://img.shields.io/endpoint.svg?url=https://actions-badge.atrox.dev/sundowndev/PhoneInfoga/badge?ref=master" alt="build status" />
  </a>
  <a href="https://goreportcard.com/report/github.com/sundowndev/PhoneInfoga">
    <img src="https://goreportcard.com/badge/github.com/sundowndev/PhoneInfoga" alt="go report" />
  </a>
  <a href="https://codeclimate.com/github/sundowndev/PhoneInfoga/maintainability">
    <img src="https://api.codeclimate.com/v1/badges/3259feb1c68df1cd4f71/maintainability" />
  </a>
  <a href="https://codecov.io/gh/sundowndev/PhoneInfoga">
    <img src="https://codecov.io/gh/sundowndev/PhoneInfoga/branch/master/graph/badge.svg" />
  </a>
  <a href="https://github.com/sundowndev/PhoneInfoga/releases">
    <img src="https://img.shields.io/github/release/SundownDEV/PhoneInfoga.svg" alt="Latest version" />
  </a>
</div>

<h4 align="center">Advanced information gathering & OSINT framework for phone numbers</h4>

# ⚠️ Disclaimer

> **This software is an open-source project developed for the community and is not affiliated with any organization or institution.**  
> It is shared purely for **educational purposes**, software development testing, and to contribute to the growth of the open-source community.

---

### ⚖️ Legal Responsibility
By using this software, you agree that:
- **All responsibility lies with you, the user.**
- The platform and its contributors provide this software **"as is"**, without any warranty of any kind, express or implied.  
  This includes, but is not limited to, the warranties of **merchantability**, **fitness for a particular purpose**, or **non-infringement**.  

> ⚠️ **Use it at your own risk.**

---

### 🎯 Intended Use
The primary purpose of this project is to:
- Educate the community by sharing open-source code.
- Facilitate learning and encourage innovation through open collaboration.

❌ **This software is not intended for production use.**  
We strongly recommend purchasing and using professionally licensed software for your needs.

---

### 🙌 Support the Community
If you would like to support the community and this project, consider making a donation:  
[![Donate](https://img.shields.io/badge/Donate-Click%20Here-orange?style=for-the-badge&logo=paypal)](https://ubd.one/donate)

---

### 🚨 Report Abuse
If you encounter any abuse or misuse of this software, please report it to:  
📧 **[abuse@ubden.com](mailto:abuse@ubden.com)**

---

> Thank you for being a part of the open-source community! 🌟


<p align="center">
  <a href="https://sundowndev.github.io/PhoneInfoga/">Documentation</a> •
  <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/sundowndev/PhoneInfoga/master/api/openapi.yml">API documentation</a> •
  <a href="https://demo.phoneinfoga.crvx.fr/">Demo instance</a> •
  <a href="https://medium.com/@SundownDEV/phone-number-scanning-osint-recon-tool-6ad8f0cac27b">Related blog post</a>
</p>

![](./docs/images/screenshot.png)

## About

PhoneInfoga is an information gathering framework for phone numbers that uses only free resources. This tool might not be able to recover your name or address by scanning your number (fortunately), anyway, that is not the purpose. The goal is to provide an easy way to investigate and parse information from any phone number.

**This project is under active development. Numverify scan does not work on demo instance because my server's IP got blocked. [Roadmap is here](https://github.com/sundowndev/PhoneInfoga/projects/1)**

## Current status

This project has recently been rewritten in Go language. Why ? To improve code base, maintainability, have a stronger test suite and be able to compile code base. PhoneInfoga v2 brings new features such as serving a REST API and a web client. Usage of scanners was improved in order to drop usage of Selenium/Geckodriver which has cause many users to have troubleshoots using the tool. You can still use the legacy version in [tag v1.11](https://github.com/sundowndev/PhoneInfoga/tree/v1.11) and the legacy Docker image (`sundowndev/phoneinfoga:legacy`). Some features were not included in the v2 MVP such as input/output CLI options. The roadmap of the project changed so we can focus on the web client features such as downloading scan results as CSV, Instagram/Whatsapp lookup, and more.

## Features

- Check if phone number exists and is possible
- Gather standard informations such as country, line type and carrier
- OSINT footprinting using external APIs, Google Hacking, phone books & search engines
- Check for reputation reports, social media, disposable numbers and more
- Scan several numbers at once
- Use custom formatting for more effective OSINT reconnaissance
- **NEW**: Serve a web client along with a REST API to run scans from the browser
- **NEW**: Run your own web instance as a service
- **NEW**: Programmatic usage with Go modules

## Anti-features

- Does not claim to provide relevant or verified data, it's just a tool !
- Does not allow to "track" a phone or its owner in real time
- Does not allow to get the precise phone location
- Does not allow to hack a phone

![Footprinting process](https://i.imgur.com/qCkgzz8.png)

## License

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Fsundowndev%2FPhoneInfoga.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Fsundowndev%2FPhoneInfoga?ref=badge_shield)

This tool is licensed under the GNU General Public License v3.0.

[Icon](https://www.flaticon.com/free-icon/fingerprint-search-symbol-of-secret-service-investigation_48838) made by <a href="https://www.freepik.com/" title="Freepik">Freepik</a> from <a href="https://www.flaticon.com/" title="Flaticon">flaticon.com</a> is licensed by <a href="http://creativecommons.org/licenses/by/3.0/" title="Creative Commons BY 3.0" target="_blank">CC 3.0 BY</a>.
