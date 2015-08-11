#admin2devops
##Conference: VMworld 2015
##Series: #vBrownbag Tech Talk's
##Time 20 minutes
##Presenters: Jonathan Frappier & Tim Jabaut

###Title:
Stop being an "Admin" and learn to embrace "DevOps"

###Abstract:
You don't need to be Facebook, Google, or Netflix to benefit from the culture and methodologies embraced by DevOps. There are less than 1000 companies* in the US with more than 10,000 employees... and roughly 6 million with 500 or less*. Chances are you don't need to solve the same problems at scale that Google or Netflix does. (*US Census 2008)

###Time Table Breakdown
1. Introduction
2. Topic Overview
3. Core
4. Lessons Learned
5. Key Takeaways

###Introduction
What is DevOps? Like many things in the technology space, there are quite a few definitions, which doesn't help us understand what we are trying to do. For a lot of folks, it's also easy to look at the surface and say well we don't have a development team, so I can't DevOps. 

Let's define DevOps so we are thinking about this from the same perspective. Brian Gracey formerly of EMC Code, and now an Analyst with Wikibon uses a definition I like: 

"DevOps is a CULTURAL and OPERATIONAL model that fosters COLLABORATION to ENABLE high-performance IT to ACHIEVE business goals." 

I think that really sums up nicely what technology groups should be trying to do. In fact, from that respect DevOps isn't really all that new of a concept. We have been talking about IT transformation and IT-as-a-Service since someone coined the Everything-a-a-Service acronym...

And all this is true, because it rhymes!  

![Lego Movie Rhymes](/images/rhymes.jpg)

###Topic Overview
- Collaboration
- Automation
- Configuration Management
- Agile
- Additional Operational Benefits

###Core

####Collaboration
DevOps is as much about collaboration as it is technology, further its not enough to just create "DevOps" team and start automating away. If you are not working with teams across the organization, you could be just "shifting silos" as Mike Kavis talks about in DevOps and Bottlenecks (via virtualizationpractice.com). In his article Mike talks about how you end up shifting bottlenecks (a popular theme in the Phoenix Projet) without actually improving output. You might improve the output of one team, maybe the server group but do hundreds or thousands of lines of Puppet/Chef/Ansible code improve the output of the QA team?

Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum 

####Automtion
Have you ever had to install a complex application with many procedural steps? What if you had to do it to 10 servers, or maybe a 100. With DevOps it doesn't matter. You define the process, write the script, then choose the host or host(s) to execute againt. Of course if you only have to perform something once it might not be a great candidate for automation.

In the following, I needed to be able to install Linux, Nginx, MySQL, PHP, and Wordpress. This install was for DEV environments, and as such needed to be able to be rebuilt over and over again to reset the base configuration.

<show manual series of events>

I started thinking to myself, I do not want to have to rebuild everytime I need to test a new module of an iterative change. So I wanted to automate the process. That's where tools like Chef, Puppet, SaltStack, Ansible and others come in.

<show Ansible playbook>

####Configuration Management
Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum 

####Agile
Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum Lorem ipsum
 
####Additional Operational Benefits
With such a focus on "Dev" and "Ops" around collaboration, there are a few operational benefits that I have seen get overlooked.

- Disaster Recovery
- Compliance 

###Lessons Learned
1. Scripts are stupid (not bad, just stupid)
4. Start small, remove manual tasks
2. Take the time to re-write using native modules
3. It's not going to happen overnight
5. If you're a Ops, make friends with Devs and learn their methodologies
6. If you're a Dev, make friends with Ops and learn their methodologies

