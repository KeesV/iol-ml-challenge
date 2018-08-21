# Step 3; find the victim!

In the previous step, we created the web service. Now you have a way to talk to your model and get predictions back.

The web service will look like something below:

![azuremlwebservice.png](azuremlwebservice.png)

There is both a request/response endpoint as well as a batch endpoint and both contain instructions on how to consume. The preview pages of the Test also contain an online test form and even ready to use C# code to call the API.

## Who will be killed next?

We built this model to predict who will be the next victim and with some hints, we should be able to query the system and find out who will most likely not survive the night.

We have narrowed down our list of possible victims to the following five cardinals. Their properties are listed below and are not part of the already trained model. Use the following data and record the outcome.

|Order|Decorated|YearsInOffice|SiblingSpouse|ParentChild|PersonalWealth|Continent|Name|
|--|--|--|--|--|--|--|--|
|CD|no|34.5|0|0|7.8292|Africa|Sergius Durio|   
|CD|no|18|0|0|7.2292|Eurasia|Epidicus Niger|     
|CD|yes|17|0|0|7.8958|America|Halisca Eulogius|      
|CB|yes|40|1|5|311.3875|Eurasia|Pyrgopolynices Commodus|    
|CP|yes|36|1|1|3690|Eurasia|Pellio Hirrus|

**Note:** you can use the button 'Test (preview)' to feed the parameters to the service for easy testing.

## The tip!

It turned out that the above data is not totally up to date. One of these cardinals was recently demoted to CD and forced to move to Africa. We do not know why, but he messed up seriously. Maybe he will be wacked by his own...

