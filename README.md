# Apex - 
<h2>Apex Trigger, Controller 와 test class </h3> 
<h3> salesforce 고유의 객체지향 언어 </h3> 

Apex Trigger란? 
트리거는 DML 작업이 발생하기 전후에 즉시 실행되는 Apex 스크립트입니다. 그런 다음 삽입, 삭제 및 레코드 업데이트와 같은 몇 가지 사용자 지정 작업을 수행합니다. 일반적으로 데이터베이스 시스템에서는 일부 작업에 대해 트리거를 사용하고 Salesforce에서 동일한 방식으로 트리거를 사용하여 Salesforce 데이터베이스에서 작업을 수행합니다.

Apex 트리거의 작업
트리거에는 두 가지 작업이 있습니다.

Before triggers: Before triggers는 필드 업데이트와 같은 DML 작업이 발생하기 전에 특정 작업을 수행해야 할 때 사용됩니다. <br/> 
After triggers: After 트리거는 특정 작업을 수행해야 할 때 사용됩니다. DML 작업이 발생한 후 대부분 시스템에서 생성한 값을 사용해야 할 때 After 트리거를 사용합니다.<br/> 
Apex 트리거의 이벤트
트리거에는 다음과 같은 7가지 이벤트가 있습니다.<br/> 
<br/> 
이벤트 전: 레코드를 삽입, 삭제 또는 업데이트하기 전에 특정 작업을 수행해야 할 때 사용됩니다. 
