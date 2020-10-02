Simple django app which creates 3 models Airport, Flight, and Passenger. After creating flight, user can add passengers to flights until list is empty.

Airport code - charfield, city - charfield,

Flight origin - foreign key to Airport, destination - foreign key to Airport, duration - integer,

Passenger first-charfield, last-charfield, flights - ManyToMany relationship with flight,
