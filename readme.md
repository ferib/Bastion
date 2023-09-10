# Bastion _but LuaObfuscated_

![pepe honk](./img/pepe-anon.gif)

[![Obfuscated Build](https://github.com/ferib/bastion/actions/workflows/master.yml/badge.svg?branch=master)](https://github.com/ferib/bastion/actions/workflows/master.yml)

Bastion framework but obfuscated with LuaObfuscator

```json
{
    "MinifiyAll": true,
    "ASCIIArt": "feet_1",
    "Virtualize": false,
    "CustomPlugins": {
        "SwizzleLookups": [ 100 ],
        "EncryptStrings": [ 0 ],
        "RevertAllIfStatements": [ 50 ],
        "ControlFlowFlattenV1AllBlocks": [ 75, 75, 33 ],
        "MixedBooleanArithmetic": [ 5 ],
        "MutateAllLiterals": [ 20 ],
        "JunkifyAllIfStatements": [ 50 ]
    }
}
```