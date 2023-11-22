# Currency Converter [visit-my-site](https://priyaganga-currency-converter.netlify.app/)
The Currency Converter React app provides a straightforward tool to convert currency amounts between different currencies:

+ Input Fields:
  The app offers two input fields where users can enter the currency amount and select the currency type (from and to) using dropdown 
  menus.

+ Currency Selection:
  Users can choose the currency type they want to convert from and to using the dropdown menus populated with available currency 
  options.

+ Conversion Operations:
  Upon providing the input amount and selecting the currencies, users can either click the "Convert" button or press enter to initiate 
  the conversion.
  The app fetches real-time currency conversion rates using a custom hook (useCurrencyInfo) from an external API .

+ Conversion Logic:
  Currency conversion occurs based on the entered amount and the fetched conversion rate.
  The conversion process happens dynamically and updates the converted amount in real-time.
  
+ Swap Functionality:
  A "swap" button allows users to quickly switch the currencies between the "from" and "to" fields for convenience.
 
Overall, the Currency Converter React app facilitates quick and easy currency conversions by allowing users to input amounts and select currencies, providing real-time conversions based on fetched exchange rates.

