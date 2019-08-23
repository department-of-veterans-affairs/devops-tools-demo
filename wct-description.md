# Widget Customization Tool

## About
The Widget Customization Tool (WCT) is an HTTP-based API that accepts arbitrary material and returns it as a customized VA widget.[1] The application is written in Python using the Flask framework, served by Gunicorn behind an NGINX proxy, and hosted on a single AWS EC2 instance.[2]

[1] WCT is not a real thing. It is a wholly contrived for the purpose of this technical demonstration.

[2] Offerors are not required to replicate this server and cloud-hosting pattern as part of their demonstration and may utilize alternative web server and cloud-hosting patterns as long as the WCT's functionality is not altered.

## WCT Team

There are 3 teams that are responsible for maintenance, operations, and improvements to the WCT. The following matrix describes the functional area(s) for which each team is responsible:

|        |Green Team|Red Team|Blue Team|
|--------|----------|--------|---------|
|Content |          |        |    x    |
|Design  |          |        |    x    |
|DevOps  |     x    |        |         |
|Frontend|          |        |    x    |
|Backend |          |   x    |         |
|Database|     x    |        |         |
