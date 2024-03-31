
# arXiv-AstroPDF-DL

Developed as part of a technical assessment, arXiv-AstroPDF-DL is a Selenium IDE script that automates the downloading of the latest Astrophysics PDF from the [arXiv](https://arxiv.org/) repository. It demonstrates the use of browser automation to facilitate quick access to new scientific publications.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Setup and Installation](#setup-and-installation)
  - [Clone the Repository](#clone-the-repository)
  - [Browser Setup](#browser-setup)
  - [Running the Script](#running-the-script)
- [Usage](#usage)
- [Troubleshooting](#troubleshooting)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Features

- **Automated PDF Downloads**: Automatically fetches and downloads the latest Astrophysics PDF from the arXiv repository.
- **Ease of Use**: User-friendly script designed for simplicity and ease of use.

## Prerequisites

Before starting, ensure you have the following:

- A web browser (Firefox or Chrome recommended).
- Selenium IDE extension for your web browser.
- [Git](https://git-scm.com/) installed for cloning the repository.

## Setup and Installation

### Clone the Repository

```bash
git clone https://github.com/ascender1729/arXiv-AstroPDF-DL.git
cd arXiv-AstroPDF-DL
```

### Browser Setup

Ensure Selenium IDE is installed in your browser and set the browser to automatically download PDFs without confirmation.

### Running the Script

For running through Selenium IDE:

1. Launch the Selenium IDE.
2. Import the `.side` project file.
3. Execute the test.

For running through Selenium Side Runner:

```bash
selenium-side-runner -c "browserName=chrome" "SPICE-IN Lens - Technical Assessment.side"
```

## Usage

To download the latest Astrophysics PDF from arXiv:

- Open the script with Selenium IDE.
- Run the script and the download should start automatically.

## Troubleshooting

If the script does not perform as expected:

- Check that the Selenium IDE is correctly installed and configured.
- Ensure that the browser settings allow for automatic downloading of PDF files.

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions about the script, you can reach out to me directly here on GitHub or through the email provided in my profile.

GitHub Profile: [@ascender1729](https://github.com/ascender1729)

Project Link: [arXiv-AstroPDF-DL](https://github.com/ascender1729/arXiv-AstroPDF-DL)
