# ⚡ Hostel Electricity Usage Logger  

A simple **Python + CSV** based project to monitor hostel room electricity consumption.  
The tool allows students/administrators to **log daily usage**, **analyze monthly consumption with Pandas**, and **visualize results using Matplotlib**.  

---

## 📌 Features  
- 📝 **Log daily electricity usage** of hostel rooms into a CSV file  
- 📂 Store data in a structured format: **Room | Date | Units**  
- 📊 **Analyze monthly electricity consumption** per room using Pandas  
- 🚨 Highlight rooms that cross a **set usage threshold** (e.g., 400 units/month)  
- 📉 Generate **bar charts** for quick visualization of electricity usage trends  

---

## 🗂️ Project Structure  
Hostel-Electricity-Logger/
│-- electricity_usage.csv # Main data file (Room, Date, Units)
│-- main.py # Python script with logging, analysis, and visualization
│-- README.md # Project documentation

---

## ⚙️ Requirements  
Make sure you have Python installed (**>=3.7**).  
Install the required libraries using **pip**:

##  ▶️ How to Run

- Clone or download this repository.

- Ensure you have a CSV file named electricity_usage.csv with columns:

Room,Date,Units


- Run the Python script:

python main.py


- Follow the menu to:

## ✅ Log new usage

## 📊 Analyze monthly reports

## 📉 Generate visualizations

## 📊 Sample CSV File (electricity_usage.csv)
Room,Date,Units
101,2025-07-01,12
102,2025-07-01,15
103,2025-07-01,18

## 📈 Sample Output

- Monthly Summary Table (via Pandas)

- Bar Chart showing room-wise electricity consumption

- 🚨 Rooms exceeding the threshold are highlighted

- 🚀 Future Enhancements

- 🖥️ Add GUI support (Tkinter/Streamlit)

- ⚡ Automate daily logging via a web form

- 📑 Export reports in Excel/PDF formats

## 👨‍💻 Author

Developed by Rushal Nikam
For educational and hostel management use.

```bash
pip install pandas matplotlib
