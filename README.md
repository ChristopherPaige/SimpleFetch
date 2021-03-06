# SimpleFetch



![Project Logo](https://i.postimg.cc/xTV41LPx/Simple-Fetch.png)



## Description
![Project Image](https://i.postimg.cc/CLmWyqCZ/simplefetch.png)
![Project_Image2](https://i.postimg.cc/jdbsqPJZ/simple-fetch.png)

SimpleFetch is a lightweight script that I wrote for fun, and it was an attempt to make a bare-bones implementation of Neofetch written in Python3. Neofetch is obviously my favorite, and is clearly a better option. Neofetch is much more complex, and provides a lot more functionality! Here is a link if you want to try it out! [Neofetch](https://github.com/dylanaraps/neofetch) 

This was a fun experiment, and I learned quite a bit making it! 

#### Technologies

- Python3
- Platform
- Subprocess
- py-cpuinfo
- psutil
- pyfiglet
- simple_chalk


## Usage

- Make sure you have Python3 installed!
- Copy the SimpleFetch folder to your home directory.

### ZSH

Open the nano text editor in your terminal and type: sudo nano ~/.zshrc

Add this line below to the bottom of the file under # Aliases or MyAliases, etc.

- alias sf="cd SimpleFetch && python3 simple_fetch.py; cd ~"


### Bash

Open the nano text editor in your terminal and type: sudo nano ~/.bashrc

Add this line below to the bottom of the file under # Aliases or MyAliases, etc.

- alias sf="cd SimpleFetch && python3 simple_fetch.py; cd ~"


### Fish

Open your terminal and type: alias -s sf="cd SimpleFetch/ && python3 simple_fetch.py; cd ~"


# Contributors
- Christopher Paige
- Montassar Ben Dhifallah [Github Profile](https://github.com/Momentum-TN)
  - Co-Authored, fetch_GPU_info()
  - Co-Authored, i_req()
  - Requirements.txt

[Back To The Top](#SimpleFetch)
## License

MIT License

Copyright (c) [2021] [ChristopherPaige]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.


