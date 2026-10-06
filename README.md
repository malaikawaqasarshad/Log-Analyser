# Log-Analyser-V1
A lightweight log analysis tool designed to analyse and extract useful insights from application and system logs.
The project helps identify suspicious log activity.
Be sure to only analyse content which you have authorised access to. The logs I analysed were hypothetical.

## Features

* Parse log files efficiently
* Search and filter log entries
* Identify errors and warnings
* Generate useful statistics and summaries
* Analyse events by timestamp
* Detect recurring log messages and patterns
* Handle large log files without manually searching through them
* Simple command-line interface

## Technologies

* **Language:** Python, Jupyter Notebook
* **Input:** Log files in `.txt` format
* **Output:** Console reports, analysis results, results in the JSON file

> Update this section with the exact technologies and libraries used in your project.

## Installation

Clone the repository:

```bash
git clone https://github.com/malaikawaqasarshad/Log-Analyser.git
cd YOUR_REPOSITORY
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Usage

Run the analyser with:

```bash
python main.py path/to/your/logfile.log
```

Example:

```bash
python main.py logs/application.log
```

The analyser will process the log file and provide a summary of the information it finds.

### Example Output

Failed logins by IP:
192.0.2.15 : 5

Suspicious IP addresses:
⚠ 192.0.2.15 - 5 failed attempts

## Roadmap

Future improvements could include:

* [ ] Support for additional log formats
* [ ] CSV/JSON export
* [ ] Graphs and visualisations
* [ ] Real-time log monitoring
* [ ] Custom filtering rules
* [ ] Web-based dashboard
* [ ] Improved performance for very large log files
* [ ] Automated anomaly detection

## License

This project is licensed under the MIT License.

## Author

**Malaika Waqas Arshad**

* GitHub: (https://github.com/malaikawaqasarshad)



If you found this project useful, consider giving the repository a star!
