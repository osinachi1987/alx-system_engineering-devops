Issue Summary
From 10:12 AM to 12:34 PM, network to Branch 2 was down resulting in every staff not being able to work, to access file servers, to surf the internet and communicate with other branches via IP Phones. Because of this the branch was on a stand still, this issue affected 100% of work production and customer satisfaction.




Timeline (all times Pacific Time)
7:30 AM: Communication device and Network device was powered on
10:12 AM: Network Outage begins
10:17 AM: Email was sent to ISP provider and a follow up call
10:54 AM: ISP communicated back that everything was ok from their end, they could communicate with our router.
11:09 AM: I logged in to my router to cross check the configurations once more.
11:34 PM: Started a reconfiguration of the router and the ISP interface on another port
12:34 PM: Branch came back online 100%
Root Cause

At 5:30 PM the previous day, due to the decommissioning of one of our ISP (syscode) to integrate another ISP (MTN) we had to configure one of the network interfaces for MTN.
At the point of the configuration the network duplex was set to auto, which i think was the root cause of the downtime at that point, because when i tend to reconfigure another interface on the router i used full duplex 100%, that was the only changes that was different from the first configuration i did that later when down.



Resolution and recovery

At 10:12 AM when the downtime occurred, a mail and a follow up call was sent to the new ISP MTN to check the link to resolve issue, at 10:54 AM, the ISP reached out to us to check our configuration that everything was fine from their end and they could reach our router interface, then at 11:09 AM, I logged into our router to cross check my configuration to know the root cause, but everything also seems fine but at 11:34 AM i decided to reconfigure another port since we have one extra port on the router and was able to complete at 12:30 PM when the network was restored. The only changes on the configuration was to set the network duplex to full and not half. 


Corrective and Preventative Measures

In the last two days, we’ve conducted an internal review and analysis of the outage. We have been monitoring the link to see if there were any downtimes and we continue to render our support to ensure the business operations runs smoothly.


The IT Team is committed to continually and quickly improving our technology and operational processes to prevent outages. We appreciate your patience and again apologize for the impact to you, the users, and the organization. We thank you for your trust and continued support.

Sincerely,

IT Business Support Team
