The **React Currency Converter** is a web application that enables users to perform currency conversions using the API.
With a simple and user-friendly interface, this app allows users to select the currencies they want to convert from and to, specify the amount, and instantly get the converted result. This app provides real-time exchange rate data.

**Features:**
-Choose the currency to convert from a drop-down list.
-Select the currency to convert to from another -drop-down list.
-Input the amount to be converted.
-Fetch the current exchange rate and get the converted amount.

**Technologies Used:**
-React: JavaScript library for building user interfaces.
-Axios: Promise-based HTTP client for making API requests.

**Project Installation**
Provide step-by-step instructions on how to install the project dependencies, if any.

![image](https://github.com/Prat-2002/Todaypay/assets/94755712/e0995c87-0aee-42a8-a629-37b9a5a14865)

**Usage**
Explain how to use/run the project. Include any commands or scripts needed to start the application.

![image](https://github.com/Prat-2002/Todaypay/assets/94755712/0958509e-4d68-459b-94fb-832e7c3d1637)


**API Integration**
The project uses the following API endpoint to retrieve currency information:

![image](https://github.com/Prat-2002/Todaypay/assets/94755712/f40fbfe6-728a-40eb-ba2e-201328ce887b)

**Method**
GET

**Parameters**
{currency_symbol}: Replace this with the currency symbol to fetch its information.

**Implementation**
The provided code snippet demonstrates how to make an API call using Axios within a React component using the useEffect hook:

![image](https://github.com/Prat-2002/Todaypay/assets/94755712/93defe4d-6099-47c5-9d00-2875e027ff17)

**Usage**
-Ensure the 'Axios' library is installed in your project.
-Modify the 'from' state variable with the desired currency symbol before making the API call.
-Implement the desired logic to handle the fetched currency information within your component.

**Acknowledgments:**
-This project utilizes the API for currency conversion data.
