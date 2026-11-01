# Currency Tracker

A desktop application built with Python and `ttkbootstrap` that tracks and visualizes currency exchange rates directly from the National Bank of Ukraine (NBU) API.

## Features

- **Live Data**: Fetches actual exchange rates for USD and EUR against UAH.
- **Interactive Graphs**: Plots rate history using `matplotlib` for different periods (Week, Month, Year).
- **Modern UI**: Clean, dark-themed interface built with `ttkbootstrap`.
- **Modular Architecture**: Clean separation between data parsing (`parser.py`) and user interface (`interface.py`).

## How it works

The app makes HTTP requests to the [NBU API](https://bank.gov.ua/NBU_Exchange/exchange_site) to get JSON data. The data is parsed and then visualized as a line chart.

## Tech Stack

- **Python 3**
- **Tkinter / ttkbootstrap** (GUI)
- **Requests** (API calls)
- **Matplotlib** (Data visualization)

## How to run

1. Make sure you have Python installed.
2. Install the required libraries:
   ```bash
   pip install requests matplotlib ttkbootstrap
3. Run the main interface file:
     python interface.py

## Project Structure
parser.py — handles API requests, JSON parsing, and graph plotting.
interface.py — handles the GUI and user interaction.

## Note on AI usage
The code in this project was written with the help of AI as part of my learning journey. I understand how the code works, managed the architecture, and can explain the logic behind the API requests and plotting.
