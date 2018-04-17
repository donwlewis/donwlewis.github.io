# What is DevOps? (To Me)

Today I had an epiphany moment.  I think I have finally come to realize what DevOps means for me, and the organization that I work for.

First, let me start off by giving a little background about my organization, and my "definition" of DevOps.  First of all, without giving too much information, I work in an organization and industry that is highly regulated, and highly sensitive.  This presents a rather unique challenge when it comes to DevOps.  It presents problems that add complexity to the way things are executed, and designed.  This does not make it impossible, just more...challenging.

So what does DevOps mean?  The term to me is both objective and subjective.  The idea of DevOps wraps itself around principals that I find to be objective.  For example, when you think of DevOps, you automatically know that you are going to adopt, engineer, and execute processes that will be done in an automated fashion.  It also brings about a principal of being agile (more in terms of flexibility in this case, not necessarily agile development).

But the idea is also subjective.  In each organization, ad DevOps process is going to look different depending on your organizations processes, requirements, and business needs.  Today, I think I am on the first step of starting to figure that our for myself.

## Late to the Game

So you might be thinking "Wow...late to the game aren't we?".  Yes and no.  Like I explained, in a highly regulated business, it is difficult to adopt these principals quickly, because of bulky business requirements and regulations.  Some of the business needs are warranted and others not so much.  But when you are stuck in an old school culture, you have to get creative on how you are going to provide solutions that will provide the type of agility that DevOps can provide, but also make sure you are helping the business with their needs.  Some of that will require work on educating the business on what those process should look like.  And you can't really do that without understanding the business needs.

## So what Epiphany?

So what was my great epiphany?  Testing...yea I know not very climactic, and pretty obvious.  But I am not just talking about application level testing.  I am talking about full stack testing including regulatory requirements, security requirements, and application requirements.  And pushing those as far down the development stack as possible.  The idea here is that we get the developers to understand the business requirements as early in the development process as possible.  This may come as a shock to developers, as they might not want to get into that level of detail that early on, but it will ultimately be beneficial for both the business and the developers as developers will understand the business needs and requirements better, and the business can enforce best practices and standards early on in the development stage.

So what would this look like?  Let me see if I can present an example of what I am talking about.  In this scenario, let us assume I have built the framework and the tooling required to accommodate this scenario.  I have an application developer who built this pretty sweet app.  He wants to move it into a development environment that is hosted within the organizations realm of management (i.e. private cloud or hybrid offering).  The developer submits his code to a process that will deploy the necessary resources, with the required run time to deploy and run the application.  During this process, the tools runs the necessary checks against that app to determine if it meets the requirements to move into this space.  If it does, awesome, we build the resources and move on.  If not, we provide a list of issues that need to be resolved in order to move on.  Developer fixes, resubmits, and the process starts all over again.

To a lot of people, this is probably not a new thing.  The biggest reason why it was an epiphany for me revolved more around the regulatory requirements that our business has.  More recent tooling (such as inspec) have provided a means by quick we can codify a lot of these requirements, thus giving us a means buy which we can automate out compliance requirements, as well as push those requirements further down the stack.  This lets us make sure the developers are developing code that meets those regulatory requirements.

And that is pretty awesome to me!

## Closing Thoughts

And when I said I want to push this way down the stack, I mean I want to push it way down.  This includes providing guidelines and tooling for developers to use down at the local development level.  This will also require a framework and tooling that will be able to provide the necessary run times required when someone submits their application for approval.

The next part of this journey for me is to start defining how this process is going to work and what it is going to look like.  Tools are definitely part of the conversation, but it is more important to define what we want/need to do, then go get/build the proper tools we need to do them.  It's the start of an exciting journey for me, as for the first time I am getting a clear vision of what DevOps looks like for my organization.

## So Whats Next?

Whats next?  Its time to plan, engineer and build...
