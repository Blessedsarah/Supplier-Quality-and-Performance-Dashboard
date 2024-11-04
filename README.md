# Supplier-Quality-and-Performance-Dashboard

### Project Overview
This project provides Enterprise Manufacturers Ltd. with a comprehensive overview of supplier quality performance, highlights key metrics, such as defect quantities, downtime, and their impacts on overall operations, centralizing critical supplier data to improve quality management and procurement efficiency. By analyzing these metrics, Enterprise Manufacturers can make data-driven decisions to minimize downtime, enhance supplier quality, and optimize operational processes.

### Tools and Data Soure
- **Tools:** Power BI, DAX
- **Data Sources:** Supplier data was provided by Tina Okonkwo for Enterprise Manufacturers Ltd, a pseodu company. This dataset included columns such as date, vendor, plant location, category, material type, defect type, total defect quantity, and total downtime minutes

### Data Preparation Process
The data preparation process included normalizing and structuring the supplier data for more effective analysis. The following steps were taken:

**Normalization:** The original dataset was broken down into several tables for a more organized data model:

- **Vendor Table**: Contains unique vendors and their details.
- **Plant Table:** Lists plant locations associated with each vendor.
- **Category Table:** Specifies supplies categories.
- **Material Type Table:** Distinguishes various material types.
- **Defect Type Table:** Classifies types of defects.
- **Defect Table:** Logs defect occurrences with relevant metrics, such as quantity and downtime.

**Data Modeling:** Relationships were established between the facts and dimenwion tables using primary and foreign keys. 

![image](https://github.com/user-attachments/assets/06ebff7c-6e08-4563-a1ad-e547bbbd9c89)

**Date Table Creation:** A custom date table was generated in Power BI using DAX measures to support time-based analysis. This table allows for tracking trends and patterns over time.

![image](https://github.com/user-attachments/assets/f723a253-f807-4c61-bf15-9d55c8775702)







