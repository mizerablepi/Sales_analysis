# Sales_analysis
This Notebook is a simple exploratary data analysis on the sales data from a electronics shop. We clean the the data a bit and then answer a few question related to the data. See how to run this notebook in [instructions.md](https://github.com/mizerablepi/Sales_analysis/blob/main/instructions.md)

## Questions that are answered using this data:
1. Which month had the best sales? How much was earned in that month?
2. Which city had the highest number of sales?
3. What time should we display ads to maximize likelihood of customers buying product?
4. What products are often sold together?
5. Which product was ordered the most? Why do you think it sold the most?

## Q1: Which month had the best sales? How much was earned in that month?
![image](https://user-images.githubusercontent.com/41267142/227176585-957f6bf7-ee88-4524-ab2d-9facd00b7ba4.png)<br>
_We can see that december has the highest sales, the sales add up to approximately $4.5 million (4613443.34 to be precise)_

## Q2: Which city had the highest number of sales?
![image](https://user-images.githubusercontent.com/41267142/227176983-48cfd129-5e83-45bb-b7cd-431ab4de3674.png)<br>
_San Fransico was the city with the highest number of sales_

## Q3: What time should we display ads to maximize likelihood of customers buying product?
![image](https://user-images.githubusercontent.com/41267142/227177375-1dcac7b8-cba0-4bd0-84c7-52f58c7744e2.png)<br>
_It looks like the most orders were placed at around 12:00 and 19:00. So we can suggest showing ads around these times to increase sales_

## Q4: What products are often sold together?
![image](https://user-images.githubusercontent.com/41267142/227177592-092f5d45-3536-4581-bd09-9bddc02a8b31.png)<br>
_From the graph we see that 'iPhone', and 'Lightning charging cable' were sold the most together._

## Q5: Which product was ordered the most? Why do you think it sold the most?
![image](https://user-images.githubusercontent.com/41267142/227175878-c063ba87-d447-48c6-96ea-3d4b2c82a916.png)<br>
From the graph we can see that AAA batteries and AA batteries are the most sold products.<br>
The reason why batteries are sold the most is probably beacause batteries are cheaper compared to other products also sold, we also see the 3rd and 4th most sold products are also somewhat cheap. To test our hypothesis lets overlay the units sold graph with the mean price of each product.<br>
![image](https://user-images.githubusercontent.com/41267142/227176357-f2d4ee42-f480-4072-b49f-2657b1decbea.png)<br>
As we see cheap products are sold more, therefore price could be the factor that determines how much a product is sold but that is not the only reason as we can see that costly products like laptops are sold more than dryer and washing machine that are comparitivly cheaper.
