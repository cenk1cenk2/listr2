[listr2](../README.md) / [index](../modules/index.md) / PromptInstance

# Interface: PromptInstance

[index](../modules/index.md).PromptInstance

## Hierarchy

* *Omit*<BasePromptOptions, ``"onCancel"`` \| ``"onSubmit"``\>

  ↳ **PromptInstance**

## Properties

### footer

• `Optional` **footer**: *string*

Inherited from: Omit.footer

Defined in: src/utils/prompt.interface.ts:32

___

### header

• `Optional` **header**: *string*

Inherited from: Omit.header

Defined in: src/utils/prompt.interface.ts:31

___

### initial

• `Optional` **initial**: *string* \| *number* \| *boolean* \| *number*[] \| () => *string* \| () => *Promise*<string\>

Inherited from: Omit.initial

Defined in: src/utils/prompt.interface.ts:27

___

### message

• **message**: *string* \| () => *string* \| () => *Promise*<string\>

Inherited from: Omit.message

Defined in: src/utils/prompt.interface.ts:26

___

### required

• `Optional` **required**: *boolean*

Inherited from: Omit.required

Defined in: src/utils/prompt.interface.ts:28

___

### stdin

• `Optional` **stdin**: *ReadStream*

Inherited from: Omit.stdin

Defined in: src/utils/prompt.interface.ts:29

___

### stdout

• `Optional` **stdout**: *WriteStream*

Inherited from: Omit.stdout

Defined in: src/utils/prompt.interface.ts:30

## Methods

### cancel

▸ **cancel**(`err?`: *string*): *void*

#### Parameters:

| Name | Type |
| :------ | :------ |
| `err?` | *string* |

**Returns:** *void*

Defined in: src/utils/prompt.interface.ts:164

___

### format

▸ `Optional`**format**(`value`: *any*): *any*

#### Parameters:

| Name | Type |
| :------ | :------ |
| `value` | *any* |

**Returns:** *any*

Inherited from: Omit.format

Defined in: src/utils/prompt.interface.ts:34

___

### result

▸ `Optional`**result**(`value`: *any*): *any*

#### Parameters:

| Name | Type |
| :------ | :------ |
| `value` | *any* |

**Returns:** *any*

Inherited from: Omit.result

Defined in: src/utils/prompt.interface.ts:35

___

### skip

▸ `Optional`**skip**(`value`: *any*): *boolean* \| *Promise*<boolean\>

#### Parameters:

| Name | Type |
| :------ | :------ |
| `value` | *any* |

**Returns:** *boolean* \| *Promise*<boolean\>

Inherited from: Omit.skip

Defined in: src/utils/prompt.interface.ts:33

___

### submit

▸ **submit**(): *void*

**Returns:** *void*

Defined in: src/utils/prompt.interface.ts:163

___

### validate

▸ `Optional`**validate**(`value`: *any*, `state`: *any*): *string* \| *boolean* \| *Promise*<boolean\> \| *Promise*<string\> \| *Promise*<string \| boolean\>

#### Parameters:

| Name | Type |
| :------ | :------ |
| `value` | *any* |
| `state` | *any* |

**Returns:** *string* \| *boolean* \| *Promise*<boolean\> \| *Promise*<string\> \| *Promise*<string \| boolean\>

Inherited from: Omit.validate

Defined in: src/utils/prompt.interface.ts:36
