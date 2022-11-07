## Problem of scaling horizontally on AWS

Scaling horizontally - more machines  
Scaling vertically - more resource for a machine  
  
Scaling horizontally is like ... Putting a knot at the end of a water hose and putting holes in the water hose.  
  
More holes - more water pours out.  
  
But... If the pressure reaches a critical point, the whole water hose just blows up.  
  
As an real example:  
  
In networking, scaling horizontally usually requires that the loadbalancer can distribute the work.  
  
Too many nodes and the loadbalancer will be overwhelmed by incoming connections - worst case going down under traffic, meaning none of the workers get any request.  
  
Other example: More nodes, but nodes take too long for requests.  
  
Yes you could add more nodes - but as the requests take too long, you're having a larger and larger mass of unfinished requests stuck in processing. Either the loadbalancer gives up at some point or you can't add more nodes / add nodes fast enough.  
  
Spreading work across several nodes as a band aid is never a good solution.  
  
The whole organism of loadbalancer and services needs to be balanced out or you'll end up with a doomsday machine

## 2.
I lost my key pair not sure where i saved but i want connect throw putty itself not in console [#Connect](https://www.youtube.com/hashtag/connect) ec2 You can take backup of image or snapshot to recover the instance back but [#here](https://www.youtube.com/hashtag/here) [#i](https://www.youtube.com/hashtag/i) [#want](https://www.youtube.com/hashtag/want) [#same](https://www.youtube.com/hashtag/same) [#public](https://www.youtube.com/hashtag/public) [#ip](https://www.youtube.com/hashtag/ip) address how to recover my ip ? Plz team any one can provide link how to recover is that possiable ?

## 3. Daily tasks
- A new, empty AWS Account  
* The ability to run 120 high memory EC2 instances, including up to 80 instances of dl1.24xlarge, but don't worry, 40 of them will be spot instances. I'll probably just start with two m5.xlarge for simplicity.  
* VPC Peering into our primary AWS network  
* VPC Peering into a 3rd party's network (because we're paying them for this service)  
* A couple cross-acount IAM roles  
* Granting "AWS: AdministratorAccess" to said IAM roles