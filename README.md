# zenclass-task5
Create a shell script to print the HTTP error code
![script to print the HTTP error code](https://github.com/ranju386/zenclass-task5/blob/main/script-img.jpg)
![output of the script code](https://github.com/ranju386/zenclass-task5/blob/main/zenclasstask5-2.jpg)

Given a file, replace all occurrence of the word ""give"" with ""learning"" from the 5th line till the end in only those lines that contain the word "welcome"

![input file file.txt](https://github.com/ranju386/zenclass-task5/blob/main/zenclasstask5-3.jpg)
## sed command sed '5,$ {/welcome/s/give/learning/g}' file.txt
![output after sed command](https://github.com/ranju386/zenclass-task5/blob/main/zenclasstask5-4.jpg)
