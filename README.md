# BMI-Calculator
Development of the Gradio Multi-Tab Health Calculator App  Unit selection, weight, height, date, classification, and visual indicator are all included in the BMI calculator.  
**Calculator for Daily Metabolic Rate:**  Age, gender, height, weight, degree of activity, and the Harris-Benedict equation are all inputs.  
**Food Tracker:** Daily calorie intake computation, daily total display, user-friendly interface.

This project uses the Gradio framework to create a health management application in Python.  The app's simplified multi-tab interface combines three key health functions: recording food intake, estimating daily metabolic rate, and calculating body mass index.  Matplotlib for visualization and pandas for data administration are examples of supporting libraries.  
Users can enter their height and weight in various units on the BMI Calculator tab. They can also choose to include a date entry to chart their progress.  Based on recognized BMI bands, each result is color-coded and classified as underweight, normal, overweight, or obese.  Additionally, the system keeps track of each user's BMI computations, which are shown in a time-series graph to show patterns over time.

The Harris–Benedict equation (Roza & Shizgal, 1984) is used in the Daily Metabolic Rate tab to determine the Basal Metabolic Rate (BMR) and Total Daily Energy Expenditure (TDEE).  Users enter their height, weight, age, gender, and degree of exercise, which corresponds to typical activity parameters.  Both raw data and a goal-based table with recommended calorie intakes for weight gain, weight loss, or maintenance are provided.  
Dietary recording is made easy with the Food Tracker tab.  Users can insert bespoke items with calorie values or choose from a pre-defined list of common foods.  Entries can be deleted every day and are kept by date.  The interface creates a weekly calorie intake bar chart with an energy balancing reference line, highlights current day totals, and compares intake to the user's TDEE.

All things considered, this app prioritizes accessibility, visualization, and customization while providing users with a portable yet feature-rich health calculator.  An entertaining platform for tracking food consumption and energy expenditure is created by combining visual indications, historical tracking, and real-time feedback.
