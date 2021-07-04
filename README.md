# CI/CD

#### Q. What are the fundamental differences between DevOps & Agile?
DevOps is a practice of bringing development and operations teams together whereas Agile is an iterative approach that focuses on collaboration, customer feedback and small rapid releases. DevOps focuses on constant testing and delivery while the Agile process focuses on constant changes.

#### Q. Explain difference between Kubernetes vs Docker vs Jenkins vs Ansible

While Ansible uses Python while Docker and Kubernetes run on Go Programming. Ansible also easy to use and effective for configuration management, and Docker is easy to understand and isolate. However, Kubernetes requires well-planned efforts when it comes to defining nodes and manual installation.

#### Q. What is meant by Continuous Integration?
Continuous integration (CI) is the practice of automating the integration of code changes from multiple contributors into a single software project. ... The version control system is also supplemented with other checks like automated code quality tests, syntax style review tools, and more.

#### Q. Define Microservice Architecture?
Microservice architecture – a variant of the service-oriented architecture (SOA) structural style – arranges an application as a collection of loosely-coupled services. In a microservices architecture, services are fine-grained and the protocols are lightweight.

#### Q. How is DevOps different from Agile/SDLC?
DevOps is a practice of bringing development and operations teams together whereas Agile is an iterative approach that focuses on collaboration, customer feedback and small rapid releases. DevOps focuses on constant testing and delivery while the Agile process focuses on constant changes.

#### Q. What are benefits of CI-CD?

Smaller code changes are simpler (more atomic) and have fewer unintended consequences.
Fault isolation is simpler and quicker.
Mean time to resolution (MTTR) is shorter because of the smaller code changes and quicker fault isolation.
Testability improves due to smaller, specific changes. These smaller changes allow more accurate positive and negative tests.
Elapsed time to detect and correct production escapes is shorter with a faster rate of release.
The backlog of non-critical defects is lower because defects are often fixed before other feature pressures arise.
The product improves rapidly through fast feature introduction and fast turn-around on feature changes.
Upgrades introduce smaller units of change and are less disruptive.
CI-CD product feature velocity is high. The high velocity improves the time spent investigating and patching defects.
Feature toggles and blue-green deploys enable seamless, targeted introduction of new production features. 
You can introduce critical changes during non-critical (regional) hours. This non-critical hour change introduction limits the potential impact of a deployment problem.
Release cycles are shorter with targeted releases and this blocks fewer features that aren’t ready for release. 
End-user involvement and feedback during continuous development leads to usability improvements. You can add new requirements based on customer’s needs on a daily basis.

#### Q. What is PaaS?
Platform as a service (PaaS) or application platform as a service (aPaaS) or platform-based service is a category of cloud computing services that allows customers to provision, instantiate, run, and manage a modular bundle comprising a computing platform and one or more applications, without the complexity of building and maintaining the infrastructure typically associated with developing and launching the application(s); and to allow developers to create, develop, and package such software bundles.

#### Q. How DevOps tools work together?
Build — Continuous integration tools, build status. Test — Test and results determine performance. Package — Artifact repository, application pre-deployment staging. Release — Change management, release approvals, release automation.

#### Q. What does Containerization mean?
Containerization is defined as a form of operating system virtualization, through which applications are run in isolated user spaces called containers, all using the same shared operating system (OS).

#### Q. What is the function of CI (Continuous Integration) server?

Continuous Integration (CI) is a development practice where developers integrate code into a shared repository frequently, preferably several times a day. Each integration can then be verified by an automated build and automated tests.

#### Q. What are the differences between continuous integration, continuous delivery, and continuous deployment?

Continuous Delivery requires building, testing, and releasing faster and more frequently. Continuous Integration happens before you build as you are testing code. ... With Continuous Deployment, any updated working version of the app is automatically pushed to production.

#### Q. What do you know about serverless model?

Serverless is a cloud-native development model that allows developers to build and run applications without having to manage servers. ... A cloud provider handles the routine work of provisioning, maintaining, and scaling the server infrastructure. Developers can simply package their code in containers for deployment.

#### Q. What is the difference between Monolithic, SOA and Microservices Architecture?

SOA is a modular means of breaking up monolithic applications into smaller components, while microservices provides a smaller, more fine-grained approach to accomplishing the same objective.

#### Q. What is virtualisation?

Virtualization is software that makes computing environments independent of physical infrastructure, while cloud computing is a service that delivers shared computing resources (software and/or data) on demand via the Internet.

#### Q. What is the difference between a blue/green deployment and a rolling deployment?

Once you swap the environment from blue to green, the traffic is directed to your new green environment. You can delete or save your old blue environment for backup until the green environment is stable. In Rolling Deployment, you have only ONE complete environment.

#### Q. What are some tools used for DevOps? Describe your experience working with any of these tools?

Docker
In the top order of DevOps tools,Docker is the most popular and most commonly used DevOps tool by the DevOps Engineers. Docker is a Linux-based open-source platform that focuses on containers, meaning you package up the software with its dependencies and ship everything together as a unit—no need to worry about managing dependencies separately. It’s portable and highly secure, you can use any language with it, and it integrates well with a number of other tools, such as Jenkins, Ansible, and Bamboo. Research firm Forrester cited Docker as a leader in the enterprise container platform category for Q4 2018.
Ansible
The second most popular DevOps tool is Ansible. CIO says “Ansible has become the DevOps darling for software automation.” This open-source DevOps tool is used for automating software provisioning, configuration management, and application deployment is easy to use—you don’t even need to have a dedicated systems administrator—yet can handle highly complex deployments. Plus, it’s agentless and uses a simple syntax written in the YAML language. NASA uses Ansible.
Git
The third popular DevOps tool is Git. Git is a highly popular open-source DevOps tool used by industry giants such as Microsoft, Amazon, and Facebook. It allows you to track the progress of your development work and coordinate work among team members. Git is great for experimenting, because you can revert to previously saved versions of your work, and you can also create branches separately and then add in the new features when they’re ready. You’ll need to host a repository for the work as well, such as GitHub.
Puppet
The fourth popular DevOps tool is Puppet. Puppet lets you manage and automate software inspection, delivery, and operation. This open-source DevOps tool has a solid track record and thousands of modules and is easily integrated with many other platforms. While the free version is great for smaller projects, consider Puppet Enterprise if your projects tend to be larger. Puppet Enterprise lets you manage multiple teams and thousands of resources.
Chef
The fifth most used DevOps tool is Chef. Chef is the powerful open-source configuration management tool that lets you turn infrastructure into a code to manage data, attributes, roles, environments, and more. As a Puppet competitor, it supports multiple platforms and easily integrates with cloud-based platforms. Regardless of the size of your infrastructure, Chef can automate your infrastructure configuration and application deployment, as well as manage configurations across your network.

Jenkins
The sixth best DevOps tool is Jenkins. Jenkins is known for quickly finding issues in code. It’s a free, open-source DevOps tool used for automating the delivery pipeline, and lets you test and report changes almost in real-time. Jenkins has a huge plugin ecosystem (more than a thousand plugins), so it integrates with pretty much every other DevOps tool out there. Plus, it runs out of the box on Windows, Mac OS X, and Linux.
Nagios
The seventh top DevOps tool is Nagios. Nagios is Used to find and correct problems in networks and infrastructure, Nagios is one of the most popular free and open-source monitoring tools. There are two Nagios editions: Nagios Core and Nagios XI; the latter offers many more features for even greater functionality. You can use Nagios to monitor applications, services, network protocols, and more, and it lets you keep records of things like outages and failures. Forum support is available for both editions.
Splunk
The eighth most used DevOps tool is Splunk. Splunk makes machine data and logs accessible to and usable by everyone on the team. While machine data contains a lot of info that can improve productivity and efficiency, it’s hard to analyze and visualize without a tool like Splunk. Developers can build custom Splunk applications and integrate Splunk data into other applications. The company itself has won several awards and is on the Forbes Digital 100 list.
Bamboo
Bamboo stands at ninth position in the popularity of DevOps Tools. Bamboo is similar to Jenkins but isn’t free. For the cost, you’ll get prebuilt functionalities—which means there are far fewer plugins (because you won’t need them).  Bamboo also has a highly intuitive user interface with features such as auto-completion. All in all, it can save you a lot of time when compared to open-source tools, depending on what you’re trying to accomplish.

#### Q. What Is Canary Deployments?

Canary Deployment
A canary deployment, or canary release, is a deployment pattern that allows you to roll out new code/features to a subset of users as an initial test.

Implement Canary Releases
The initial steps for implementing canary deployment are: create two clones of the production environment, have a load balancer that initially sends all traffic to one version, and creates new functionality in the other version. When you deploy the new software version, you shift some percentage – say, 10% – of your user base to the new version while maintaining 90% of users on the old version. If that 10% reports no errors, you can roll it out to gradually more users, until the new version is being used by everyone. If the 10% has problems, though, you can roll it right back, and 90% of your users will have never even seen the problem.

Note that infrastructure changes and configuration changes should always be tested with canaries because of their sensitivity.

Why Canary Deployment?
Canary deployment benefits include zero downtime, easy rollout and quick rollback – plus the added safety from the gradual rollout process. It also has some drawbacks – the expense of maintaining multiple server instances, the difficult clone-or-don’t-clone database decision.

Typically, software development teams implement blue/green deployment when they’re sure the new version will work properly and want a simple, fast strategy to deploy it. Conversely, canary deployment is most useful when the development team isn’t as sure about the new version and they don’t mind a slower rollout if it means they’ll be able to catch the bugs.

Where Did the Canary Deployment Concept Come From?
You might be wondering why a little yellow bird is used to indicate a test release of a new feature. To answer that, we’ll have to go back to the coal mining days of the 1920s. Miners brought caged canaries into the coal mines because if there was a high level of toxic gases (typically carbon monoxide), the canary would die, alerting the miners to evacuate the tunnel immediately.

In a similar vein, when you release a feature to a small subset of users, those users can act as the canary, providing an early warning if something goes wrong so that you can rollback to the previous, stable version of the application.

#### Q. What are the anti-patterns of DevOps?

So you wanna do DevOps? Okay, but before you start, let’s have a look at some of the things you shouldn’t do.

In the good old days, we just called them “bad ideas”, but along came diplomacy and political correctness, out went the “brain storm” and in came the “idea shower” and with it came the “anti-pattern”.

If the “pattern” is the right way, then inherently the “anti-pattern” is the wrong – and so to stop you going wrong, we’ve compiled this list (with a little help from the DevOps community).

1. DevOps is a process
Not exactly. It’s a philosophy. It’s a way of thinking. DevOps is supported by process and tools.

DevOps according to Gene Kim, is underpinned by 3 core principles known as the “Three Ways”.

The First Way emphasizes the performance of the entire system – the value stream.

The Second Way is about shorting and amplifying feedback loops.

The Third Way is about creating a culture that fosters continual learning and understanding.

http://itrevolution.com/pdf/Top11ThingsToKnowAboutDevOps.pdf

2. Agile equals DevOps?
If you’re asking this question, then you’re probably running some agile process. That’s good. You’ve got a software development process that compliments DevOps, but Agile doesn’t mean you’ve adopted DevOps.

DevOps is an agile enabler allowing operations to collaborate supporting a more continuous flow of work into IT Operations and out into production where customers can realize its value.

3. Rebrand your ops/dev/any team as the DevOps
CIO: “I want to embrace DevOps over the coming year.”

MGR: “Already ready done, we changed the department signage this morning. We are so awesome we now have two DevOps teams.”

Yeah great. And I bet you now have lots of “DevOps” engineers walking round too. If you’re lucky they may sit next to each other at lunch.

4. Start a separate DevOps group
Go on. I dare you. Done it? Well done. You’ve implemented DevOps. Actually what you just did is create yet another silo. Now you’ve got yourself another team you’ve got to try and integrate. Another team with walls to breakdown. Maybe you could go back and rebrand (see AP: x) and create 3 DevOps teams then you’d be super awesome.

DevOps is not about cherry picking some developers and some IT Operations people and silo’ing them off. You’ve got to embrace and embed.

Collapse the development team into the ops team or vice-versa. You need to fully break down the barriers / walls / guards between the teams and mould them into a single unit with shared goals and responsibilities.

http://www.slideshare.net/realgenekim/2012-velocity-london-devops-patterns-distilled

5. The hostile takeover
DevOps. So that’s a word that starts with “Dev”. That means development lead, because development comes first…… Problem?

DevMgr – “Er, we’re now doing DevOps. My guys need to learn the production systems.”

OpsMgr – “Er….ok. So who’s going to be developing the code?”

The word DevOps is clever. It’s a portmanteau. This means the combination of two words, to form a new word, which gives a new meaning. It even delivers some efficiency. It doesn’t mean we took the word operations and replaced it with the word development. So why would you try and adopt DevOps in that manner?

DevOps requires both groups to recognise their key skills. Share what needs to be shared to collaborate. Learn what needs to be learnt to improve. It does not mean retraining. It does not mean cross-skilling (however, this may be a welcome side-effect). It does mean providing feedback and visibility to improve.

http://www.slideshare.net/realgenekim/2012-velocity-london-devops-patterns-distilled

6. DevOps is a buzzword
If you think DevOps is a buzzword, then you’ve probably been using “The Cloud” as a misnomer too. DevOps is a word, you got that right. Actually, it’s a portmanteau of Development and IT Operations (I’ll collect my gold star from teacher later).

DevOps is more than just a cool buzz word. It’s a state of mind. You must embrace its values, you must help others embrace its values and you must continually improve yourself and help others to improve for it to be successful. Once you throw away the BS and start collaborating you might get people to think your catchy new word “DevOps” might actually be cool.

http://www.slideshare.net/realgenekim/2012-velocity-london-devops-patterns-distilled

7. Sell DevOps as a silver bullet
DevOps is voodoo. You basically get your Development team and your IT Operations team together. They smoke some peyote and then sacrifice a chicken. Once you’ve done that your organisation will be revolutionised.

You’ll be able to ship software faster than ever before. Configuration will be self-managing. Your deployment tools will become self-aware. Your development and IT Operations teams will have a new found harmony.

Get this….. DevOps is hard work! For most, it requires Culture Change! That’s one of the hardest things you’ll ever attempt. For seasoned development and IT Operations teams you’re about to try and turn their world up-side-down. Don’t try and do it overnight or you will fail.

8. DevOps means Developers Managing Production
No. Hell No and No again. I’m so incensed you’ll just have to read this….

9. DevOps is Development-driven release management
Let me get 2 things clear;

DevOps is not development driven.
DevOps is not IT Operations driven.
If you want a developer-driven environment, fine, go create one. Just don’t call it DevOps. It’s not.

Take a look at this article for example.

http://www.computerweekly.com/cgi-bin/mt-search.cgi?IncludeBlogs=113&tag=release%20management&limit=20

“Within DevOps, programmers are programmers.” – Right on!

“Equally, within DevOps, operations staff are operations staff.” – We’re cooking now!

“Traditionally, getting software out to production can be either the responsibility of operations or of the development team.”

Hang on……

“IT operations teams will have established and trusted deployment strategies in place that minimise downtime and ensure stability at the expense of agility and speed of response.”

Yep, we’re back on track…… and then bam!

“Development-driven release management” – What? It gets worse
“Development-driven release management goes the other way and looks at how deployment can be carried out as often and easily as possible.

However, these deployments aren’t necessarily into production……………

From a process standpoint, continuous delivery has two big requirements: first, the process itself has to be solid beyond development. This means that it has to be as solid as any process that a traditional IT operations team might put into place.”

No. Non. Nej. Na. Nee. Nein.

Development-driven anything may be a process. It’s just not DevOps.

Replacing your IT Operations team with an automated deployment process is nonsense. Please don’t try this at home folks!

10. We can’t do DevOps – We’re Unique
Yes you are, you little beauty you! But you’re not special enough that you can’t adopt DevOps. I bet you’re the best developer out there; you code quicker than lighting, and deliver the sort of code that makes grown men cry with joy. No? Okay, so you’re the most awesome Ops Guy on planet. If Chuck Norris were an IT Operations Engineer he’d be want to be you.

However, you and your organisation don’t have some unique factor that won’t allow you to adopt DevOps. So give it a go!

Jesse Robbins from OpsCode has some good advice for getting started;

Start Small – Build Trust
Create Champions
Build Confidence
Celebrate Success
Exploit Circumstance
http://www.slideshare.net/jesserobbins/cloud-expo-jesserobbinsopscode20130129b

https://www.ibm.com/developerworks/mydeveloperworks/blogs/ambler/entry/adoption_antipattern_we_re_special?lang=en

11. We can’t do DevOps – We’ve got the wrong people
Well why did you hire them? That’s right – they’re awesome! If you don’t think that, then you need to take a long hard look at yourself, then go and discover the real hidden talents in your team.

Someone told me recently that they couldn’t do DevOps because “they have the wrong developers or the wrong ops people…”. So they have developers who can’t code? I thought to myself, “my organisation has the wrong developers, people who can’t code, they run HR and Marketing!”

DevOps fosters a collaborative working relationship between Development and IT Operations. This collaboration can extend right through the organisation further enhancing working relationships between teams.

You don’t have the wrong people. You have the wrong thought process. Deal with it.

12. Collaboration when things go pear-shaped
Ok genius. You messed up. So what? We all do it. But now you want your IT Operations guys out of bed at 2am to clean-up something they know nothing about. They are IT Operations engineers – not the “fixer” like Michael Clayton. Waiting until an error occurs during a deployment for Development and IT Operations to collaborate sucks.

It’s too late for this problem….. but maybe not for the next. You have your Development team and your IT Operations team talking (or swearing at 2am) with each other, but at least they are talking. Keep the dialogue going. Get a retrospective review of what happened and how you can fix it going forward. If you have encountered this situation, then try and keep the dialogue going with between your teams. Open the communication channels with Development and IT Operations early. There’s hope for you yet!
#### Q. Which among Puppet, Chef, SaltStack and Ansible is the best Configuration Management (CM) tool? Why?
Chef vs Puppet vs Ansible vs Saltstack
Availability
Let me compare chef vs puppet vs ansible vs saltstack on the basis of availability. All the tools are highly available which means that there are multiple servers or multiple instance present. Say, if your main master or server goes down, there is always a backup server or the different master to take its place. Let us take a look at each tool one by one:

Chef – When there is a failure on the primary server i.e. chef server, it has a backup server to take the place of the primary server.

Puppet –  It has multi-master architecture, if the active master goes down, the other master takes the active master place.

Ansible – It runs with a single active node, called the Primary instance. If primary goes down, there is a Secondary instance to take its place.

Saltstack – It can have multiple masters configured. If one master is down, agents connect with the other master in the list. Therefore it has multiple masters to configure salt minions.

Ease of Setup
When I talk about ease of setup, let me add my personal experience because when I was installing chef, puppet and saltstack, I faced some issues but when I was installing Ansible, it was just like a cake walk. So let us focus on each tool one by one:

Chef – Chef has a master-agent architecture. Chef server runs on the master machine and Chef client runs as an agent on each client machine.  Also, there is an extra component called workstation, which contains all the configurations which are tested and then pushed to central chef server. Therefore, it is not that easy.

Puppet – Puppet also has a master-agent architecture. Puppet server runs on the master machine and Puppet clients runs as an agent on each client machine. After that, there is also a certificate signing between the agent and the master. Therefore, it is also not that easy.

Ansible – It has only master running on the server machine, but no agents running on the client machine. It uses ssh connection to login to client systems or the nodes you want to configure. Client machine VM requires no special setup, hence it is faster to setup!

#### Q. What is Puppet?

Saltstack – Here Server is called as salt master and clients are called as salt minions which run as agents in the client machine.

Apart from this “Chef vs puppet vs Ansible vs Saltstack” blog, if you want to get trained from professionals on these technologies, you can opt for a structured training from edureka! Click below to know more.

Management
Before I explain the difference between these tools on the basis of management, let me tell you puppet and chef follows pull configurations & Ansible and Saltstack follows push configuration. You must be wondering what are these configurations? In push configuration, all the configurations present in the central server will be pushed to the nodes whereas, in the pull configuration, the slave nodes will automatically pull all the configurations from the central server without any commands. 

Chef – You need to be a programmer to manage the configurations as it offers configurations in Ruby DSL. Client pulls the configurations from the Server.

Puppet – Not very easy to manage the configurations as it uses its own language called Puppet DSL(Domain Specific Language). Client pulls the configurations from the Server. It is quite system-administrator oriented and there is non-immediate remote execution.

Ansible – Easy to learn to manage the configurations as it uses YAML i.e. Yet Another Markup Language which closely resembles English. Server pushes configurations to all the nodes. Good for real-time application and there is immediate remote execution.

Saltstack – Easy to learn to manage the configurations as it uses YAML as well. Server pushes configurations to all the clients. Immediate remote execution

Scalability
All the four tools are highly scalable. Suppose if you need to configure around 50 nodes today, and tomorrow say 500. Not a problem with these tools. It can handle large infrastructure, you just need to specify the IP address and the hostname of the nodes that you want to configure and rest of the task will be handled by these tools. Therefore, all these tools are highly scalable.

Configuration Language
Chef – Chef uses Ruby Domain Specific Language (Ruby DSL). It has a steep Learning Curve and its developer oriented.

Puppet – Puppet uses its own puppet Domain Specific Language (Puppet DSL). It is not very easy to learn and its system administrator oriented.

Ansible – Ansible uses YAML i.e Yet Another Markup Language (Python). It is quite easy to learn and its administrator oriented. Python is inbuilt into most Unix and Linux deployments nowadays, so setting the tool up and running is quicker.

Saltstack – Salstack also uses YAML (Python). It is again easy to learn and administrator oriented. 

Next, let us move forward and compare chef vs puppet vs ansible vs saltstack on the basis of interoperability.

#### Q. Before a client can authenticate with the Puppet Master, its certs need to be signed and accepted. How will you automate this task?

Before Puppet agent nodes can retrieve their configuration catalogs, they require a signed certificate from the local Puppet certificate authority (CA). When using Puppet’s built-in CA instead of an external CA, agents submit a certificate signing request (CSR) to the CA to retrieve a signed certificate after it's available.

By default, these CSRs must be manually signed by an admin user, using either the puppetserver ca command or the Node requests page in the Puppet Enterprise console.

Alternatively, to speed up the process of bringing new agent nodes into the deployment, you can configure the CA to automatically sign certain CSRs.

#### Q. What are containers?
Containers are a form of operating system virtualization. A single container might be used to run anything from a small microservice or software process to a larger application. Inside a container are all the necessary executables, binary code, libraries, and configuration files.

#### Q. What are the advantages that Containerization provides over virtualization?
In a nutshell, virtualization eliminates the need for an entire server for one application. Containerization eliminates the need for an entire OS for each application. Portability, agility, fault isolation, ease of management, and security are among the advantages of utilizing containerization technology.

#### Q. What is Nagios?
Nagios monitors the network for problems caused by overloaded data links or network connections, as well as monitoring routers, switches and more

#### Q. How does Nagios works?
Nagios runs on a server, usually as a daemon or a service. It periodically runs plugins residing on the same server, they contact hosts or servers on your network or on the internet. ... Nagios uses the results from the plugins to determine the current status of the hosts and services on your network.

#### Q. What are Plugins in Nagios?
What Is A Plugin? Plugins are standalone extensions to Nagios Core that make it possible to monitor anything and everything with Core. Plugins process command-line arguments, perform a specific check, and then return the results to Nagios Core.

#### Q. What is NRPE (Nagios Remote Plugin Executor) in Nagios?
NRPE allows you to remotely execute Nagios plugins on other Linux/Unix machines. This allows you to monitor remote machine metrics (disk usage, CPU load, etc.). NRPE can also communicate with some of the Windows agent addons, so you can execute scripts and check metrics on remote Windows machines as well.

#### Q. What do you mean by passive check in Nagios?
Nagios also supports a way to monitor hosts and services passively instead of actively. The key features of passive checks are as follows: Passive checks are initiated and performed by external applications/processes. Passive check results are submitted to Nagios for processing.

#### Q. When Does Nagios Check for external commands?
When Does Nagios Check For External Commands? Immediately after event handlers are executed. This is in addtion to the regular cycle of external command checks and is done to provide immediate action if an event handler submits commands to Nagios.

#### Q. What are the core operations of DevOps?
The core operations of DevOps are application development, code developing, code coverage, unit testing, packaging, deployment with infrastructure, provisioning, configuration, orchestration, and deployment.

#### Q. What is Nginx and how it works?
How Does Nginx Work? Nginx is built to offer low memory usage and high concurrency. Rather than creating new processes for each web request, Nginx uses an asynchronous, event-driven approach where requests are handled in a single thread. With Nginx, one master process can control multiple worker processes.

#### Q. What is Ngrok?
ngrok is a cross-platform application that enables developers to expose a local development server to the Internet with minimal effort. The software makes your locally-hosted web server appear to be hosted on a subdomain of ngrok.com, meaning that no public IP or domain name on the local machine is needed.

#### Q. How is container different from a virtual machine?
Virtual machines and containers differ in several ways, but the primary difference is that containers provide a way to virtualize an OS so that multiple workloads can run on a single OS instance. With VMs, the hardware is being virtualized to run multiple OS instances.

#### Q. Why and When to use CICD Pipeline?
A CI/CD pipeline automates your software delivery process. The pipeline builds code, runs tests (CI), and safely deploys a new version of the application (CD). Automated pipelines remove manual errors, provide standardized feedback loops to developers, and enable fast product iterations.

#### Q. How to use jfrog artifactory with jenkins?

To install the Jenkins Artifactory Plugin, go to Manage Jenkins > Manage Plugins, click on the Available tab and search for Artifactory. Select the Artifactory plugin and click Download Now and Install After Restart.

<br/>

# Jenkins

#### Q. Explain how you can move or copy Jenkins from one server to another?

Move a job from one installation of Jenkins to another by simply copying the corresponding job directory.
Make a copy of an existing job by making a clone of a job directory by a different name.
Rename an existing job by renaming a directory.

#### Q. Explain how can create a backup and copy files in Jenkins?

#### Q. Explain how you can setup Jenkins job?
#### Q. Mention some of the useful plugins in Jenkins

<br/>

# Docker

#### Q. Why use Docker?
#### Q. What is a Docker?
#### Q. Installing Docker on Linux (CentOS)
#### Q. Basic Docker Commands
#### Q. Deploying Containers
#### Q. Working with Containers
#### Q. Load and work with HCL product images
#### Q. Customize a container
#### Q. Push personal container to Docker Hub
#### Q. Create a container by Dockerfile
#### Q. Docker composes
#### Q. Docker networking
#### Q. Data collection for support
#### Q. Explain a use case for Docker
#### Q. What is Docker image?
#### Q. What is Dockerfile used for?
#### Q. What is the difference between a Docker image and a container?
#### Q. Do I lose my data when the Docker container exits?
#### Q. What platforms does Docker run on?
#### Q. How to stop and restart the Docker container?
#### Q. What is Docker container? How to create Docker container?
#### Q. Can I use json instead of yaml for my compose file in Docker?
#### Q. What is Docker Swarm?
#### Q. How is Docker different from other container technologies?
#### Q. What is Docker hub?
#### Q. How exactly are containers (Docker in our case) different from hypervisor virtualization (vSphere)? What are the benefits?

<br/>

# Kubernetes

#### Q. Kubernetes architecture
#### Q. Kubernetes installation
#### Q. Pod
#### Q. ReplicaSet
#### Q. Deployment
#### Q. Services
#### Q. Rolling update
#### Q. Environment
#### Q. Persistent volumes
#### Q. Namespace
#### Q. Troubleshooting
#### Q. What is containers Orchestration in Kubernetes?

<br/>

# Helm

#### Q. What is Helm?
#### Q. Helm installation
#### Q. Create Helm project
#### Q. Deploy Helm chart
#### Q. Troubleshooting
