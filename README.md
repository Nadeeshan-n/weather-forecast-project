# Weather Forecast Accuracy Project 

This project is a Linux-based automation pipeline built using Bash scripting. It collects real-time weather data, stores historical records, and evaluates forecast accuracy over time.

##  Features
- Fetches real-time weather data using wttr.in API
- Logs daily observed and forecast temperatures
- Calculates forecast accuracy automatically
- Categorizes accuracy (excellent, good, fair, poor)
- Maintains historical dataset
- Generates weekly statistics (min/max error)

##  Project Files
- `rx_poc.sh` → Collects weather data and logs it
- `fc_accuracy.sh` → Computes forecast accuracy
- `historical_fc_accuracy.tsv` → Stores historical records
- `week_fc.sh` / `weakly_stats.sh` → Weekly analysis

##  Technologies Used
- Bash scripting (Linux)
- curl (API requests)
- awk, grep, cut (text processing)

##  Use Case
This project demonstrates how shell scripting can be used for:
- Data collection
- Automation
- Basic data analysis

##  Learning Outcomes
- Working with APIs in Linux
- File handling and logging
- Data extraction and processing
- Automating workflows using shell scripts

##  How to Run
```bash
bash rx_poc.sh
bash fc_accuracy.sh
bash week_fc.sh
