# RentakarConception
Conception Rentakar


# Rentakar


# Ici bientôt les versions pour harmoniser

The Rentakar project is a Java and Spring Boot-based platform for booking rental vehicles, using a microservices architecture and technologies such as Maven and JPA Repository. Developed for a car rental company, this platform allows clients to reserve a variety of vehicles, from cars to two-wheelers and utility vehicles, each with specific rental conditions.

![Image](https://github.com/user-attachments/assets/95827894-3138-4350-be6e-eb951118e641)


### Key Features:

Vehicle Properties: Each vehicle has a unique registration number, brand, model, color, base rental price, and mileage rate. Additional attributes:

Two-wheelers: Engine displacement (cc)
Utility Vehicles: Cargo volume (m³)
Client Requirements for Booking: Clients must provide identity details (name, birthdate, driver's license number and year of issuance). Certain age and license criteria apply based on the vehicle’s horsepower.

### Booking Rules:

Only one vehicle reservation per client at a time.
Clients must be at least 18 years old; age restrictions apply based on vehicle horsepower.
An estimated mileage is required for each booking; final cost adjusts based on actual mileage.
Pricing Calculation:

Cars: Base price + price per km * estimated km
Two-wheelers: Base price + (displacement * 0.001 * price per km * km)
Utility Vehicles: Base price + (volume * 0.05 * price per km * km)
This project specification outlines the requirements for a functional, dynamic rental platform aimed at an optimal user experience for booking and cost management.

## Used Tools

- Java 17 
- Spring Boot v3.3.5
- Maven 3
- Spring Data JPA
- Spring Web MVC
- Spring Security with JWT
- database MySQL

## Technical Stack Data Flow Diagram

https://lucid.app/lucidchart/bf0d029d-9327-4955-888e-a4019faebb12/edit?invitationId=inv_a44ad55f-069a-4920-ad0c-3601b1b7a64b&page=0_0#

![Image](https://github.com/user-attachments/assets/45f85d0f-9c49-4bff-bac5-10f03cd29892)

## Our RoadMap Backlog

![image](https://github.com/user-attachments/assets/7efca6cd-8147-474e-bba7-bf1a50516d33)

![image](https://github.com/user-attachments/assets/12210067-7dbc-4703-a10c-58032e3580bc)

![image](https://github.com/user-attachments/assets/3799b30d-6bfa-4d05-8e8e-3cd18c87328c)


https://github.com/users/RDelory74/projects/2/views/3?layout=roadmap

## MCD and MLD data modeling

https://docs.google.com/spreadsheets/d/1fdGbzb7HEDLIkYrechx6NHA8EtOB6do0-IhZgiAwo1o/edit?usp=sharing

![image](https://github.com/user-attachments/assets/1ad3fb99-e7ea-4326-8004-82e71fda8695)

![image](https://github.com/user-attachments/assets/1222245b-9934-49ff-89b5-bf6464a49b49)


## Functional services Routing Plan

![Image](https://github.com/user-attachments/assets/feebab81-28b0-4708-8da1-23b447fe4c02)

https://docs.google.com/spreadsheets/d/1b-3YNS8xP8rsfvc2xtgP398PD1WojTeitGDiYTQsHXg/edit?usp=sharing

## Directory Guideline 

![Image](https://github.com/user-attachments/assets/d04a6d5f-f4f5-4793-bcab-99a28b6c0ba7)
