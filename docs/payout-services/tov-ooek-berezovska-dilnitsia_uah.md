
# ТОВ"ООЕК"(Березовська дільниця) (service) 
![tov-ooek-berezovska-dilnitsia_uah](https://static.openfintech.io/payout_methods/tov-ooek-berezovska-dilnitsia_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `tov-ooek-berezovska-dilnitsia_uah` 
 
**Method:** `tov-ooek-berezovska-dilnitsia` [show -->](/payout-methods/tov-ooek-berezovska-dilnitsia/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] ТОВ"ООЕК"(Березовська дільниця) 
:	[RU] ТОВ"ООЕК"(Березовська дільниця) 
:	[UK] ТОВ"ООЕК"(Березовська дільниця) 
 
**Amount limits:** from `1.00` to `14999.00` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`client_id`|✔|`string`|`/^[\w\|\.\| \|\-\|\+\|@\|\#]{1,128}$/`| 
 

### Details 
 
1. **`client_id`** 
 
	Type: `string` 
 
	Regexp: `/^[\w|\.| |\-|\+|@|\#]{1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Введіть особовий рахунок 
	: [RU] Введіть особовий рахунок 
	: [UK] Введіть особовий рахунок 
 
	Hint:  
	: [EN] Введіть особовий рахунок 
	: [RU] Введіть особовий рахунок 
	: [UK] Введіть особовий рахунок 
 

## JSON Object 

```json
{
  "code":"tov-ooek-berezovska-dilnitsia_uah",
  "method":"tov-ooek-berezovska-dilnitsia",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043e\u0441\u043e\u0431\u043e\u0432\u0438\u0439 \u0440\u0430\u0445\u0443\u043d\u043e\u043a",
        "ru":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043e\u0441\u043e\u0431\u043e\u0432\u0438\u0439 \u0440\u0430\u0445\u0443\u043d\u043e\u043a",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043e\u0441\u043e\u0431\u043e\u0432\u0438\u0439 \u0440\u0430\u0445\u0443\u043d\u043e\u043a"
      },
      "regexp":"\/^[\\w|\\.| |\\-|\\+|@|\\#]{1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043e\u0441\u043e\u0431\u043e\u0432\u0438\u0439 \u0440\u0430\u0445\u0443\u043d\u043e\u043a",
        "ru":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043e\u0441\u043e\u0431\u043e\u0432\u0438\u0439 \u0440\u0430\u0445\u0443\u043d\u043e\u043a",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043e\u0441\u043e\u0431\u043e\u0432\u0438\u0439 \u0440\u0430\u0445\u0443\u043d\u043e\u043a"
      },
      "example":"3300\/2716"
    }
  ],
  "amount_min":"1.00",
  "amount_max":"14999.00"
}
```  
