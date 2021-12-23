# Hotel managment in Java
#### Video Demo : [Youtube](https://www.youtube.com/watch?v=W6hTv8vPAG4)
#### GitHub repo: [GitHub](https://github.com/gerardsiles/Hotel_management)
#### Description:

The final project is a program written in Java, that can manage customers, rooms and reservations.
I have implemented options to filter some information, wich is going to be explained in the following lines.
The program preloads information found at the end of the Hotel.java file.

the project contains the following classes:
Main: is where all the interaction with the user is happening, and is calling the methods on the other classes.
Hotel: is where all the methods to interact with the hotel are built, and where the information is kept.
Reservations: is where all the methods to interact with the reservations are built.
Rooms: Generalitzation class, with all the methods to interact.
SingleRoom: Specialitzation class, with the specific information.
DoubleRoom: Specialitzation class, with the specific information.
SuiteRoom: Specialitzation class, with the specific information.

In the main menu we have 6 options to choose from:
> 1 Manage reservations

    this has a submenu, where we can create, delete or list the reservations. During this process, it checks if the
    customer exists, and if the room is available on that period of time. During the deleting process it checks if
    the reservation exists.
> 2 Manage rooms

    this has a submenu, where we can create, delete or list the rooms. During the creation process, it checks if the
    room nubmer allready exists. During the deleting process, also checks if the room exists.
> 3 Manage customers

    this has a submenu, where we can create, delete or list customers. During the creation process, it checks if the
    customer allready exists, as well during the deleting process.
> 4 Available rooms in a period of time

    This implements a filter, that goes through the reservations on a period of time that the user inputs and outputs
    the rooms that are available for that specific period, filtered by what type of room it is.
> 5 Reservations in a period of time

    This implements a filter that outputs the existing reservations on a period of time.
> 6 Reservations by customers in a period

    This implements a filter that outputs the existing reservations on a period of time, filtered by the customers that
    made the reservation.

During the design, I have followed the basic principles of object oriented programming, and it has been depeloped
with the `model-view-controller` design pattern. I also used `GIT` to control the versions during the development stage.

In the future, I would like to increase this project connecting it to a database, since now is working with the data
locally, with ArrayList.
