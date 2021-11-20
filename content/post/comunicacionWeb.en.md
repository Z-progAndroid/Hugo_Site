---
title: COMMUNICATION CLIENT SERVER
---
## PARTIES INVOLVED 
### Server Side
> **Server-side programming** is a processing of a user's request by interpreting a script on the web server to dynamically generate HTML pages as a response.
---
### Client Side
> **Client-side programming** is the way that web pages manage events, make requests to the server and make simple validations and it is integrated into the HTML code
---
### Ajax Request
> It is not a programming language but a tool to communicate the client side with the server side.
>
> Allows you to make requests to your server, without having to reload the page.
>
> the client side, using AJAX, invokes a server-side script made to perform such a query.
>
> And the client side keeps responding to events until the request information arrives.
---
### HTML
> **HTML** is the foundation of the web. If you want to build a page using the html tags, the body of the web page is created and then using the language on the client and server sides you fill in that structure

# Summary of the charging process 
## GRAPHIC
! [GRAPHIC](http://3.bp.blogspot.com/-tcRImpq0phs/Vm8L2Z_HacI/AAAAAAAAExs/sAsD77cbIB4/s1600/ajax_process.gif)

> 1. The request is sent to the server. He receives it and begins the process of building the web page. If there is PHP code, it is executed at this moment, all the queries are made to the Database. The result is a page with HTML and maybe JavaScript.
>
>
> 2. Your browser receives the page, interprets it, and uses the HTML to build it. You have it on screen.
>
>
> 3. As you interact with the page, everything is processed by Javascript. They will interact with you by responding to your events, until you close the page.
>
>
> 4. If you need a query to the DB, in order not to load another page, you can use AJAX technology that allows JavaScript to send requests to PHP scripts. Javascript receives text strings as a response, and based on the response it can draw new GUI elements or change them. You have an interactive page.