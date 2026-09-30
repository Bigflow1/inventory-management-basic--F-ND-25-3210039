# F/ND/25/3210039
# Feature 1 
# Feature Name: 
  Supplier Performance and Lead-Time Tracker
# ​Description: 
  A tracking feature that monitors past supplier delivery timelines and automatically adjusts reordering schedules if a vendor consistently delivers late.
# ​Purpose: 
  To factor real-world supply chain bottlenecks into the reordering timeline before stock runs out.
# ​How It Works: 
  It logs the date a purchase order was placed versus the date goods were actually received, calculating an average delay variance for each vendor.
# ​Information Required: 
  Purchase order creation date, expected delivery date, actual goods receipt date, and vendor ID.
# ​Output / Action: 
  Automatically extends the lead-time parameter for specific vendors and triggers earlier reorder warnings to compensate for expected delays.
# ​Benefits: 
  Prevents unexpected stockouts caused by slow suppliers and improves vendor accountability.
# ​Limitations / Dependencies: 
  Requires staff to accurately log goods receipt dates immediately upon delivery arrival.
# ​Sources: 
  Supply Chain Management Best Practices

# Feature 2

# ​Feature Name: 
  Automated Reorder Point (ROP) Calculation
# ​Feature Name: 
  Dynamic Economic Order Quantity (EOQ) & Reorder Point Calculator
# ​Description: 
  A tool that continuously recalculates stock thresholds based on historical sales velocity and supplier lead times rather than using static minimums.
# ​Purpose: 
  To prevent stockouts of fast-moving items while minimizing excess holding costs for slow-moving goods.
# ​How It Works: 
  The system tracks daily sales averages and lead-time delays, automatically updating the threshold where a new purchase order must be triggered.
# ​Information Required: 
  Average daily consumption rate, supplier lead time in days, safety stock buffer, and current inventory level.
# ​Output / Action: 
  Generates a low-stock alert or auto-creates a purchase order draft when stock hits the newly calculated threshold.
# ​Benefits: 
  Eliminates manual monitoring, reduces human error, and adapts automatically to seasonal buying trends.
# ​Limitations / Dependencies: 
  Relies heavily on accurate, real-time sales logging; sudden spikes in demand can temporarily throw off predictive averages until updated.
# ​Sources: 
  Internal System Logic & Inventory Optimization Principles
