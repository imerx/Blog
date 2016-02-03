# project Blog

##  course provide by the University of Nuevo Mexico on Coursera [Web Aplication Architectures](https://www.coursera.org/course/webapplications)
for more information about how this course is graded [Acomplishments] (https://www.coursera.org/account/accomplishments/records/gysTRD3ssRgGuKmE)


##Install 

clone  or download this repository  and run  in your locally using rails console.

## Project Overview
Developed a blog to post comments using  Ruby 2.0 , AJAX, Jquery, and authenticates method authenticate_or_request_with_http_basic

    def authenticate
      authenticate_or_request_with_http_basic do |name, password|
        name == "admin" && password == "secret" 
    end 


## Course Description
This course explores the development of web application architectures from an engineering perspective.
We will consider the fundamental design patterns and philosophies associated with modern web application architectures, 
along with their major components.  By the end of this course, I expect you to be able to:

* Design, develop and deploy a modern web application.  This course is not about how to build a pretty web page, 
it's about how to build and deploy the full stack of protocols and technologies associated with a complete web app. 
That said, it is not possible for you to become an expert in this area in a few weeks. My goal, rather,
is to put you on the right path by providing a solid foundation and framework for understanding web applications,
allowing you to dig deeper and learn more on your own. The next bullet points describe how we're going to do this.

* Understand the major architectural components in web apps, and how they fit together.  Modern web apps are complex. 
A typical application has a database along with numerous scripts on one end of the web stack, a web server in the middle
that delivers information over the Internet, and a user's browser on the other end of the web stack.  Even getting started
in trying to understand these components can be overwhelming. Consider just the programming languages involved in a
typical web stack: from the database (SQL), to the web server (scripting language), to the browser (JavaScript, HTML, CSS), 
we're dealing with five different programming languages, not to mention the protocols they're operating over
– and you need to know a little about them too! 
We'll introduce a number of software design patterns throughout the course that are aimed at helping you to manage this complexity.

* Use Ruby on Rails.  We're going to learn about web apps through the Ruby on Rails framework.  
Rails is a framework for creating web applications that is built on top of the Ruby programming language. 
I believe this is one of the best frameworks for learning about web applications, and it's also proving highly
successful as a platform for commercial offerings.  That said, there are many other frameworks available, and the 
concepts you will learn using Rails are transferable to these other frameworks.

* Better understand modern software engineering practice.  We’ll be using the latest tools and practices in software development, 
source code control, testing, and application deployment. This will include exposure to agile development practices, t
he numerous tools that software engineers are expected to know how to use, and the cloud-based resources that are becoming 
increasingly important in web applications.  