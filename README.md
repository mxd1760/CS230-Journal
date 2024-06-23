# CS230 Journal

This is a software requirements reccomendation document for an application commisioned by a company called "The Gaming Room."
This client wanted to port their existing gaming application to more platforms than just the Android version they currently have, which also required some changes to the server solution.
The web client is their main target since it's the easiest way to get onto multiple platforms though reccomendations on other clients were discussed in the document in keeping with the general goal and helping with considerations for other ports in the future.

I think that this document does particularly well in discussing the many options in detail as well as expanding on the speciric requirements for a web app.

I hope that when this application eventually gets engineered the discussion will help the software engineers to focus on just writing the required application code instead of having to worry as much about how they are using the resources of whatever system they're targeting.

More examples would be an easy way to improve the effectiveness of this document in describing the things it's trying to do, even if that might make things longer. It might be easier to do this with links to other documents that go into greater detail to improve the amount of information shared while keeping things concise for those just scanning the text.

In this case, I think that the most important user need that was addressed was how to manage the various image data sizes so that it wouldn't hurt the performance of the game, even when sending large image files to the client.
These kinds of user specific considerations help make the hardest parts of actually developing the software easier which hopefully will make the development process go by more smoothly.

Based on this project I think that robust designs are really just designs that are more flexible. Any plan will run into issues right when it starts getting implimented but the best plan tries to see those issues before they come up and help someone navigate around them rather than forcing them to make hard decisions halfway through that could change the course of development entirely.
