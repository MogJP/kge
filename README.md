# KGE
KrunkGroupEditor. User-Friendly & Extensive & Reflect an opinion from community!
It can edit any property.
![image](https://user-images.githubusercontent.com/81292406/112282794-cae1a500-8cca-11eb-816d-9f6939c1fff8.png)

## Easy Json Parser (user-friendly mode)
```
1.select target property(e.g. interface id)
2.select operation(e.g. increase)
3.input operation value(e.g. 3)
4.click run
5.copy to clipboard / save to file / Re-parse json(this will copy json from output to input)
```

## Advanced Json Parser (advancecd mode, any property)
```
1.Type advanced property (look the following table)
2.Select Proper Operation
3.Turn on "number" checkbox if the value is number.(for example, interface id)
4.Type Value
5.Press Run
```
```
--- Advanced Property Table ---
in  | Interface ID
tin | Target
```
```
- If theres no property, try this -
1 I recommend you to turn on "Quick GUI" from editor setting.(my favorite is "middle click")
2 Middle Click object -> JSON -> copy and paste it to somewhere
3 Select the object of 1.2 and change the property what you want to edit in this software.
4 Middle Click object of 1.3 -> JSON -> copy and paste
5 Compare the 2 json data. if you find diffrence, thats the property!

1 For example, if you change cube interface id from 0 to 10, json will be like this:
2 Before : [{"p":[-1,16,67],"s":[10,10,10]}]
3 After changing property : [{"p":[-1,16,67],"s":[10,10,10],"in":10}]
4 "in": 10 is interface id. say more, "in" is the property and 10 is value.

:) I would appreciate if you send me Advanced-property & in-game-property via suggestions/bugreports button.
```
