# Currency Converter

A Spring Boot application that integrates with a public API to deliver real-time currency conversion.


## Features

- Fetch real-time exchange rates for the specified base currency.

- Convert an amount between two currencies using the fetched exchange rates.

- RESTful API endpoints.


## Technologies Used

Java 17

Spring Boot

Maven

IDE (Preferred: Eclipse)


## Installation

 - Clone the Repository

```git clone https://github.com/<your-username>/currency-converter.git```

 - Navigate to the Project Folder

```cd currency-converter```

- Checkout the Master Branch

```git checkout master```


## Configuring Your API Key

- Sign up at Open Exchange Rates.


- Generate a free API key.


- Use this key when building and running the application as shown below.


## Building the Project

```mvn clean package -Dcurrency.api.key=<your-api-key>```


## Running the Application

```java -jar -Dcurrency.api.key=<your-api-key> target/currencyconverter-0.0.1-SNAPSHOT.jar```


## Accessing the Application

Exchange Rates API:
```http://localhost:8080/api/rates?base=USD```
