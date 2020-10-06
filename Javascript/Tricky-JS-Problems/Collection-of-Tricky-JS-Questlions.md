#### 1- Question: What is `typeof []`

**Answer**: Object. Actually Array is derived from Object. If you want to check array use Array.isArray(arr)

#### Question: What is `typeof` arguments

**Answer**: Object. arguments are array like but not array. it has length, can access by index but can't push pop, etc.

#### Question: What is `2+true`

**Answer**: 3. The plus operator between a number and a boolean or two boolean will convert boolean to number. Hence, true converts to 1 and you get result of 2+1

#### Question: What is '6'+9

**Answer**: 69. If one of the operands of the plus (+) operator is string it will convert other number or boolean to string and perform a concatenation. For the same reason, "2"+true will return "2true"

#### Question: What is the value of 4+3+2+"1"

**Answer**: 91 . The addition starts from the left, 4+3 results 7 and 7+2 is 9. So far, the plus operator is performing addition as both the operands are number. After that 9 + "1" where one of the operands is string and plus operator will perform concatenation.

#### Question: What is the value of "1"+2+4

**Answer**: "124". For this one "1" + 2 will produce "12" and "12"+4 will generates "124".

#### Question: What is the value of -'34'+10

**Answer**: -24. minus(-) in front of a string is an unary operator that will convert the string to a number and will make it negative. Hence, -'34' becomes, -34 and then plus (+) will perform simple addition as both the operands are number.

#### Question: What is the value of +'dude'

**Answer**: NaN. The plus (+) operator in front of a string is an unary operator that will try to convert the string to number. Here, JavaScript will fail to convert the "dude" to a number and will produce NaN.