[Bot Builder Toybox - Prompts](../README.md) > [DatetimePrompt](../interfaces/botbuilder_toybox_prompts.datetimeprompt.md)



# Interface: DatetimePrompt


Prompts the user to reply with a date or time.

## Type parameters
#### O 

## Methods
<a id="prompt"></a>

###  prompt

► **prompt**(context: *[BotContext]()*, prompt: *`string`⎮[Partial]()[Activity]()*, speak?: *`undefined`⎮`string`*): `Promise`.<`void`>



*Defined in [packages/botbuilder-toybox-prompts/lib/datetimePrompt.d.ts:35](https://github.com/Stevenic/botbuilder-toybox/blob/848ed38/packages/botbuilder-toybox-prompts/lib/datetimePrompt.d.ts#L35)*



Sends a formated prompt to the user.


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| context | [BotContext]()   |  Context for the current turn of conversation. |
| prompt | `string`⎮[Partial]()[Activity]()   |  Text or activity to send as the prompt. |
| speak | `undefined`⎮`string`   |  (Optional) SSML that should be spoken for prompt. The prompts `inputHint` will be automatically set to `expectingInput`. |





**Returns:** `Promise`.<`void`>





___

<a id="recognize"></a>

###  recognize

► **recognize**(context: *[BotContext]()*): `Promise`.<`O`⎮`undefined`>



*Defined in [packages/botbuilder-toybox-prompts/lib/datetimePrompt.d.ts:40](https://github.com/Stevenic/botbuilder-toybox/blob/848ed38/packages/botbuilder-toybox-prompts/lib/datetimePrompt.d.ts#L40)*



Recognizes and validates the users reply.


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| context | [BotContext]()   |  Context for the current turn of conversation. |





**Returns:** `Promise`.<`O`⎮`undefined`>





___


