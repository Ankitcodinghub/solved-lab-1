# solved-lab-1
**TO GET THIS SOLUTION VISIT:** [SOLVED:Lab 1](https://www.ankitcodinghub.com/product/solvedlab-1-2/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;2357&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;SOLVED:Lab 1&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
Introduction The goals of this lab are: To give you practise designing a class. Object-oriented analysis was discussed in last week’s lectures;, and there is an exercise on designing and building a Point class. To give you practise implementing a class. This will make you review lots of the material from CSC108: creating simple classes, writing methods, and basic data structures in Python. To give everyone practise function design recipe, especially students who have not used it in a previous course. The function design recipe was used in class last week. It is a strategy for writing functions that makes them easier to write correctly and leaves behind an excellent docstring. Use standard Python style. You should consult CSC108 style guidelines and pep 8. In CSC148, we follow pep 8, and not CSC108, style in preferring to use parentheses for long lines. We also don’t leave a blank line between the docstring and the function body (the syntax highligher eectively distinguishes these elements). In addition, this lab will make sure that: students who have not used the PyCharm IDE get familiar with it, or the IDE they plan to use in this course, and everyone can successfully submit les on MarkUs, the system where you’ll later submit assignments. Don’t hesitate to make use of other resources, such as our course notes or How to Think Like a Computer Scientist to read up on any topic that you’ve forgotten about. If you are doing these exercises in a lab period, show your work to your TA frequently, so that they can make sure you are on the right track. Feel free to ask your TA questions | that’s why they’re here! We also encourage you to ask other students if you get stuck, and please be generous in helping others. Getting started with Pycharm 1. Log in to your cdf account. 2. Follow the instructions to congure Pycharm, and create a csc148 directory structure for your work. Do not try to install PyCharm on CDF | it’s already there, under the menu for First Year CDF. Although we recommend PyCharm, you are allowed to use any IDE you want in this course. In what remains, we will refer to your IDE, rather than PyCharm. 3. In your IDE, navigate to csc148/Labs/lab01 4. Start the browser and navigate to the lab01 page on the CSC148H1 web site: http://www.cdf.toronto.edu/~heap/148/W16/Labs/lab01 For each lab, you will nd handouts and other resources linked from this page. 5. Download the le specs.txt from http://www.cdf.toronto.edu/~heap/148/W16/Labs/lab01/ 1 and save it in the lab01 subdirectory you created above. 6. Open the le specs.txt in your IDE. This is the specication for the code you have to write in the rest of this lab. Before moving on to the next section, show your work to your TA. Designing a class 1. Create a new le called lab01.py. 2. Perform an object-oriented analysis of the specications in specs.txt, following the same recipe we used in class for Point: (a) choose a class name and write a brief description in the class docstring. (b) write some examples of client code that uses your class (c) decide what services your class should provide as public methods, for each method declare an API1 (examples, header, type contract, description) (d) decide which attributes you class should provide without calling a method, list them in the class docstring This analysis will require a fair amount of thought. Don’t worry about getting it completely right: you need to leave enough time to get to the next steps where you will implement your design. If you’re stuck, you may look at an example of Point class API, or the (much longer) class recipe used for building the Course class 3. Using your CDF username and password, log on to MarkUs at the following URL: https://markus.cdf.toronto.edu/csc148-2016-01/ Find the Lab 1 submission page, and submit your le lab01.py. Get help from other students or your TA if you’re not sure how to do this or if you run into any problems! You won’t be graded on what you submit for this lab, only for the fact that you submitted. Before moving on to the next section, show your work to your TA. 1use the CSC108 function design recipe 2 Implementing a class 1. write the body of special methods __init__, __eq__, and __str__ 2. write the body of other methods 3. Save your le, then submit it on on MarkUs. If you are working with a partner, be sure that each of you submits at least one le during this lab. 4. Save your modied le lab01.py, then re-submit it on MarkUs. (Get in the habit of submitting your work multiple times to MarkUs | every time that you complete some feature in your code. New submissions simply replace old ones, and in addition, MarkUs keeps track of previous versions so that it is possible to go back to previous versions if needed.) Before moving on to the next section, show your work to your TA. If you’re stuck, you might look at the code for completed Point class. Before moving on to the next section, show your work to your TA. Using your class 1. Create a new le named lab01tester.py where you will carry out the following tasks: from lab01 import NameOfYourClass (but replace NameOfYourClass with the actual name of the class you wrote). You may need to review how to import names of Python objects such as classes. Create a race registry. Register the following runners: Gerhard (with time under 40 minutes), Tom (with time under 30 minutes), Toni (with time under 20 minutes), Margot (with time under 30 minutes), and Gerhard (with time under 30 minutes | he’s gotten faster). Report the runners in the speed category of under 30 minutes. 2. Submit your le lab01tester.py on MarkUs. 3. Run your le to make sure everything works…But don’t panic if it doesn’t! 4. If you have to, use the rest of your time to debug your code, with the help of other students, and your TA. Show your work to your TA one last time. Congratulations: you’re done with the rst lab! Additional practice As well as the race registry, here are some additional exercises in designing and implementing classes. We set up each one so that one appropriate solution involves just a single class. We certainly don’t expect you to do this many exercises in the lab, but they are here for additional practice. We’ll have a brief quiz at the end of the lab, which will involve an exercise similar to the race registry or one of the additional exercises. How did you do? Make sure you are o to a solid start in csc148 by identifying any concepts that caused you diculty and mastering them before the course moves on. Use the resources linked to in this handout, as well as course oce hours and the Computer Science Help Centre to get any help you need.
