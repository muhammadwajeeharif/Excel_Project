# Conditional Logical Formula Project

## Weather Data :point_down:

![alt text](https://github.com/muhammadwajeeharif/Excel_Project/blob/c1c33db4694fc63b381f2488a4fbc8a2259a4532/Conditional%20Logical%20Project/Weather_Data.png)


- This data refers from Boston Logan Airport Weather dataset.
- This data includes STATION_NAME,LAT,LONG,DATE,MONTH,TEMP (F),PRCP (mm),Freeze,Climate,PRCP Type,Conditions.
- Formula for different columns are as follows:
	
	- For **Freeze** we used this formula: **=IFERROR(IF(G2<32,"Yes","No"),"Other")**.
	- For **Climate** we used this formula: **=IFERROR(IF(G2<40,"Cold",IF(G2>80,"Hot","Mild")),"Other")**.
	- For **PRCP Type** we used this formula: **=IF(AND(I2="Yes",H2>0),"Snow",IF(AND(I2="No",H2>0),"Rain","None"))**.
	- For **Conditions** we used two formula: **=IF(OR(K2="Snow",K2="Rain"),"Wet","Dry")** and **=IF(NOT(H2=0),"Wet","Dry")**.

## Weather Data Solution :point_down:

![alt text](https://github.com/muhammadwajeeharif/Excel_Project/blob/c1c33db4694fc63b381f2488a4fbc8a2259a4532/Conditional%20Logical%20Project/Solution.png)	