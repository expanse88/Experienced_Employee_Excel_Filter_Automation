---

# Employee Experience Filter Automation

This UiPath automation processes employee data stored in Excel and identifies employees with more than **3 years of experience**. It simplifies HR reporting tasks by automatically filtering and exporting the required data.

---

## 📌 Features

* Reads employee data from an Excel file.
* Applies a filter to select rows where **Experience > 3 years**.
* Writes the filtered results into a new sheet named **"Experienced"**.
* Fully automated using UiPath (no manual intervention needed).

---

## 📂 Project Structure

* `Main.xaml` → Contains the automation workflow.
* `EmployeeData.xlsx` → Input Excel file with employee records.
* `Experienced.xlsx` → Output file with filtered employee data.

---

## 🛠️ Technologies Used

* **UiPath Studio**
* **Excel Application Scope**
* **Excel Activities**

---

## 🚀 How to Run

1. Open the project in **UiPath Studio**.
2. Place your input Excel file (`EmployeeData.xlsx`) in the project folder.
3. Run the workflow.
4. The filtered data will be saved into `Experienced.xlsx` (or a new sheet if using the same file).

---

## 📊 Example

**Input (EmployeeData.xlsx):**

| Name    | Department | Experience |
| ------- | ---------- | ---------- |
| Alice   | HR         | 2          |
| Bob     | IT         | 4          |
| Charlie | Finance    | 5          |

**Output (Experienced.xlsx):**

| Name    | Department | Experience |
| ------- | ---------- | ---------- |
| Bob     | IT         | 4          |
| Charlie | Finance    | 5          |

---

## 🎯 Use Case

This automation is useful for:

* HR teams filtering experienced employees for promotions, appraisals, or training programs.
* Automating routine Excel-based filtering tasks.
* Saving manual effort and reducing errors.

---

## 📌 Author

Developed by Harshit Nahata👨‍💻

---
 
