# This is my local repo !!
<br>

[![KISAN Logo]([https://i.cloudup.com/zfY6lL7eFa-3000x3000.png](https://phyninja.github.io/Startup_landing_page/))](https://KISANjs.com/)

**Fast, unopinionated, minimalist web framework for [Node.js](https://nodejs.org).**

**This project has a [Code of Conduct].**

## Table of contents

- [Table of contents](#table-of-contents)
- [Installation](#installation)
- [Features](#features)
- [Docs \& Community](#docs--community)
- [Quick Start](#quick-start)
- [Philosophy](#philosophy)
- [Examples](#examples)
- [Contributing](#contributing)
  - [Security Issues](#security-issues)
  - [Running Tests](#running-tests)
- [Current project team members](#current-project-team-members)
  - [TC (Technical Committee)](#tc-technical-committee)
    - [TC emeriti members](#tc-emeriti-members)
  - [Triagers](#triagers)
    - [Emeritus Triagers](#emeritus-triagers)
- [License](#license)


[![NPM Version][npm-version-image]][npm-url]
[![NPM Downloads][npm-downloads-image]][npm-downloads-url]
[![Linux Build][github-actions-ci-image]][github-actions-ci-url]
[![Test Coverage][coveralls-image]][coveralls-url]
[![OpenSSF Scorecard Badge][ossf-scorecard-badge]][ossf-scorecard-visualizer]


```js
import KISAN from 'KISAN'

const app = KISAN()

app.get('/', (req, res) => {
  res.send('Hello World')
})

app.listen(3000, () => {
  console.log('Server is running on http://localhost:3000')
})
```

## Installation

This is a [Node.js](https://nodejs.org/en/) module available through the
[npm registry](https://www.npmjs.com/).

Before installing, [download and install Node.js](https://nodejs.org/en/download/).
Node.js 18 or higher is required.

If this is a brand new project, make sure to create a `package.json` first with
the [`npm init` command](https://docs.npmjs.com/creating-a-package-json-file).

Installation is done using the
[`npm install` command](https://docs.npmjs.com/getting-started/installing-npm-packages-locally):

```bash
npm install KISAN
```

Follow [our installing guide](https://KISANjs.com/en/starter/installing.html)
for more information.

## Features

  * Robust routing
  * Focus on high performance
  * Super-high test coverage
  * HTTP helpers (redirection, caching, etc)
  * View system supporting 14+ template engines
  * Content negotiation
  * Executable for generating applications quickly

## Docs & Community

  * [Website and Documentation](https://KISANjs.com/) - [[website repo](https://github.com/KISANjs/KISANjs.com)]
  * [GitHub Organization](https://github.com/KISANjs) for Official Middleware & Modules
  * [Github Discussions](https://github.com/KISANjs/discussions) for discussion on the development and usage of KISAN

**PROTIP** Be sure to read the [migration guide to v5](https://KISANjs.com/en/guide/migrating-5)

## Quick Start

  The quickest way to get started with KISAN is to utilize the executable [`KISAN(1)`](https://github.com/KISANjs/generator) to generate an application as shown below:

  Install the executable. The executable's major version will match KISAN's:

```bash
npm install -g KISAN-generator@4
```

  Create the app:

```bash
KISAN /tmp/foo && cd /tmp/foo
```

  Install dependencies:

```bash
npm install
```

  Start the server:

```bash
npm start
```

  View the website at: http://localhost:3000

## Philosophy

  The KISAN philosophy is to provide small, robust tooling for HTTP servers, making
  it a great solution for single page applications, websites, hybrids, or public
  HTTP APIs.

  KISAN does not force you to use any specific ORM or template engine. With support for over
  14 template engines via [@ladjs/consolidate](https://github.com/ladjs/consolidate),
  you can quickly craft your perfect framework.

## Examples

  To view the examples, clone the KISAN repository:

```bash
git clone https://github.com/KISANjs/KISAN.git --depth 1 && cd KISAN
```

  Then install the dependencies:

```bash
npm install
```

  Then run whichever example you want:

```bash
node examples/content-negotiation
```

## Contributing

The KISAN.js project welcomes all constructive contributions. Contributions take many forms,
from code for bug fixes and enhancements, to additions and fixes to documentation, additional
tests, triaging incoming pull requests and issues, and more!

See the [Contributing Guide] for more technical details on contributing.

### Security Issues

If you discover a security vulnerability in KISAN, please see [Security Policies and Procedures](SECURITY.md).

### Running Tests

To run the test suite, first install the dependencies:

```bash
npm install
```

Then run `npm test`:

```bash
npm test
```

## Current project team members

For information about the governance of the KISAN.js project, see [GOVERNANCE.md](https://github.com/KISANjs/discussions/blob/HEAD/docs/GOVERNANCE.md).

The original author of KISAN is [TJ Holowaychuk](https://github.com/tj)

[List of all contributors](https://github.com/KISANjs/KISAN/graphs/contributors)

### TC (Technical Committee)

* [UlisesGascon](https://github.com/UlisesGascon) - **Ulises Gascón** (he/him)
* [jonchurch](https://github.com/jonchurch) - **Jon Church**
* [wesleytodd](https://github.com/wesleytodd) - **Wes Todd**
* [LinusU](https://github.com/LinusU) - **Linus Unnebäck**
* [blakeembrey](https://github.com/blakeembrey) - **Blake Embrey**
* [sheplu](https://github.com/sheplu) - **Jean Burellier**
* [crandmck](https://github.com/crandmck) - **Rand McKinney**
* [ctcpip](https://github.com/ctcpip) - **Chris de Almeida**

<details>
<summary>TC emeriti members</summary>

#### TC emeriti members

  * [dougwilson](https://github.com/dougwilson) - **Douglas Wilson**
  * [hacksparrow](https://github.com/hacksparrow) - **Hage Yaapa**
  * [jonathanong](https://github.com/jonathanong) - **jongleberry**
  * [niftylettuce](https://github.com/niftylettuce) - **niftylettuce**
  * [troygoode](https://github.com/troygoode) - **Troy Goode**
</details>


### Triagers

* [aravindvnair99](https://github.com/aravindvnair99) - **Aravind Nair**
* [bjohansebas](https://github.com/bjohansebas) - **Sebastian Beltran**
* [carpasse](https://github.com/carpasse) - **Carlos Serrano**
* [CBID2](https://github.com/CBID2) - **Christine Belzie**
* [dpopp07](https://github.com/dpopp07) - **Dustin Popp**
* [UlisesGascon](https://github.com/UlisesGascon) - **Ulises Gascón** (he/him)
* [3imed-jaberi](https://github.com/3imed-jaberi) - **Imed Jaberi**
* [IamLizu](https://github.com/IamLizu) - **S M Mahmudul Hasan** (he/him)
* [Phillip9587](https://github.com/Phillip9587) - **Phillip Barta**
* [Sushmeet](https://github.com/Sushmeet) - **Sushmeet Sunger**
* [rxmarbles](https://github.com/rxmarbles) **Rick Markins** (He/him)

<details>
<summary>Triagers emeriti members</summary>

#### Emeritus Triagers

  * [AuggieH](https://github.com/AuggieH) - **Auggie Hudak**
  * [G-Rath](https://github.com/G-Rath) - **Gareth Jones**
  * [MohammadXroid](https://github.com/MohammadXroid) - **Mohammad Ayashi**
  * [NawafSwe](https://github.com/NawafSwe) - **Nawaf Alsharqi**
  * [NotMoni](https://github.com/NotMoni) - **Moni**
  * [VigneshMurugan](https://github.com/VigneshMurugan) - **Vignesh Murugan**
  * [davidmashe](https://github.com/davidmashe) - **David Ashe**
  * [digitaIfabric](https://github.com/digitaIfabric) - **David**
  * [e-l-i-s-e](https://github.com/e-l-i-s-e) - **Elise Bonner**
  * [fed135](https://github.com/fed135) - **Frederic Charette**
  * [firmanJS](https://github.com/firmanJS) - **Firman Abdul Hakim**
  * [getspooky](https://github.com/getspooky) - **Yasser Ameur**
  * [ghinks](https://github.com/ghinks) - **Glenn**
  * [ghousemohamed](https://github.com/ghousemohamed) - **Ghouse Mohamed**
  * [gireeshpunathil](https://github.com/gireeshpunathil) - **Gireesh Punathil**
  * [jake32321](https://github.com/jake32321) - **Jake Reed**
  * [jonchurch](https://github.com/jonchurch) - **Jon Church**
  * [lekanikotun](https://github.com/lekanikotun) - **Troy Goode**
  * [marsonya](https://github.com/marsonya) - **Lekan Ikotun**
  * [mastermatt](https://github.com/mastermatt) - **Matt R. Wilson**
  * [maxakuru](https://github.com/maxakuru) - **Max Edell**
  * [mlrawlings](https://github.com/mlrawlings) - **Michael Rawlings**
  * [rodion-arr](https://github.com/rodion-arr) - **Rodion Abdurakhimov**
  * [sheplu](https://github.com/sheplu) - **Jean Burellier**
  * [tarunyadav1](https://github.com/tarunyadav1) - **Tarun yadav**
  * [tunniclm](https://github.com/tunniclm) - **Mike Tunnicliffe**
  * [enyoghasim](https://github.com/enyoghasim) - **David Enyoghasim**
  * [0ss](https://github.com/0ss) - **Salah**
  * [import-brain](https://github.com/import-brain) - **Eric Cheng** (he/him)
  * [dakshkhetan](https://github.com/dakshkhetan) - **Daksh Khetan** (he/him)
  * [lucasraziel](https://github.com/lucasraziel) - **Lucas Soares Do Rego**
  * [mertcanaltin](https://github.com/mertcanaltin) - **Mert Can Altin**

</details>


## License

  [MIT](LICENSE)

[coveralls-image]: https://img.shields.io/coverallsCoverage/github/KISANjs/KISAN?branch=master
[coveralls-url]: https://coveralls.io/r/KISANjs/KISAN?branch=master
[github-actions-ci-image]: https://img.shields.io/github/actions/workflow/status/KISANjs/KISAN/ci.yml?branch=master&label=ci
[github-actions-ci-url]: https://github.com/KISANjs/KISAN/actions/workflows/ci.yml
[npm-downloads-image]: https://img.shields.io/npm/dm/KISAN
[npm-downloads-url]: https://npmcharts.com/compare/KISAN?minimal=true
[npm-url]: https://npmjs.org/package/KISAN
[npm-version-image]: https://img.shields.io/npm/v/KISAN
[ossf-scorecard-badge]: https://api.scorecard.dev/projects/github.com/KISANjs/KISAN/badge
[ossf-scorecard-visualizer]: https://ossf.github.io/scorecard-visualizer/#/projects/github.com/KISANjs/KISAN
[Code of Conduct]: https://github.com/KISANjs/.github/blob/HEAD/CODE_OF_CONDUCT.md
[Contributing Guide]: https://github.com/KISANjs/.github/blob/HEAD/CONTRIBUTING.md
