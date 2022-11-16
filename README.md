# shineunited/coding-standard
Coding Standards for Shine United Projects


## Core Ruleset

### ShineUnited
All projects should include the ShineUnited standard in there codesniffer configuration. This is largly a modification of the PSR12 coding standard.

```xml
<rule ref="ShineUnited" />
```

## Additional Rulesets

### ShineUnited-RequireTypeHints
Requires all parameters, returns and properties to be type hinted.
```xml
<rule ref="ShineUnited-RequireTypeHints" />
```

### ShineUnited-RequireStrictTypes
Requires strict_types=1 to be declared in all php files.
```xml
<rule ref="ShineUnited-RequireStrictTypes" />
```

### ShineUnited-RequireComments
Requires comments for files, classes and most functions.

```xml
<rule ref="ShineUnitedRequireComments" />
```
