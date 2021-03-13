# Eleggo
> Eleggo is a programmable brain computer interface, which uses a modification of the OpenBCI Cyton board to complete tasks such as hand movement detection, directional thinking, etc.

<p align="center">
<img src="docs/promotional/Project Banner.png" alt="Project Banner">
</p>

<p align="center">
<a href="https://github.com/braind3d/Eleggo/fork">
<img src="https://img.shields.io/badge/contributions-welcome-brightgreen.svg?color=339C5E&style=flat-square" alt="Contributions welcome badge">
</a>

<a href="LICENSE">
<img src="https://img.shields.io/github/license/braind3d/eleggo?color=339C5E&style=flat-square" alt="License badge">
</a>
</p>

<p align="center">
<a href="https://github.com/braind3d/eleggo-ml/issues?q=is%3Aissue+is%3Aopen">
<img src="https://img.shields.io/github/issues-raw/braind3d/eleggo-ml?label=ml%20open%20issues&color=339C5E&style=flat-square" alt="ML Open issues status badge">
</a>

<a href="https://github.com/braind3d/eleggo-ml/issues?q=is%3Aissue+is%3Aclosed">
<img src="https://img.shields.io/github/issues-closed-raw/braind3d/eleggo-ml?label=ml%20closed%20issues&color=339C5E&style=flat-square" alt="Closed issues status badge">
</a>

<a href="https://github.com/braind3d/eleggo-server/issues?q=is%3Aissue+is%3Aopen">
<img src="https://img.shields.io/github/issues-raw/braind3d/eleggo-server?label=server%20open%20issues&color=339C5E&style=flat-square" alt="server Open issues status badge">
</a>

<a href="https://github.com/braind3d/eleggo-server/issues?q=is%3Aissue+is%3Aclosed">
<img src="https://img.shields.io/github/issues-closed-raw/braind3d/eleggo-server?label=server%20closed%20issues&color=339C5E&style=flat-square" alt="Closed issues status badge">
</a>

<a href="https://github.com/braind3d/eleggo-hardware/issues?q=is%3Aissue+is%3Aopen">
<img src="https://img.shields.io/github/issues-raw/braind3d/eleggo-hardware?label=hardware%20open%20issues&color=339C5E&style=flat-square" alt="hardware Open issues status badge">
</a>

<a href="https://github.com/braind3d/eleggo-hardware/issues?q=is%3Aissue+is%3Aclosed">
<img src="https://img.shields.io/github/issues-closed-raw/braind3d/eleggo-hardware?label=hardware%20closed%20issues&color=339C5E&style=flat-square" alt="Closed issues status badge">
</a>
</p>

## Get started
<p align="center">
<img src="docs/promotional/Project Structure.png" alt="Project Structure">
</p>


The project consists of 3 main components:
- **Machine learning algorithms**, such as hand movement detection and directional thinking detection, which process EEG data for classification (located in "[eleggo-ml](https://github.com/braind3d/eleggo-ml)")
- **Server & Web Client**, which provides an easy to program way for setting the se (located in "[eleggo-server](https://github.com/braind3d/eleggo-server)")
- **BCI board**, which is using the OpenBCI Cyton board as a base and modifying it so that it only uses non-deprecated elements (located in"[eleggo-hardware](https://github.com/braind3d/eleggo-hardware)")

For each of the components' directories there is a corresponding `README.md` with instructions on how to get started.

## Authors
- **Angel Penchev** ([@angel-penchev](https://github.com/angel-penchev)) - Machine learning
- **Bogdan Mironov** ([@bogdanmironov](https://github.com/bogdanmironov)) - Machine learning
- **Madlen Sarkisian** ([@Maddie02](https://github.com/Maddie02)) - Backend server and frontend client
- **Miroslav Mirchev** ([@Miro-02](https://github.com/Miro-02)) - Hardware
- **Simeon Georgiev** ([@simo1209](https://github.com/simo1209)) - Hardware


## Headset in use
<p align="center">
<img src="docs/promotional/Headset.jpg" alt="Headset">
</p>

## Contributions
1. Fork it (<https://github.com/braind3d/Eleggo/fork>)
2. Create your feature branch (`git checkout -b feature/fooBar`)
3. Commit your changes (`git commit -a`)
4. Push to the branch (`git push origin feature/fooBar`)
5. Create a new Pull Request
6. Upon review it will be merged.

## License
Distributed under the BSD-3 Cause license. See [LICENSE](LICENSE) for more information.