# 🌦️ Live Weather Notifier for Patna, Bihar

This Python script scrapes live weather data from [weather.com](https://weather.com) and sends desktop notifications for the current temperature and rain chances in Patna, Bihar.

## 📋 Features
- Scrapes live weather data using the `requests` and `BeautifulSoup` libraries.
- Displays a **Windows toast notification** showing the current temperature and rain chances in Patna, Bihar.
- Lightweight and easy to run.

## 🔧 Requirements

Ensure you have Python 3.x installed, along with the following libraries:

- `requests` — for sending HTTP requests to fetch the weather data.
- `beautifulsoup4` — for parsing the HTML data and extracting the weather details.
- `win10toast` — for sending toast notifications to the Windows desktop.

Install the dependencies using the following command:

```bash
pip install requests beautifulsoup4 win10toast

## 🚀 How to Run
1.	Clone the repository or download the script.
2.	Install the dependencies using the command mentioned above.
3.	Run the Python script:
```bash
python weather_notifier.py

You will receive a Windows desktop notification with the current temperature and rain chances for Patna, Bihar.
