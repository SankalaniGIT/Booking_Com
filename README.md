# Booking-com-Test-Automation-Project
> This is a test automation task on [__Booking.com__](https://www.booking.com/) website (Reservation).

## Installation

Clone the repo:

```sh
git clone https://github.com/SankalaniGIT/Booking_Com.git
```

Install dependencies:

You need to install these dependencies from [_mvnrepository_](https://mvnrepository.com/):

```sh
Selenium
Testng
Webdrivermanager
Java 11+
Maven 3.8+
```

## Test Scenarios

Scenario:
1. Navigate to official Booking.com site (https://www.booking.com)
2. Click on Language icon on top panel (Set it to English (UK))
3. Click on Currency icon on top panel Set it to Australian Dollar (AUD)
4. Click on the “Stays” Tab on top panel.
5. Type Any location in “Where are you going” text field. (E.g.: - Kandy)
6. Select the Check-in and Checkout (Should be further day from the currently system date
and different between to dates should be 2 days)
7. Select 1 adults and 0 children and 1 room and verify it.
8. Click on the Search button.
9. Verify the Search Location is correct.
10. Select the Property rating.
11. Select the sort by Price in top panel in search result.
12. Get the name and amount with the tax of the second item from the search List page.
13. Click the second item from the search List page and navigate to the hotel Detail page and
verify the hotel name.
14. Select the room against the amount and tax that you store in previous page.
15. Click on I’ll reserve.
16. Verify the checkout date, check in date and amount.
17. Fill all the mandatory fields in your details. First name, Last name, Email (Always You
valid Test data, don’t use any if your personal details)
18. Click on Next: Final details > button.
19. Verify your entered details are matched in final screen.
20. Click on Booking.com top logo and navigate to the home page.


## Skills

- Java
- Selenium
- TestNG
- POM (Page Object Model)
