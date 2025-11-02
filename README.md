Overview:

This project is a simple web-based dashboard created using Python and HTML.

It demonstrates two features related to electric vehicles (EVs):

Feature A – Static Fleet Overview:
Displays a list of predefined electric vehicles with their ID, model, current battery percentage, and status (Available, Charging, or On Trip).

Feature B – Basic Charging Cost Calculator:
Allows the user to select a vehicle and enter a charging duration (in hours).
The system calculates the estimated cost using this formula:
Cost = Charging Duration × 7.5 kW × $0.15 per kWh.

How to Access (in Google Colab):

1. Open the Google Colab notebook that contains the code.

2. Run the to start the Flask web app.

3. Wait until you see a line that says “Public URL: NgrokTunnel: "https://overholy-comfortable-odin.ngrok-free.dev"”

4. Click the provided link to open the dashboard in your browser.

How to Use the Website:

1. The main page automatically shows both features.

2. The top section displays the fleet overview with 5–10 vehicles.

3. In the bottom section, you can select a vehicle, type the charging duration in hours, and click “Calculate” to view the estimated cost.
