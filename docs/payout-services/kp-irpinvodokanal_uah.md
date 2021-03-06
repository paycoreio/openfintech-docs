
# KP 'Irpinvodokanal' (service) 
![kp-irpinvodokanal_uah](https://static.openfintech.io/payout_methods/kp-irpinvodokanal_uah/logo.svg?w=400&c=v0.59.26#w24)  

## General 
 
**Code:** `kp-irpinvodokanal_uah` 
 
**Method:** `kp-irpinvodokanal` [show -->](/payout-methods/kp-irpinvodokanal/) 
 
**Currency:** `UAH` [show -->](/currencies/UAH/) 
 
**Name:** 
 
:	[EN] KP 'Irpinvodokanal' 
:	[RU] КП 'Ирпиньводоканал' 
:	[UK] КП 'Ірпіньводоканал' 
 
**Amount limits:** from `2` to `14999` UAH 

## Fields 

### Overview 

|Key|Required|Type|Regexp| 
|:---:|:---:|:---:|:---:| 
|`or`|✔|`string`|`/^(\w\|\.\| \|\-\|\+\|@){1,128}$/`| 
|`pib`|✔|`string`|`/^(\w\|\.\| \|\-\|\+\|@){1,128}$/`| 
 

### Details 
 
1. **`or`** 
 
	Type: `string` 
 
	Regexp: `/^(\w|\.| |\-|\+|@){1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] OR 
	: [RU] ОР 
	: [UK] ЗР 
 
	Hint:  
	: [EN] OR 
	: [RU] ОР 
	: [UK] ЗР 
 
2. **`pib`** 
 
	Type: `string` 
 
	Regexp: `/^(\w|\.| |\-|\+|@){1,128}$/` 
 
	Required: `1` 
 
	Label:  
	: [EN] PIB 
	: [RU] ПИБ 
	: [UK] ПІБ 
 
	Hint:  
	: [EN] PIB 
	: [RU] ПИБ 
	: [UK] ПІБ 
 

## JSON Object 

```json
{
  "code":"kp-irpinvodokanal_uah",
  "method":"kp-irpinvodokanal",
  "currency":"UAH",
  "fields":[
    {
      "key":"or",
      "type":"string",
      "label":{
        "en":"OR",
        "ru":"\u041e\u0420",
        "uk":"\u0417\u0420"
      },
      "regexp":"\/^(\\w|\\.| |\\-|\\+|@){1,128}$\/",
      "required":true,
      "position":1,
      "hint":{
        "en":"OR",
        "ru":"\u041e\u0420",
        "uk":"\u0417\u0420"
      },
      "example":"1234567"
    },
    {
      "key":"pib",
      "type":"string",
      "label":{
        "en":"PIB",
        "ru":"\u041f\u0418\u0411",
        "uk":"\u041f\u0406\u0411"
      },
      "regexp":"\/^(\\w|\\.| |\\-|\\+|@){1,128}$\/",
      "required":true,
      "position":2,
      "hint":{
        "en":"PIB",
        "ru":"\u041f\u0418\u0411",
        "uk":"\u041f\u0406\u0411"
      },
      "example":"\u041f\u0435\u0442\u0440\u043e\u0432 \u0410.\u0410."
    }
  ],
  "amount_min":"2",
  "amount_max":"14999"
}
```  
