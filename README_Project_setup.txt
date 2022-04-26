


Azure sql database connection setup.
-------------------------------------------------------------------------------------------------------

We have used Azure SQL database for our project.

Please let us know a hour before you review our report, so that we can setup an azure account and send you the required credentials to you.
Contact: Sasikumar Jayapal for Azure setup.

Once you got Azure credentials from us. Please do the required changes in the following codes as below.

1).comment out the below connection code from the following jupyter notebooks
--------------------------------------------------------------------------------------------------------

#defining connection parameters
import pyodbc 

conn = pyodbc.connect("Driver={SQL Server Native Client 11.0};"
                      "Server=LAPTOP-FMSOI4VL;"
                      "Database=MscDAP;"
                      "Trusted_Connection=yes;")




2).uncomment the below azure connection code from the jupyter notebooks and update the connection details that we will share with you.
---------------------------------------------------------------------------------------------------------
# #defining connection parameters
# import pyodbc 
# server = 'msc-dat-analytics.database.windows.net' 
# database = 'MscDAT' 
# username = 'dap' 
# password = 'India-data-analytics' 
# conn = pyodbc.connect('DRIVER={ODBC Driver 17 for SQL Server};SERVER='+server+';DATABASE='+database+';UID='+username+';PWD='+ password)

Note: please make sure sql server management studio is installed(SSMS) on your local machine and connected with the credentials provided above.

-----------------------------------------------------------------------------------------------------------
Azure connection has to be made on the follwoing notebooks.
1).DAP_PRJ.ipynb
2).US_Disaster_Events.ipynb
3).Natural_Disaster_Events.ipynb
4).Earthquake.ipynb
5).Master_Disaster_Integration_Datasets.ipynb
6).Master_Disaster_Events_Automated.ipynb

-------------------------------------------------------------------------------------------------------------
Run Master_Disaster_Events_Automated.ipynb notebook.

If it is not working please go with the below order.
-------------------------------------------------------------------------------------------------------------
Once you made changes on connection strings please run them the same order as below.

1).DAP_PRJ.ipynb
2).US_Disaster_Events.ipynb
3).Natural_Disaster_Events.ipynb
4).Earthquake.ipynb
5).Master_Disaster_Integration_Datasets.ipynb
5).Master_Disaster_Event_Visuals.ipynb

--------------------------------------------------------------------------------------------------------------
If you face any dificulties in any of the above task please let Sasikumar Jayapal, Babita chaini know.
--------------------------------------------------------------------------------------------------------------
                                                END