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

### **Credits**
- **Data Source**: [The Himalayan Database](https://www.himalayandatabase.com/downloads.html)
- **Curator**: [Nicolas Foss, Ed.D., MS](https://www.linkedin.com/in/nicolas-foss)