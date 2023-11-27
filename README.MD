## Tests 

```
// Building a contructor 
Describe: Place(location, landmarks, timeOfYear, notes);

Test: "Assigning this function to a variable will create a new object."  
Code: let seattle = new Place("Seattle", "Bellevue", 2023, "Ermek goes to a college there.");  
Expected output: seattle { location: "Seattle", landmarks: "Bellevue", timeOfYear: 2023, notes: "Ermek goes to a college there." };  
 
// Building a method
Describe: Place.prototype.allInfo();

Test: "All values will be presented as a result in a sentence form."  
Code: seattle.allInfo();  
Expected output: "You've selected Seattle. Its landmark is Bellevue. We have visited in 2023. Additional note: Ermek goes to a college there.";  

// Get results using object and method functions
Describe: getPlaceValue();

Test: "It will return selected radio button value."  
Code: getPlaceValue();  
Expected output: "kyrgyzstan";  

Describe: getData();

Test: "The returned value from getPlaceValue() will be applied and generate result using Place.prototype.allInfo() function."  
Code: getData();  
Expected output: "You've selected Seattle. Its landmark is Bellevue. We have visited in 2023. Additional note: Ermek goes to a college there.";  
```