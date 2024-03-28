# RohitJaju_R3_TechnicalAssessment
API validation tests : Technical assessment R3 : For exchange rates API
****Validations performed for : 1.Total currency count 2.API success response 3.Json schema validation 4. AED currency range 3.6 to 3.7.**

Steps to execute:
1.Right click on following file and run as TestNG : \src\test\java\base\ExchangeRateAPI_R3.java

2.Execution result will be displayed in console as below with printed response of API,
 ==========================================================  
[RemoteTestNG] detected TestNG version 7.0.1
The status received: HTTP/1.1 200 OK
The response time is: 0
The status received: 200
}
Total 162 -> currencies are present in API
#### AED Rate: 3.6725
** AED currency rate :3.6725 is inside the correct range
PASSED: getRequestOpenEr_API
PASSED: validate_AED_range
PASSED: validate_JSON_schema

===============================================
    Default test
    Tests run: 3, Failures: 0, Skips: 0
============================================================

3. Execution report output can be seen at : \Assignment_R3_ExchangeRates\testautomationu.webdriver_java-0.0.1-SNAPSHOT\test-output\index.html

