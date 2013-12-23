## Understanding Web Infrastructure

At RBSavvy, a lot of our clients tend to be non-technical people.  We love this type of work.  We get the opportunity to develop outside the lines, without all the baggage of another developer telling you exactly how problems should be solved.  We also get the opportunity to teach our clients about the process of web development, web infrastructure, development technologies, etc.

We often get blank stares from our clients as we explain the intricies of infrastructure choices and development methodologies.  Our clients ask for more reading material to help them better understand, but we've been unable to find great resources that explain the technical concepts of database servers, caching strategies, background worker processes, and REST APIs in a non-technical way.  This series aims to do just that.  In this first post, we're going to overview Web Infrastructure as a whole and break down various parts in future posts.

Your average web application consists of a few major parts: web servers, application servers, database servers, and background task servers.  Depending on the number of web requests and the complexity and quality of code, you may need more than a single web, application, database server... etc.

Also, depending on the complexity or functionality of your application, you may have other servers or services such as email, caching, memory, or servers. We will not cover these exceptions at this point.
