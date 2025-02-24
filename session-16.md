when we run run any command on shell it gives some status the status of the command denoted $? 
it the status is success $? will be 0 other wise it will be non-zero
to check if the condition get succees or failure by using if

if condition:
-------------
if [condition]; then
 commands
fi

if-else condition:
---------------
if [condition]; then
commands
else
commands
fi

else-if:
--------
if [expression1]; then
commands
elif [expression2]; then
commands
else
commands
fi

