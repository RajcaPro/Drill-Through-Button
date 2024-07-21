# Drill Through Button

Hey everyone! 🌍🤝
I hope you are doing great :)

Today I come to you with an idea. 

Suppose our business problem contains a note like this :
create a report that contains a start page and one report page : Executive Summary. The home page is to present a shortcut linking only to this one page of the report. 
People using this report will primarily use this page. But the bosses themselves want us to create an additional report page especially for them, which will not be displayed to other users ( we will talk about permissions in one of the next posts :) ). 

The question is do we have to create a new report ? 
We could, but in our case we did not get permission to do so.

So the question is what to do ? 

With the help of Drill Through comes to us !
with this, we can use the button created to send the user to another report page, which we have previously hidden !

Step 1.

For the sake of problem solving, let's create a 2-page report with visuals.
The first will contain a single :clustered column chart which contains on the x axis the region and on the y axis profit and profit py ( previous year).
For this, we create a button to send us back to the second page of the report.

On the second page of the report I will create sample visualisations. It does not matter what they are, as it depends on the individual business context!

Result :

![image](https://github.com/user-attachments/assets/b0faf409-c845-4b67-8c9b-f6933b52df49)


![image](https://github.com/user-attachments/assets/5ce72b65-6806-4252-b356-1fa835528b83)

Let's assume that our button is to be triggered when we click on any of the regions.
We have a number of sales directors, and each of them will want, when redirected to the second page of the report, all the visuals on that page to apply only to their region.

So let's change the settings of our button !

![image](https://github.com/user-attachments/assets/7cd2ef2e-e784-4262-8209-713e83d2e182)

Our next task is to create a destination for the drill through, i.e. our second report page. 

![image](https://github.com/user-attachments/assets/b669a2b5-a8bb-409b-a097-20c6e68c9db4)

To do so, let us turn to our second page of the report.

In the page format settings, go to -> page information and change the page type to Drill Through, name the page XYZ.

![image](https://github.com/user-attachments/assets/cf480222-f57e-41b8-9916-ecb655113c09)

Next, in the Drill through from section, let's select our region chart.

![image](https://github.com/user-attachments/assets/9c072475-1415-4835-8209-4b3a8b09aa14)

Once the page is prepared in this way, we can return to our !

In the Action -> destination section, our XYZ page appears, which we must select !

![image](https://github.com/user-attachments/assets/9fa2baac-9957-4e72-8aaa-a56a21c1daff)

Result :

![image](https://github.com/user-attachments/assets/84b19a8a-9300-49d0-8384-c6ffd2ea5ce7)

We can see that our button is greyed out, indicating that one of our regions must be selected in order to use it ! 

![image](https://github.com/user-attachments/assets/2fe699f9-f03a-4e5c-8faf-7561cff48ba5)

Finally, we can create an arrow on the second page of the report to return to the Executive Summary.
To ensure that our button actually displays data for each region, we will create a region slicer.

![image](https://github.com/user-attachments/assets/c24cd68d-4cb5-4c6d-be94-3e10d16f0c05)




Everything works! ✨ 
This is the end of this guide ! 

I hope you will use it in your work 🚀

Regards,
Mateusz Rajca







