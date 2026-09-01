# MRP-Project

## INTRODUCTION
In this project, I act as a Production Planning & Inventory Control (PPIC) staff member tasked with preparing a multi-level Material Requirements Planning (MRP) template to help the company translate finished goods requirements into component requirements based on the Bill of Materials (BOM) structure. I will create an MRP template capable of calculating gross requirements, scheduled receipts, projected available balance, net requirements, planned order receipts, and planned order releases, taking into account lot sizing and lead time. The output of this project will serve as my tool to plan material requirements in a more structured manner, reduce the risk of component shortages, and align production plans with material procurement. Previously, material requirements were often calculated manually based on rough estimates of finished goods demand. As a result, the production team experienced several delays because lower-level components were not available when needed. Management has requested that I build a multi-level MRP template that connects finished goods demand from the Master Production Schedule (MPS) with the BOM structure, available inventory, scheduled receipts, lot size, and lead time for each item. This template must enable me to determine when materials need to be ordered or produced so they are available on time to meet production requirements.

## BACKGROUND 🔖
This study case and the data i got from IODA ACADEMY PPIC Workshop

## USED TOOL 🧰
EXCEL

## CONTENT LEARNED AND APPLIED SKILLS 📚 📝
1. Material Requirement Planning (MRP)
2. Multi-Level Bill of Material
3. Lot Sizing
4. Lead Time Offset
5. Net Requirement Calculation
6. Planned Order Release

## ANALYSIS
1. Calculate gross requirements for each item. Gross requirements for parent items are obtained from MPS calculations. Meanwhile, for level 1 items, gross requirement calculations are based on the planned order releases of parent items. Likewise, for level 2 items, they are based on the planned order releases of level 1 items.
2. Calculating projected on-hand inventory by adding scheduled receipts, previous week's on-hand inventory, and planned order receipts, then subtracting gross requirements.
3. Net requirements represent the net material needed before placing an order.
4. Determining planned order receipts based on net requirements and the applicable lot sizing rules for each item.
5. Shifting planned order receipts to planned order releases according to the lead time of each item.

## RESULT
<img width="1138" height="426" alt="image" src="https://github.com/user-attachments/assets/902cac80-78a3-4933-ab93-b7e6e1c5c54d" />


