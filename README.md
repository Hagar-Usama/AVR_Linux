
# AVR Guide **[Linux Edition]** 📟

Linux people, let's code

![Build-Passing][1] ![Embedded-AVR][2] ![Linux-Lover][3]

[1]: https://img.shields.io/:Build-Passing-whiteGreen.svg?style=round-square
[2]: https://img.shields.io/:Embedded-AVR-yellow.svg?style=round-square
[3]: https://img.shields.io/:Linux-Lover-maroon.svg?style=round-square


---

## Table of Contents
* [Introduction][10]
* [Technologies][11]
* [Launch][12]
* [To-do List][15]
* [Bugs][16]
* [License][17]


[10]: https://github.com/Hagar-Usama/AVR_Linux#introduction

[11]: https://github.com/Hagar-Usama/AVR_Linux#technologies

[12]: https://github.com/Hagar-Usama/AVR_Linux#launch

[13]: https://github.com/Hagar-Usama/AVR_Linux#screenshots

[15]: https://github.com/Hagar-Usama/AVR_Linux#to-do-list

[16]: https://github.com/Hagar-Usama/AVR_Linux#bugs

[17]: https://github.com/Hagar-Usama/AVR_Linux#license

---

## Introduction
Linux people, I have made this guide for myself, my Linuxian teammates 💚.
I believe what can be done on Windows, can be done on Linux 🐧.

---

## Technologies

* interactive script to compile and upload AVR codes 🙌
---

## Launch

 How to Launch?
 > It is a BIG question! 🙆 Assuming you have wired you AVR properly, you have just small steps:
 1. Install the required packages
 1. Compile your code and generate a hex file
 1. Install USBASP driver
 1. Upload your hex file on the AVR


🙀😥 Huh?
 > To install the required packages, copy this line to your terminal
 ``` bash
$ sudo apt-get install gcc-avr avr-libc avrdude
 ```
**OR** execute Essential_Packages script either by double click if executable or RUN
```  bash
$ chmod 755 Essential_Packages
$ ./Essential_Packages
```



> To check your connection , i.e, the AVR is connected properly to the programmer, run the script file Check_Connection
``` bash
$ chmod 755 Check_Connection
$ ./Check_Connection
```
**You will have to install the usbasp driver first** [driver attached]



> To compile your file into a hex file, run the script file Covert_to_Hex
``` bash
$ chmod 755 Covert_to_Hex
$ ./Covert_to_Hex
```


> Finally, upload the hex file, run the script file Upload_Hex
``` bash
$ chmod 755 Upload_Hex
$ ./Upload_Hex
```

Boring long steps 😒, ha?
>  AVR_All_in_One script file, compiles and uploads the code [ interactive bash ]
``` bash
$ chmod 755 AVR_All_in_One
$ ./AVR_All_in_One
```

![seq1][36]

![seq2][37]

![seq2][32]

Still Confused? 🤔
>check  👉 [this video][31]. It is creepy, but may help.

Wonder why 755? 🤔

>check  👉 [this][30]

 [30]: https://technicalbud.com/chmod-file-permissions-775/
 [31]: https://www.youtube.com/watch?v=namySz6WsB0&feature=youtu.be
 [32]: https://github.com/Hagar-Usama/AVR/blob/master/screenshot/blink2.gif
 [33]:https://github.com/Hagar-Usama/AVR/blob/master/screenshot/Screenshot_%D9%A2%D9%A0%D9%A1%D9%A9%D9%A0%D9%A8%D9%A2%D9%A1_%D9%A2%D9%A0%D9%A1%D9%A8%D9%A3%D9%A3.png
 [34]:https://github.com/Hagar-Usama/AVR/blob/master/screenshot/Screenshot_%D9%A2%D9%A0%D9%A1%D9%A9%D9%A0%D9%A8%D9%A2%D9%A1_%D9%A2%D9%A0%D9%A1%D9%A8%D9%A5%D9%A7.png
 [35]: https://github.com/Hagar-Usama/AVR/blob/master/screenshot/Screenshot_%D9%A2%D9%A0%D9%A1%D9%A9%D9%A0%D9%A8%D9%A2%D9%A1_%D9%A2%D9%A0%D9%A2%D9%A1%D9%A3%D9%A7.png
 [36]: https://github.com/Hagar-Usama/AVR/blob/master/screenshot/Screenshot_%D9%A2%D9%A0%D9%A1%D9%A9%D9%A0%D9%A8%D9%A2%D9%A1_%D9%A2%D9%A0%D9%A2%D9%A1%D9%A3%D9%A7.png
 [37]:https://github.com/Hagar-Usama/AVR/blob/master/screenshot/Screenshot_%D9%A2%D9%A0%D9%A1%D9%A9%D9%A0%D9%A8%D9%A2%D9%A1_%D9%A2%D9%A0%D9%A2%D9%A1%D9%A5%D9%A0.png


---



## To-do List
* [x] build a neat README
* [ ] GUI version (QT4)



---

## Bugs 🐞
* None

---

## License
![License](http://img.shields.io/:License-MIT-blue.svg?style=round-square)

[MIT License](https://opensource.org/licenses/MIT "MIT")
