# The Goal of this projects 

The goal of this projects is to learn how to use microsoft fabric with a personnal project. The project is to compute some insightfull KPI about the electric vehicle fleet in the US.



# Architecture 



![schema eletric vehicle](https://github.com/user-attachments/assets/5a180a57-70bb-4edb-a701-b92391ed18af)



In the first step we retrieved and modify the name of the column that are set up by data.gov because it's easier to work with column name without space and special character. The second step is to insert it with the current_timestamp in the bronze table. In the third steps, we retrieve by vehicle id the last raw added in order to have an accuracy information for each vehicle and still can add more vehicle. Finaly, we create 3 tables in the gold layer (datamart) where we compute some KPI like the number of vehicle by state or the market share by each maker of vehicle electric. 




## Stack 



<p align="center">
  <a href="https://go-skill-icons.vercel.app/">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=py,fabric,spark" />
  </a>
</p>
