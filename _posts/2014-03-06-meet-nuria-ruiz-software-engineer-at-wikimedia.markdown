---
layout: post
tags: spanish wikimedia developer madrid remote
title: "Meet Nuria Ruiz, Software Engineer at Wikimedia"
name: Nuria Ruiz
position: Software Engineer
company: Wikimedia
photo: nuria-ruiz.jpg
date: 2014-03-06
categories: wikimedia developer
description: We talked about many things, including how is it to work remotely in Wikimedia, her thoughts about what makes a good engineer and her experience getting in the industry with a Physics degree. We even got an scary anecdote from her days doing devops at Amazon.
intro: |
  We interviewed Nuria Ruiz, who recently joined Wikimedia as an engineer coming from a great background on different jobs and roles. We talked about many things, including how is it to work remotely in Wikimedia, her thoughts about what makes a good engineer and her experience getting in the industry with a Physics degree. We even got an scary anecdote from her days doing devops at Amazon.

  You can follow Nuria on twitter as [@pantojacoder](http://twitter.com/pantojacoder).
---

### Where are you working?

I’m currently working at the Wikimedia Foundation, which is the foundation behind Wikipedia. Wikipedia is one of the multiple products they do, the most well known one. I’ve only been there for couple months, so I don’t do a whole lot that is not learning. Although I’m doing a real project it involves a lot of getting to know how the community works. I’m doing this because a very particular thing about Wikimedia Foundation is that not only do you need to take assignments from your boss and your peers, but there’s also a community of volunteers that you need to take into account when you do anything.

Right now I’m trying to gather community feedback for my project to make sure it’s viable and the community likes it, because if they don’t like it they have veto power, which is an interesting thing, right?

### You mean the community has veto power over your projects?

Yes, that’s super interesting because I’ve never worked anywhere where you have an outside force that actually determines your work. So I’m trying to see if what we want to do - which is gather User Agent data - is viable within the privacy restrictions of Wikimedia. That has many implications, since User Agent data has very precise information about things like the build of Windows that you are using. You can use that data for fingerprinting and to pinpoint a specific user. We have to do some sanitization and anonymization, and we need to check how far we need to go with this process to make it comply with the privacy requirements of Wikimedia. See: http://www.mediawiki.org/wiki/EventLogging/UserAgentSanitization

It’s both a logistically complicated problem, because you need to involve hundreds of people in the discussion, and technically complicated, because it’s not easy to sanitize data.

### And what’s the area or department that you work in?

I work in the Analytics team. It’s the team that provides other teams with tools to deal with data. The team has been newly created; we are currently six members in the team, but three of us are also new to the company. One interesting thing is that Wikimedia doesn’t have tech managers. There’s only Engineers and Directors, and the Engineers are self-organised within projects, which is very different than anywhere I’ve worked before.

As an engineer you actually have a lot of power because you can decide “this is the implementation I want to go for” and you can be all gung-ho and say “I’m just going to deploy it and that’s how it’s going to be” or you can gather more feedback. You have a lot of autonomy.

### Do you get to choose what you are going to actually work on?

Yes, you have 100% say on your projects. You could be hired on the analytics team, but lets say you are very passionate about getting into Impala (a project of the ever-growing Hadoop ecosystem). You can say “I really think that this is going to solve our problem X, so I’m just going to install it and try prove that it works well for what we want”. Every team has a mission that you have to contribute to, but provided you are reasonable, you can do this kind of thing and there’s a bunch of people that work on this fashion in Wikimedia. You need to know your public in order to proof your results.


### How does that translate in what’s your day to day like at work? What does your normal day entail?

In my team, everybody is remote. We have 3 people on the East Coast and 3 in Europe. The director of the team works in the main office on the west coast but the rest of us are distributed.

Since everybody is remote, you need to produce lots of documentation. Normally, whatever you are working on, everything you do must be documented and everything goes through code reviews every day. You interact with your colleagues via Google Hangouts and hardly see them in person. Since every day involves lots of work to document what you are doing, there’s definitely a communication overhead. Normally you get a project, decide what it is that you are going to do, probably create an internal wiki to gather your team’s feedback and - once everybody is kind of in agreement - you create an external wiki and gather community feedback. Once you have all that, you decide on implementation, start implementing and interact with your peers via Google Hangout.

This obviously depends on your level of autonomy. For me right now, I’m not autonomous yet, so I need to work with someone to make sure I’m working on the right systems or testing them in the right way.

### Do you have less of a communication overhead once you have decided what you are implementing?

Yes. It’s understood that engineers have complete autonomy. It’s part of the Foundation’s mission that you empower people to do what they think is right. At the beginning you interact with your peers a lot and you document a lot to make sure you get on the same page and I think that overhead gets smaller once you are more clear on what the outcome needs to be.

Overall it’s very interesting and it is a very different way of working compared to anywhere I’ve worked before, that’s for sure.

### Where have you been working before?

Before Wikimedia I worked at Tuenti, a social network in Madrid, at the time I joined (in 2010) was the biggest website in Spain and it had more traffic in the country than both Google and Facebook combined. It was a very large enterprise, probably one of the largest in Europe at the time. I worked there for three years. I worked mostly on frameworks, which is what I’ve done the longest and what I think I know how to do best.

Before Tuenti, I worked at Amazon for 7 years where I did many different jobs. I was a web developer, I did devops. I was also an engineer in Amazon Web Services when it started and I also worked in platform for a long time.

Before Amazon I worked in a laboratory as a physicist. Well, as a physicist but not doing my own research. I worked on other people’s research, as a Research Assistant.

### Your background is as a physicist, not as a Software Engineer?

My background, what I studied at school, is Physics. I worked in Software early on after finishing my degree because there were many jobs at the time. I finished my degree in 1997, so it was a long time ago. At that time there many jobs in computer science that couldn’t be filled in by computer scientist graduates because the degree hardly existed, it was fairly new. It was easy to transition from a Math or Physics degree to a CS position. Everybody assumed you needed training but that you were smart enough to pick it up.

I worked on software early on for a couple of years but, after that, I thought it would be nice to go back to science and work as a programmer in a scientific setup. I studied physics, but the experimental kind, like atmospheric science or oceanography. I very much liked the experimental side of physics so I got a job that involved gathering oceanographic data by sailing on a ship in the ocean, and I liked that very much. I think that’s something that you are never going to get from a position that doesn’t entail science because fieldwork is something that is not common on CS jobs. I liked the fieldwork a lot and would probably do that again.

### When you say going on a ship in the ocean, is that a metaphor or were you actually on a ship in the ocean?

No metaphor: I was actually on a ship in the ocean 6 weeks a year crossing the ocean gathering data. I did that as part of my job. I worked for PMEL (Pacific Marine Environmental Laboratory) for three years, which is one of the biggest oceanographic labs in the world. There were five big physical oceanographic labs in the world at the time: one was in Japan (JAMSTEC), another one in France (worked with us under [IRD](http://en.wikipedia.org/wiki/Institut_de_recherche_pour_le_d%C3%A9veloppement)) and the other three in the US (WHOI, PMEL and Scripps).

So I worked in PMEL and the goal for the project I worked on was doing [El Niño predictions](http://en.wikipedia.org/wiki/Tropical_Atmosphere_Ocean_project), which is a huge project that involves hundreds of people around the world. In order to do that you have an array of buoys that spans all around the equator. There are about 65 buoys in the tropical pacific Ocean,  those buoys need maintenance because they are gathering data but don’t last forever. You need to go on a ship, get the buoy, suck the data out (some of the data is transmitted via satellite, but some other data is in the buoy) and replace the buoy with a new one. That’s an ongoing project, since you need to maintain the array of buoys to get a continuous data feed to make your predictions.

![Picture Nuria took from the ship](/assets/photos/nuria-ruiz-ship.jpg)

### Did that job have some CS related part?

Computer science is everywhere. First you have a data stream that goes via satellite, but that is just bytes, to convert those into physics data you need processing and calibration. You have physical instrument that transmits bytes and you need to transform that into things like rain or radiation emissions and that’s purely processing. So you have tons of processing of data and data at a huge scale. Imagine how big the network is!

### So you were doing Big Data in the 90’s?

Yes, that was Big Data. This was at the time where all that data went to a mainframe. That’s how big it was. We did this project in the year 2000 to move all this data into MySQL, but at the time the data set was so large that we had database problems. Hadoop didn’t exist back then and everything was home-grown solutions. But the people who were doing it were very capable. These people were working with computers from very early on and they used to solve problems in very ad-hoc ways that worked.

### Where did you get the training to be able to do that job?

You trained on the job. They choose people with a background on physics to work as research assistants because you had to understand the constraints of working with a physical system, not a theoretical system, which is very different. Then you trained on the job as much or as little as you wanted because the quality of the programs we wrote at the lab were of a different nature. Some people just did the bare minimum every time they needed to get your processing going. Some other people worked on building a system that you could use repeatedly, but you trained yourself.

### Did you just do programming for data processing?

No, you have to do everything. You also needed to setup and manage your Linux servers. Although that seems like a lot of work, it is very common in a scientific setup. You join a lab, somebody gives you a computer, you setup your computer, setup your printer, if there’s a Linux server you administer it, if there’s something that needs to be installed you do it. The IT staff usually just buy and replace the hardware, but they are not there to help you process your data.

The people who worked in the lab were very capable. Some people had been around since the days of punch cards. Those people were going to do anything and no task was too daunting. They had seen the world change so much that everything seemed possible to them. I came to learn that for them, administering systems and processing data were small problems.

### You had to learn to program after university then?

Yes, I started learning a little bit in my last year of university; once I finished, I got a job in Spain that paid me to learn for half a year and I had to stay there some time after that. I think I worked for another half a year there. After that I just had to learn on the job. But at the time everyone had to do it like that since most people working on CS didn’t have CS backgrounds.

### With all the different roles you have worked on, you must have had to learn “on the job” a lot, didn’t you?

Yes, I think that’s true for anyone working in computer science. Any time you change jobs you have to learn a lot. And if you like learning different things you will learn a lot.

I think that a good way to define somebody who has worked for a long time in computer science is that you know a little about many things and a lot about very few things. And that’s always a good background. Since things change so fast, the strongest skill you want to have is being able to assimilate knowledge. Most knowledge that you have is going to be outdated in 5 or 10 years.

### So you need to have a broad foundation so things can ring a bell later?

Yes, the problem with that is that you learn lots of things but sometimes lack the theoretical foundation. Either you go and seek it or you have big holes in your knowledge. You know about A, B and D but it’s like a cheese with holes. For example, I know very little about networking because I’ve always worked with people who knew a lot about it, so I focused on other things. I definitely have gaps of knowledge that I’m always trying to fill.

### And when you got your first job programming and you had to start to learn. What is it that you learned?

In the very first job? Oh my god, we used a visual environment that was like the prehistoric Visual Studio and prehistoric Visual Basic. Some of the very first editions of it. It was all Windows based. That year was the only time of my life that I programmed in Windows. After that I learned that the visual environment to program was a rarity and it was not common.

It now sounds bizarre to me that it was all Windows based because I don’t know how to use Windows at all anymore.

### And what are you using right now?

In Wikimedia, the site itself (that is, wikipedia), is written in PHP, but it’s just the web piece. The ecosystem and all the tools around it is mostly Python. There is also JavaScript, although not very much. And there is also Java for Big Data jobs which is what part of my team members are setting up.

There’s many Python experts working in Wikimedia and many PHP experts.

### And Python is more for the support programs that run in the background?

Yes, that’s right. Wikipedia is like two different sites. One is the side that everyone sees: the Wikipedia site, with 500 million users. The other site is the one the editors see, which is the interactive side, but most people hardly ever see that. They’re two completely different infrastructures.

### Did you have experience with those languages or are you learning on the job?

I used Java in Amazon for a long time, but I haven’t used it much in the last 4 years. Python, I’ve never used it at a large scale like here. Also, the Python community has a certain way of doing things.

I think Python is a great tool to learn because all the work that I used to do at the lab in Matlab you can do in Python. If you had to learn a new language right now, I think the most versatile one is Python. The physics programs that are used to process data for physics are moving from Fortran 90 and Matlab into Python.

### How did you end up working in Wikimedia?

After the startup I was working for got bought by Telefonica I no longer wanted to work there because I didn’t want to work for such a large company. I wanted to keep the focus of working for a small company and I wanted to work somewhere that it was 100% customer focus.

I thought to myself: “Which is the project that I use that has a true customer focus that I can identify with myself as a consumer?” And I thought about Wikipedia. I use Wikipedia almost every day and it just exists for its users. No other purpose.

So I sent my resume. Nobody approached me, but after I sent my resume they answered very fast.

### Did you find they had an opening and send the resume?

Yes, I saw they had an opening in the analytics team and I wanted to get more into the computer science side of data. So I sent them a resume for that position.

I thought that they probably received hundreds of resumes and they probably wouldn’t answer. I know now they get at least three hundred responses for every position.

Since I had worked in the west coast for many years and I know many recruiters around Silicon Valley and Seattle. I thought I could always reach out to them by other means if I needed to, but the recruitment department in Wikipedia is great and they answer well and they filter well. They put a lot of emphasis on cover letters. Tons of people want to work there, but they want to know why is Wikimedia compelling to you.

### Where did you find the opening?

I must have seen it in [Stack Overflow Careers](http://careers.stackoverflow.com/), because their site has a very handy filter for remote positions. You can look only at positions that allow remote work.

### And you sent it even though you thought they would have hundreds of candidates?

At the time I thought it would be thousands of people. I asked the recruiters once I joined and they told me it actually is in the hundreds. So I spent some time writing the cover letter telling them I wanted to work in a mission-driven organization, not a profit-driven one.

> #### Nuria's Cover Letter to Wikimedia
>
> I would love the opportunity to have a position at Wikimedia and be part of a project whose main purpose is to enable people to share knowledge. I want to learn more and get better at what I do and learning from talented people, while working for a greater purpose, seems an amazing opportunity.
>
> I have worked in large (tuenti.com) and very large (Amazon.com) websites. Most of my experience is around developing front-end frameworks (in desktop and mobile) for other developers to use. At work I use PHP, Javascript and, sometimes, Java. To try things at home I prefer Python. As of couple months ago I have been trying to solve the challenges that come up with the development of hybrid mobile apps (HTML/native) in Android.
>
> I am used to working in a multicultural environment and I understand the challenges that present when you have a distributed team.
>
> Thanks for taking the time to read this.
>
> Looking forward to hear from you,
> Nuria

### And why is it that you wanted to work in a smaller company?

I wanted to work on a company in which you could really focus on the product and I think the larger the company, the more bureaucracy it has. That is not always true, but it is definitely true in many cases. The larger the place, the more bureaucracy it has and it’s harder to get stuff done. There are many other stakeholders besides the user. Being small, it’s easier to be agile.

Although that’s not true everywhere; in some large companies there are small segments that can run as a small organization.

### Having worked in big and smaller companies, have you identified anything specifically that in your opinion stops progress once you get bigger?

I definitely think that, no matter how large the organization, if you have too much process it reduces the ability you have to change things. The less you can change things, the less agile you are and the less you can focus on your end user.

I think that, even if you are a large company, you always need to leave an element of chaos. If you have to weigh chaos and bureaucracy, an element of chaotic organization is probably better because it allows you to react faster. However, it’s hard to find the balance.

In my experience, once you go over 150 or 200 people things change dramatically. Once you cannot remember everybody’s name, things do change. Some organizations adapt better than others, but they need to change.

### Do you think there’s anything that can be done when you have a larger organization to manage it better?

When I worked early on Amazon, we were thousands of developers. Not many thousands, I don’t know how many,  but I would say probably 3 thousand at most. I think it worked pretty well. The hierarchical organization was very flat. You were never more than four steps from Jeff. He liked to call it ‘the pancake’.

I think it can work with a flat hierarchy and a very strong audit process where you can empower employees to do whatever they want but ask them to proof why things worked. Everything has to have a value proposition and you need a very strong process that validates ideas once they are executed.

That worked pretty well. I mean, we were able to develop Amazon Web Services that way and it did work. I don’t know if it stills work that way, but it definitely worked for us.

An example: If I remember right, when Amazon launched S3, they had the product developed, the launch date was approaching and it was just some months away. The manager for S3 at the time, got together with the engineers to review again the number of machines they needed for their growth they were forecasting and they realised they were not ready to scale that much and they needed another year of development. If I remember this properly, the manager of S3 went to Andy Jassy who was the head of AWS at the time and requested one extra year for the project. They launched one year late and, although S3 had many problems at launch, it worked remarkably well to be the first of its kind. There was a lot of adaptability and having numbers and metrics helped. But it was definitely chaotic.

### Did they do any outside communication about the delay?

No, because I believe the project was secret at the time. I learned this happened because once we launched S3 we also launched Amazon Mechanical Turk at the same time and I remember hearing one of the engineers tell this story. But at the time this happened S3 was a secret project.

### If you were not working at Wikimedia, what other kind of job would you look for?

Besides looking at Wikimedia I also contacted change.org because I like their product a lot. I asked if they would consider a remote position and the CTO got back to me (because I follow him on Twitter) and he told me to email him because he was looking for engineers. I did email him and he did answer, which I thought it was pretty amazing, but he told me they didn’t consider remote candidates.

I would have mostly looked in the non-profit sector. Or a [B-corp](http://www.bcorporation.net/what-are-b-corps) like Etsy. I would have liked a big org, not-for-profit, ideally remote to be able to learn the mechanisms of remote working, and with an international focus. I think it’s always good if you are a remote worker that the company understands different cultures, languages and schedules. For the culture fit. I think Etsy would be like that since they have a big foreign component, is a big org, and is also a big on PHP but they also have Python ecosystem.

I talked with Etsy’s recruiters, but they didn’t allow remote by default. They allow existing workers with whom they have a relationship to work remotely, but they don’t currently employ remote from day one.

### Why is it that you wanted a remote position so much?

I thought it would be something to learn: how to efficiently work from a remote position. It seems remote is a new trend, sounds a bit like “go to the beach and work from your laptop”. It’s not like that, but it seems there’s this growing idea that workers can work remotely and be productive, so I wanted to give it a try for myself. Regarding organizations, I couldn’t think of a better one than Wikimedia, since it is always been remote. Wikipedia started that way and it’s not just a new trend for the foundation. That was very interesting to me.

### How is remote working for you so far?

It’s harder than I thought it would be. It’s actually really hard because not only you have to be disciplined (that’s OK, I think I’m very disciplined), but you also have to always have a positive mindset because it is so easy to read things wrong when everybody is talking on IRC. IRC is very brief and you can mistake briefness for harshness. And you don’t have all the body language and intonation to help you. You have emoticons, but I’ve never been very fond of those and I don’t use them very much.

It is harder than I thought it might be. And it is also tiring because it’s harder to communicate via Skype than it is to communicate in person. You cannot even get around a whiteboard and discuss something. The lack of whiteboard is a logistical challenge, but there are also many challenges on the communication process.

Regardless, I believe it’s something to learn since it’s the way the future is going to be. Some percentage of the workforce is going to be remote. In the book “Remote” by 37signals they say that everybody is remote at some point in the day because you would send an email to someone and that’s asynchronous communication which is already remote.

It is nice to learn how to manage that better, but it’s definitely hard to do it well.

### Where are you working from?

I work from home in Madrid a couple of days a week and from a co-working space the rest of the time. Because most of my team is on the East Coast, I kind of work on East Coast time and I have to go home and do the late calls.

### You have time-shifted a bit to fit the east coast schedule?

Yes, you have to start working later and finish later. You need to compromise there a little bit because if you have 3 different time zones the easiest is to compromise on the middle one, so between West Coast, East Coast and Europe, it is easier for everyone to work on East Coast time.

That doesn’t bother me. I always liked the flexibility. Your teammates understand that you might not be available tomorrow evening because it’s your daughter’s birthday. That is very well accepted and that’s where having a company that understands working on different time zones and cultures really helps.

### Why did you choose to get a coworking space? Was it to avoid getting too reclusive?

Have you seen The Oatmeal comic [“working from home is both horrible and awesome”](http://theoatmeal.com/comics/working_home)? The one where they guy ends up like a neanderthal in the house?

No, it is because my house is very small and working from there is not that easy logistically. We set it up so that you can do it since my husband is an architect and he does that very well. But it still is very small. My apartment is not even 70 m^2 and my husband works from home full time. It gets tiring to work in such a small space. It is nice to work in a bigger space. If I had a house four times bigger than mine I think I wouldn’t need the coworking.

However, it is also nice to be able to come to the coworking space and talk to people. But I could do away with that, work from home, and get the social fix in different ways. Living in Spain there’s no lack of social opportunities. Everything you do here is social.

### What are the skills that you feel are most important for your job?

I think the most important skill is to be able to communicate well. Although, to be fair, you could be in a team where somebody communicates well and, if you are not a good communicator, you could do away with that. You could have a person in the team who fills that role. But you have to communicate with lots of people: sometimes with users, product owners, people complaining when there are problems, etc. And you have to be able to transform verbal communication in some kind of technical diagram or fix. Communication is very important.

Another thing is an ability to learn new things and liking to learn new things. Some people have the ability to learn but maybe they don’t care and they just want to focus on the technology they know well. An ability to learn new things also plays a part into making better decisions.

I also think you should be internally motivated. You need to find motivation within the work itself rather letting your deadlines motivate you. Otherwise you end up not being able to deliver when you don’t have a deadline. It’s important to be inherently motivated and being able to do a good job just because you think that’s what you need to do.

### What advice would you give to somebody who wants to find a nice job?

I think the most important thing for any job is to know who do you work for and who do you work with. You can be doing the nicest task ever, but if you don’t work in a nice environment you will not enjoy it. It’s very important to work in a team where you have a good cultural fit. Maybe not a exact cultural fit, but at least somewhere where you feel comfortable.

It’s also very important to look for a team that has a good manager who advises you well and who you can communicate with you.

The third point would be looking for a task that you find interesting for itself. However, you have to know that any job that you get in a high-tech field will change dramatically. In six months you might be doing something different. Look for something that interests you while having an open mind.

The cultural fit I would definitely say is more important than anything.

### How do you choose something that you really like considering it might change dramatically?

If you work at a very high-profile state-of-the-art company (Google, Facebook, Amazon, or even a start-up) you are going to work at a very fast pace and your job is going to change a lot. You cannot let change unsettle you and you need to have adaptability, which I also think is a skill. I would advise everybody to think that, although their job looks fantastic now, in six months it might be something completely different but still be fantastic.

Also, there’s always 30% of tasks that you have to do in your work that are completely outside of your position. You will need to do interviews, fill recruitment reports, look at various bug lists, or fix a build system somebody did 5 years ago. Every job has a percentage of time that you spend doing things that don’t strictly pertain to your position.

### Do you think spending time on these extra tasks happens very often?

Yes, if you work on a large enough system you will end up having to do these extra tasks. Your team might depend on this piece of work from another team and you need to help fix it. There should be a balance and that should not be your full job, but you will need to do it.

On my experience, all jobs require having to talk with other people and doing other tasks apart from programming. Even in jobs that are very low in the stack you have to do other things besides write code.

### Is that why you mention communication as one of the key skills for your job?

Yes. It’s true that in a team people take different roles: some people might write code 60% of their time, others might program 30% of their time and spend the rest of the time communicating. The team members help each other with their different strengths and weaknesses. But you should definitely expect not to be writing code all the time and expect needing to use other skills.

### Are those roles taken on by developers or do you have different positions for the different roles?

In my experience, those roles are usually distributed among developers. In some companies, there would be specific positions. As an example, at Amazon we had the Technical Project Manager position and that person never writes code and just manages a project at large scale, but it is a very technical position. On my last team at Amazon, the Technical Project Manager had a PhD on distributed computing. So it’s still a very technical position, even if you don’t write code.

For developers, especially if you work at a more senior level, you are expected to do things like giving a presentation to convince a business person why this is the right architecture and why it is going to take three more weeks to get it done. That’s part of your job.

### So you think that, even when your position is as a developer, you are not going to be programming 80% of your time?

In my experience that only happens if you are doing a code contest or something like that :)

In the real world, I have never seen that be the case. Maybe there are some jobs where you get to employ 80% of your time coding, but I have not seen that.

### And given that developers need to take different roles in a team besides programming, does that mean you don’t need to be an amazing developer to be valuable?

Certainly. And you may also be very good with certain piece of technology and be very valuable in a team that doesn’t use that technology at all. The principal engineer I worked with at Amazon before moving to Spain was a super good C++ developer and he had developed many of the algorithms Amazon uses in the warehouses for efficiency, but we were a Java shop in the platform team. He didn’t know much Java, and yet his input was invaluable. He had had this complete vision of the system that nobody else had.

The technologies you know don’t necessarily go hand in hand with what you can contribute and the skills you have. I actually think that diversity is always a must. A diverse group with different backgrounds and skills is always better, makes better decisions.

### After all these years of working in different roles, is there anything you have learned that you particularly wish you could have told to your own past self?

Yes, I wish I would have dedicated more time to learning early on on my career. I would dedicate more time to learn the fundamentals of computer science. For example, I’m trying to learn about cryptography now, which is something I don’t really know much about. I would have liked to learn things such as cryptography earlier.

### When do you think having learned the fundamentals earlier on could have helped you?

Right now is a good example, this project I’m doing about gathering user agent data. We have to remove information that is fingerprintable and finding unique user agents. A better knowledge of cryptography is going to help me a lot. We have to do the opposite of finding duplicates, we need to find unique data and remove it.

The thing is that, everything you learn helps. It’s sometimes funny that you do some [Coursera](https://www.coursera.org/) course and the week after finishing it you are using your newly found knowledge. Every piece of information seems to be useful at some point.

### What kind of resources do you use to learn these things?

I’m a super-fan of Coursera. If they added a “Donate to Coursera” button, I would be donating tomorrow. But there’s also so many other good resources nowadays like the Google Python courses that Google gives to their engineers, which are available online. Twitter is also publishing material in [their engineering site](https://engineering.twitter.com/) and you can start learning Scala very well. Those are the three I use the most apart from Wikipedia.

Wikipedia is always the best reference to kind of know what’s going on. After you get a general idea you always need to dig further to learn the details.

### Do you use Github and read other people’s code?

I use Github, but not very much. I should use it more. When I have a problem I sometimes check in Github, but the issue with Github is that everything gets searched in equal terms and there is a lot of noise that you need to search through to get to good things.

I do search for concrete projects. As an example, I used it quite a bit on the last project I did in my previous company where I was looking for libraries for dependency injection in Android. There are some amazing open source projects on that.

I find Github is good for finding some very concrete solutions, but not to look for anything broadly.

###  The project you mentioned you’re working on, what does it bring to Wikipedia?

I’m working on identifying how Wikimedia can best store user agent data without breaking Wikimedia’s strong privacy policy. That data would allow us to get new stats like a precise ranking of mobile device usage in Wikipedia, which we don’t have right now.

### What was the Wikimedia interview process like?

Of all the processes I’ve gone in my life, this was the most focused on the cultural fit. There were around 7 interviews, and only two or three were technical interviews. All the other interviews were about cultural fit.

### Were the interviews remote?

Yes, all the interviews via through Google Hangouts and it is hard to interview via Google Hangouts. It is very tiring, but any interview you do right now is probably going to start with some process where you write code remotely, so it is good to get trained on that.

### Does Wikimedia have an standard process, or is it ad-hoc for each candidate?

It is pretty standard because once you pass the technical filter and the team cultural fit, the CEO of Wikimedia interviews every candidate they want to make an offer to and she has veto power. Also the CTO interviews every technical candidate.

That makes the interview process longer. As you can imagine, the CEO of Wikimedia has a tight agenda! My process was three months, which I think it’s quite long. I would normally expect a two month interview processes. I’ve seen processes in Amazon take three months, but those were rare and it was more common to complete the process in weeks.

### Are you interviewing people now for Wikimedia?

Yes, I did my first interview via Google Hangout last week. I found it was a hard thing, as you need to keep track of it and take the notes, which was not easy on a Hangout.

### What are the things you value the most when interviewing people?

As I said before, communication is very important to me. It is very hard to dig answers out of somebody who doesn’t communicate very well. I also expect people to be able to backup what they say in their resume. If your resume says you like to write protocols but you cannot explain any protocol you have written, that’s bad.

You also have to be careful when you say you are an expert on anything because somebody is going to call you on that. It is OK to day “I took the Scala course in Coursera and I would love to learn more Scala”, that’s a good thing to say, but if you have only played with some technologies at home, you are probably not an expert since you have not used them in a real setup.

I also value having an ability to deal with ambiguity. Every software requirement you are going to get is going to be ambiguous and is likely to change, so questions that are ambiguous on purpose cannot unsettle you.

### Would you usually ask interview questions that are intentionally ambiguous to have the candidate digs deeper into what you really want?

Yes. Some questions have deadlocks, but in general you shouldn’t get blocked. If I tell you the Wikipedia homepage is blank and ask you what might be the reason, there are many reasons why that might be the case and you cannot just choose one at random. You have to be able to pull from your knowledge and try to troubleshoot the problem.

### What do you think interviewees should pay more attention to?

I think something many people fail at when interviewing, including myself, is that we get too caught up in our own thoughts. You start with a train of thought and you try to make that work regardless. Maybe you should back up and start with a different train of thought. But it’s easier said than done, especially in an interview setting where you are worried about being wrong.

I think it’s the responsibility of the interviewer in those cases to give you another question to give you the opportunity to rethink it.

Another thing that comes across too often is people inflating their resumes. That’s not a good sign because people will call you on that. If you portray a project as something amazing and you didn’t use source control, by definition that project was not so big. You have to make sure you portray what you did in the light it deserves.

### What would you recommend for people who are getting into the industry and don’t have a portfolio of projects to highlight?

I would recommend they list the projects they did at school that they were passionate about and that they list them as a school projects. Those are very valuable too and there’s nothing wrong with them. It’s also good to list your interests. You might have been using Java at school but you are interested in Lisp and use it in your free time.

Having a Github account and contributing to an existing project is really good too. There are many projects you can contribute to and it also allows you to test your skills contributing to a real system.

Those things show you have an interest. For many people computer science is just a way to get a nice job. If that’s the only think you are looking for, it’s hard to find an inherently motivated person. It should be something that motivates you where you want to find a nice position with good teammates.

### Do you have any interesting stories from your experience in the industry?

I have a million stories, but some of them may scare people and others are good ones. Which one would you like?

### Let’s do an scary story first! can you tell us one?

The thing with those is that you learn a lot. When I was doing devops at Amazon (where we had like one scary story every week), we had just opened a datacenter in Virginia and it was the first time we were deploying to a different datacenter. We were deploying something in the new datacenter... I think it was the Japanese website because we used to deploy the front-end for Japan, the US and Europe. After we finished the deploy, the whole japanese website was just a blank page, nothing was rendered, which means obviously nothing worked and nobody could buy anything on Amazon Japan. We started reviewing everything, trying to figure out why the deployment had not worked. It seemed all the software was properly installed in all the machines and we were struggling to find out what was going on. In the end, somebody who had been doing ops from Amazon since the company started figured out that all the DNS addresses had been provisioned, but the machines they resolved to were not there. It was like we were deploying to the void. The tool made it look like all the machines existed but they had not been provisioned, they were like ghost machines and the infrastructure was getting confused. It was like deploying to /dev/null

It took all night to figure that out and we managed to fix it when the sun was coming up in Seattle, which means in Japan it was already time for people start buying. We were able to reverse everything, people had to be woken up to help provision all the machines, it even required a good deal of software work and some people in the datacenter fixing some things. It was very stressful because, when that happens, you are losing tons of money. It’s OK to make those mistakes when it is something very new, but it’s still very stressful.

### Is it stressful because of the situation or because somebody is going to get fired for that?

Nobody would get fired for doing something you haven’t done before and finding unexpected problems. That’s expected. Now, if that happened three times, probably somebody would get fired. But if you are doing something new it’s expected that you are going to encounter problems.

Even though nobody is going to get fired, it’s very stressful to have this kind of issues.

There was this time where all the book cover pictures disappeared from Amazon in the middle of the day and we were like “what is happening!?!?” Of course, you try to collect yourself and stay cool, but you look at the website and there are no book covers, and it’s stressful.

On the other side, you learn a lot from those stressful moments and it has the nice side of the story: we were in a team where we all trusted each other 100% because there are very important challenges and everybody needs to do their part to overcome the issues. The devops team I worked on that year was crazy and whatever had to be done, we got it done. Now, ten years later, we still have team lunches and we still see each other because we built tons of confidence in each other. In that respect it was very rewarding, because we had very difficult challenges and we managed to accomplish them.

### And how is it that you have taken so many different roles in the industry? How did you get to do devops?

I found myself doing devops because reorgs at Amazon were crazy and sometimes from one day to another your job was different and you had a new job title. I was moved from Web Developer to DevOps. After doing it for a while I decided I liked development better than operations. Although at Amazon, any development you do includes some operations because you are responsible for your own software. The difference was that in devops you were also responsible for other people’s software, not only your own.

I try to always find what I like to do best and focus on that because I think focusing on what you like makes you happier. Another example is that I definitely like coding better than managing teams.

### What do you like about the job?

I like to write code because I like abstractions and solving problems.

### And how is work structured in Wikimedia?

I shouldn’t talk about QA because I still don’t know how it works at all. Ops is unbelievable. We have less than 15 people for all Wikimedia. For 500 million users! The Ops person in my team is extremely good, he is an operations guy but also a backend developer, he knows about front-end, Java, Python… They must be like an elite force.

### Do you have one ops person dedicated to each team?

Normally people with commit access to Wikimedia can commit to branches and, after a thorough review process, they can commit their changes to master and you get a deployment window so that the ops person knows you are going to deploy some software and they can keep an eye on it, but they don’t need to do anything.

You can push your changes to production yourself or the automated system pushes to production regularly, but there’s no involvement from ops to get code into production. You are supposed to have done your homework.


### For your project, what are the steps before it goes live?

If my project is implemented, we will initially deploy it ourselves to our internal systems in Wikimedia. It is easier since it doesn’t go to our 500 Million customers, it just gets deployed into our internal infrastructure. Then we can just turn our analytics off, deploy the analytics system, and turn it back on.

### If somebody were interested in joining Wikimedia, where can they apply?

They can go to [our Jobs wiki page](http://wikimediafoundation.org/wiki/Work_with_us) where we have all the open positions published.

### Being a remote team, is the team composed of mainly senior people or do you have some junior people to?

It’s senior people. There’s definitely some people more senior than others, and also senior in different aspects. For example, we just hired somebody who is very senior in Artificial Intelligence but very junior in terms of building large production systems.

That’s a drawback from working on a remote team. People working remotely need to be quite self-sufficient. Wikimedia has some junior people working on-site in the office and also some volunteers who contribute to the project but don’t get paid.

### If somebody junior wants to join wikipedia, what would they need to do?

It will be hard to work in a fully remote team. I think they would need to be based in the office in San Francisco or contribute as volunteers. We have three people that I know of in Wikimedia whose job is to help volunteers. If you approach them and tell them you want to work in certain project they get in touch with the people working in the project assign the project to you if there’s nobody else waiting.

If you want to contribute some code, we have a page with [MediaWiki Annoying Little Bugs](http://www.mediawiki.org/wiki/Annoying_little_bugs) which are a good way to start getting familiar with the code base.


