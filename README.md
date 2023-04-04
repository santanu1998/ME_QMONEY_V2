
# QMoney

## Overview

#### QMoney is a visual stock portfolio analyzer. It helps portfolio managers make trade recommendations for their clients.

During the course of this project,

* Implemented the core logic of the portfolio manager and published it as a library.

* Refactored code to add support for multiple stock quote services.

* Improved application stability and performance.

### Images

![Screenshot 2023-04-04 165157](https://user-images.githubusercontent.com/69622683/229778252-d93e1438-0230-4681-b9b2-5c343eb84569.png)

                                          QMoney Architecture
                                          
![Screenshot 2023-04-04 165238](https://user-images.githubusercontent.com/69622683/229778418-e5b9cfac-5d69-46fa-ad68-a92538042f7a.png)

                                           QMoney Portfolio Manager Interface

## Fetch stock quotes and compute annualized stock returns

### Scope of Work

* Used Tiingo’s REST APIs to fetch stock quotes.

* Computed the annualized returns based on stock purchase date and holding period.

### Skills used

#### Java, REST API, Jackson

### Refactor using Java interfaces and publish a JAR file

### Scope of Work

* Refactored code to adapt to an updated interface contract published by the backend team.

* Published the portfolio manager library as a JAR for easy versioning and distribution.

* Created examples to help document library (JAR) usage.

### Skills used

#### Interfaces, Code Refactoring, Gradle

### Improve application availability and stability

### Scope of Work

* Added support for a backup stock quote service (Alpha Vantage) to improve service availability.

* Improved application stability with comprehensive error reporting and better exception handling.

### Skills used

#### Interfaces, Exception Handling

### Enhance application performance

### Scope of Work

* Improved application responsiveness by introducing multithreading.

* Wrote unit tests to measure performance improvements.

### Skills used

#### Multithreading
