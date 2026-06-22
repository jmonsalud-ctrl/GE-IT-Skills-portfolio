### Data Analytics & Visual Report

#### Dataset Focus: Samal Island Tourism and Coastal Waste Monitoring Dataset (Mock CSV Analysis)

#### 1. Data Cleaning Protocol Log

- **Raw Input Problem:** The CSV file contained missing values in the monthly tourist arrival records, inconsistent waste measurement units (kilograms and metric tons), and duplicate entries from multiple barangay reporting offices.
- **AI Cleaning Instruction:**  
  `"Scan the dataset. Identify all null values in the Tourist Arrivals and Coastal Waste columns. Replace missing values using the median value of the corresponding month. Standardize all waste measurements to Metric Tons (MT), remove duplicate records, and output the first 5 rows of the cleaned dataset."`
- **Result:** Successfully normalized 156 records across 12 coastal barangays and standardized all environmental monitoring metrics into a single reporting format.

#### 2. Visualizations Generated

##### Chart 1: Annual Tourist Arrivals in Samal Island (2020–2025)

*Embedded High-Contrast Line Chart: Annual Tourist Arrivals in Samal Island (2020–2025)*

![Annual Tourist Arrivals Chart](media/Samal_Tourist_Chart.png)

##### Chart 2: Coastal Waste Collected vs Tourist Arrivals

*Embedded High-Contrast Bar Chart: Coastal Waste Generation Trends (2020–2025)*

![Coastal Waste Trend Chart](media/Samal_Coastal_Waste_chart.png)

#### 3. Human Analytical Narrative (The 'Why' Factor)

"The visuals reveal a steady but great increase of tourist arrivals in Samal Island following the reopening and recovery period after the pandemic. Between 2020 and 2025, visitor numbers nearly tripled, demonstrating the island's growing importance as a tourism destination within the Davao Region.

However, the second chart also highlights an increase in coastal waste generation. While the automated AI analysis initially interpreted this trend as a simple consequence of tourism growth, a more human review suggests a pretty complex relationship. Due to the increased visitor activity, These findings emphasize the importance of sustainable tourism planning. Local government units should mostly consider expanding waste collection programs as these may threaten the very ecosystems that attract visitors to Samal Island in the first place.

The analysis demonstrates how AI-assisted data cleaning and visualization can rapidly identify patterns, but ultimately human interpretation remains absolutely essential for statistical trends to real-world environmental and community impacts."
``
