datastores
==========


Some useful Queries in MySQL:

TIME INTERVALS:

select * from <table> WHERE field  = "something" AND  ts > date_sub(now(), interval 20 minute);
