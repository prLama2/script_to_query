# script_to_query
python script to query for Minnesota Twins
Minnesota Team Data Fetcher

This project is a Python script that queries the College Football Data API to retrieve team information for the University of Minnesota and processes the result into a CSV file.

📚 Project Overview
The script connects to the public College Football Data API using a provided API key to fetch data about college football teams. It filters the response to retrieve information specifically about the University of Minnesota and writes the data to a CSV file.

🛠 Technologies Used
- Python
- Requests library
- CSV module

🚀 How to Run the Script
Prerequisites
- Python 3.x installed on your machine
- An API key for the [College Football Data API](https://collegefootballdata.com/)

Steps
1. Clone this repository to your local machine:
   ```bash
   git clone <your-repository-url>
   cd <your-repository-folder>
   ```
2. Install dependencies (if needed):
   ```bash
   pip install requests
   ```
3. Replace the `API_KEY` variable in the script with your actual API key.
4. Run the script:
   ```bash
   python weather_api_to_csv.py
   ```

📄CSV Output
The script generates a CSV file named `minnesota_team_data.csv` containing the following columns:
- School
- Mascot
- Conference
- Division

Example output:
| School     | Mascot        | Conference   | Division |
|------------|---------------|--------------|----------|
| Minnesota  | Golden Gophers| Big Ten      | FBS      |

💡 API Details
- Endpoint used: `https://api.collegefootballdata.com/teams/fbs`
- Authorization: Bearer token (API key)
