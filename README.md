# 🚗 Unlocking Automotive Trends – Python for Data Science

## 📌 Project Overview  
This project leverages **Python for Data Science** to explore and analyze an automotive dataset.  
Through exploratory data analysis (EDA), visualization, and statistical insights, the project uncovers:  
- **Customer preferences** (body type, fuel efficiency, features)  
- **Performance trends** (mileage, displacement, engine design)  
- **Safety & design patterns** (safety features, seating capacity, vehicle dimensions)  
The goal is to identify key **automotive market trends**, helping manufacturers, researchers, and consumers understand trade-offs between **efficiency, safety, and performance**.  

---

## 🛠️ Tools & Technologies  
- **Language:** Python  
- **Libraries:** Pandas · NumPy · Matplotlib · Seaborn  
- **Methods:** EDA · Data Cleaning · Visualization · Outlier Handling · Correlation Analysis  

---

## 🚀 Key Insights  

### 🏷️ Car Body Types & Preferences  
- **SUVs** are most preferred (447 units), followed by **Sedans (333)** and **Hatchbacks (316)**.  
- Coupes (41) and MUVs (39) are less popular among the top five.  

### ⚙️ Driving Modes & Variability  
- Only **2 cars support all driving modes** (Normal, Comfort, Eco, Sport, Power).  
- **195 cars** provide a mix of some modes → showing rarity of fully versatile vehicles.  

### ⛽ Fuel Efficiency Trends  
- **E Verito variants** dominate top eco-friendly models (~63.44 MPG).  
- **E20 Plus variants** also excel (~48.44 MPG).  
- Strong focus on electric & hybrid designs for manufacturers.  

### 🏭 Manufacturer Comparisons  
- **City Mileage Leaders (Top 10):** Renault (~19.5 km/l) → Volkswagen (~16 km/l).  
- **Outlier:** Lamborghini (~6.29 km/l), lowest city mileage.  
- Among 4 compared brands:  
  - Renault leads in city mileage (~19.5 km/l).  
  - Skoda lags (~14.5 km/l).  
  - Highway mileage is similar across all four.  
- **High performers overall:** Datsun, Maruti Suzuki, Renault (~18.8 km/l).  
- **Low performers:** Bentley, Maserati (luxury → focus on performance, not mileage).  

### 📊 Engine Displacement & Mileage  
- Weak **negative correlation**: Higher displacement → Lower city mileage.  
- Outliers detected (possible data errors or hybrid exceptions).  

### 🏎️ Manufacturer Variability  
- **Bugatti & Bentley** → very consistent displacement (0% variation).  
- **Audi & Ford** → high variability (37–41%), offering diverse engine options.  

### ⚖️ Weight & Design Features  
- **Bentley & Bugatti** → highest kerb & gross weights (premium designs).  
- **Bajaj & Datsun** → lowest variability, indicating consistent lightweight vehicles.  

### 🛡️ Safety & Convenience Features  
- **Most common safety features:**  
  - Airbags (highest coverage)  
  - ABS  
  - Hill Assist (least common)  
- **Convenience focus:**  
  - Central locking (1,127 cars)  
  - Child safety locks (1,201 cars)  
- **Warning systems:**  
  - Fasten Seat Belt Warning (~95%) → most common  
  - Door Ajar Warning  
  - High Speed Alert System  

### 📏 Vehicle Dimensions  
- Average car dimensions:  
  - Height → **1,593 mm**  
  - Length → **4,297 mm**  
  - Width → **1,789 mm**  
- **Luxury brands (Bentley, Bugatti):** Larger, spacious builds.  
- **Compact brands (Bajaj, Fiat):** Smaller, urban-oriented vehicles.  

---

## 📊 Visualizations  
- **Bar Charts:** Body type preferences, manufacturer mileage comparisons  
- **Line Charts:** Mileage vs. displacement trends  
- **Histograms:** Mileage distribution by brand  
- **Correlation Matrix:** Feature dependencies across manufacturers  
- **Stacked Columns:** Mean vs. median city mileage  
- **Distribution Charts:** Safety & convenience features  

---

## ✅ Summary  
The **Unlocking Automotive Trends Project** provides an in-depth exploration of automotive data to highlight:  
- **Consumer preferences** (SUV dominance, mileage-focused electric cars)  
- **Manufacturer strengths/weaknesses** (Renault as an efficiency leader, Lamborghini as a low-mileage outlier)  
- **Design trade-offs** (luxury cars = performance + size vs compact cars = efficiency)  
- **Safety standards** (airbags & warnings nearly universal, hill assist less common)  

This analysis helps identify how **fuel efficiency, safety, and design priorities** differ across manufacturers and market segments, offering valuable insights for both **industry decision-making** and **customer awareness**.  


