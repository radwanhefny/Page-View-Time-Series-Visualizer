# 📊 Page-View-Time-Series-Visualizer
A Python program that visualizes daily freeCodeCamp forum page views using line, bar, and box plots. The project cleans the data, handles outliers, and creates insightful visualizations to explore trends and seasonality.
## ✨ Features
- Cleans page view data by removing outliers (top/bottom 2.5%).
- Draws a line plot to visualize daily page views over time.
- Draws a bar plot showing average monthly page views per year.
- Draws box plots for yearly and monthly distributions (trend and seasonality).
- Saves all plots as PNG images.
## 📋 Prerequisites
Before running this project, ensure you have:
- Python 3.8+
- Pandas, NumPy, Matplotlib, Seaborn libraries
- CSV dataset fcc-forum-pageviews.csv inside a data folder
- Basic knowledge of Python and data visualization
## 🚀 Getting Started
1. Clone the repository:
```bash
git clone https://github.com/radwanhefny/fcc-forum-pageview-visualizer.git
cd fcc-forum-pageview-visualizer
```
2. Install dependencies:
```bash
pip install -r requirements.txt
```
3. Run the visualization scripts:
```bash
python main.py
```
## 🎬 Screenshots / Demo
### Line Plot
**Figure:**  
![Line Plot](https://github.com/radwanhefny/Page-View-Time-Series-Visualizer/blob/main/examples/Figure_1.png)  
**Result:**  
![Line Plot Result](https://github.com/radwanhefny/Page-View-Time-Series-Visualizer/blob/main/examples/Result_1.png)

### Bar Plot
**Figure:**  
![Bar Plot](https://github.com/radwanhefny/Page-View-Time-Series-Visualizer/blob/main/examples/Figure_2.png)  
**Result:**  
![Bar Plot Result](https://github.com/radwanhefny/Page-View-Time-Series-Visualizer/blob/main/examples/Result_2.png)

### Box Plot
**Figure:**  
![Box Plot](https://github.com/radwanhefny/Page-View-Time-Series-Visualizer/blob/main/examples/Figure_3.png)  
**Result:**  
![Box Plot Result](https://github.com/radwanhefny/Page-View-Time-Series-Visualizer/blob/main/examples/Result_3.png)

## 🗂️ Project Structure
```
📁 fcc-forum-pageview-visualizer
├── time_series_visualizer.py
├── test_module.py            
├── main.py             
├── data/
│   └── fcc-forum-pageviews.csv    # Dataset
├── requirements.txt
└── README.md


```
## 🛠️ Usage
Example usage inside Python:
```python
from time_series_visualizer import draw_line_plot, draw_bar_plot, draw_box_plot

line_fig = draw_line_plot()
bar_fig = draw_bar_plot()
box_fig = draw_box_plot()


```
Expected output:
- line_plot.png → Daily page views over time
- bar_plot.png → Average monthly page views per year
- box_plot.png → Year-wise and month-wise box plots
## ✅ Tests
Run the FreeCodeCamp test suite:
```bash
python test_module.py
```
## 🧠 How It Works
1. Reads the CSV dataset using Pandas.
2. Filters outliers (values below 2.5th percentile and above 97.5th percentile).
3. Creates three types of visualizations: line, bar, and box plots.
4. Saves each plot as a PNG image.
5. Provides insights on trends, seasonality, and distribution of page views.

## 🤝 Contributing
Contributions are welcome!
1. Fork the repository
2. Create a new feature branch
3. Submit a pull request
Please ensure your code is clean, structured, and well-commented.
## 📝 License
This project is licensed under the MIT license - see the LICENSE file for details. 
## 📞 Support
If you have questions or need help, feel free to:
- Open an issue on this repository  
- Connect with me on LinkedIn: https://www.linkedin.com/in/radwanhefny  
