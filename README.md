### Dataset Documentation: The History of Himalayan Mountaineering Expeditions

This documentation provides an overview of the two datasets (`EXPEDITION_DATA.csv` and `PEAKS_DATA.csv`) related to Himalayan mountaineering expeditions. The data is sourced from **The Himalayan Database**, which documents climbing expeditions in the Nepal Himalaya. The datasets are rich in historical and geographical information, making them ideal for exploring trends, success rates, and other aspects of mountaineering.

---

### **Dataset Overview**

#### **1. `EXPEDITION_DATA.csv`**
This dataset contains detailed information about mountaineering expeditions, including their outcomes, routes, and other expedition-specific details.

- **Key Variables:**
  - **EXPID**: Unique expedition ID.
  - **PEAKID**: Unique peak ID (links to `PEAKS_DATA.csv`).
  - **YEAR**: Year of the expedition.
  - **SEASON_FACTOR**: Season of the expedition (e.g., Spring, Summer, Autumn, Winter).
  - **HOST_FACTOR**: Host country of the expedition (e.g., Nepal, China, India).
  - **ROUTE1, ROUTE2, ROUTE3, ROUTE4**: Climbing routes used.
  - **SUCCESS1, SUCCESS2, SUCCESS3, SUCCESS4**: Logical values indicating success on each route.
  - **TERMREASON_FACTOR**: Reason for expedition termination (e.g., bad weather, technical difficulty, success).
  - **O2USED, O2NONE**: Use of supplemental oxygen.
  - **TOTMEMBERS**: Total number of expedition members.
  - **MDEATHS, HDEATHS**: Number of member and hired personnel deaths.
  - **NOHIRED**: Logical value indicating if no hired personnel were used.

#### **2. `PEAKS_DATA.csv`**
This dataset contains information about the peaks in the Himalayas, including their height, location, and climbing status.

- **Key Variables:**
  - **PEAKID**: Unique peak ID (links to `EXPEDITION_DATA.csv`).
  - **PKNAME, PKNAME2**: Names of the peak.
  - **HEIGHTM, HEIGHTF**: Height of the peak in meters and feet.
  - **HIMAL_FACTOR**: Mountain range the peak belongs to (e.g., Annapurna, Dhaulagiri, Khumbu).
  - **REGION_FACTOR**: Region of the peak (e.g., Khumbu-Rolwaling-Makalu, Langtang-Jugal).
  - **OPEN**: Logical value indicating if the peak is open for expeditions.
  - **PSTATUS_FACTOR**: Climbing status of the peak (e.g., Unclimbed, Climbed).
  - **PYEAR**: Year of the first recorded climbing attempt.
  - **PSMTDATE**: Date of the first successful summit.

---

### **Here are some questions you can explore. The grading will depend on the difficulty of the questions, and not all questions are mandatory; you may explore others on your own as well.**


---

### **General Trends**  
1. **How has the number of expeditions changed over the years?** *(Analyze expedition count by year.)* **(10 marks)**  
2. **Which seasons are most popular for expeditions?** *(Analyze expedition count by season.)* **(8 marks)**  
3. **Which countries host the most expeditions?** *(Analyze expedition count by host country.)* **(8 marks)**  

---

### **Peak-Specific Analysis**  
4. **Which mountain range has the highest average peak height?** *(Find the highest avg. height per mountain range.)* **(10 marks)**  
5. **What is the distribution of climbing statuses across different mountain ranges?** *(Compare peak statuses across ranges.)* **(8 marks)**  
6. **Are there differences in peak heights between open and closed peaks?** *(Compare peak heights for open vs. closed peaks.)* **(8 marks)**  

---

### **Expedition Outcomes**  
7. **Which climbing routes have the highest success rates?** *(Find success rate per climbing route.)* **(10 marks)**  
8. **How does the use of supplemental oxygen affect summit success rates?** *(Compare success rates for oxygen users vs. non-users.)* **(10 marks)**  
9. **What are the most common reasons for expedition termination?** *(Find the most frequent termination reasons.)* **(8 marks)**  
10. **Are expeditions with no hired personnel associated with higher or lower death rates?** *(Compare death rates for expeditions with vs. without hired personnel.)* **(10 marks)**  

---

### **Geographical and Historical Insights**  
11. **Which regions have the highest number of unclimbed peaks?** *(Find regions with most unclimbed peaks.)* **(8 marks)**  
12. **What is the historical trend of first ascents over time?** *(Analyze the trend of first recorded ascents by year.)* **(6 marks)**  
13. **Which peaks have the most disputed or claimed successes?** *(Identify peaks with the highest disputed/claimed records.)* **(6 marks)**  

---

### **Total: 100 marks**  

---


### **Some Ideas**  
- **Line Chart**: Show trends in expedition counts or first ascents over time.  
- **Bar Chart**: Compare the number of expeditions across seasons, countries, or mountain ranges.  
- **Stacked Bar Chart**: Visualize the distribution of climbing statuses within different regions.  
- **Box Plot**: Compare peak heights for open vs. closed peaks or success rates with vs. without oxygen.  
- **Heatmap**: Show the correlation between expedition success rates and climbing conditions.  
- **Scatter Plot**: Explore relationships between peak height and expedition success.  
- **Pie Chart**: Display the proportions of different expedition termination reasons.  
- **Histogram**: Show the frequency distribution of first ascents or expedition years.  

---

### **Credits**
- **Data Source**: [The Himalayan Database](https://www.himalayandatabase.com/downloads.html)
- **Curator**: [Nicolas Foss, Ed.D., MS](https://www.linkedin.com/in/nicolas-foss)
- **Image Credit**: Cover of the book *Himalayas by the Numbers* by The Himalayan Database organization.
