# python_projects_Chocolate_house_webapp
In this python project, we will build a grocery store management application. It will be 3 tier application,
1. Front end: UI is written in HTML/CSS/Javascript/Bootstrap
2. Backend: Python and Flask
3. Database: mysql



 Installation Instructions

Download mysql for windows: https://dev.mysql.com/downloads/installer/

`pip install mysql-connector-python`

 Exercise 

After initial deployment, users provided feedback. The exercises below guide you in enhancing the application based on this feedback:

1. Flavors Module (formerly Products Module):
   - Add an edit button next to the delete button for managing current seasonal flavors allowing you to modify details as necessary.
   
2. Flavors Module:
   - Implement a new form for adding Unit of Measurement (UOM) such as "Box" or "Kilogram" to manage different quantities of chocolates. This enhancement affects both the backend (Python server) and the frontend (UI).

3. Orders Module:
   - Add front-end validation to ensure all fields are correctly filled out. For instance, the customer's name, chocolate flavor, and quantity should all be validated to prevent submission of invalid orders.

4. Orders Module:
   - Address a bug where manually changing the total price of an item does not update the overall grand total. Ensure that changes reflect across all totals seamlessly.

5. Orders Module:
   - Include a "View" button in the grid displaying orders. Clicking this should reveal detailed insights into each order, such as individual item prices, indicated quantities, and total calculations.

 Conclusion

This Chocolate House Management application fosters efficient management of chocolate-related operations, from flavor offerings to inventory and customer orders. Improvements based on user feedback aim to enhance both functionality and user experience.


