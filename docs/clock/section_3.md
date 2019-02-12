# Project: **Clock**


### Writing the code

##### (Sec. 2) 

We want the SenseHat to display the time at all times. 

If you look at the section, you'll see the following code:

```python
while True: 
    
    #get the time 
    time_now = datetime.now().time()
```

Before we start coding inside the "while loop" we will first check the "type" of "time_now"

Copy and paste the following code outside the while loop:

```python
time_now_test = datetime.now().time()
```
* Print the **_time now test_** value
* Print the **_type_** of the **_time now test_** value

What is the result of the code above? 

You should have gotten the output of the time to the nearest second and the type of **_<class 'datetime.time'>_**. 

Just like we have words or in python terms _strings_ and whole numbers or in python terms _int_ and decimal numbers in python terms as _float_, there is another type of _datetime.time_, which is used for the date and time. 

For our clock, we want to display the time to the nearest minute. 

How can we do this? 

One way to do this is convert our _datetime.time_ into a string. See the next section for instructions on this step, or have a go if you know how!  


--- 

#### [next section --->](section_4.md)

#### [<--- previous section](section_2.md)
