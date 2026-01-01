# Digital Twin of Urban Air Pollution Control System (Vensim)

This project presents a **system dynamics–based Digital Twin** of an urban air pollution system, developed using **Vensim PLE**.  
The model simulates how air pollution evolves over time under the influence of **policy interventions, electric vehicle adoption, green cover dynamics, industrial emissions, and atmospheric conditions**.

---

## 📌 Project Objective
To create a Digital Twin that helps:
- Understand long-term air pollution behavior
- Analyze the impact of environmental policies
- Evaluate sustainability strategies before real-world implementation

---

## 🧠 What Makes This a Digital Twin?
The model dynamically mirrors a real-world city system by:
- Reacting to pollution levels
- Adjusting policies automatically
- Simulating delayed and nonlinear responses
- Incorporating seasonal atmospheric effects

---

## 🧱 Model Structure

### 🔵 Stocks
- **Air Pollution Level** – Accumulated pollution in the city
- **Green Cover** – Vegetation contributing to pollution absorption
- **EV Adoption Level** – Fraction of vehicles converted to electric

### 🟢 Flows
- Pollution Generation
- Pollution Absorption
- Tree Plantation
- Deforestation
- EV Adoption Increase

### 🟡 Auxiliary Variables
- Vehicle Emissions
- Industrial Emissions
- Policy Strength
- Atmospheric Dispersion Factor
- Pollution Damage Effect (lookup)
- Population Growth Factor

---

## 🔁 Key Feedback Loops
1. **Pollution → Policy → EV Adoption → Vehicle Emissions → Pollution**
2. **Pollution → Policy → Tree Plantation → Green Cover → Pollution Absorption**
3. **Seasonal Weather → Atmospheric Dispersion → Pollution Absorption**

---

## ⚙️ Important Equations (Conceptual)

- **Air Pollution Level**

- **Policy Strength**

- **EV Adoption Level**

- **Pollution Absorption**
- 
## 🌦️ Advanced Features
- Nonlinear policy response using lookup functions
- Seasonal atmospheric dispersion effects
- Saturation limits on green cover growth
- Time delays and feedback-driven behavior

---

## 📊 Simulation Scenarios
- No policy intervention
- Moderate environmental policy
- Strong policy enforcement

Each scenario demonstrates different pollution trajectories over time.

---

## 🛠 Tools Used
- **Vensim PLE**
- System Dynamics Modeling
- 
## 📈 Results
The Digital Twin shows:
- Initial pollution growth due to population and emissions
- Policy-triggered stabilization
- Long-term pollution reduction through EV adoption and green cover expansion

---

## 🚀 Future Enhancements
- Integration with real-time air quality sensor data
- Health impact modeling (hospital load)
- Economic cost of pollution
- Machine learning–based emission forecasting

Digital-Twin-Air-Pollution/
├── model/
│   └── air_pollution_digital_twin.mdl
├── results/
│   ├── pollution_scenario_1.png
│   ├── pollution_scenario_2.png
│   └── pollution_scenario_3.png
├── README.md
