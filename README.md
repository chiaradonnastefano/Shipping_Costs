## 🚚 Project Overview

This project aims to **optimize shipping routes and reduce associated costs** by intelligently assigning customer orders to the most suitable plants and carriers. The goal is to **minimize total shipping costs** while satisfying a variety of business rules and operational constraints.

---

## 🎯 Key Objectives

- Assign orders to the most **cost-effective plant** for fulfillment.  
- Choose the **optimal port** for dispatching each order to minimize shipping expenses.

---

## 📌 Constraints & Considerations

- **Product-Plant Compatibility**: Each plant can only process specific product types.
- **Plant-Port Connectivity**: Plants are only connected to certain ports, which limits routing options.
- **Vendor Managed Inventory (VMI)**: Some customers require order fulfillment from designated VMI-assigned plants.
- **Customer-Specific Plant Assignment**: Certain customers can only be served by specific plants.
- **Physical Connectivity**: Only physically connected plant-port pairs are considered valid.
- **Item Handling Restrictions**: Plants are constrained by the types of items they can handle.
