---
slug: /IPluginMap
title: IPluginMap
hide_title: true
displayed_sidebar: contracts
---

# IPluginMap

## Methods

### getAllFunctionsOfPlugin

```solidity
function getAllFunctionsOfPlugin(address pluginAddress) external view returns (bytes4[])
```

_Returns all functions that are mapped to the given plug-in contract._

#### Parameters

| Name          | Type    | Description |
| ------------- | ------- | ----------- |
| pluginAddress | address | undefined   |

#### Returns

| Name | Type     | Description |
| ---- | -------- | ----------- |
| \_0  | bytes4[] | undefined   |

### getAllPlugins

```solidity
function getAllPlugins() external view returns (struct IPluginMap.Plugin[])
```

_Returns all plug-ins known by Map._

#### Returns

| Name | Type                | Description |
| ---- | ------------------- | ----------- |
| \_0  | IPluginMap.Plugin[] | undefined   |

### getPluginForFunction

```solidity
function getPluginForFunction(bytes4 functionSelector) external view returns (address)
```

_Returns the plug-in contract for a given function._

#### Parameters

| Name             | Type   | Description |
| ---------------- | ------ | ----------- |
| functionSelector | bytes4 | undefined   |

#### Returns

| Name | Type    | Description |
| ---- | ------- | ----------- |
| \_0  | address | undefined   |

## Events

### PluginSet

```solidity
event PluginSet(bytes4 indexed functionSelector, string indexed functionSignature, address indexed pluginAddress)
```

_Emitted when a function selector is mapped to a particular plug-in smart contract, during construction of Map._

#### Parameters

| Name                        | Type    | Description |
| --------------------------- | ------- | ----------- |
| functionSelector `indexed`  | bytes4  | undefined   |
| functionSignature `indexed` | string  | undefined   |
| pluginAddress `indexed`     | address | undefined   |
