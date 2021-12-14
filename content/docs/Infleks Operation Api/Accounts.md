# <span style="color:orange">Accounts</span>

Lorem ipsum dolor sit amet, consectetur adipiscing elit, 
sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
 Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut
 aliquip ex ea commodo consequat. 


## <span style="color:orange">[GET] Gets a Single Accounts ID</span>



`/gate/v1/accounts/{accountId}`



 dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, when an unknown printer took a galley of type and 
 scrambled it to make a type specimen book.
 
 ## Response  
 
 It is a long established fact that a reader will be distracted by the readable 
 content of a page when looking at its layout
 
 
 ### Example  
 
```Json
{
  "accountId": "123456789",
  "accountStatus": "OPEN",
  "accountType": "INDIVIDUAL",
  "branchId": 1,
  "creationDate": "2020-08-10 14:30:20",
  "customerId": 123456789,
  "reportGroup": "ALL",
  "reportMethod": "LETTER",
  "reportPeriod": "MONTHLY",
  "taxCalculationMethod": "WEIGHTED_AVERAGE",
  "viopAccountStatus": "ACTIVE"
}
```

## Properties


{{< columns >}}
-accountId

<---> 


<span style="color:grey">String</span> <br>
Account Id

 ------------
<---> 

{{< /columns >}}




{{< columns >}}
-accountStatus

<--->
 

<span style="color:grey">String</span> <br>
Account Status
 

------------
<---> 

 
{{< /columns >}}


{{< columns >}}

-branchId

<---> 


<span style="color:grey">Integer</span> <br>
Branch Id

 ------------
<---> 

{{< /columns >}}

{{< columns >}}

-creationDate

<---> 


<span style="color:grey">String</span> <br>
Creation Date 

 ------------
<---> 

{{< /columns >}}

{{< columns >}}

-customerId

<---> 


<span style="color:grey">Integer</span> <br>
Customer Id

 ------------
<---> 

{{< /columns >}}

{{< columns >}}

-reportGroup

<---> 


<span style="color:grey">String</span> <br>
Report Group

 ------------
<---> 

{{< /columns >}}

{{< columns >}}

-reportMethod

<---> 


<span style="color:grey">String</span> <br>
Report Method

 ------------
<---> 

{{< /columns >}}

{{< columns >}}

-reportPeriod

<---> 


<span style="color:grey">String</span> <br>
Report Period

 ------------
<---> 

{{< /columns >}}

{{< columns >}}

-taxCalculationMethod

<---> 


<span style="color:grey">String</span> <br>
Tax Calculation Method

 ------------
<---> 

{{< /columns >}}

{{< columns >}}

-viopAccountStatus

<---> 


<span style="color:grey">String</span> <br>
VIOP Account Status

 ------------
<---> 

{{< /columns >}}
