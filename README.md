# Schwurbel Archiv Repository

A tool for downloading, parsing, and analyzing data from the `schwurbel-archiv` collection on Archive.org.

## Table of Contents

1. [Introduction](#introduction)
2. [Requirements](#requirements)
3. [Usage](#usage)
4. [Contributing](#contributing)
5. [License](#license)

## Introduction

This Jupyter notebook-based tool provides a simple way to interface with the `schwurbel-archiv` collection on Archive.org. It provides capabilities such as:
- Installing necessary Python packages
- Searching for items within the collection
- Downloading, parsing, and analyzing the data
- Exporting the data to CSV

## Requirements

- Python 3.9+
- Jupyter Notebook
- Libraries: pandas, uuid, datetime, BeautifulSoup, internetarchive

## Usage

1. Clone the repository
   ```bash
   git clone git@github.com:michaelachmann/schwurbelarchiv-loader.git
   ```
   
2. Navigate to the cloned directory and start Jupyter Notebook
   ```bash
   cd schwurbelarchiv-loader
   jupyter notebook
   ```

3. Open the provided notebook

4. Install the required packages by executing the `!pip install internetarchive` cell.

5. Execute cells sequentially to download, parse, and analyze the data.

6. Exported data will be saved to the CSV file: `data/2023-07-06-Schwurbelarchiv-Liste.csv`.

## Contributing

1. Fork the repository
2. Create a new branch for your feature or bugfix
3. Make your changes
4. Submit a pull request and describe your changes

## License

This project is licensed under the GPL-3 License



---

Created by [Michael Achmann-Denkler](https://go.ur.de/michael-achmann). For any questions, feedback, or collaboration inquiries, please contact me at [michael.achmann@informatik.uni-regensburg.de](mailto:michael.achmann@informatik.uni-regensburg.de)