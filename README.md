<a name="readme-top"></a>

<!-- ABOUT THE PROJECT -->
## About The Project

Notebooks to standardize the catalog mailing process.

* List Generating
> This notebook calls a sproc that compiles customer records into their predefined segments. Just enter required variables in the initial cell, and fine tune the hold out group percentages as needed to meet target mailing counts.
* Customer Processing
> This notebook helps store returned mail files from 3rd party contractors in their respective db, and prepares data to be uploaded into NetSuite in small increments.
* Pagination Processing
> This notebook is a boiler plate, as the data you receive will not always be clean, but the goal is to join whatever values are sent over in a csv with that item's internal id, and prep it to be uploaded into NetSuite.

<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

Make sure you have venv installed.

* venv
  ```py
  pip install venv
  ```
* Create a pw.py file with needed server credentials.
### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/MDeanLindsay/Klaviyo-API.git
   ```
2. Create venv.
   ```sh
   python -m venv .venv
   ```
3. Initialize venv.
   ```sh
   .\.venv\Scripts\bin\activate
   ```
5. Install requirements.
   ```sh
   pip install -r requirements.txt
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>