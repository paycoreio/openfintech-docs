
# Kiev Interactive Telecommunications (service) 
![kievskie-interaktivnye-telekomunnikatsii_uah](https://static.openfintech.io/payout_methods/kievskie-interaktivnye-telekomunnikatsii_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `kievskie-interaktivnye-telekomunnikatsii_uah` 
 
**Method:** `kievskie-interaktivnye-telekomunnikatsii` [show -->](/payout-methods/kievskie-interaktivnye-telekomunnikatsii/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] Kiev Interactive Telecommunications 
:	[RU] Киевские интерактивные телекомунникациы 
:	[UK] Київські інтерактивні телекомуннікаціи 
 
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
	: [EN] Payment code 
	: [UK] Платіжний код 
	: [RU] Платежный код 
 
	Hint:  
	: [EN] Enter payment code 
	: [UK] Введіть платіжний код 
	: [RU] Введите платежный код 
 

## JSON Object 

```json
{
  "code":"kievskie-interaktivnye-telekomunnikatsii_uah",
  "method":"kievskie-interaktivnye-telekomunnikatsii",
  "currency":"UAH",
  "fields":[
    {
      "key":"client_id",
      "type":"string",
      "label":{
        "en":"Payment code",
        "uk":"\u041f\u043b\u0430\u0442\u0456\u0436\u043d\u0438\u0439 \u043a\u043e\u0434",
        "ru":"\u041f\u043b\u0430\u0442\u0435\u0436\u043d\u044b\u0439 \u043a\u043e\u0434"
      },
      "regexp":"\/^\\d{1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"Enter payment code",
        "uk":"\u0412\u0432\u0435\u0434\u0456\u0442\u044c \u043f\u043b\u0430\u0442\u0456\u0436\u043d\u0438\u0439 \u043a\u043e\u0434",
        "ru":"\u0412\u0432\u0435\u0434\u0438\u0442\u0435 \u043f\u043b\u0430\u0442\u0435\u0436\u043d\u044b\u0439 \u043a\u043e\u0434"
      },
      "example":"3005300460"
    }
  ],
  "amount_min":"2",
  "amount_max":"14999"
}
```  
