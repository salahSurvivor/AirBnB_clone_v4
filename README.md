# AirBnB_clone_v4: Web Dynamic (hbnb)

## Table of Contents

- [Description](#description)
- [Purpose](#purpose)
- [Requirements](#requirements)
- [File Descriptions](#file-descriptions)
- [Environmental Variables](#environmental-variables)
- [Usage](#usage)
- [Bugs](#bugs)
- [Authors](#authors)
- [License](#license)

## Description

hbnb is a comprehensive clone of the AirBnB web application, developed across four iterative phases. This version encompasses the completion of Phase 1, Phase 2, Phase 3, and the Final Version (Phase 4), which focuses on dynamic web functionality, including loading objects from the client-side using a custom RESTful API and jQuery.

## Purpose

The primary aim of Phase 4 is to facilitate learning in the following areas:

- Requesting own API
- Modifying HTML element styles
- Getting/updating HTML element styles
- Making GET/POST requests with jQuery Ajax
- Modifying the Document Object Model (DOM)
- Listening/binding to DOM and user events

## Requirements

- All files compiled with Ubuntu 14.04 LTS
- Documentation provided
- Organized file structure
- Python unit tests for all files
- Compliance with PEP 8 and semistandard coding standards

## File Descriptions

The project directory is structured as follows:

- `tests`: Contains unit test files
- `web_dynamic`: Includes Flask, template, and static files
- Python scripts (e.g., `0-hbnb.py`, `1-hbnb.py`) integrating Flask with AirBnB static HTML templates and handling custom template requests
- HTML templates (e.g., `0-hbnb.html`, `1-hbnb.html`) for various functionalities
- JavaScript files (e.g., `1-hbnb.js`, `2-hbnb.js`) implementing dynamic features
- CSS files for styling (e.g., `3-footer.css`, `4-common.css`)

## Environmental Variables

The project relies on the following environmental variables:

- `HBNB_ENV`: Running environment ("dev" or "test")
- MySQL database credentials and configuration
- `HBNB_TYPE_STORAGE`: Type of storage used ("file" or "db")

## Usage

1. Run the API in one terminal window:

```
$ HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db HBNB_API_PORT=5001 python3 -m api.v1.app
```

2. Run Flask in another terminal window:

```
$ HBNB_MYSQL_USER=hbnb_dev HBNB_MYSQL_PWD=hbnb_dev_pwd HBNB_MYSQL_HOST=localhost HBNB_MYSQL_DB=hbnb_dev_db HBNB_TYPE_STORAGE=db python3 -m web_dynamic.2-hbnb
```

3. Open a web browser and visit `0.0.0.0:5000/2-hbnb` (or other Flask file versions).

## Bugs

At present, there are no known bugs.

## Authors

- Fithi Salma
- Salaheddine Naji

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
