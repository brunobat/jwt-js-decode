[jwt-js-decode](../README.md) > [JwtDecode](../classes/jwtdecode.md)

# Class: JwtDecode

Class for creating a JwtDecode object with three parts of JWT Token, header and payload decoded and parsed, signature in initial form
*__class__*: JwtDecode

## Hierarchy

**JwtDecode**

## Index

### Constructors

* [constructor](jwtdecode.md#constructor)

### Properties

* [header](jwtdecode.md#header)
* [payload](jwtdecode.md#payload)
* [signature](jwtdecode.md#signature)

---

## Constructors

<a id="constructor"></a>

###  constructor

⊕ **new JwtDecode**(str: *`string`*): [JwtDecode](jwtdecode.md)

*Defined in jwt-js-decode.ts:102*

**Parameters:**

| Param | Type |
| ------ | ------ |
| str | `string` |

**Returns:** [JwtDecode](jwtdecode.md)

___

## Properties

<a id="header"></a>

###  header

**● header**: *[JwtPart](../interfaces/jwtpart.md)*

*Defined in jwt-js-decode.ts:86*

Header (first) part of JWT Token
*__name__*: header

*__type__*: {JwtPart}

___
<a id="payload"></a>

###  payload

**● payload**: *[JwtPart](../interfaces/jwtpart.md)*

*Defined in jwt-js-decode.ts:94*

Payload (second) part of JWT Token
*__name__*: payload

*__type__*: {JwtPart}

___
<a id="signature"></a>

###  signature

**● signature**: *`string`*

*Defined in jwt-js-decode.ts:102*

Signature (third) part of JWT Token
*__name__*: signature

*__type__*: {string}

___
