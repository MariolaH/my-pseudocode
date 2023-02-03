# SHRIMP FRIED RICE  
<img src='./img/shrimp.jpeg' width="180" height="150">

---  


## ABOUT:
---

```

- This recipe was curated by a local Chef.

- This dish features spicy and umami notes.

- It can be prepared with any type of protein but the chef recommends shrimp.

- Time to cook: 20 minutes

```

---

## INIT: Variables for the program

---

```
- Measure all ingredients using measuring spoons
- Measuring utensils and bowls:
        - 1 tablespoon
        - 0.5 cup
        - 6 small 4 oz bowls
        - 3 soup bowls
- Place all measured ingredients in seperate bowls
- Chef
- Working heat source, stove
- Clean work space
- Large plate: 1
- Fork: 1
- Large pan: 1
- Medium spatula: 1
- Raw defrosted deveined tail-off shrimp: 10
- Frozen mixed vegetables: 0.5 cup
- Cooked brown rice: 1 cup
- Soy Sauce: 1 tablespoon
- Olive oil: 2 tablespoons
- Raw cracked egg: 1

Dry Seasonings:

- Sriracha Seasoning: 2 tablespons
- Salt: 1 tablespoon
- Pepper: 1 tablespoon

COMBINE: with spatula

```




---

## FUNCTIONALITY:

---

```

STEP 1 CHECK GROCERIES

    Does Chef have all the ingredients?
        If True
            PROCEED
        IF False
            STOP       

```
```

STEP 2 PREPARE ENVIRONMENT 

    IF cleanSpace === True
        PROCEED
    IF cleanSpace === False
        STOP

```
```

STEP 3 TURN STOVE ON

    1. Put pan on stove element

    2. Turn stove on to medium
    

```



```

STEP 4 PAN

 IF hotPan === True
        PROCEED
 IF hotPan === False
        STOP

```
```

STEP 5 OLIVE OIL

    1. Add olive oil

    IF hotOliveOil === True
            PROCEED
    IF hotOliveOil === False
            STOP     

```

```

STEP 6 PROTEIN

    1. Add shrimp to pan 

    2. Mix with spatula 

    3. When shrimp changes from clear to white 

    4. PROCEED

```

```

STEP 7 VEGETABLES

    1. add frozen vegetables

    2. Mix with spatula 

    3. When frozen vegetables starts to soften 

    4. PROCEED

```

```

STEP 8 DRY SEASONING

    ARRAY spices = [2 tbs Sriracha Seasoning, 1 tbs Salt, 1 tbs Pepper]

    1. Add Dry seasonings

    2. Mix with spatula

    IF taste === adequate
        PROCEED
    ELSE
        STOP    

```

```
STEP 9 CARB

    1. add rice 

    2. cook for 2 mins

    3. Combine with spatula

    4. PROCEED

```
```

STEP 10 LIQUID SEASONING

    1. add soy sauce

    2. cook for 2 mins

    3. Mix with spatula

    IF taste === adequate
            PROCEED
        ELSE
            STOP  
```
```

STEP 11 EGG

    1. PLACE ingredients onto half the pan

    2. Pour egg into empty half of pan

    3. Scramble till not runny 

    4. PROCEED

```
```

STEP 12 COMBINE

    IF combineIngredients === True
            PROCEED
    IF combineIngredients === False
            STOP 

```

```

STEP 13 FRY


    IF friedIngredients === 2 mins
                PROCEED
            ELSE
                STOP 

```

```

STEP 14 PLATE

    1. turn off element

    2. take pan off element 

    3. with spatual place ingredients onto plate

    4. place pan on cold stove element

    5. PROCEED        

```
```

STEP 15 ENJOY

    Enjoy!

```

```

START PROGRAM

    STEP 1
    STEP 2
    STEP 3
    STEP 4
    STEP 5
    STEP 6
    STEP 7
    STEP 8
    STEP 9
    STEP 10
    STEP 11
    STEP 12
    STEP 13
    STEP 14
    STEP 15

END PROGRAM

```



Like in step 6: While shrimp is not pink, mix with spatula
Step 4: While pan is not hot, wait

Can you take what you’ve written and make them more code-like? Any loops you can find or statements like “WHILE x, do Y”? Or any repeatable things that could be thought of as functional?
Like in step 6: While shrimp is not pink, mix with spatula
Step 4: While pan is not hot, wait
Could mix with spatula be thought of as it’s own function (repeated block of code in a program you’d be writing)
This is a very good pseudocode for the procedural parts and the object parts of the code.
Are there opportunities to think about the different things you might need? Like a measure function to get the right measurements of ingredients? You could think about trying to identify repeated functionalities in your code that could be it’s own thing.
Otherwise I think you’ve thought through things well, but this is a list of things I think that could take it to the next level.