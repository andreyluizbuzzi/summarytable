# Change Log

## Version v1.3.0 (not released yet)
** Possible to reference calculated rows in row formulas.
** Possible to add ranges i row formulas, using double colon. Syntax: "formula": "[1240]::[1668]"

## Version v1.2.0
** Any formula expression (including parenthesis etc.) is now possible on column calculations. Javascript's standard evaluation of expressions are used instead of custom one.
** Added attribute "displayAllRows", to make it possible to force rows to be displayed even if no data is available.
** Display empty cell instead of (blank) when cell contains no data.

## Version v1.1.0
** Bug fix: Calculation columns did not handle formulas correctly.

## Version v1.0.0
** First version
