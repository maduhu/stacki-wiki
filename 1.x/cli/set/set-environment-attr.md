## set environment attr

### Usage

`stack set environment attr {environment} {attr} {value} [attr=string] [shadow=boolean] [value=string]`

### Description

Sets an attribute to an environment and sets the associated values

### Arguments

* `{environment}`

   Name of environment

* `{attr}`

   Name of the attribute

* `{value}`

   Value of the attribute


### Parameters
* `[attr=string]`

   same as attr argument
* `[shadow=boolean]`

   If set to true, then set the 'shadow' value (only readable by root
	and apache).
* `[value=string]`

   same as value argument

### Examples

* `stack set environment attr test sge False`

   Sets the sge attribution to False for test nodes


