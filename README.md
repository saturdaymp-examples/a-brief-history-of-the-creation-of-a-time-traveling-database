# A Brief History of the Creation of a Time Traveling Database
A lighting talk I gave at the [Edmonton PASS](https://edmpass.pass.org/) [Speaker Idol Contest](https://www.meetup.com/EDMPASS/events/257714563/) about creating a temporal database many years ago.

# Quickstart
You'll need SQL Server installed to run the demos.  If you have [Docker](https://www.docker.com/) installed there is a Docker Compose file to get you up and running quickly:

````
docker-compose up
````

You can then run the [Schema.sql](Schema.sql) script to create the database.  It has two temporal tables Customers and Addresses with triggers that enforce the temporal rules.  The [DemoQueries.sql](DemoQueries.sql) has some example data and queries to play with.

# Contributing
If you have any questions, notice a bug, or have a suggestion/enhancment please let me know by opening a [issue](https://github.com/saturdaymp-examples/temporal-db-example/issues) or [pull](https://github.com/saturdaymp-examples/temporal-db-example/pulls) request.

# Acknowledgements
Thanks to [Edmonton PASS](https://edmpass.pass.org/) for inviting me to speak.
