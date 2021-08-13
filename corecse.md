PT.1
The high level overview of what would happen when we type attainu.com in browser would be the following :

1st We enter attainu.com as the url in the web browser

2nd The browser starts by looking up the IP address for the domain name via Domain Name Server or DNS (matching the url to an ip address in the dns)

3rd Then the browser sends a HTTP request to the server after which the server sends back a HTTP response

4th The browser then proceeds by intiation of rendering the HTML and further the web browser sends requests for additional objects 
embedded in HTML (images, css, JavaScript) and repeats steps 3 and this step.

5th Once the page is loaded, the browser sends further asynchronous requests if needed for additional website requirements.


PT.2

Pagination is a process by wherein we split the contents of the website or a section of contents from the website into discrete pages and data sets 
to make website look more visually friendly and appealing for user

Overall Pagination has 2 main aspects : 

1st Division into a number of pages and 

2nd Further division of each numbered page as per specific size containing certain amount of information, data, 
or records

Thus pagination allows user to view particular set of data on a particular page at a given time making the experience pleseant for them.

In web development we have 2 types of paginination namely client side pagination and server side pagination wherein

Client side pagination : When query is made an page is loaded the server returns data in 1 big chunk to the client thus intially when web application first 
                         starts loading it generally takes some time however once web application is fully loaded one can easily flip through pages as all
			 the data has been loaded upfront.
			 
			 This type of pagination is suited for simple static websites especially where all data is to be shared with user and amount of data
			 is not humongous and to and fro request between database and frontend is not frequently needed.

Server Side pagination : When query is made an page is loaded the server does not return data in 1 big chunk to the client, thus intially when web 
                         application first starts loading it generally is quicker however as it has to serve data from the database depending on the route 
			 webpage of the specific intial load further as client progresses to different sections or pages as per web application layout 
			 continous request and response to and from the database is made.
       
       This type of pagination is suited especially when regular interaction takes place between the database and frontend part of the web applications like business,erp, ecommerce etc.
       
