# NY-Bus-Breakdown-Delay-Analysis
Abstract 

The Bus Breakdown and Delay system collects information from school bus vendors operating out in the field in real time. Bus staff that encounter delays during the route are instructed to radio the dispatcher at the bus vendor’s central office. The bus vendor staff are then instructed to log into the Bus Breakdown and Delay system to record the event and notify Office of Pupil Transportation (OPT). OPT customer service agents use this system to inform parents who call with questions regarding bus service. The Bus Breakdown and Delay system is publicly accessible and contains real time updates. All information in the system is entered by school bus vendor staff.

Purpose of this study:

The purpose of this case study is to get some data insights and analyze the several factors causing the breakdowns and delays. Furthermore, it provides an overview of the trend over the years and suggests factors that can help in minimizing the problem of delay.

Data Description and Explanatory variables description

1.Bus Breakdown and Delays: 21 columns – columns used in analysis are listed here
Field Name	Description
Field Name: School_Year
Data Type: varchar
	Indicates the school year the record refers to. The DOE school year starts in September every year. 
Field Name: Busbreakdown_ID
Data Type: integer
	Unique ID of each record.
Field Name: Run_Type
Data Type: varchar
	Designates whether a breakdown or delay occurred on a specific category of busing service.
Field Name: Bus_No
Data Type: char
	The bus number is assigned by the bus vendor. The numbers are not unique identifiers and may be repeated across vendors. 
Field Name: Route_Number
Data Type: char
	This refers to the unique identifier four (1 alpha + 3 numeric) character route numbers indicate curb-to-curb service while five (1 alpha + 4 numeric) indicates stop-to-school service.
Field Name: Reason
Data Type: varchar
	Reason for delay as entered by staff employed by reporting bus vendor
 
Field Name: Boro
Data Type: varchar
	Borough, county or state in which the delay occurred, as entered by the staff employed by the reporting bus vendor.
Field Name: Bus_Company_Name
Data Type: varchar
	Bus vendor name of the reporting bus vendor.
Field Name: How_Long_Delayed
Data Type: char
	Length of delay as estimated by the staff employed by the reporting bus vendor. OPT does not systematically monitor the contents of this field in real time.
Number_Of_Students_On_The_Bus
Data Type: integer
Width: -	Number of students on the bus at the time of the incident as estimated by the staff employed by the reporting bus vendor. OPT does not systematically monitor the contents of this field in real time.
Has_Contractor_Notified_Schools
Data Type: integer
Width: -	Indicator status as reported by the staff employed by the reporting bus vendor. OPT does not systematically monitor the contents of this field in real time.
Has_Contractor_Notified_Parents
Data Type: varchar
Width: 3	Indicator status as reported by the staff employed by the reporting bus vendor. OPT does not systematically monitor the contents of this field in real time.
Have_You_Alerted_OPT
	Indicator status as reported by the staff employed by the reporting bus vendor. OPT does not systematically monitor the contents of this field in real time.
Breakdown_or_Running_Late
Data Type: varchar
Width: 12	Indicator status as reported by the staff employed by the reporting bus vendor. OPT does not edit this field. Designates whether a bus has broken down (and requires another vehicle to be dispatched to finish the route) or is delayed (and may not require another vehicle).

Link to data set:https://data.cityofnewyork.us/resource/fbkk-fqs7.json
