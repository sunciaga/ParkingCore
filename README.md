# ParkingCore
A robust, logic-first parking management engine built in Python.

ParkingCore is a technical solution focused on managing parking slots through state logic and dynamic time-delta calculations.

# 📋 Technical Blueprints (Core Functions)

To bring ParkingCore to life, we will implement these functional modules:
- initialize_lot(capacity):
Generates the initial workspace (e.g., a dictionary with 10 or 20 empty slots).
- check_in(plate, slot_id):
Binds a license plate to a specific slot.
Logs the entry timestamp using the datetime module.
- view_status():
Renders a visual map of the lot.
Example: [01: OCCUPIED] [02: VACANT] [03: VACANT].
- check_out(slot_id):
Calculates the time difference and applies the hourly/minutely rate.
Releases the slot and displays the final billing ticket.
- dashboard_metrics():
Displays total revenue and current occupancy levels
