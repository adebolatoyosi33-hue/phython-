# phython
Drug inventory report
# Drug Inventory Management System

## Project Goal

The objectives of this project are to:

- Track the inventory levels of pharmaceutical products.
- Calculate the remaining stock after customer purchases.
- Compute the total revenue generated from drug sales.
- Determine whether drugs need to be restocked based on inventory thresholds.
- Identify expired drugs that should not be sold.
- Demonstrate the use of Python fundamentals to solve a real-world pharmacy inventory problem.

---

## Data Source

A sample pharmacy inventory dataset containing information for two drugs:

| Information | Value |
|------------|-------|
| Drug Name | Paracetamol |
| Category | Pain Reliever |
| Initial Stock | 250 units |
| Units Sold | 120 units |
| Unit Price | ₦500 |
| Expired | False |

### Bonus Challenge

| Information | Value |
|------------|-------|
| Drug Name | Amoxicillin |
| Category | Antibiotic |
| Initial Stock | 180 units |
| Units Sold | 70 units |
| Unit Price | ₦1,200 |
| Expired | True |

---

## Tools Used

- Python
- Jupyter Notebook
- Variables
- Numeric Data Types
- Arithmetic Operators
- Comparison Operators
- Boolean Expressions
- Conditional Statements
- Print Statements

---

## Methods

- Store drug information using Python variables.
- Calculate remaining inventory after sales.
- Compute revenue generated from each drug.
- Compare remaining stock with the restocking threshold.
- Evaluate whether a drug has expired.
- Display inventory reports and recommendations using conditional logic.

---

## Findings

- **Paracetamol** generated sales revenue while maintaining sufficient stock levels after sales.
- The inventory management logic successfully determined whether restocking was required.
- **Amoxicillin** was correctly flagged as expired and should not be sold despite remaining inventory.
- The project demonstrates how simple Python programming concepts can automate inventory monitoring and improve pharmacy operations.

---

## Recommendations

- Regularly monitor inventory levels to avoid stock shortages.
- Restock drugs before inventory reaches the minimum threshold.
- Remove expired drugs immediately to ensure patient safety.
- Automate inventory updates by integrating the system with a database.
- Expand the system to support multiple products and daily sales records.

---

## Limitations

- The project uses a small sample dataset with only two drugs.
- Inventory information is stored using variables instead of a database.
- Restocking thresholds are predefined and not dynamically calculated.
- The system is designed for educational purposes and does not include a graphical user interface.

---

## Sample Output

```python
Drug Name: Paracetamol
Initial Stock: 250
Units Sold: 120
Remaining Stock: 130

Revenue Generated: ₦60,000

Restock Required: False

----------------------------------

Drug Name: Amoxicillin
Initial Stock: 180
Units Sold: 70
Remaining Stock: 110

Revenue Generated: ₦84,000

Expired Drug: True
Do Not Sell: True
```

---

## How to Run

1. Clone this repository:

```bash
git clone https://github.com/Teeolulope/Drug-Inventory-Management-System.git
```

2. Open **gift assignment.ipynb** in Jupyter Notebook or JupyterLab.

3. Run all cells from top to bottom to reproduce the inventory analysis and reports.

---

## Author

**Toyosi Adebola**
