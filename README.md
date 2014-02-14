DistributedCrawler_Server
=========================

Distributed Crawler is a project to crawl up the web and find information. This will take the Advantage of Crowd-Computation. This has a server and client architecture, where the server is run and the clients can be run on independent machine.

The server handles the following tasks:
- Clients Co-ordination, Client Management, Task Allocation, Redundancy Check
- Data Management from Clients and on Server
- Grouping of Data from multiple sources, and managing Hadoop for that
- Storing the Data for Search
- Showing on the website for the users to search
- Hadoop Manager to Scale up and Scale down the Hadoop Server according to need
