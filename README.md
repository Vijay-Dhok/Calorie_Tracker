# Calorie_Tracker DashBoard
This project is 100% self-made — from collecting and preparing  my own raw data to building data models and designing the final interactive dashboard.
![image alt](https://github.com/Vijay-Dhok/Calorie_Tracker/blob/8d93227c65d53e55548e275139d12ce304419bf9/DashBoard%20.png)

🎯 **Objective**:
To track and analyze daily calorie consumption and macro-nutrient intake (Protein, Carbohydrates, Fats) in order to monitor fitness progress, support dietary goals (e.g., bulking or cutting), and improve nutritional habits.

**Slicer Panel**
A dedicated slicer panel has been added to allow dynamic filtering and exploration of the data. This enhances interactivity and allows users to focus on specific days, meal types, or macro elements.



![image alt](https://github.com/Vijay-Dhok/Calorie_Tracker/blob/591a4c917e4eba43b05142e9312d9d508c9ae2cc/Slicer_Panel.png)






**🔘 Interactive Buttons – Enhanced Navigation & Detail Views**
To make the dashboard more dynamic and user-friendly, I have integrated interactive buttons that allow smooth navigation and on-demand detail views.

**Item List Button:**

Reveals a detailed list of all food items consumed for the selected date.

Helps users understand exactly what contributed to their macro and calorie intake.

**Quantity Breakdown Button:**

Displays a breakdown of the quantity (in grams or ml) for each food item consumed.

Useful for identifying portion sizes and tracking serving patterns over time.

**🔙 Back Button:**

Acts as a page navigation control, allowing users to return to the main dashboard or previous visual page.

Enhances user experience by simulating app-like navigation within Power BI.

🧠 Purpose:
These buttons create a more interactive and intuitive experience, allowing users to dive deeper into their food log and return without getting lost in multiple visuals.


📊 **Key Features**:

**1]Nutrient Intake KPIs:**


![image alt](https://github.com/Vijay-Dhok/Calorie_Tracker/blob/f0481a21ddea240ff64cc8dd4127161f108390c7/kpi.png)


*Show Actual Intake vs. Goal
The card displays the actual amount consumed (e.g., Protein Intake: 144.00g) against a target/goal (e.g., Goal: 162.50g).

**Calculate and Display % Difference**

The percentage next to the goal indicates how much the actual intake is above or below the goal.
Example:
Protein: −11.38% → means intake is 11.38% below the goal
Fat: +26.73% → means intake is 26.73% above the goal

**Color Coding for Visual Feedback**

Red Color + Exclamation Mark (!): When the intake is below or above the goal in a way that may be considered undesirable (e.g., under-consuming protein or over-consuming fat).
Green Color + Check Mark (✓): When the intake is on target or within a healthy margin of the goal.

**Purpose:**
This visual system helps you quickly identify which nutrients are on track and which ones need adjustment—especially important in fitness goals like bulking, cutting, or maintaining.

**2]Macronutrient Trends (Line Chart):**



![image alt](https://github.com/Vijay-Dhok/Calorie_Tracker/blob/f0481a21ddea240ff64cc8dd4127161f108390c7/Carb%20protein%20fat%20intake%20in%20kcal.png)




Tracks daily trends of Fat, Protein, and Carbohydrate intake over time in kcal.

**Constant Goal Lines (Reference Lines):**

For each macro-nutrient, a horizontal constant line represents the target/goal value.
Example: If your protein goal is 162.5g (≈650 kcal), a line is drawn across the chart at that level.
By comparing daily values to the goal lines, you can see how consistently you hit your nutritional targets.
If your intake line stays near or above the constant line regularly, it indicates good dietary discipline
This acts as a benchmark to easily compare daily intake against the goal.

**🎯 Purpose:**

This visualization helps evaluate whether you're on track, overconsuming, or under-consuming specific macro-nutrients over time.

**3]Top 3 Macro Sources per day:**



![image alt](https://github.com/Vijay-Dhok/Calorie_Tracker/blob/f0481a21ddea240ff64cc8dd4127161f108390c7/Tables.png)



for e.g.
Protein: Chicken Breast, Whey Protein, Eggs

Carbs: Banana, Rice, Peanut Butter

Fats: Eggs, Ghee, Oil

**4]Percentage Distribution (Donut Chart):**




![image alt](https://github.com/Vijay-Dhok/Calorie_Tracker/blob/f0481a21ddea240ff64cc8dd4127161f108390c7/Percentage%20distribution%20of%20calories%20by%20day.png)





Visual breakdown of calorie contribution from each macro-nutrient on a specific day (e.g., 9 May 2025).

**5]Calories by Meal (Bar Chart):**









![image alt](https://github.com/Vijay-Dhok/Calorie_Tracker/blob/f0481a21ddea240ff64cc8dd4127161f108390c7/Distribution%20of%20calories%20by%20meal.png)

Distribution of total calorie intake by meal type: Dinner, Lunch, Snacks, Breakfast

**6]Weight Monitoring (Line Chart):**









![image alt](https://github.com/Vijay-Dhok/Calorie_Tracker/blob/f0481a21ddea240ff64cc8dd4127161f108390c7/weight%20increase.png)

Day-wise analysis of weight gain/loss trends in kg to correlate with calorie intake.

**✅ Benefits:**
Helps users stay on track with macro and calorie goals.

Identifies which meals contribute most to calorie intake.

Tracks weight trends in relation to dietary intake.

Visual insights into top food contributors to macros.

**🚀 Scope for Improvement**
While the current version is functional and visually appealing, future enhancements could include:



**Automatic Data Import:**

Integrate APIs (like MyFitnessPal, Google Fit, or manual Excel imports) to automate data entry instead of manual logs.

**Dynamic Goal Setting:**

Allow users to input or adjust macro goals over time and track progress toward changing targets.

**Mobile-Optimized Layout:**

Redesign dashboard layout for better mobile/tablet responsiveness.

**Nutritional Insights/Alerts:**

Generate health tips or alerts when certain thresholds (e.g., excess fat, low protein) are crossed.

**Meal Suggestions:**

Recommend food items to help meet daily macro goals based on gaps identified.








