# arXiv-AstroPDF-DL

This repository hosts a Selenium IDE script for the automated downloading of the latest Astrophysics PDF from the arXiv repository. The script is designed to facilitate researchers, educators, and enthusiasts in keeping up with the latest papers in the Astrophysics domain without manual searching and downloading.

## Prerequisites

Before running this script, you'll need:

- A modern web browser (Firefox or Chrome recommended).
- The Selenium IDE extension installed on your browser. You can download it from the [official Selenium site](https://www.selenium.dev/selenium-ide/).
- [Git](https://git-scm.com/) installed to clone the repository.

Optional:
- The Selenium Command Line Runner ([Selenium Side Runner](https://www.selenium.dev/selenium-ide/docs/en/introduction/command-line-runner)) if you prefer to run the script from the command line.

## Installation and Setup

Follow these steps to get the script up and running on your local machine:

```bash
# Clone the repository
git clone https://github.com/ascender1729/arXiv-AstroPDF-DL.git

# Navigate to the cloned directory
cd arXiv-AstroPDF-DL
```

## Running the Script

You can run the script using two methods:

### Method 1: Using Selenium IDE

1. Open Selenium IDE in your browser.
2. Import the `SPICE-IN Lens - Technical Assessment.side` file into Selenium IDE by clicking 'Open an existing project'.
3. Once the project is loaded, execute the test suite or individual tests as needed.

### Method 2: Using Selenium Side Runner (Command Line)

If you have installed Selenium Side Runner, you can run your Selenium IDE scripts from the terminal. Execute the following command within the repository directory:

```bash
selenium-side-runner -c "browserName=chrome" "SPICE-IN Lens - Technical Assessment.side"
```

This command will launch Chrome and run the automated script to download the latest PDF. Please make sure that the `.side` file name matches the name of the file in the directory.

## Understanding the Repository Contents

- `LICENSE`: The license file describes the permissions, limitations, and conditions under which the software is released.
- `README.md`: This detailed guide on setting up and using the automated script.
- `SPICE-IN Lens - Technical Assessment.side`: The actual Selenium IDE script that performs the automated PDF download from arXiv.

## Contributing

Feel free to fork this repository, make changes, and submit pull requests. Your contributions to improve the script or expand its functionality are highly appreciated.

## License

This project and its contents are released under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact and Support

If you encounter any problems or have suggestions, please submit an issue on the [GitHub issue tracker](https://github.com/ascender1729/arXiv-AstroPDF-DL/issues), or propose changes by submitting a pull request.

## Acknowledgments

- Thanks to arXiv for providing free access to scientific papers.
- Microsoft Research India for their SPICE-IN Lens initiative which inspired the creation of this script.
