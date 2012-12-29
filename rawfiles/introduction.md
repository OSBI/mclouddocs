Meteorite Cloud Introduction
============================

Background
----------
Meteorite Cloud has been written from the ground up with the BI developer in mind. There are many products on the market
that allow users to upload data files to a pre canned database, and run some standard dashboards or reports over the top
of them. Meteorite Cloud is different, it gives you complete flexibility over the design and implementation of the BI stack,
from the database used, to the ETL and BI tool used to process and display your data.

Largley built on open source tools, Meteorite Cloud offers the flexibility BI developers require, along side the stability
a managed BI server setup can provide.

Speed
-----
When you start a new server on Meteorite Cloud, we don't just offer a slice of a large cluster of servers and access to a multi
tennant platform. Instead each server is setup specifically for you. We take the stress and time out of configuring a BI server,
instead of it taking a number of hours to configure your server to run with your database of choice, and find the piece of
configuration thats preventing the server from starting up, we do it all for you, and completely automatically 24 hours a day.
Using open source software we automatically setup each server with the correct variables and parameters, so you don't have to.
But if in future you want to change one of the predefined settings to something else, we offer the ability for you to do that to.

Software
--------

###BI Software
####Yellowfin
Yellowfin offer an alternative approach to BI. The product has been designed to be as user friendly and scalable as possible
to make the delivery of information across the organisation as easy as possible.

Yellowfin is a standalone B.I. solution that provides reporting and dashboards via the web and mobile devices.
Yellowfin’s mobile offering is market leading and includes intuitive use of tablet and smartphone functionality with
collaboration and feedback, allowing users to take action on the data wherever they are in the world.

Yellowfin is a relatively new solution in the BI marketplace, but it has already achieved success in Asia and the US.
Yellowfin’s reputation is growing rapidly. In Howard Dresner’s Wisdom of Crowds survey 2012 Market Study Yellowfin was
identified as the leading “emerging” BI vendor and achieved an equal highest overall ranking.

####Pentaho
Pentaho provides a complete BI suite including integrated reporting, analytics, dashboards, statistical analysis and ETL.
Pentaho provides a cost effective solution to delivering enterprise BI through both open source and commercial offerings.

The Pentaho solution is flexible and easy to customise making it idea for integration into 3rd party applications.
It can provide much of the functionality of traditional BI vendors at a fraction of the cost.

####Saiku
Saiku is an OLAP analytics system allowing users to undertake ad hoc analysis on complex datasets in real-time.
OLAP (OnLine Analytical Processing) is a way of analysing data in rows, columns and cells in which users can easily
manipulate the data via a drag and drop graphical interface.

Users are able to drill through from summary information to detail, select and restrict the values they see, sort and
filter the information based on values in the data and easily pivot the view to gain insight into the relationships and
causes of changes to the data.

Saiku is a lightweight, flexible, web based OLAP analytics tool, that has been designed from the ground up to be fast,
easy to use, easy to integrate and easy to customise. Developed by Analytical-Labs, part of Meteorite BI, it is used by
an extensive, rapidly growing global community.

###ETL Software
####PDI
Pentaho data integration (PDI), also known as Kettle and Spoon, is an open source ETL tool that offers a cost effective
alternative to traditional data integration tools such as Informatica, Ab Initio and offerings from major software vendors including IBM, Oracle and SAP. It provides an intuitive graphical interface that facilitates the extraction, transformation and loading (ETL) of data from numerous source systems.

With a modern, open, standards based architecture, the ability to re-use components and an extensive library of community
build plug ins, PDI can significantly reduce the costs of developing and maintaining data integration solutions.

####Talend
Talend provides a fully featured data integration solution. Talend's unified integration platform includes data integration,
ETL, data quality, master data management and application integration. Talend is the most widely used and deployed data
integration solution in the world.

Open source and commercial versions of the software allow Talend to meet the needs of almost any data integration requirement
from cost effective single project solutions through to enterprise wide application integration. Talend has been deployed
by a large number of major organisations globally and is seen as a visionary in the latest Gartner Magic Quadrant for
Data Integration.

###Database Software
####Vectorwise
Vectorwise is a revolutionary analytic database that offers the performance of major data warehousing appliances at a
fraction of the cost.  Vectorwise has broken numerous benchmark records using low cost commodity hardware, thanks to an
underlying system design that makes much more efficient use of modern processors.

Vectorwise is ideally suited to BI deployments with large data volumes that require fast access to ad hoc information.
It can also significantly reduce development effort through a simplified design without the need for indexes or aggregate
tables.

####PostgreSQL
Postgres is a powerful, open source relational database with rich functionality and extensive support for recognised standards.
Postgres has all the features of other leading databases without the need for expensive enterprise licences.

Originally developed by the team behind Ingres, Postgres is widely used in mission critical solutions within major
multinational organisations. Postgres has the ability to handle large data volumes and is considered to be a very stable
database platform.

Postgres continues to be developed by a large user community and has received significant investment and sponsorship from
corporate users.

####MySQL
MySQL is a widely deployed open source relational database. It is used as a cost effective database for numerous business
intelligence solutions in both open source and commercial solutions within major international companies. MySQL is a good
choice for users familiar with other common relational databases as it offers similar functionality and performance without
the need for enterprise licences. Since Oracle’s acquisition of Sun Microsystems, MySQL has been owned by Oracle, who
continue to develop and support it.

MySQL is an ideal solution where small to medium data volumes are processed and the power of an analytic database is not
required.

Configuration
-------------
When configuring a serverMeteorite Cloud sets sensible defaults to the various configuration options for software packages
we supply. But we also offer the ability for you to fine tune your servers configuration to fine tune it to your needs.
Using Git repositories we version all the configuration files we allow people to adjust, meaning, if you make a mistake
you can always roll back to your previous configuration.

Payment
-------
Unlike other cloud based BI providers, we have no minimum contract. Along with the setup, we try to be as flexible as possible with
payment. You can run servers from hourly to multi year deals, the longer your contract the less you pay.

To run servers by the hour or by the day, you have to buy credits, these credits are then assigned to your servers and
as your server runs the credits are subtracted. So if you buy 24 hours worth of credits, then run a server for 6 hours and
switch it off you still have 18 hours worth of credit remaining to be used at a later date.

If you want to run your server weekly or longer, then we offer rolling subscriptions, when your server is started, you are billed
for the initial period, then going forward you are billed every period, until you switch your server off. For example if you are
doing a proof of concept and want to run the server for a month, you will be billed for the initial month. If the POC goes well and
it gets extended, don't worry because you are automatically rebilled. When the POC is over, you could then migrate the work you did
to a Meteorite Cloud server with a longer annual or bi annual billing cycle.
