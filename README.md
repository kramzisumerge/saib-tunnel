# saib-tunnel


input paramters : 

{
	"X-SAIB-Function" : "P100100",
	"X-SAIB-Transaction-Id" : "a7339761-7f3e-420f-b0ef-a5203f08632d",
	"X-SAIB-Timestamp" : "2026-03-18T12:58:57.605Z",
	"X-SAIB-Time-Zone" : "UTC+03:00",
	"X-SAIB-Channel" : "BPM",
	"X-SAIB-CIF" : "100215",
	"body": {
	"transferNumber": "TRX123456789",
	"action": "APPROVE",
	"comment": "GOOD REQUEST"
}
}

reponse : {  "status": 152361335001,  "statusDescription": "Action completed successfully",  "serverDateTime": "2026-03-11T13:25:41Z",  "icsReference": "ICS-987654321"}



GetValueDate input parameters : 
{
	"X-SAIB-Function" : "P100100",
	"X-SAIB-Transaction-Id" : "a7358f41-7103-4442-849a-f6109c0d8970",
	"X-SAIB-Timestamp" : "2026-03-18T13:13:42.641Z",
	"X-SAIB-Time-Zone" : "UTC+03:00",
	"X-SAIB-Channel" : "BPM",
	"X-SAIB-CIF" : "100215",
	"systemDate": "18-03-2026",
	"requestValueDate": "t+1"
}

response : {  "status": 152361335001,  "statusDescription": "Transfer date retrieved successfully",  "serverDateTime": "2026-03-11T13:25:41Z",  "valueDate": "2026-03-12"}
