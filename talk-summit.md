# Groundhog Day

Hi everyone,

this is my first summit and it is being great so far.
We are talking about a lot of challenges and proposing solutions as well.
After the summit we are going to be in a better position to initiate much of them. This is great news.

Well, my talk, today, is not about specific solutions. But I hope that after this talk we, as a company, will have a better understanding of what means building great products. In the title it is Engine as the main character of the story, but actually the reflexion I want to put on the table is related to any CARTO product. 

This reflexion is, in fact, my personal vision, the one I have deloped througout years, about the core of what we usually call digital products and digital services. Since it is my personal vision, I feel a natural way of expressing it is just walking along some of the main experiences drove me to this reflexion.

After that travel, we will get to the main message I want to share with you today. And the bottom line is simply this: act outside the box. Unlike the popular sentence, think outside the box, today I want to give real references to all the parts of the phrase: act, outside, box.

# Berlin, IBM, the Box

Well, before joining this wonderful world of companies and products, I was having fun at university. It was a bunch of years in Berlin, making research about history of mathematics and statistics, and helping students as an assistant professor.

One of the main figures on my topics was Leibniz. This man. So, he is really important and interesting due to many things, and he was really prolific. So thousands and thousands of his manuscripts are managed by the National Academy of Science, and there are specific people translating them to digital format.

I started having a lot fun programming, coding, designing my own programs to solve issues I faced regarding my research. I started loving open source philosophy, because I saw it worked, it was very effective. By that time I was not aware of this, but I was controlling everything because everything was just about me. And that feeling was great.

Well, step by step I started leaving university life and my first job experience out there was at IBM, here in Spain. The job looked quite normal to my teamates and managers, but from the first day I realized that I was beginning something completely new. 

IBM had its portfolio of products and of them, one in which the company was putting a lot of efforts, was WebSphere Portal. It looked like a good product since it had

    - a lot of features

It was quite stable. It scaled up well. It had a regular support and a regular documentation, useful for internal use, for people working at IBM, but not for users. So, it was a reasonable good box, ready to be delivered. My job was that. 

    - box

As a Solution Architect, I had to be with the client for a time. To my managers and teammates was just a process of product customization, just handling the requests of the client, modifying or adding new features to the product. So we were still within the box.

    - points within the box

But as soon as I started being with the client, I realized that reality was out of the box. That the situations, needs, motivations, goals, that trigger new requests, features, etc., were not under our control. They ocurred out of the box.

    - points out of the box

So, I basically started having a lot of interviews, talks with a lot of people in the client. I was used to sitting down and talking to them, eating with them... That discovery has always stayed with me in my career. Interaction design and product management have developed different wording and explanations for this. I like the one that represents it using economics terms.

    - supply and demand


# Bloated Products

Let's see a real example using that frame of supply/demand perspectives. The frame is useful because despite of our efforts to be user-centric or customer-centric, much of the things we think are in the demand side, are not. And much of the time we think we are understanding users, we are not.

# Engine as a Great Product

Kindle.

Engine as a great product.

# Thanks


It was around 2005, I was around 30. Now are now in 2018, I am 42. CARTO is not IBM, in fact, after a short time there, I have always been in companies more like CARTO, much more smaller than IBM, more in the startup scene or just mid-size companies. Still, 













qué quiero contar

engine from supply perspective

    - what we have built
    - a collection of libraries
    - a set of APIs
    - a pile of technology running under Builder

engine from demand perspective
    
    - what people need
    - which pains must be fixed
    - which situations are the root 

i'm going to refer them to over and over again
supply and demand are going to frame my talk

supply and demand come from economics but it is going to be used here in a different way

it is about from which perspective we look at the world

the first perspective is a selfish perspective: it is all about what we make,
what we build, what we ship... It is what we make.

The other side is the demand side. It is all about what you can't control. It is about
what is going on for the customer in ther life. It is out of our control:

    - we cannot decide what is happening to the customer
    - we cannot control what they are trying to do
    - we cannot control what they value

needs, desires, motivation, contexts

All of these things happen in the real world.

---------- image of a shop from inside and outside ??? ----------------
---------- image of a bike repair workshop from inside and outside ??? ----------------
---------- image of carto.com and builder too ??? ----------------

Although we know we must be user-centric. Although we are pretty informed product
managers or designers, or whatever. Although we like to think that we are sitting in
the demand box. But it turns out that in reality, a lot of things that we think
are demand, really aren't. And a lot of time when we think that we're understanding
the user, it's actually not the case.

That's what we are going to get into today.

Let's start with an example.

------------ example of share views with somebody https://github.com/CartoDB/support/issues/1266 -------------

It could also be regarding limits, that it's a project in progress, or whatever.
The thing here is that it is true that there are users asking for it.
But if we look closer at it we realize that when they ask for sharing and permissions,
that's just defining supply.

That is just telling us what we should make. If you look at this, it is not different
of having somebody from a higher level telling you "okay, in the next sprint we are
going to build a feature to manage permissions to look like x,y,z...

-------------- customer, people, user centric is not about being reactive,
is not about being on the supply side -----------------------------------------

But it is still difficult to understand what is the demand.
How would it look like?

Supply usually look like an app. Like a built product. And when you are
in the supply side, and you are thinking about a feature request, you are thinking
inside of the app. Inside of the whatever you have.

-------------------------------------------------
|                                               |
|                   box/app                     |
|                                               |
-------------------------------------------------

Then if you are good on product management, you have enough skills to understand
design topics, engineering topics, and so on, you start breaking the problem into
different parts like:

    - ok, we will need a new feature on the admin screen
    - ok, we will need to do something on the user model, maybe some new tables
    - ok, we will need to do something to record this

and bla bla bla

and it starts looking pretty well and organized

and we start talking about the implementation

---------------- reference to the classy story for kids about
it's just about four corners --------------------------------------------

we want to go out of our well controlled world, and ask directly people
not what, why, etc. 

You want to ask WHEN did you want it? You want to go to the real-life situation,
that exact moment when you feel that you need something.

And then you have to start asking questions.

"Well how did that come to your attention?"

"Hi, here Robert. I usually manage all this stuff related to CARTO. I am research engineer
at Scoop. We have changed our plan recently. We are now enterprise. The day we changed it,
we loose some of our viewers and builders."

"what did you do then?"

"I tried to share permissions with all of them, but they are a lot. So, I thought that
I maybe could do it via API."

Viewers,builders "How has it changed after upgrade?"

"Well, we want they to access to all maps."

....

Maybe it's just about when you are upgrading, you should receive some kind of notification
about the management of your viewers and builders, allowing you to do it the easy way. And
a bug fix to support this customer.


The we try to recreate the situation they had, upgrading from a normal plan to an enterprise one.
And see what's happening.

Now we have some understanding of the demand, we can think on alternatives to the first one
supply side solution. And probably it requires much more less engineering/design people, and
much more less big projects.

If we compare one to the first one, the first one is one hundred times more complicated.


----------------- risk and priority ---------------------------

Intuition. Stomach feeling.
You need to feel some certainty. That you know well the story, the case, the reality.
You can feel that there is chain of cause and effect.

CAUSE AND EFFECT 

It sounds good to go focus on the user, but in the reality if I don’t have a real, concrete, 
rigorous, clear understanding of: “this happens when … “ and I don’t have cause and effect, 
I’m not going to be able to make really trustworthy, informed decisions.






















































