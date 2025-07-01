📊 Data Analyst Candidate Selection Tool
This is a simple Python script that filters and visualizes the top Data Analyst candidates from an Excel file. It supports exporting selected candidates and generating insightful pie/bar charts based on their skills.

✅ Features
📥 Reads Excel files containing candidate data

🔎 Filters top 5 candidates with "Data Analysis" in their skills

📁 Exports the filtered data to a new timestamped Excel file

📊 Visualizes candidate data using bar or pie charts

🧠 Simple logic to interpret skill levels from skill strings like Data Analysis - Advanced

📂 Input File Format
The Excel file should contain at least the following columns:

Name	Mobile Number	Skill	Age
John Doe	1234567890	Data Analysis - Advanced	28
Jane Smith	9876543210	Data Analysis - Intermediate	25

▶️ How to Run
Install required packages (if not already installed):

pip install pandas matplotlib openpyxl
Run the script:

python main.py
Follow the prompts:

Enter the path to your Excel file

Choose the type of visualization: none, pie, or bar

📈 Chart Types
pie: Shows distribution of skills among top 5 candidates

bar: Aggregates skill levels and visualizes them per candidate (based on Beginner–Expert scale)

📝 Output
Console prints top 5 candidates

A new Excel file named like top_data_analyst_candidates_20250627_143215.xlsx is saved

If selected, a chart is displayed using matplotlib

🛠 Future Improvements
Add CLI argument support (e.g., --file, --chart)

Add GUI interface using Tkinter or Streamlit

Include email/contact validation

🧑‍💻 Author
Built by Astha_Rai – feel free to contribute or fork this project!
