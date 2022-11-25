# Lab 8
1. Create an empty project for an online laptop shop  
2. Install json-server globally for using it as a fake backend  
3. Define the interface for the laptop with the following fields: id(guid), modelName, price  
4. Create json-server config for laptops' fake backend  
5. Create service and implement crud operations for laptops:  
   create  
   update  
   delete  
   The service should call json-server laptops endpoint using httpclient for fetching and updating laptops data  
6. Create a laptop management component for displaying laptops as a table  
7. Add a new laptop addition form above the table and implement thec feature using the service. The list should refresh after a new laptop is successfully saved to db  
8. Add a column with a delete button for each row in the table. Implement the delete feature using the service.  
9. Implement the table inline edit feature. Add a column with an edit button for each row in the table. When a user clicks the edit button, editable input fields should appear in each cell of the selected row, the save button should appear instead of the edit button, and the cancel button should appear instead of the delete button. Once the user saves the changes or cancels the edit operation, the table should return to its initial state(without editable inputs)  
10. Add input for quick searching laptops by model name. Search results should appear under search input when a user changes the value of the search field (no search button). For performance optimization don't send a request to the server on every keystroke. Instead, the search should start when the user stops typing. Use rxjs to accomplish this task.  
