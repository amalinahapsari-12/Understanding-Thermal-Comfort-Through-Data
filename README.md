# Understanding Thermal Comfort Through Data

### Project Overview  
Thermal comfort describes how people **feel** in an indoor environment — whether they perceive it as too cold, too warm, or just right.  
This project explores **how people’s thermal sensations vary** under different environmental and personal conditions.

Using the **Thermal Sensation Vote (TSV)** scale  
(-3 = Cold → 0 = Neutral → +3 = Hot), I analyzed how **climate, building type, gender,** and **air temperature** influence thermal perception.

The goal is not to provide definitive answers, but to **observe and understand comfort patterns** that can inform better, more energy-efficient building designs.

---

## Key Questions  
- How are thermal sensations distributed among people overall?  
- Do different **climates** affect how people perceive comfort?  
- How closely does **air temperature** relate to how people actually feel?  
- Are there noticeable comfort trends across **building types**?  
- Do **men and women** experience thermal environments differently?

---

## Tools Used  
- **Python** (Matplotlib, NumPy, Pandas) — data analysis & visualization  
- **Excel** — preliminary data cleaning  
- **Matplotlib RdYlBu_r palette** — color mapping of thermal sensations  
- **Jupyter Notebook** — for analysis workflow and documentation

---

## Visualizations & Insights  

### Thermal Sensation Distribution  
![Histogram](images/hist_tsv_final_adjusted.png)  
Most responses cluster around **neutral to slightly warm**, suggesting that many people experience acceptable comfort.  
Colors follow the TSV scale — from cool (blue) to warm (red).

---

### TSV by Climate  
![Climate](images/box_tsv_climate_enhanced.png)  
People in **hotter climates** tend to report **warmer sensations** even at similar air temperatures.  
This indicates that **climate adaptation** affects comfort perception.

---

### Air Temperature vs. Thermal Sensation  
![Scatter](images/scatter_ta_tsv_horizontal_scale.png)  
A **positive correlation** appears: as air temperature rises, so does perceived warmth.  
The red trend line highlights this pattern, while variation shows individual differences.

---

### Average TSV by Building Type  
![Building Type](images/bar_tsv_building_type_fixed.png)  
Comfort varies by building function — **offices** are near neutral, while **residential and educational** spaces show slightly different tendencies.  
Design and usage clearly shape comfort experiences.

---

### TSV by Gender  
![Gender](images/box_tsv_gender_styled_v2.png)  
On average, **women** report slightly **cooler sensations** than men, though the difference is small.  
This aligns with earlier studies while emphasizing that comfort depends on context.

---

## Overall Storyline  
Thermal comfort is influenced by many factors — **temperature, climate, building use, and personal traits** all play a role.  
By visualizing these relationships, we gain insights into how people adapt and perceive their environments, guiding **human-centered, energy-conscious design**.

---

## Closing Message  
This project highlights the value of combining **data and human experience**.  
Numbers alone can’t describe comfort — but when analyzed thoughtfully, they reveal patterns that help us create **more inclusive, adaptive, and comfortable indoor environments**.

---

### 📁 Repository Structure  
thermal-comfort-analysis/
│
├── data/ # Cleaned TSV dataset (optional)
├── images/ # All visualization outputs
├── notebook/ # Jupyter notebook
│ └── thermal_comfort_analysis.ipynb
└── README.md
