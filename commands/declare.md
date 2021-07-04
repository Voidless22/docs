## Syntax

**<span style="color:red">/declare</span>
*<span style="color:blue">varname</span>*\|*<span style="color:blue">varname\[array extents\]</span>*
\[<span style="color:blue">type</span>\]
\[<span style="color:blue">local</span>\|<span style="color:blue">global</span>\|<span style="color:blue">outer</span>\]
\[*<span style="color:blue">defaultvalue</span>*\]**

## Description

This creates a variable or array of a particular type with a particular scope, and a default value if desired. The
parameters must be given in order, but any after *varname* may be skipped to use the defaults.

**Notes**

-   The default type is string
-   The default scope is local
-   The default value is nothing (empty string, or 0)

These variables can be of any type that exist in MQ2DataVars. The variable will then have access to the members of that
type.

## See Also

-   [MQ2DataVars](../documentation/mq2datavars.md) for extensive information on variables and how to manipulate them.

[Return to Slash Commands](slash-commands.md)

