# Project: **Clock**


### Writing the code

##### (Sec. 3) 

What happens when you try to run the following code? : 



The SenseHat "showmessage" function can only show strings. We saw in the last section that the type of "datetime.now().time()" is not a string. 

In Python it is possible to convert one type into another. 
See the example bellow: 


From the example, try to find the syntax of converting to a string. You can google or try looking at the introduction to python workshop, or by printing the type of a string and seeing how it is written. 

You will need to add your code under the section "#converting time_now to a string"

```python
while True: 
    
    #get the time 
    time_now = datetime.now().time()
    
    #converting time_now to a string 
```

Once you have converted time_now to a string, for our clock we want to display the time to the nearest minute. 

Remember when we printed what time_now was? it was to the nearest milisecond.

How can we display time_now to the nearest mintue? (see next section) 

--- 

#### [next section --->](section_5.md)

#### [<--- previous section](section_3.md)
