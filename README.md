<p align="center">
   <img width="800" src="https://raw.githubusercontent.com/SvenTiigi/SwiftPlaygroundsCLI/gh-pages/readme-assets/SwiftPlaygroundsCLI.png" alt="SwiftPlaygroundsCLI Header Logo">
</p>

<p align="center">
   <a href="https://developer.apple.com/swift/">
      <img src="https://img.shields.io/badge/Swift-5.1-orange.svg?style=flat" alt="Swift 5.1">
   </a>
   <a href="https://github.com/SvenTiigi/SwiftPlaygroundsCLI/actions?query=workflow%3ACI">
      <img src="https://github.com/SvenTiigi/SwiftPlaygroundsCLI/workflows/CI/badge.svg" alt="CI Status">
   </a>
   <a href="https://github.com/SvenTiigi/SwiftPlaygroundsCLI/releases">
      <img src="https://img.shields.io/github/release/SvenTiigi/SwiftPlaygroundsCLI.svg" alt="Version">
   </a>
   <a href="https://sventiigi.github.io/SwiftPlaygroundsCLI">
      <img src="https://github.com/SvenTiigi/SwiftPlaygroundsCLI/blob/gh-pages/badge.svg" alt="Documentation">
   </a>
   <br/>
   <a href="https://github.com/yonaskolb/Mint">
      <img src="https://img.shields.io/badge/Mint-compatible-brightgreen.svg" alt="Mint">
   </a>
   <a href="https://brew.sh">
      <img src="https://img.shields.io/badge/Homebrew-compatible-brightgreen.svg" alt="brew">
   </a>
   <a href="https://twitter.com/SvenTiigi/">
      <img src="https://img.shields.io/badge/Twitter-@SvenTiigi-blue.svg?style=flat" alt="Twitter">
   </a>
</p>

<br/>

<p align="center">
   Easily generate Swift Playgrounds from your command line
   <br/>
   for the new <a href="https://apps.apple.com/de/app/swift-playgrounds/id1496833156?mt=12">Playgrounds</a> App on macOS 👨‍💻
</p>

<p align="center">
   <img src="https://raw.githubusercontent.com/SvenTiigi/SwiftPlaygroundsCLI/gh-pages/readme-assets/Demo.png" width="90%" alt="Demo">
</p>

## Features

- [x] Easily generate and instantly open Swift Playgrounds
- [x] Generate Playground with SwiftUI template
- [x] Open code from GitHub in a Swift Playground

## Installation

### Mint 🌱

[Mint](https://github.com/yonaskolb/Mint) is a package manager that installs and runs Swift command line tool packages.

```bash
$ mint install SvenTiigi/SwiftPlaygroundsCLI
```

### Homebrew 🍺

[Homebrew](https://brew.sh/) is a free and open-source software package management system that simplifies the installation of software on Apple's macOS operating system.

```bash
$ brew tap SvenTiigi/SwiftPlaygroundsCLI
$ brew install swiftplaygroundscli
```

## Usage 👨‍💻

To generate a new Swift Playground simply run:

```bash
$ swiftplayground new
```

If you wish to specify a name for the Playground run:

```bash
$ swiftplayground new MyAwesomePlayground
```

To generate a Playground with a SwiftUI template run:

```bash
$ swiftplayground new --view
```

<p align="center">
   <img src="https://raw.githubusercontent.com/SvenTiigi/SwiftPlaygroundsCLI/gh-pages/readme-assets/ViewOptionDemo.png" alt="View Option Demo">
</p>

A Playground with contents from a GitHub URL can be generated via:

```bash
$ swiftplayground new --url https://gist.github.com/SvenTiigi/7eae5e55edd9be41211470fcbd937285
```

<p align="center">
   <img src="https://raw.githubusercontent.com/SvenTiigi/SwiftPlaygroundsCLI/gh-pages/readme-assets/RemoteOptionDemo.png" alt="Remote Option Demo">
</p>


## Arguments

A list of the available arguments that are supported by the SwiftPlaygroundsCLI.

| Long parameter | Short parameter | Description
| ----------- | ----------- | -------------- |
| `--view` | `-v` | Generate a Playground with a SwiftUI template |
| `--url` | `-u` | Generate a Playground with contents from a URL |
| `--silent` | `-s` | Generate a Playground without opening the Playgrounds application |

## Contributing
Contributions are very welcome 🙌 🤓

## Credits
SwiftPlaygroundsCLI is inspired by [`Playground`](https://github.com/JohnSundell/Playground) from [JohnSundell](https://twitter.com/johnsundell)

## License

```
SwiftPlaygroundsCLI
Copyright (c) 2020 Sven Tiigi <sven.tiigi@gmail.com>

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
```
