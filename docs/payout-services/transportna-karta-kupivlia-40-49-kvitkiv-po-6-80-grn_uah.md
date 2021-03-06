
# Транспортна карта (купівля 40-49 квитків по 6.80 грн.) (service) 
![transportna-karta-kupivlia-40-49-kvitkiv-po-6-80-grn_uah](https://static.openfintech.io/payout_methods/transportna-karta-kupivlia-40-49-kvitkiv-po-6-80-grn_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `transportna-karta-kupivlia-40-49-kvitkiv-po-6-80-grn_uah` 
 
**Method:** `transportna-karta-kupivlia-40-49-kvitkiv-po-6-80-grn` [show -->](/payout-methods/transportna-karta-kupivlia-40-49-kvitkiv-po-6-80-grn/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] Транспортна карта (купівля 40-49 квитків по 6.80 грн.) 
:	[RU] Транспортна карта (купівля 40-49 квитків по 6.80 грн.) 
:	[UK] Транспортна карта (купівля 40-49 квитків по 6.80 грн.) 
 
**Amount limits:** from `2.00` to `14999.00` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`nomer_karti`|✔|`string`|`/^[\w\|\.\| \|\-\|\+\|@\|\#]{1,128}$/`| 
|`kilkist_pojizdok`|✔|`string`|`/^[\w\|\.\| \|\-\|\+\|@\|\#]{1,128}$/`| 
 

### Details 
 
1. **`nomer_karti`** 
 
	Type: `string` 
 
	Regexp: `/^[\w|\.| |\-|\+|@|\#]{1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Номер карти 
	: [RU] Номер карти 
	: [UK] Номер карти 
 
	Hint:  
	: [EN] Номер карти 
	: [RU] Номер карти 
	: [UK] Номер карти 
 
2. **`kilkist_pojizdok`** 
 
	Type: `string` 
 
	Regexp: `/^[\w|\.| |\-|\+|@|\#]{1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] Кількість поїздок 
	: [RU] Кількість поїздок 
	: [UK] Кількість поїздок 
 
	Hint:  
	: [EN] Кількість поїздок 
	: [RU] Кількість поїздок 
	: [UK] Кількість поїздок 
 

## JSON Object 

```json
{
  "code":"transportna-karta-kupivlia-40-49-kvitkiv-po-6-80-grn_uah",
  "method":"transportna-karta-kupivlia-40-49-kvitkiv-po-6-80-grn",
  "currency":"UAH",
  "fields":[
    {
      "key":"nomer_karti",
      "type":"string",
      "label":{
        "en":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u0438",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u0438",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u0438"
      },
      "regexp":"\/^[\\w|\\.| |\\-|\\+|@|\\#]{1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u0438",
        "ru":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u0438",
        "uk":"\u041d\u043e\u043c\u0435\u0440 \u043a\u0430\u0440\u0442\u0438"
      },
      "example":"100000000393"
    },
    {
      "key":"kilkist_pojizdok",
      "type":"string",
      "label":{
        "en":"\u041a\u0456\u043b\u044c\u043a\u0456\u0441\u0442\u044c \u043f\u043e\u0457\u0437\u0434\u043e\u043a",
        "ru":"\u041a\u0456\u043b\u044c\u043a\u0456\u0441\u0442\u044c \u043f\u043e\u0457\u0437\u0434\u043e\u043a",
        "uk":"\u041a\u0456\u043b\u044c\u043a\u0456\u0441\u0442\u044c \u043f\u043e\u0457\u0437\u0434\u043e\u043a"
      },
      "regexp":"\/^[\\w|\\.| |\\-|\\+|@|\\#]{1,128}$\/",
      "required":true,
      "position":2,
      "hint":{
        "en":"\u041a\u0456\u043b\u044c\u043a\u0456\u0441\u0442\u044c \u043f\u043e\u0457\u0437\u0434\u043e\u043a",
        "ru":"\u041a\u0456\u043b\u044c\u043a\u0456\u0441\u0442\u044c \u043f\u043e\u0457\u0437\u0434\u043e\u043a",
        "uk":"\u041a\u0456\u043b\u044c\u043a\u0456\u0441\u0442\u044c \u043f\u043e\u0457\u0437\u0434\u043e\u043a"
      },
      "example":"40"
    }
  ],
  "amount_min":"2.00",
  "amount_max":"14999.00"
}
```  
