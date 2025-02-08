# cardputer_llm
Standalone LLM [Ollama]([https://en.wikipedia.org/wiki/ELIZA](https://ollama.com/)) on your [Cardputer](https://shop.m5stack.com/products/m5stack-cardputer-kit-w-m5stamps3).<br>
<img width=640 src = "https://github.com/user-attachments/assets/578215ab-22bc-4f01-a7f8-c62d11771f7c" /><br>
It works like [this](https://x.com/layer812/status/1888252596865093982).<br>
## how to make it.
### cabling
Connect Cardputer with Raspberry pi Zero 2 W as following.<br>
<img width="640" alt="Image" src="https://github.com/user-attachments/assets/88f34f47-0db6-486f-a3f4-8ec20891e76f" />
### Install Ollama
Install Ollama on Raspberry Pi Zero 2 W according to [Gilzone's guide](https://github.com/Gilzone/Installing-a-LLM-on-Raspberry-Pi-Zero-2-W).<br>
### Install Cardterm
Install [Cardterm](http://www.picosoft.co.jp/CardTerm/) on Cardputer.<br>
Change baudrate of Cardterm with setup.sys<br>
``baudrate = 115200``<br>
### Enable serial console.
Enable serial console for Raspberry Pi Zero 2 W with raspi-config.<br>
### Run a model
After boot Raspberry Pi Zero 2 W, you can run a model.<br> 
``$ ollama run smollm2:135m-instruct-q4_K_S``<br>
It takes loooong time :)<br>
## Note
Please use this at your own risk.
