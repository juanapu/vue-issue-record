# vue-issue-record
a respository to record common vue issues

## vue-cli
> less-loader
```p
 error: Unrecognised input
 reason: vue-cli has already defined loader, will alert error when define repeately
 solution: npm i less less-loader -D (without define less-loader manually)
```
##  forlder class name format
|   element               |      tips                |     correct example         |  wrong example           |
|   ---------------------:| -----------------------: |  -------------------------: |  -----------------------:|
|folder>component.vue      |    folder name  cannot be camel case   | Header>Header.vue  | HeaderLayout>Header.vue        |
|folder>component.vue      |    component name  can be camel case   | Header>HeaderLayout.vue  | null     |
