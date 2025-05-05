# CIS-2023-Linux-Final-Project

CIS-2023-Linux-Final-Project

### Commands used to create CountTo50.sh script

![1-CountTo50ScriptSetup](https://github.com/user-attachments/assets/65281f8e-10cf-4378-9529-9de02b98cf53)

### Execution of CountTo50.sh script

![2-CountTo50ScriptExecute](https://github.com/user-attachments/assets/23cc571f-0c16-4354-be44-242bf416a1ef)

### All commands entered into Ubuntu test system

ls -l

sudo touch CountTo50.sh

ls -l

sudo chmod 750 CountTo50.sh
ls -l 

sudo vi CountTo50.sh

#!/bin/bash

for i in {1..50}; do
  echo $i
done

:wq

sudo ./CountTo50.sh
