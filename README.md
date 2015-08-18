# SQL-Cloning-Query
This clones information and allows you to find and replace specified values.
The given variables are:
@TableName : The name of the table you want to Clone
@NewTableName : The new Table Name to insert the values into. Defaults to '' which means use "TableName" as "NewTableName"
@VarCharFind : The Value you wish to find in order to replace it. Defaults to '' which means you do not wish to replace anything
@VarCharReplace : The Value you wish to replace your find value with. Only works with VarCharFind does not equal ''
@OptionalParam : The "Where" Clause which limits the amount of data you are cloning. Always start with "Where"
