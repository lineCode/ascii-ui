[terminal-in-canvas](../README.md) > ["widgets/Text"](../modules/_widgets_text_.md)



# External module: "widgets/Text"

## Index

### Classes

* [Text](../classes/_widgets_text_.text.md)


### Interfaces

* [TextOptions](../interfaces/_widgets_text_.textoptions.md)
* [TextToken](../interfaces/_widgets_text_.texttoken.md)


### Type aliases

* [TokenizerFunction](_widgets_text_.md#tokenizerfunction)


### Functions

* [tokenizer](_widgets_text_.md#tokenizer)



---
## Type aliases
<a id="tokenizerfunction"></a>

###  TokenizerFunction

**Τ TokenizerFunction**:  *`function`* 

*Defined in [widgets/Text.ts:9](https://github.com/danikaze/terminal-in-canvas/blob/6c46a1f/src/widgets/Text.ts#L9)*


#### Type declaration
►(text: *`string`*): [TextToken](../interfaces/_widgets_text_.texttoken.md)[]



**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| text | `string`   |  - |





**Returns:** [TextToken](../interfaces/_widgets_text_.texttoken.md)[]






___


## Functions
<a id="tokenizer"></a>

###  tokenizer

► **tokenizer**(text: *`string`*): [TextToken](../interfaces/_widgets_text_.texttoken.md)[]



*Defined in [widgets/Text.ts:257](https://github.com/danikaze/terminal-in-canvas/blob/6c46a1f/src/widgets/Text.ts#L257)*



Given a text, it will split it into words


**Parameters:**

| Param | Type | Description |
| ------ | ------ | ------ |
| text | `string`   |  Text to split |





**Returns:** [TextToken](../interfaces/_widgets_text_.texttoken.md)[]
text splitted into tokens






___

