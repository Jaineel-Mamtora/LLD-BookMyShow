# LLD-BookMyShow

For Requirements: check out the `requirements/requirements.md` file.

UML Class Diagram:

![UML Class Diagram](./bookmyshow-class-diagram.svg)

# Types of Design Patterns:-

- ### Factory Design Pattern:
  The MovieFactory class can be used to create different types of movies, such as ActionMovie, ComedyMovie, and DramaMovie.
- ### Observer Design Pattern:
  The BookMyShow class can be used to observe changes in the Movie class. For example, if a new movie is added, the BookMyShow class can be notified so that
  it can update its database.
- ### Strategy Design Pattern:
  The PaymentStrategy interface can be used to define different payment methods, such as CreditCardPayment, DebitCardPayment, and CashPayment.
- ### Singleton Design Pattern:
  In Book My Show, an example of the Singleton Pattern can be the use of a "TicketBookingManager" class. This class manages the booking process, handles seat
  availability, and ensures that only one instance of the TicketBookingManager is used throughout the application.
