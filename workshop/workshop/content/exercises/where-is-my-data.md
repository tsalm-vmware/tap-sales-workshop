**Where is my Data ?**

As Cody, I have now deployed an app, that is running in a container...but containers are ephemeral by nature. 
So, if my container crashes, I will loose all my data 😱!

Moreover, my app is an inclusion app: so if every user adds an emoji and the app crashes, I loose all the emoji. Not really inclusive, isn't it?

It is time to rework a bit my application and add persistence into it by using a postgreSQL dabatase... I need one which is compliant with my company security standards.

Luckly, Peter has come up with a solution for me using VMware Application Catalog !