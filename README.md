# Insurance-Risk-Claim-Analysis
Power BI


# 🚗 Insurance Risk & Claims Analysis

## 📄 Domain Document

This dataset contains detailed information about **car insurance policyholders**, their vehicles, and their **claim history**. Each record represents an individual customer with demographic details such as **birthdate, gender, marital status, education level, household income, and parental status**. These attributes help understand customer profiles and how personal characteristics may influence driving behavior and insurance risk.

The dataset also captures details about the insured vehicle, including **car make, model, color, year of manufacture, and usage type** (personal, commercial, or commuting). Combined with the **coverage zone**, this information helps assess environmental and vehicle-related risk factors. For example, an older commercial car in an urban area may carry a different risk profile compared to a new personal car in a rural zone.

On the financial and claims side, the dataset includes **claim amount, claim frequency, and household income**. These fields are critical for evaluating customer value and risk. Households with multiple young drivers may signal higher risk.  

Overall, this dataset can be used to build **Power BI dashboards** for:
- Claims analysis  
- Customer segmentation  
- Risk profiling  
- Premium optimization  

Insights derived can help insurance companies design fairer pricing models, identify high-risk segments, detect potential fraud, and improve customer targeting strategies.  

---

## 📝 Dataset Fields

### 1️⃣ ID
- **Definition:** Unique identifier for each policyholder or insurance record  
- **Type:** Numeric / Text (Primary Key)  
- **Details:** Ensures uniqueness; not used directly in analysis  
- **Business Use:** Track policyholders across datasets  

### 2️⃣ Birthdate
- **Definition:** Date of birth of the policyholder  
- **Type:** Date  
- **Details:** Used to calculate **Age**, a key factor in risk assessment  
- **Business Use:** Segment customers into age groups and price premiums accordingly  

### 3️⃣ Car Color
- **Definition:** Exterior color of the car  
- **Type:** Categorical (Text)  
- **Details:** May influence visibility, theft probability, and preferences  
- **Business Use:** Detect patterns or unusual claims  

### 4️⃣ Car Make
- **Definition:** Manufacturer/brand (e.g., Toyota, BMW)  
- **Type:** Categorical  
- **Details:** Different makes have varying repair costs and accident likelihood  
- **Business Use:** Analyze claims by brand; assist underwriting  

### 5️⃣ Car Model
- **Definition:** Specific car model (e.g., Corolla, X5)  
- **Type:** Categorical  
- **Details:** Granularity beyond make; risk varies by model  
- **Business Use:** Compare claims for luxury vs economy models  

### 6️⃣ Car Use
- **Definition:** Primary purpose (Personal, Commercial, Commute)  
- **Type:** Categorical  
- **Details:** Commercial/commuting cars usually have higher claim rates  
- **Business Use:** Pricing and risk profiling  

### 7️⃣ Car Year
- **Definition:** Manufacturing year of the car  
- **Type:** Numeric  
- **Details:** Calculate **Car Age** = Current Year – Car Year  
- **Business Use:** Segment by vehicle age (New, Mid-age, Old)  

### 8️⃣ Coverage Zone
- **Definition:** Geographic risk area (e.g., Urban, Rural)  
- **Type:** Categorical  
- **Details:** Impacts accident probability, theft risk, repair costs  
- **Business Use:** Regional comparison; mapping dashboards  

### 9️⃣ Education
- **Definition:** Highest education level (High School, Graduate, Postgraduate)  
- **Type:** Categorical  
- **Details:** Correlates with income and risk behavior  
- **Business Use:** Marketing campaigns and segmentation  

### 🔟 Gender
- **Definition:** Gender (Male, Female, Other)  
- **Type:** Categorical  
- **Details:** Gender differences in claims may exist  
- **Business Use:** Demographic breakdowns in dashboards  

### 1️⃣1️⃣ Marital Status
- **Definition:** Single, Married, Divorced, etc.  
- **Type:** Categorical  
- **Details:** Married people may be lower risk  
- **Business Use:** Compare claims and adjust risk  

### 1️⃣2️⃣ Parent
- **Definition:** Has children (Yes/No)  
- **Type:** Boolean / Categorical  
- **Details:** Driving behavior may differ  
- **Business Use:** Segment claims by parent status  

### 1️⃣3️⃣ Claim Amt
- **Definition:** Total monetary value of claims  
- **Type:** Numeric (Currency)  
- **Details:** Measures insurance losses  
- **Business Use:** Calculate total/average losses; detect high-cost claims  

### 1️⃣4️⃣ Claim Freq
- **Definition:** Number of claims filed  
- **Type:** Numeric (Integer)  
- **Details:** Indicates risk behavior  
- **Business Use:** KPI for risk assessment; identify high-frequency vs high-severity risk  

### 1️⃣5️⃣ Household Income
- **Definition:** Annual income of household  
- **Type:** Numeric  
- **Details:** Impacts affordability of premiums  
- **Business Use:** Segment income bands; compare claim patterns; target offers  

### 1️⃣6️⃣ Kids Driving
- **Definition:** Number of licensed kids in the household  
- **Type:** Numeric (Integer)  
- **Details:** More young drivers = higher accident probability  
- **Business Use:** Group into categories (None, 1 Kid, 2 Kids, 3+ Kids); estimate household risk  

---

## 📊 Use Cases
- Build **Power BI dashboards** for:
  - Claims and loss analysis  
  - Customer segmentation  
  - Risk profiling  
  - Premium optimization  
- Detect **fraud patterns**  
- Design fairer **pricing models**  
- Improve **marketing and customer targeting**  

---

