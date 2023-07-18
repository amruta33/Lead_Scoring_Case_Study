
<div style="color:white;
           display:fill;
           border-radius:5px;
           background-color:#1663BE;
           font-size:110%;
           font-family:Calibri;
           letter-spacing:0.5px">

<p style="padding: 0.015px;
              color:black;">  

#    Problem Statement

<p style="padding: 0.015px;
              color:white;">
</p>
</div>
An education company named <b>X Education</b> sells online courses to industry professionals. On any given day, many professionals who are interested in the courses land on their website and browse for courses. 

The company markets its courses on several websites and search engines like Google. Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos. When these people fill up a form providing their email address or phone number, they are classified to be a lead. Moreover, the company also gets leads through past referrals. Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. Through this process, some of the leads get converted while most do not. The typical lead conversion rate at <b>X Education</b> is around 30%. 

Now, although <b>X Education</b> gets a lot of leads, its lead conversion rate is very poor. For example, if, say, they acquire 100 leads in a day, only about 30 of them are converted. To make this process more efficient, the company wishes to identify the most potential leads, also known as ‘Hot Leads’. If they successfully identify this set of leads, the lead conversion rate should go up as the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone. A typical lead conversion process can be represented using the following funnel:


<img src="https://cdn.upgrad.com/UpGrad/temp/189f213d-fade-4fe4-b506-865f1840a25a/XNote_201901081613670.jpg" class="img-thumbnail" alt="Cinque Terre">

It can be seen that there are a lot of leads generated in the initial stage (top) but only a few of them come out as paying customers from the bottom. In the middle stage, potential leads need to be nurtured well (i.e. educating the leads about the product, constantly communicating etc. ) in order to get a higher lead conversion.

<b>X Education</b> wants to select the most promising leads, i.e. the leads that are most likely to convert into paying customers. The company requires to build a model wherein lead score will be assigned to each of the leads such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. 

<b>The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.</b>



<div style="color:white;
           display:fill;
           border-radius:5px;
           background-color:#1663BE;
           font-size:110%;
           font-family:Calibri;
           letter-spacing:0.5px">

<p style="padding: 0.015px;
              color:black;">  

# Business Goal

<p style="padding: 0.015px;
              color:white;">
</p>
Building a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.