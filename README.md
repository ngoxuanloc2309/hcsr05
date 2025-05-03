# hcsr05
I am Logan

Config: + PB9(Trigger): GPIO_OUTPUT
        + PB8(Echo):    GPIO_INPUT
To run hcsr05 you need to follow these step:
1. Add function "SR05_Init(void)" in main function (after init function)
2. Declare "extern distance" in "Code begin 0"
3. In while loop, let's code "distance = SR05_Active(void)"
