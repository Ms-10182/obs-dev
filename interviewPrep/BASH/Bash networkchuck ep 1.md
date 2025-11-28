which $SHELL 
> this will show which shell im using

echo "message"
> this will ask linux to say something

nano script.sh
>creates a new file in editor mode

#! 
> this is called sheba 

eg:
```bash
#!/bin/bash

echo "hi mom"
```

```bash
variable=value
```
> just write the var name and value
> NEVER PUT SPACE around =

```bash
read variable
```
>To take input at runtime 

```bash
variable=$1
```
>this will take input from shell runtime
>if no args is passed then it will be empty

```bash
user=$(whoami)
```
>Here use $() to use a terminal command

```bash
#!/bin/bash

name=$1
compliment=$2

date=$(date)
workingDir=$(pwd)
user=$(whoami)

echo "good morning $name !!"

echo "today is $date"
echo "you are working in $workingDir"
echo "you are logged in as $user"

sleep 1

echo "you are looking good today $name !!"

sleep 1

echo "you have the best $compliment i have ever seen $name !!"

```

