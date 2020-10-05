# WiFi4EU - Portal
EnGenius Cloud WiFi4EU Portal Sample

## Installation
* Edit splash.html to modify two variables **wifi4euNetworkIdentifier** and **wifi4euLanguage**, and remove **var selftestModus = true;**.
* Host splash.html on your static webserver such as Apache, Nginx, GitHub or Firebase, etc.
* Configure the Engenius Cloud SSID setting with a Click-Through splash page authentication
    * Select Captive Portal Tab
    * Enabled --> Switch to Enabled
    * Authentication Type --> Select Click-through
    * Advanced Setting --> Walled Garden
        * Add the domain of the WiFi4EU suporting resources  **collection.wifi4eu.ec.europa.eu**
    * Select Splash Page Tab
        * Splash Page Type --> Select External Splash Page URL
        * Point the "Customer URL" to the HTML file. ex: `https://yourserver/splash.html`
