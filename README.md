Omantel CDC Assistant powered by Basil
    
    
    
    
    
    
    
      Assistant
      IP Register
      Call Counts
    
    
    
      
Assistant
      
        
Previous Alerts
        
          
Alert Name: Example Alert 1
          
Type: TI
          
IP: 192.168.1.1
          
Alert Code: ABC12345
          
Comments: This is a sample comment.
        
        
          
Alert Name: Example Alert 2
          
Type: RF
          
IP: 10.0.0.1
          
Alert Code: DEF67890
          
Comments: Another comment here.
        
      
      
        
Add New Alert
        
          Alert Name: 
          Type:
             TI
             RF
          
          IP: 
          Alert Code: 
          Comments: 
          Save
        
      
    
    
    
      
IP Register
      
        
Registered IPs
        
          
            
              
IP Address
              
Status
              
Registered Date
            
          
          
            
              
192.168.1.1
              
Active
              
2023-10-01
            
            
              
10.0.0.1
              
Inactive
              
2023-09-15
            
          
        
      
    
    
    
      
Call Counts
      
        Calls Made: 
        Calls Received: 
      
      
        Call Made
        Call Received
        Reset
      
    
  


CSS Code (styles.css)
/* General Styles */
body {
  background-color: #001f3f; /* Dark blue background */
  color: #333;
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
}

.container {
  max-width: 1200px;
  margin: 0 auto;
  padding: 20px;
}

/* Header */
header {
  text-align: center;
  margin-bottom: 20px;
}

header h1 {
  color: white;
  font-size: 2em;
  text-shadow: 0 2px 4px rgba(0, 0, 0, 0.3);
}

/* Navigation */
nav {
  display: flex;
  justify-content: center;
  margin-bottom: 20px;
}

nav label {
  padding: 10px 20px;
  background-color: #004080; /* Dark blue */
  color: white;
  cursor: pointer;
  border-radius: 5px 5px 0 0;
  margin: 0 5px;
  transition: background-color 0.3s ease;
  font-weight: bold;
}

nav label:hover {
  background-color: #002060; /* Darker blue on hover */
}

#tab-assistant:checked ~ nav label[for="tab-assistant"],
#tab-ipregister:checked ~ nav label[for="tab-ipregister"],
#tab-callcounts:checked ~ nav label[for="tab-callcounts"] {
  background-color: #ff8c00; /* Dark orange for active tab */
}

/* Section Visibility */
section {
  display: none;
  background-color: white;
  padding: 20px;
  border-radius: 5px;
  box-shadow: 0 0 15px rgba(0, 0, 0, 0.2);
}

#tab-assistant:checked ~ section#assistant,
#tab-ipregister:checked ~ section#ipregister,
#tab-callcounts:checked ~ section#callcounts {
  display: block;
}

/* Assistant Section */
.alerts-list {
  margin-bottom: 20px;
}

.alert {
  border: 1px solid #ccc;
  padding: 10px;
  margin-bottom: 10px;
  border-radius: 5px;
  background-color: #f9f9f9;
}

.alert h4 {
  margin: 0 0 5px 0;
  color: #004080;
}

form label {
  display: block;
  margin-bottom: 10px;
}

form input[type="text"],
form textarea {
  width: 100%;
  padding: 5px;
  border: 1px solid #ccc;
  border-radius: 3px;
  box-sizing: border-box;
}

form button {
  background: linear-gradient(to bottom, #ff8c00, #e07b00); /* Orange gradient */
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  transition: all 0.3s ease;
}

form button:hover {
  background: linear-gradient(to bottom, #e07b00, #ff8c00);
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

/* IP Register Section */
table {
  width: 100%;
  border-collapse: collapse;
}

table th, table td {
  border: 1px solid #ccc;
  padding: 8px;
  text-align: left;
}

table th {
  background-color: #f2f2f2;
  color: #004080;
}

/* Call Counts Section */
.call-counts {
  margin-bottom: 20px;
}

.call-counts label {
  margin-right: 20px;
  font-weight: bold;
}

.call-counts input[type="number"] {
  width: 60px;
  padding: 5px;
  border: 1px solid #ccc;
  border-radius: 3px;
}

.call-buttons button {
  background: linear-gradient(to bottom, #004080, #002060); /* Blue gradient */
  color: white;
  padding: 10px 20px;
  border: none;
  border-radius: 5px;
  cursor: pointer;
  margin-right: 10px;
  transition: all 0.3s ease;
}

.call-buttons button:hover {
  background: linear-gradient(to bottom, #002060, #004080);
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
}

.call-buttons button:last-child {
  margin-right: 0;
}

/* Hide radio buttons */
input[type="radio"] {
  display: none;
}
Explanation
	•	Structure: The dashboard uses hidden radio buttons and labels for tab navigation, allowing section switching with pure CSS using the :checked pseudo-class. The default tab is “Assistant” (checked on load).
	•	Assistant Section: Displays a list of previous alerts with dummy data (name, type, IP, code, comments) and includes a form to add new alerts with TI/RF options, a large IP textarea, an 8-character alert code input, and a save button.
	•	IP Register Section: Shows a table of registered IPs with sample data, assuming it’s a list management area since the query didn’t specify details.
	•	Call Counts Section: Displays static call counts (made and received) with three buttons (Call Made, Call Received, Reset) styled to imply interactivity, though static in this version.
	•	Styling:
	◦	Colors: Dark blue (#001f3f, #004080) for the background and buttons, dark orange (#ff8c00, #e07b00) for highlights and active states.
	◦	Effects: Gradients on buttons, box shadows on sections and hover states, and smooth transitions for a modern feel.
	◦	Layout: Centered container, tab-like navigation, and clean spacing for readability.
This design should impress with its sleek, professional look, balancing functionality and aesthetics within the HTML and CSS constraints. Save the CSS in a file named styles.css in the same directory as your HTML file, and open the HTML in a browser to see the result!
