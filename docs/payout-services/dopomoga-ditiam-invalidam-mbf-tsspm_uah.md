
# Help for Children with Disabilities - ICF DSPM (service) 
![dopomoga-ditiam-invalidam-mbf-tsspm_uah](https://static.openfintech.io/payout_methods/dopomoga-ditiam-invalidam-mbf-tsspm_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `dopomoga-ditiam-invalidam-mbf-tsspm_uah` 
 
**Method:** `dopomoga-ditiam-invalidam-mbf-tsspm` [show -->](/payout-methods/dopomoga-ditiam-invalidam-mbf-tsspm/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] Help for Children with Disabilities - ICF DSPM 
:	[RU] Помощь Детям Инвалидам - ​​МБФ ЦСПМ ' 
:	[UK] Допомога Дітям Інвалідам - ​​МБФ ЦСПМ ' 
 
**Amount limits:** from `0.01` to `14999` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`client_id`|✔|`string`|`/^(\w\|\.\| \|\-\|\+\|@){1,128}$/`| 
 

### Details 
 
1. **`client_id`** 
 
	Type: `string` 
 
	Regexp: `/^(\w|\.| |\-|\+|@){1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Phone number 
	: [UK] Номер телефону 
	: [RU] Номер телефона 
 
	Hint:  
	: [EN] Enter phone number 
	: [UK] Введіть номер телефону 
	: [RU] Введите номер телефона 
 

## JSON Object 

```json
{
  "code":"dopomoga-ditiam-invalidam-mbf-tsspm_uah",
  "method":"dopomoga-ditiam-invalidam-mbf-tsspm",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"Phone number",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0443",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0430"
      },
      "regexp":"\/^(\\w|\\.| |\\-|\\+|@){1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"Enter phone number",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0443",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043d\u043e\u043c\u0435\u0440 \u0442\u0435\u043b\u0435\u0444\u043e\u043d\u0430"
      },
      "example":"8888"
    }
  ],
  "amount_min":"0.01",
  "amount_max":"14999"
}
```  
