# Health Analysis Census

The Health Analysis Census is a web-based application designed to record and analyze patient health data while providing detailed information about specific health conditions. It is ideal for small-scale healthcare data management and educational purposes.

## Features

1. **Patient Data Management**:
   - Add patients with attributes such as name, gender, age, and condition.
   - Generate a real-time report summarizing:
     - Total number of patients.
     - Breakdown of conditions.
     - Gender-based condition analysis.

2. **Condition Search**:
   - Search for detailed information about specific health conditions using the search bar.
   - Retrieve data from an external JSON file (`health_analysis.json`), including:
     - Symptoms
     - Prevention methods
     - Treatment options
     - Associated images

3. **Interactive Interface**:
   - Easy-to-use form for patient data entry.
   - Dynamically updated report for instant analytics.
   - Intuitive search functionality with informative results.

## Project Structure

### **HTML**
- Defines the structure of the application, including:
  - Navigation menu with links and search functionality.
  - A form for patient data entry.
  - A report section to display analytics.
  - A results section for health condition search.

### **CSS**
- Provides styling for the interface to make it visually appealing and user-friendly.

### **JavaScript**
- Manages application logic, including:
  - Handling patient data entry and analytics.
  - Fetching and displaying health condition data from a JSON file.

### **JSON**
- External data file (`health_analysis.json`) containing predefined information about various health conditions.


