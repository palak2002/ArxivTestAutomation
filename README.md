
# Arxiv Test Automation

This repository contains a Selenium IDE project for automating the download of the latest PDF file from arXiv.org -> [here](arXiv.org).

## Prerequisites

- **Selenium IDE:** You can install Selenium IDE from [here](https://www.selenium.dev/selenium-ide/).
- **Selenium Side Runner:** You can install Selenium Side Runner from [here](https://www.seleniumhq.org/selenium-ide/docs/en/introduction/command-line-runner/).

The test automation includes the following tests:
1. **New Submission:** This test downloads the latest PDF from the arXiv homepage.
2. **Date Latest:** This test downloads the latest PDF from the arXiv "Recent Quantitative Biology" section.
3. **Advanced Search:** This test searches for PDFs with the term "Computer Science" and downloads the latest PDF from the search results.
4. **Submission Date:** This test sorts the arXiv search results by submission date and downloads the latest PDF.
5. **Recent PDF:** This test downloads the latest PDF from the arXiv "Recent Nuclear Theory" section.
6. **New Announcement Date:** This test searches for PDFs with the term "quantum" and sorts the results by announcement date, then downloads the latest PDF.


## Running the Test Automation

To run the test automation, navigate to the directory on cmd where your `.side` file is located and run the following command:

```bash
selenium-side-runner /path/to/your-project.side
```

## Project Structure

The project contains the following files:

- `arxiv-test-automation.side`: The Selenium IDE project file.
- `LICENSE`: The MIT License file.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

## Note

The arxiv-test-automation.side file was created using Selenium IDE and can be executed using Selenium Side Runner. The project is designed to download the latest PDF file from arXiv.org. The project was tested on Chrome and Firefox browsers.

## Confidentiality

Please note that this project does not contain any confidential information, such as passwords or personal details. The project is designed for assignment.
