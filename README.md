# Internet-Status-Checker
   A simple web application that checks the current internet connection status, displays the user's IP address, and shows network strength if available.

Features
   - Checks if the internet connection is online or offline.
   - Displays the user's public IP address using the [ipify API](https://www.ipify.org/).
   - Shows the network's downlink speed (if supported by the browser).
   - User-friendly interface with responsive design.

How to Use
   - The application will automatically check the internet connection status when the page loads.
   - It displays:
     - Connection Status: Whether the device is connected to the internet or not.
     - IP Address: The public IP address of the device (fetched using the ipify API).
     - Network Strength: The estimated downlink speed of the network (if available).

Technologies Used
   - HTML
   - CSS
   - JavaScript
   - [ipify API](https://www.ipify.org/) for fetching the public IP address

Code Explanation
   - HTML: Provides the structure, including sections for connection status, IP address, and network strength.
   - CSS: Adds styling, making the app visually appealing with a clean, responsive layout.
   - JavaScript: Manages the logic for checking the internet connection, fetching the IP address using the `ipify` API, and displaying the network's downlink speed (if available).
