---
tags: ["Brian Sandoval", "BEATS", "Week 5"]
---
## Week 5 blog

#### The rundown this week.
This week I was assigned along with Erik and Alex to work on the datadog part of the project. Currently setting up a screen board manually is set up and reading the metrics or our ec2 instance. Doing this through datadog tool took a bit of figuring out but it became a bit more simpler to apply the metrics we wanted calculated by using the modules datadog had setup. So far we are having trouble with finding the metrics for finding the latency speed of our website and the number of requests. We had to take a pause with doing this part because our other group members are unable to do their aws part if we do not set up the packer. So far we are able to set it up we just need to setup further configurations for this task which we will end up doing over the weekend. One of the problems that we encounter is that on our amazon console when we check our ec2 instances the packer created instance is in the initializing mode most likely due to the configuration.

#### Future Plans
Apart from working on the configurations I will be working on setting up the metrics for the apache web server and automate everything through ansible so that once we have setup the service the metrics will start sending information to our datadog monitor I as well want to be able to finish setting up the logging of the rest of the services. Most of it should be done by the end of the weekend. I want to be able to come up with most of it finished that way we can test them on our instances, plus making sure everything is syncing within the given specs of time. I believe the transmission of data will require a bit of help from the Erik and Alex.
