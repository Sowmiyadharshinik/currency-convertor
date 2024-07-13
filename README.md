# currency-convertor
Creating a currency converter using Flutter involves building a mobile application that allows users to convert amounts between different currencies

Main Function

Entry Point: 
The main function starts the Flutter app by calling runApp and passing CurrencyConverterApp.
CurrencyConverterApp Class

Stateless Widget:
CurrencyConverterApp is a stateless widget that sets up the app.

MaterialApp: 
This widget provides material design and specifies the app's title, theme, and home screen (CurrencyConverter).

CurrencyConverter Class
Stateful Widget:
CurrencyConverter can maintain its state, meaning it can update its display dynamically.

State Creation:
The createState method creates an instance of _CurrencyConverterState, where the app's state and logic are managed.
_CurrencyConverterState Class

State Variables:

TextEditingController:
Controls the text field for the amount input.

Selected Currency:
Holds the selected currency from the dropdown.

Converted Amount: 
Stores the conversion result.

Exchange Rates: A map containing predefined exchange rates for various currencies.
Currency Conversion Logic:

Conversion Function: _convertCurrency parses the input amount, retrieves the exchange rate for the selected currency, and calculates the converted amount.
State Update: setState updates the UI with the new converted amount.

Build Method

Scaffold: Provides the app's basic structure with an app bar and body.

AppBar: Displays the app's title and removes the shadow.
Body: Contains the main content, wrapped in padding for spacing.
Column Layout: Arranges the UI elements vertically:

Text Field: For user input of the amount in USD, with a label and border styling.

Dropdown Menu: For selecting the target currency from predefined options.

Convert Button: Triggers the conversion function when pressed.

Result Display: Shows the converted amount in the selected currency.

Summary


This Flutter app provides a simple interface for currency conversion. Users input an amount in USD, select a target currency, and see the converted amount based on predefined exchange rates. The app demonstrates basic Flutter concepts like state management, user input handling, and UI layout.






