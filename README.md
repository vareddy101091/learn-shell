# learn-shell

### We will learn shell scripting topics.
### Here are the topics.

1. How to write shell script file.
2. Printing
3. Variables
4. Inputs
5. Conditions
6. Loop
7. Function
8. Exit Status
9. Quotes
10. SED Editor

# SED Command Options
[echo Hello World

 Enable Color
 Syntax - echo -e "\e[COLmMESSAGE\e[0m"
 -e - enable \e (Enable color in echo command)
 All the input should be there in quotes (Double quotes preferred)
 \e - Enable a color
 COLm - Color Code - Red(31m), Green(32m), Yellow(33m), Blue(34m), Magenta(35m), Cyan(36m)
 \e[0m - Disable the color. (Once we enable the color we have to diable that, else color folloows to next lines)

echo -e "\e[31mRED COLOR\e0m"
echo Normal Text