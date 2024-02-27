By Referring to C-based Lab videos and RISC-V-based lab videos

Snapshots of the compiled C code and RISC-V

Step 1: check whether the leafpad is installed in ur machine by using the commands leafpad sum1ton.c& (sum1ton.c is the file name) If the leafpad editor is opened without any errors then type the C code. **If the leafpad is not installed in ur machine then install by using the following command

sudo snap install leafpad**
![11](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/b03d727a-7f4b-438e-8e14-2e080a4e2745)
**Step 2: Writing the C code in the leafpad editor using the following command

leafpad sum1ton.c&
![22](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/a8d52b4f-70d0-414f-82ec-944f595b0d61)
Step 3: After writing the C code save the editor by Ctrl+s

Step 4: Check for the errors by using the following command(compilation step)

gcc sum1ton.c
![33](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/843887fd-3e98-4e48-8bcc-7074b0d331e9)
Step 5: Check the output by using the command

./a.out

![aa](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/212a0a0a-3cf1-4a9f-966c-c7c65d5e8aeb)
The results will be displayed as

Sum of numbers from 1 to 500 is 125250

***RISCV Compilation and Execution

Step 1: View the C Code in the editor window using the following command

cat sum1ton.c 

![44](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/9dec6953-7b21-4b9d-ac9f-714301d50139)

Step 2: Compile the code in riscv using the following command


riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c
Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.

use the command

ls -ltr sum1ton.c



![last](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/543a3bbd-1de6-409e-9f5f-b97312fed6ae)




![111](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/fce6212b-d837-48fa-ae06-7f2b9fddc8ba)




![222](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/5e609641-d726-4ed3-b83f-15dec7bff02b)






![333](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/b5c8acb9-7b0a-439e-b1c6-153243d66338)



![444](https://github.com/maraputivishnusai/maraputivishnusai/assets/160378830/03ef5814-462d-4c32-bf7e-4768e10ffca1)

