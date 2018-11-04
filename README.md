# CreativeTargeting
CreativeTargetingLineItem
I am trying to set CreativeTargeting at the lineitem level when creating the lineitem. But it throws an error 

Value assigned is dynamicvalueID
Request made: Service: NetworkService Method: getCurrentNetwork networkCode: networkID URL: https://ads.google.com/apis/ads/publisher/v201711/NetworkService Request ID: requestID ResponseTime(ms): 43 OperationsCount: null IsFault: false FaultMessage: null
Exception in thread "main" java.lang.NullPointerException
	at com.google.api.ads.dfp.axis.v201711.LineItem.setCreativeTargetings(LineItem.java:309)
	at dfp.axis.v201711.lineitemservice.CreateLineItems.runExample(CreateLineItems.java:158)
	at dfp.axis.v201711.lineitemservice.CreateLineItems.main(CreateLineItems.java:275)

Process finished with exit code 1
