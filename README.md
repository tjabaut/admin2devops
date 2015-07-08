#admin2devops
##Conference: VMworld 2015
##Series: #vBrownbag Tech Talk's
##Time 20 minutes
##Presenters: Jonathan Frappier & Tim Jabaut

###Possible Title1:
Stop being an "Admin" and learn to embrace "DevOps"

###Possible Title2:
Practical DevOps - Real world stories about small and medium size businesses embracing the DevOps culture to build more agile technology teams

###Abstract:
You don't need to be Facebook, Google, or Netflix to benefit from the culture and methodologies embraced by DevOps. There are less than 1000 companies* in the US with more than 10,000 employees... and roughly 6 million with 500 or less*. Chances are you don't need to solve the same problems at scale that Google or Netflix does. In this session you will hear about how small and medium sized business achieved business goals through the use of DevOps methodologies, including some unexpected benefits. (*US Census 2008)


###Time Table Breakdown
1. Introduction
2. Topic Overview
3. Core
4. Lessons Learned
5. Key Takeaways

Have you ever had to install a complex application with many procedural steps? What if you had to do it to 10 servers, or maybe a 100. With DevOps it doesn't matter. You define the process, write the script, then choose the host or host(s) to execute againt. Of course if you only have to perform something once it might not be a great candidate for automation.

In the following, I needed to be able to install Linux, Nginx, MySQL, PHP, and Wordpress. This install was for DEV environments, and as such needed to be able to be rebuilt over and over again to reset the base configuration.

<show manual series of events>

I started thinking to myself, I do not want to have to rebuild everytime I need to test a new module of an iterative change. So I wanted to automate the process. That's where tools like Chef, Puppet, SaltStack, Ansible and others come in.

<show Ansible playbook>
