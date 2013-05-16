datastores
==========


Some useful Queries in MySQL:

TIME INTERVALS:

select * from <table> WHERE field  = "something" AND  ts > date_sub(now(), interval 20 minute);


 INSERT INTO gnet_dashboards( accountID,app_id, first_name, last_name, email, dashboard_title, setup_date, activated_date, last_accessed_date, suspended_date, terminated_date, globe, publish_feed) VALUES ( "AANA-44I5JM", "5Kx8bgUJBvj91NWKgk3fGu5EW", "Eggermont", "Antonio", "gnet.akamai.cctv@gmail.com", "CCTV", 1368729301, 1368729301, 0, 0, 0, 1,0 );
