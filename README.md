<h1 align="center"> MVC </h1>
<h2 align="center"> What Basically  You Need To Know About MVC Architecture </h2>
<h2> What is MVC? </h2>

<p> MVC stands for; <br>
-Model <br>
-View <br>
-Controller. <br> <br>
MVC is one of the most used frameworks and  is known as an architectural pattern. As I mentioned above, it divides an application into three main logical components:
Model, 
View and 
Controller. 
Each of these components  has specific responsibilities in order to handle specific development aspects of an application.
Let’s look closer at these components in detail. </p>
<div align="center">

![Screenshot 2022-08-31 094713](https://user-images.githubusercontent.com/101064345/187722090-8a1cd866-e297-41e9-9435-444b38ba174d.png)

</div>


## Model 
Model is the lowest level of the pattern which is responsible for maintaining data. So, the Model component basically corresponds to all the data-related logic that  users work with. <br>
The Model component corresponds to all the data-related logic that the user works with. It represents data that is being transferred between controllers or any other related business logic.  The model component responds to the controller requests because the controller never ever talks to the database by itself. It needs the model. The model talks to the database and then it gives the data the controller wants. <br><br> 
<b> Alert!: </b> the model component never talks with the view directly.
 
## View
The view component presents the presentation of data. So, for web applications when we think of the view component we can just think of the Html/CSS part.<br>
Views are created by the data collected from the model component. However, the data is not taken directly from the model, so the view only speaks to the controller.
 
## Controller
Controller is the main component because it acts as an interface between Model and View to process all the business logic. It handles  incoming requests, manipulates data using Model components and interacts with the Views to render the output. 



