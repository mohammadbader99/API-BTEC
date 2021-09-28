# READ-3-BTEC: White Box Testing

I will start doing a white box testing for my code:

![code](/img/server.png)

First of all I started by downloading all the needed libraries (Lines: 3, 4, 5, 6, 7, 9, 11) and started to work on them.

Then I created three routes:

1. `HomeRoute`

    Lines: 12, 16 to 18.

    At first I created the route at line 12, then I created the function that will handle the response message which will tell that the server is working(Lines: 16, 17, 18).

    This is the result after testing:

    ![Home](/img/Host.png)


2. `GetLocation`

    Lines: 13, 21 to 31.

    I created the route at line 13, then I created the function that will get the data from the API and save it in the result array (Line: 27), then the array were sent as a response to the user.

    This is the result after testing with the city 'Amman':

    ![Home](/img/Amman.png)


3. `NotFound`

    Lines: 14, 33 to 35.

    I created the route at line 14, then I created the function that will handle the response message which will be shown if the requested page does not exist (Lines: 33, 34, 35).

    This is the result after testing:

    ![Home](/img/404.png)