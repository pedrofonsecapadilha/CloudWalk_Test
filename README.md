# CloudWalk Monitoring Analyst<br>

![GitHub repo size](https://img.shields.io/github/repo-size/pedrofonsecapadilha/CloudWalk_Test?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/pedrofonsecapadilha/CloudWalk_Test?style=for-the-badge)

<div align="center">
<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcQFpazZmcdGe636Z7UEdQ5TU3Q95vWSqMIHAA&usqp=CAU" width="250px" alt="logo">
</div>

> Project made for Monitoring Analyst vacancy test at CloudWalk - Started Monday (10/07/2023) and delivered on Saturday (15/07/2023).

### Presentation:

> I did a presentation an save it in the repository named: 'app_cloudwalk pedro padilha.pdf'.
You can see to understand better what I did.
https://github.com/pedrofonsecapadilha/CloudWalk_Test/blob/master/app_cloudwalk_pedropadilha.pdf

### How it works:

> All database are in folder.
> I did everything in Jupyter Notebook, so it is easy to follow the document and understand everything, any doubts let me know 😉

### Tasks:
https://gist.github.com/everton-cw/8266937b1cfa7d95508bb0eec8343f0f

1. Get your hands dirty
> Using [this csv](https://github.com/thais-menezes/monitoring/blob/main/checkout_1.csv) and using [this csv](https://github.com/thais-menezes/monitoring/blob/main/checkout_2.csv) with hypothetical checkout data, imagine that you are trying to understand if there is any kind of anomaly behavior.
> 
> - Analyze the data provided and present your conclusions .
> - In addition to the spreadsheet data, make a query in SQL and make a graphic of it and try to explain the anomaly behavior you found.
> - In this csv you have the number of sales of POS by hour comparing the same sales per hour from today, yesterday and the average of other days. So with this we can see the behavior from today and compare to other days

Solution: https://github.com/pedrofonsecapadilha/CloudWalk_Test/blob/master/3.1-GetYourHandsDirty.ipynb

2. Solve the problem

> Alert incident in transactions: Implement the concept of a simple monitoring with real time alert with notifications to teams.
> 
> The monitoring works by receiving information about a transaction and inferring whether it is a failed or denied, or reversed or aprroved transaction. We work mostly with SQL, PromQL, Ruby and Python, but you can use any programming language that you want.
> 
> Please use the data of [this csv](https://github.com/thais-menezes/monitoring/blob/main/transactions_1.csv) and the data of [this csv](https://github.com/thais-menezes/monitoring/blob/main/transactions_2.csv). Consider that transactions with the flag denied are transactions denied by risk of the issuers. Consider that transactions with the flag reversed or failed are transactions with problems. Note: F1 represents the quantity of transactions per minute from all pos from our costumers. So with this data you can see the diferent status per minute and see if it is going well or not. When you see the padron, you can predict a alarm for the anomaly.
> 
> Your Monitoring alert system must have at least: 1 endpoint that receives transaction data and returns a recommendation to “alert” the anomalies found in transactions. A query to organize the data on the data and a graphic to see the data in real time. A model to determine anomalies and a system to report the anomalies automatically.
> 
> You are free to determine the methods to approve/deny the transactions, but a few ways to do it are:
> - rule-based - you define which cases get alerted based on predefined rules;
> - score-base - you create a method/model (you could use machine learning models here if you want) to determine the anomaly -- score of a transaction and make your decision based on it;
> - a combination of both;
>
> Monitoring alert Requirements
> - Alert transactions if failed transactions are above normal;
> - Alert transactions if reversed transactions are above normal;
> - Alert transactions if denied transactions are above normal;

Solution: https://github.com/pedrofonsecapadilha/CloudWalk_Test/blob/master/3.2-SolveTheProblem.ipynb

## 🤝 Developer

<table>
  <tr>
    <td align="center">
      <a href="https://github.com/pedrofonsecapadilha">
        <img src="https://avatars.githubusercontent.com/u/113715845?v=4" width="100px;" alt="Foto"/><br>
        <sub>
          <b>Pedro Padilha</b>
        </sub>
      </a>
    </td>
  </tr>
</table>
