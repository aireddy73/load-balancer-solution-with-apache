# Load Balancer Solution With Apache

After completing [Devops Tooling Website Solution](https://github.com/samuelbartels20/devops-tooling-website-solution) you might wonder how a user will be accessing each of the webservers using 3 different IP addreses or 3 different DNS names. You might also wonder what is the point of having 3 different servers doing exactly the same thing.

When we access a website in the Internet we use an [URL](https://en.wikipedia.org/wiki/URL) and we do not really know how many servers are out there serving our requests, this complexity is hidden from a regular user, but in case of websites that are being visited by millions of users per day (like Google or Reddit) it is impossible to serve all the users from a single Web Server (it is also applicable to databases, but for now we will not focus on distributed DBs).