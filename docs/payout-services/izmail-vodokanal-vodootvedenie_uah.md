
# Izmail Vodokanal (drainage) (service) 
![izmail-vodokanal-vodootvedenie_uah](https://static.openfintech.io/payout_methods/izmail-vodokanal-vodootvedenie_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `izmail-vodokanal-vodootvedenie_uah` 
 
**Method:** `izmail-vodokanal-vodootvedenie` [show -->](/payout-methods/izmail-vodokanal-vodootvedenie/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] Izmail Vodokanal (drainage) 
:	[RU] Измаил водоканал (водоотведение) 
:	[UK] Ізмаїл водоканал (водовідведення) 
 
**Amount limits:** from `2` to `14999` UAH 

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
	: [EN] Your personal account 
	: [UK] Особовий рахунок 
	: [RU] Лицевой счет 
 
	Hint:  
	: [EN] Enter your personal account 
	: [UK] Введіть особовий рахунок 
	: [RU] Введите лицевой счет 
 

## JSON Object 

```json
{
  "code":"izmail-vodokanal-vodootvedenie_uah",
  "method":"izmail-vodokanal-vodootvedenie",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"Your personal account",
        "uk":"\u041e\u0441\u043e\u0431\u043e\u0432\u0438\u0439 \u0440\u0430\u0445\u0443\u043d\u043e\u043a",
        "ru":"\u041b\u0438\u0446\u0435\u0432\u043e\u0439 \u0441\u0447\u0435\u0442"
      },
      "regexp":"\/^\\d{1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"Enter your personal account",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043e\u0441\u043e\u0431\u043e\u0432\u0438\u0439 \u0440\u0430\u0445\u0443\u043d\u043e\u043a",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043b\u0438\u0446\u0435\u0432\u043e\u0439 \u0441\u0447\u0435\u0442"
      },
      "example":"13245"
    }
  ],
  "amount_min":"2",
  "amount_max":"14999"
}
```  
