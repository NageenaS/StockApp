# StockApp

StockApp is a Flask-based application that aims to offer insights into stock market data by using APIs to dynamically retrieve and display stock information.



## Features

- Retrieve stock prices and data in real-time.
- Intuitive interface for navigating stock information.
- Engaging charts for visualizing stock trends.

## Prerequisites

Prior to starting the application, confirm that you have the following installed:

- Python 3.x
- Docker
- An API key from [RapidAPI](https://rapidapi.com/linuz/api/indian-stock-exchange-api2/playground) 

## Getting Started

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/StockApp.git
   cd StockApp
   ```

2. Replace `your_api_key_here` in the code with your actual API key obtained from the API provider.

3. Build the Docker image:

   ```bash
   docker build -t stockwatch .
   ```

4. Alternatively, you can pull the pre-built Docker image from Docker Hub:

   ```bash
   docker pull nageenashaik/stockwatch
   ```

5. Run the Docker container:

   ```bash
   docker run -p 5000:5000 nageenashaik/stockwatch
   ```

6. Open your web browser and go to `http://localhost:5000` to access the application.

## Usage

Once the application is running, you can use the interface to:

- Search for stocks
- View stock details
- Analyze trends through interactive charts

  ![image](https://github.com/user-attachments/assets/76da7f2e-e35f-4537-8790-edf381f1e6aa)

  ![image](https://github.com/user-attachments/assets/facd878d-95cf-4faf-9129-1760bad1b83a)


## Docker Hub

The StockApp is also available on Docker Hub. You can find the image [here](https://hub.docker.com/r/nageenashaik/stockwatch) (replace with your actual Docker Hub link). This allows you to easily deploy the application without building the image locally.

## Acknowledgements

- [Flask](https://flask.palletsprojects.com/) for the web framework.
- [APIs](https://rapidapi.com/linuz/api/indian-stock-exchange-api2/playground) for stock market data 

---

&copy;-Shaik Nageena
