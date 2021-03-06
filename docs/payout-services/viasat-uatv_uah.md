
# Viasat UATV (service) 
![viasat-uatv_uah](https://static.openfintech.io/payout_methods/viasat-uatv_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `viasat-uatv_uah` 
 
**Method:** `viasat-uatv` [show -->](/payout-methods/viasat-uatv/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] Viasat UATV 
:	[RU] Viasat UATV 
:	[UK] Viasat UATV 
 
**Amount limits:** from `200` to `149900` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`client_id`|✔|`string`|`/^\d{1,128}$/`| 
 

### Details 
 
1. **`client_id`** 
 
	Type: `string` 
 
	Regexp: `/^\d{1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] The contract number 
	: [UK] Номер договору 
	: [RU] Номер договора 
 
	Hint:  
	: [EN] Enter the contract number 
	: [UK] Введіть номер договору 
	: [RU] Введите номер договора 
 

## JSON Object 

```json
{
  "code":"viasat-uatv_uah",
  "method":"viasat-uatv",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"The contract number",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0434\u043e\u0433\u043e\u0432\u043e\u0440\u0443",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0434\u043e\u0433\u043e\u0432\u043e\u0440\u0430"
      },
      "regexp":"\/^\\d{1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"Enter the contract number",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043d\u043e\u043c\u0435\u0440 \u0434\u043e\u0433\u043e\u0432\u043e\u0440\u0443",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043d\u043e\u043c\u0435\u0440 \u0434\u043e\u0433\u043e\u0432\u043e\u0440\u0430"
      },
      "example":"0022179740"
    }
  ],
  "amount_min":"200",
  "amount_max":"149900"
}
```  
