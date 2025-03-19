# Healthcare Appointment Analysis 📊

This project delves into healthcare appointment data, identifying patterns in patient behavior, health conditions, appointment scheduling, and attendance rates. The goal is to provide actionable insights for improving healthcare delivery and minimizing no-show rates.

## **Documentation Using STAR Method**

### **Situation**
The dataset contains comprehensive records of healthcare appointments, including patient demographics, medical history, neighborhood distribution, reminders, and no-show outcomes. It aims to address key healthcare challenges, such as high no-show rates, resource allocation, and neighborhood-based trends.

### **Task**
The objectives of this analysis were to:
- Identify demographic patterns among patients, such as age and gender distributions.
- Analyze the influence of factors like health conditions, SMS reminders, scholarships, and waiting times on no-show rates.
- Explore trends across neighborhoods to enhance patient management strategies.

### **Action**
The following steps were carried out:
1. **Data Cleaning and Preparation:**
   - Removed duplicates and ensured all data fields were complete and valid.
   - Created new features such as `AgeGroup` and `DaysDifference` to enable grouped analysis.
2. **Exploratory Data Analysis (EDA):**
   - Visualized demographic distributions by age groups, gender, and neighborhoods.
   - Examined the correlation between no-show rates and factors like SMS reminders, scholarships, and health conditions.
   - Analyzed waiting times by neighborhoods to identify trends impacting attendance.
3. **Data Visualizations and Insights:**
   - Bar charts, pie charts, and heatmaps were used to represent data visually, highlighting key findings.
   - Specific insights uncovered during the analysis include:
     - Higher no-show rates in younger age groups (`19-35`).
     - Patients receiving SMS reminders had lower no-show rates, but 27.67% still missed appointments.
     - Neighborhoods with the highest patient volumes, like *Jardim Camburi*, faced longer waiting times.
     - Scholarship recipients were younger on average but exhibited slightly higher no-show rates.

### **Result**
The analysis generated actionable insights:
- **Enhanced Communication Strategies:** Further optimize SMS reminders to ensure better engagement and attendance.
- **Targeted Interventions:** Focus on young adults and high no-show neighborhoods to develop tailored solutions.
- **Improved Scheduling:** Adapt appointment schedules based on neighborhood-specific waiting times and trends.
- **Policy Recommendations:** Provide additional support to scholarship recipients and patients with multiple health conditions to reduce no-show rates.

## **Visualizations**
This repository includes:
- Charts showing demographic distributions, such as age and gender.
- Heatmaps analyzing waiting times by neighborhoods.
- Visualizations on the impact of SMS reminders, scholarships, and health conditions on no-show rates.

## **Technologies Used**
- **Python Libraries:** NumPy, Pandas, Matplotlib, Seaborn.
- **Jupyter Notebook:** For running the analysis and creating visualizations.

## **How to Run**
1. Clone this repository:
   ```bash
   git clone <repository-link>
   ```
2. Install the required dependencies:
   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
3. Open the Jupyter Notebook and run the analysis cells step-by-step.

## **Contributing**
Contributions are welcome! Please fork the repository, make your changes, and submit a pull request.

## **License**
This project is licensed under the MIT License.

