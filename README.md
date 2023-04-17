# Merchant-processing-forcasting

# Merchant Processing Forecasting Tool



#Varibles
Total_Leads= 8000
Boarded_Accounts= 240
Total_Cost= 53000
Cost_of_acq= Total_Cost/Boarded_Accounts
Yearly_Residuals= Boarded_Accounts* 1200
Monthly_Residuals= Yearly_Residuals/12
Close_percentage= Boarded_Accounts/Total_Leads
Deals_Per_Week= Boarded_Accounts/52
Agents= 6
Months_Before_Profit = Total_Cost/Monthly_Residuals
#Desired Representation



#Print the data
print("**This Model is based off agents making 100% of the residuals**")
print("Total Leads:", Total_Leads)
print("Percentage of Leads closed:",Close_percentage)
print("Total Boarded Accounts:", Boarded_Accounts)
print("Boarded Accounts per Month",Boarded_Accounts/12)
print("Accounts Per Agent:",Boarded_Accounts/Agents)
print("Closed Deals Per Week Required:", Deals_Per_Week/Agents)
print("Cost per Acqusition is: $", Cost_of_acq)
print("Months Before profitability:",Months_Before_Profit)
print("Estimated Monthly Residual: $",Yearly_Residuals/12)
print("Estimated Monthly Residual Per Agent: $",Yearly_Residuals/12/Agents)
print("Estimated Yearly Residual: $", Yearly_Residuals)
print("Estimated Yearly Residual Per Agent: $", Yearly_Residuals/Agents)
