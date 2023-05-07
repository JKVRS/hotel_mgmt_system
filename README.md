# HOTEL MANAGEMENT SYSTEM - 

## REQUIERMENT OF A HOTEL MANAGEMEMT

* GET API
1. Show all the rooms in a hotel to user  
2. show all the staff in a hotel who are working -- Housekeeping, Chef, Manager, Gurad, Receptionist, Lift Man
3. show all the user who stayed or staying in that perticular hotel with all details.
4. show number of user and total transaction in one day, one week, one month etc.
5. show all the services that are avaliable in a room of a hotel like furshnied, non furshnied, AC, Non AC, dinner include or not etc.


* POST API 
1. to add the new room in hotel.
2. to add new staff in a hotel.
3. to add new user (checking) in hotel.
4. to add any services in a room like - add double bed in a room.

* PUT API
1. to update any room in a hotel.
2. to update staff details .
3. to update user if something added mistkely.
4. to update room serices.

*DELETE API
1. to delet any room in a hotel.
2. to delete any staff or staff member when he left the hotel.
3. to delete any room services from a room

*Other services
1. make a payment -- payment API
2. refunda payment 
3. Notification service

Actors -> 

1. USER        
USER ACTIONS ->
1.1 USER WILL REGISTER AND LOGIN ON S HOTEL SITE.        ------> POST API
1.2 USER SERACH THE ROOM IN THAT PERTICULAR HOTEL IF ROOM IS AVALIABLE OR NOT   ----> GET API
1.3 USER WILL RESERVE THAT PERTICULAR ROOM               ------->
1.4 USER CAN CANCLE THTA PERTICULAR ROOM                 ------->
1.5 USER CAN ADD ROOM SERVICES WHATEVER USER WANT        ------->
1.6 USER WILL MAKE PAYMENT                               ------->

2. ADMIN
ADMIN ACTION -> 
2.1 ADMIN WILL ACCEPECT THE REQUEST OF USER             -------->
2.2 ADMIN CAN SEE LIST OF USER                          ---------> GET
2.3 ADMIN CAN SEE THE LSIT OF ALL EMPLOYEE WHO ARE WOKRING IN HOTEL   ------->GET
2.4 ADMIN CAN ALSO SEE ALL ROOMS                        --------->GET
2.5 ADMIN CAN MODIFY, ADD, DELETE ANY ROOM              ----------> POST/PUT/DELETE
2.6 ADMIN CAN MODIFY, ADD, DELETE ANY ROOM SERVICES      -------->POST/PUT/DELETE
2.7.ADMIN CAN MODIFY THE DETAILS OF WOKING EMPLOYEE OR CAN DELETE THE RECORDS OF WOKRING EMPLOYEE.  ----------->POST/PUT/DELETE

3. RECESPTIONIST
RECESPTIONIST ACTION ->
3.1 CAN SEE THE ALL THE ROOMS                ---------->GET
3.2 WILL CHECKING AND CHECKOUT FOR USER     ---------->
3.3 CANCLE THE ROOM                    ------------>
3.4 MAKE BILLING FOR USER

4. SERVER
SERVER ACTION ->
4.1 MAKE PAYMENT
4.2 REFUND PAYMENT
4.3 NOTIIFCATION SERVICE



           



