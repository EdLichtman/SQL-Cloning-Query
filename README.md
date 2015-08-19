# SQL-Cloning-Query
This clones information and allows you to find and replace specified values. </ br>
The given variables are:</ br>
@TableName : The name of the table you want to Clone</ br>
@NewTableName : The new Table Name to insert the values into. Defaults to '' which means use "TableName" as "NewTableName"</ br>
@ColumnsDelimited : Each Column you specify must end with ". If you want all the columns leave it as ''</ br>
@VarCharFind : The Value you wish to find in order to replace it. Defaults to '' which means you do not wish to replace anything</ br>
@VarCharReplace : The Value you wish to replace your find value with. Only works with VarCharFind does not equal ''</ br>
@OptionalParam : The "Where" Clause which limits the amount of data you are cloning. Always start with "Where"</ br>
