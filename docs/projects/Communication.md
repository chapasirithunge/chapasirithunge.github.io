## High bandwidth communication

Robotic necks are a relatively underexplored part of robots, partly because they’re less complex than other components. But the neck directly connects to the head, making it an important part of how robots communicate nonverbally through movements like nodding (roll, pitch, and yaw). We typically use just one type of motion, for instance, pitch to mean “yes.” But what if robots could go beyond that? What happens if a robot moves all 3 DOFs at the same time? Can you actually decode the message it’s trying to communicate?

Here’s an example:

<iframe
    width="560"
    height="315"
    src="https://www.youtube.com/watch?v=fGmw4HBGnwk&list=PLrP4k_0quIDOD2URrp9N8uLgcPIXNMggp&index=21"
    title="YouTube video player"
    frameborder="0"
    allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
    referrerpolicy="strict-origin-when-cross-origin"
    allowfullscreen>
</iframe>

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=fGmw4HBGnwk&list=PLrP4k_0quIDOD2URrp9N8uLgcPIXNMggp&index=21" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

More hardware complexity doesn’t necessarily mean richer communication. Maybe simpler approaches can work just as well for robot design. In the work below, we use information theory to explore this idea.

???+  "Read related work here"
    [Communicative Efficiency of Single vs. Multi-Axis Robot Neck Motion](https://arxiv.org/abs/2607.07390)
