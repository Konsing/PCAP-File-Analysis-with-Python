# PCAP File Analysis with Python and Jupyter

This repository contains a project focused on analyzing PCAP (Packet Capture) files using Python and Jupyter Notebook. The project includes scripts and data files necessary to perform a comprehensive analysis of network traffic captured in PCAP format.

## Table of Contents
- [Introduction](#introduction)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Analysis](#analysis)

## Introduction
This project demonstrates how to use Python libraries like `dpkt` to parse and analyze network traffic captured in PCAP files. It includes several PCAP files capturing various network activities and a Jupyter Notebook to perform detailed analysis.

## Project Structure
The project includes the following files:
- **ass1_1.pcap**: Packet capture file 1 for analysis.
- **ass1_2.pcap**: Packet capture file 2 for analysis.
- **ass1_3.pcap**: Packet capture file 3 for analysis.
- **pcap_http_analysis.py**: Python script for parsing and analyzing HTTP traffic in PCAP files.
- **pcap_analysis_notebook.ipynb**: Jupyter Notebook containing the code for analyzing the captured network traffic.

## Getting Started

### Prerequisites
- Python 3.x
- Jupyter Notebook
- `dpkt` library

### Installation
1. Clone this repository:
   ```sh
   git clone https://github.com/yourusername/pcap-analysis.git
   cd pcap-analysis
   ```

2. Install the required Python packages:
   ```sh
   pip install jupyter dpkt
   ```

## Usage

### Using the Python Script
1. **Analyze a PCAP File**:
   - Run the Python script with the PCAP file as an argument:
     ```sh
     python pcap_http_analysis.py ass1_1.pcap
     ```

### Using the Jupyter Notebook
1. **Analyze Captured Traffic**:
   - Open Jupyter Notebook:
     ```sh
     jupyter notebook
     ```
   - Open the `pcap_analysis_notebook.ipynb` file in Jupyter.
   - Run the cells in the notebook to load and analyze the captured network traffic data.

## Analysis
The `pcap_analysis_notebook.ipynb` notebook and `pcap_http_analysis.py` script include the following analyses:
- Parsing the PCAP files to extract HTTP traffic.
- Analyzing HTTP requests and responses.
- Identifying specific URI patterns and headers in HTTP requests.