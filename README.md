# Wizaplace PHP Code Sniffs

[![CircleCI](https://circleci.com/gh/wizacode/phpcs/tree/master.svg?style=svg)](https://circleci.com/gh/wizaplace/php-etl/tree/master)


## Installation

```bash
composer require --dev wizaplace/phpcs
```

```xml
<?xml version="1.0"?>
<ruleset>
    <rule ref="vendor/wizaplace/phpcs/BaBeuloula/ruleset.xml"/>
</ruleset>
```

## Coding standards

| Sniff |
|-------|
| [BaBeuloula.CodeAnalysis.Backslash](https://github.com/babeuloula/phpcs/blob/master/BaBeuloula/Sniffs/CodeAnalysis/BackslashSniff.php) |
| [BaBeuloula.CodeAnalysis.StrictTypes](https://github.com/babeuloula/phpcs/blob/master/BaBeuloula/Sniffs/CodeAnalysis/StrictTypesSniff.php) |
| [BaBeuloula.Uses.GroupUses](https://github.com/babeuloula/phpcs/blob/master/BaBeuloula/Sniffs/Uses/GroupUsesSniff.php) |
| [BaBeuloula.Functions.FunctionCallSignature](https://github.com/babeuloula/phpcs/blob/master/BaBeuloula/Sniffs/Functions/FunctionCallSignatureSniff.php) |
| [BaBeuloula.Properties.ConstantVisibility](https://github.com/babeuloula/phpcs/blob/master/BaBeuloula/Sniffs/Properties/ConstantVisibilitySniff.php) |

