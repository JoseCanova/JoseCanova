- 👋 Hi, I’m @JoseCanova
- 👀 I’m interested in ...computing
- 🌱 I’m currently learning ... java as usual (eternity learning)
- 💞️ I’m looking to collaborate on ... earn some money... lots of debts..
- 📫 How to reach me ... well. lets get all here.

<!---
JoseCanova/JoseCanova is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
### Let me think. 
On the application, opensource, im not a hero, so, work for tommorrow.
1 - The application of the thing, well, it's almost like the "Postman Flow (i remember a meeting)". with the difference that is on "practical mode" not testing mode. The restapi if well thinked can turned into production ready (for queries is quite simple , for updates operation need to know the database very well but can be used too) since is working with projections.

  Which means that for queries is just create the correct path, in a "better worlds model". The taxonomy need to analyzed to not collide namespaces, model mapper shows that its a common practice. But as soon it cames up is production ready for queries, this is amazing. 
  why?
  because a cache can be defined in specific parts of the "query path". see? 

People are fun. 
I understood, it will work, but its now a work to do alone. There are a lot of small things, that need to be described somewhere. No crystal balls, probably a story shall exist because there are some details to describe on the services. some are simples other dont and we need some description to compare the actual with the "service that will replace".  Not that big issue, but jsut this can take 2 days to understand. 


Nice - I will try to mount a presentation of the "thesis proposal"... 
It's almost a thesis. 
## FOR NOW WORK
I writing the "unit tests" for what i proposed to deliver tomorrrow. 
This is how what i can on the scheduled. 
## QUITE SIMPLE - I need to simulate an API. 
This is what im writing. problem is that the OpenApi does not processing well the version 2.01 on postman , swagger nothing
I had to write ll by hand finished now.. and starting unittests then after will pick i guess modelmapper. 
indeed i have to tak a look.
found a stackoverflow on lombok... 
the code that generated the classes is buggy (my few hours code) and 
on somemoment the copy-paste with repeated attributes throwns a StackOverflow.
interesting.

## checking this
https://thepracticaldeveloper.com/guide-spring-boot-controller-tests/

###Feign need a "port responding".. 
But is working the unit tests. so. in theory the mockserver on customer environment is just to avoid 
round trips. 
now continue the tests.

I am doing what i have planned to show tomorrow. but this weekend i didn't worked well as planned. 
And i know , it will not have "the show part" i know. but, as i said that i will try to reach a point that i estimated. 
Trying to reach it. 

Working fine. the change on format causes some problems. by the lucky i preserved the format.

I need to read this code - http://modelmapper.org/getting-started/

i write to not get mad.. i forgot that i could write here. its a blog too. more appropriate indeed. 

well... i forgot. as i forgot a lot of things.

let me see i mount the pojos . now i fixing the return methods of the api. (mock and controller). 

all by hand because nothing is working.

ModelMapper seems to be "verbose" but more appropriate. 

just the case to "put in the right package" the mapping classes.

i thought on other methods. but its mode appropriate. and will the "no mutability" principle.

which means configure all this "helper classes as beans".

the model doesn't fit.. hum... good hum?

what does it means? dont need modelmapper. its uselless you model one into another.  no need. to difficult. so.. use the new model. DTO.

Now Feign is complainning. I started 1-2 times.. then now is asking for properties. 

Understood. Feign can just be injected in a controller. and and Action is not controller. but this is not a problem indeed was just to check. 
So. i have to forward. foward to the controller. and send it back to the action as i configured.
But now need to think that he need to understand what means a method in the new domain name. 

Its not complicate to understand the concept. 
When is a struts-form, dispatch to struts . then struts forward to the controller. the controller check the method. executes the restquery and returns. 
when is jquery is on the controller direct. 
need to adjust the domain and adjust jqueryurl's.

