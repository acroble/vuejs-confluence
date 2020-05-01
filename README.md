# acroble-connect
# Spring Boot and Vue.js integration with Atlassian Connect #

![Atlassian Confluence Vue](frontend/src/assets/atlassian_confluence_vue.png)

## Usage ##

1. ngrok http 8081

2. Change urls to ngrok https url in:

    frontend\vue.config.js
    backend\src\main\resources\application.properties

3. mvn spring-boot:run

4. Access the https url. If url returns the contents of [atlassian-connect.json](backend/src/main/resources/atlassian-connect.json), then you ready to upload the app to Atlassian.

5. Upload app to your Atlassian instance. See [here](https://confluence.atlassian.com/upm/installing-add-ons-273875715.html#InstallingMarketplaceapps-Installingbyfileupload)

6. Access your app from Atlassian --> top nav bar --> Apps --> VueKit

7. Profit