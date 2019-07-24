---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

String expression = "Replace([preferredLanguage], "-", , , "_", ,  )";



ExpressionInputObject testInputObject = new ExpressionInputObject();
testInputObject.definition = null;
LinkedList<StringKeyObjectValuePair> propertiesList = new LinkedList<StringKeyObjectValuePair>();
StringKeyObjectValuePair properties = new StringKeyObjectValuePair();
properties.key = "objectId";
properties.value = "66E4A8CC-1B7B-435E-95F8-F06CEA133828";
propertiesList.add(properties);
StringKeyObjectValuePair properties1 = new StringKeyObjectValuePair();
properties1.key = "IsSoftDeleted";
properties1.value = "false";
propertiesList.add(properties1);
StringKeyObjectValuePair properties2 = new StringKeyObjectValuePair();
properties2.key = "accountEnabled";
properties2.value = "true";
propertiesList.add(properties2);
StringKeyObjectValuePair properties3 = new StringKeyObjectValuePair();
properties3.key = "streetAddress";
properties3.value = "1 Redmond Way";
propertiesList.add(properties3);
StringKeyObjectValuePair properties4 = new StringKeyObjectValuePair();
properties4.key = "city";
properties4.value = "Redmond";
propertiesList.add(properties4);
StringKeyObjectValuePair properties5 = new StringKeyObjectValuePair();
properties5.key = "state";
properties5.value = "WA";
propertiesList.add(properties5);
StringKeyObjectValuePair properties6 = new StringKeyObjectValuePair();
properties6.key = "postalCode";
properties6.value = "98052";
propertiesList.add(properties6);
StringKeyObjectValuePair properties7 = new StringKeyObjectValuePair();
properties7.key = "country";
properties7.value = "USA";
propertiesList.add(properties7);
StringKeyObjectValuePair properties8 = new StringKeyObjectValuePair();
properties8.key = "department";
properties8.value = "Sales";
propertiesList.add(properties8);
StringKeyObjectValuePair properties9 = new StringKeyObjectValuePair();
properties9.key = "displayName";
properties9.value = "John Smith";
propertiesList.add(properties9);
StringKeyObjectValuePair properties10 = new StringKeyObjectValuePair();
properties10.key = "extensionAttribute1";
properties10.value = "Sample 1";
propertiesList.add(properties10);
StringKeyObjectValuePair properties11 = new StringKeyObjectValuePair();
properties11.key = "extensionAttribute2";
properties11.value = "Sample 2";
propertiesList.add(properties11);
StringKeyObjectValuePair properties12 = new StringKeyObjectValuePair();
properties12.key = "extensionAttribute3";
properties12.value = "Sample 3";
propertiesList.add(properties12);
StringKeyObjectValuePair properties13 = new StringKeyObjectValuePair();
properties13.key = "extensionAttribute4";
properties13.value = "Sample 4";
propertiesList.add(properties13);
StringKeyObjectValuePair properties14 = new StringKeyObjectValuePair();
properties14.key = "extensionAttribute5";
properties14.value = "Sample 5";
propertiesList.add(properties14);
StringKeyObjectValuePair properties15 = new StringKeyObjectValuePair();
properties15.key = "extensionAttribute6";
properties15.value = "Sample 6";
propertiesList.add(properties15);
StringKeyObjectValuePair properties16 = new StringKeyObjectValuePair();
properties16.key = "extensionAttribute7";
properties16.value = "Sample 1";
propertiesList.add(properties16);
StringKeyObjectValuePair properties17 = new StringKeyObjectValuePair();
properties17.key = "extensionAttribute8";
properties17.value = "Sample 1";
propertiesList.add(properties17);
StringKeyObjectValuePair properties18 = new StringKeyObjectValuePair();
properties18.key = "extensionAttribute9";
properties18.value = "Sample 1";
propertiesList.add(properties18);
StringKeyObjectValuePair properties19 = new StringKeyObjectValuePair();
properties19.key = "extensionAttribute10";
properties19.value = "Sample 1";
propertiesList.add(properties19);
StringKeyObjectValuePair properties20 = new StringKeyObjectValuePair();
properties20.key = "extensionAttribute11";
properties20.value = "Sample 1";
propertiesList.add(properties20);
StringKeyObjectValuePair properties21 = new StringKeyObjectValuePair();
properties21.key = "extensionAttribute12";
properties21.value = "Sample 1";
propertiesList.add(properties21);
StringKeyObjectValuePair properties22 = new StringKeyObjectValuePair();
properties22.key = "extensionAttribute13";
properties22.value = "Sample 1";
propertiesList.add(properties22);
StringKeyObjectValuePair properties23 = new StringKeyObjectValuePair();
properties23.key = "extensionAttribute14";
properties23.value = "Sample 1";
propertiesList.add(properties23);
StringKeyObjectValuePair properties24 = new StringKeyObjectValuePair();
properties24.key = "extensionAttribute15";
properties24.value = "Sample 1";
propertiesList.add(properties24);
StringKeyObjectValuePair properties25 = new StringKeyObjectValuePair();
properties25.key = "givenName";
properties25.value = "John";
propertiesList.add(properties25);
StringKeyObjectValuePair properties26 = new StringKeyObjectValuePair();
properties26.key = "jobTitle";
properties26.value = "Finance manager";
propertiesList.add(properties26);
StringKeyObjectValuePair properties27 = new StringKeyObjectValuePair();
properties27.key = "mail";
properties27.value = "johns@contoso.com";
propertiesList.add(properties27);
StringKeyObjectValuePair properties28 = new StringKeyObjectValuePair();
properties28.key = "mailNickname";
properties28.value = "johns";
propertiesList.add(properties28);
StringKeyObjectValuePair properties29 = new StringKeyObjectValuePair();
properties29.key = "manager";
properties29.value = "maxs@contoso.com";
propertiesList.add(properties29);
StringKeyObjectValuePair properties30 = new StringKeyObjectValuePair();
properties30.key = "mobile";
properties30.value = "425-555-0010";
propertiesList.add(properties30);
StringKeyObjectValuePair properties31 = new StringKeyObjectValuePair();
properties31.key = "onPremisesSecurityIdentifier";
properties31.value = "66E4A8CC-1B7B-435E-95F8-F06CEA133828";
propertiesList.add(properties31);
StringKeyObjectValuePair properties32 = new StringKeyObjectValuePair();
properties32.key = "passwordProfile.password";
properties32.value = "";
propertiesList.add(properties32);
StringKeyObjectValuePair properties33 = new StringKeyObjectValuePair();
properties33.key = "physicalDeliveryOfficeName";
properties33.value = "Main Office";
propertiesList.add(properties33);
StringKeyObjectValuePair properties34 = new StringKeyObjectValuePair();
properties34.key = "preferredLanguage";
properties34.value = "EN-US";
propertiesList.add(properties34);
StringKeyObjectValuePair properties35 = new StringKeyObjectValuePair();
properties35.key = "proxyAddresses";
properties35.value = "";
propertiesList.add(properties35);
StringKeyObjectValuePair properties36 = new StringKeyObjectValuePair();
properties36.key = "surname";
properties36.value = "Smith";
propertiesList.add(properties36);
StringKeyObjectValuePair properties37 = new StringKeyObjectValuePair();
properties37.key = "telephoneNumber";
properties37.value = "425-555-0011";
propertiesList.add(properties37);
StringKeyObjectValuePair properties38 = new StringKeyObjectValuePair();
properties38.key = "userPrincipalName";
properties38.value = "johns@contoso.com";
propertiesList.add(properties38);
StringKeyObjectValuePair properties39 = new StringKeyObjectValuePair();
properties39.key = "appRoleAssignments";
properties39.additionalDataManager().put("value@odata.type", new JsonPrimitive("#Collection(String)"));
LinkedList<String> valueList = new LinkedList<String>();
valueList.add("Default Assignment");
properties39.value = valueList;
propertiesList.add(properties39);
testInputObject.properties = propertiesList;

graphClient.servicePrincipals("{id}").synchronization().jobs("{id}").schema()
	.parseExpression(expression,testInputObject,targetAttributeDefinition)
	.buildRequest()
	.post();

```