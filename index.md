# 5 axes robotic arm
My project is an industrial five axes robotic arm that can be controlled with an app on your phone with only a couple sliders. It will be using an arduino nano esp32, a NEMA17 motor for the base rotation, and several +servos for the rest of the joints and claw.

You should comment out all portions of your portfolio that you have not completed yet, as well as any instructions:
```HTML 
<!--- This is an HTML comment in Markdown -->
<!--- Anything between these symbols will not render on the published site -->
```

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Andrew L | Pinewood | Electrical Engineering | Incoming Sophomore

**Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg)
  
# Final Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE



# Second Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone 

# First Milestone

**Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Arduino Nano ESP32 (With Headers) | To receive imported code, read sensors, intake and output data, and to connect to the app through either wifi or bluetooth.  | $19.30 | <a href="https://store-usa.arduino.cc/products/nano-esp32-with-headers?queryID=undefined"> Link </a> |
| High-Torque NEMA 17 Stepper Motor (40N·cm+) | To serve as the base rotation for the arm | $12.99 | <a href="https://www.amazon.com/MAKERELE-Stepper-42-40mm-Connector-Printers/dp/B0FP1QQ1NT/ref=sr_1_1_sspa?crid=18HXIK5GNN9X4&dib=eyJ2IjoiMSJ9.w7_CWW7b_PgKSALA9QxV8udsr-memgYtp87GfifCx2HeYsIRjl6XTkCV1ynyPmGS4OfvD4kWfRXm3RHfwXoMxM6KjYUrvUkfFGhb5y7bMLLFZVfh5sxU-CX509Wl6Cj8WeH0lAmJw-NNA9x41gg0Sf1X0poiVzZrVR7DJ_W6_Q0l8eWwp2Vrf4tbM7rfkv0pFrqv_n1N1TdiCyttqHT2-NcXxwMpJKYZRmVNJ0wIvGI.Nv3HsFK6ZuvQJ0PjS1KE5AMAew4PoGiolsSfBCTccuE&dib_tag=se&keywords=High-Torque%2BNEMA%2B17%2BStepper%2BMotor%2B(40N%C2%B7cm%2B)&qid=1780093547&sprefix=high-torque%2Bnema%2B17%2Bstepper%2Bmotor%2B40n%2Bcm%2B%2B%2Caps%2C134&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| A4988 Stepper Driver (With Headers & Heatsink) | To power to NEMA17 motor | $5.99 | <a href="https://www.amazon.com/outstanding-StepStick-Stepper-Printer-Robotics/dp/B082F42W3H/ref=sr_1_10?crid=2B0YTVLE36JB6&dib=eyJ2IjoiMSJ9.ej_k6Aj_Uaj-XyjS2xZRF77rDJMKwjz7-9XlRGQVxgeu62VZPQZD1gUtVPVaA7EfSS0c6oNJ4-rv7itgcQbMUmEUIwcE0AjqJ1LwD0VRp9-kIiakoPt9in1MQnYgjXvZT6SHiUk3DkqrNacS7cTSB-Slyoj6jrfiqrGj3CBgNA1jBr8IiDjXwiHXaz_nskIABoeL0aZCmzlWuG__s4YCygUX6GcR3kQpiUrkqPfIu0I.apCskpN7VNbXIX-AFn5IEzwmuPwZFj0moSsw2AbqZZI&dib_tag=se&keywords=A4988+Stepper+Driver+%28With+Headers+%26+Heatsink%29&qid=1780096058&sprefix=a4988+stepper+driver+with+headers+%26+heatsink+%2Caps%2C139&sr=8-10"> Link </a> |
| MG996R High-Torque Servos | To serve as the motor to power the joints | $9.99 | <a href="https://www.amazon.com/AEDIKO-MG996R-Control-Digital-Helicopter/dp/B09BZ5955Z/ref=sr_1_8?crid=3POB5H52CRIGJ&dib=eyJ2IjoiMSJ9.pg8M9-SDz7L_x3kdbfbU4KObUUcqsCEEX9l-IenK3F6QWH2psF50Iiz5HbD_TLt4gmc8soUObrPStUebN9TJJIxEyCvepG5ns3p959Tih6gcI7zwFov6-S98yYwczkA8-LfwXcj5qwZTJxENLCLWHmm_NasK6pIHCFgxeJ8lFT6LsP2ntNVju0UsSlQs_PgHaeUQVmFfD37fcpTsr-Pb6xaYt60eJy9quZ3yMH0saa7SP1uBMMNBOvIi80afoExhTCPn1m2BoV6qf-zxnpMOFVt1ENlyB-OxKAM9gbugb0c.OyD4HNssemftXWz-kbSg-I51I-vgX0yhb1GRZ8idn8U&dib_tag=se&keywords=MG996R%2BHigh-Torque%2BServos&qid=1780096290&sprefix=mg996r%2Bhigh-torque%2Bservos%2Caps%2C341&sr=8-8&th=1"> Link </a> |
| SG90 Micro Servos | To serve as the motor to power the claw at the end | $6.99 | <a href="https://www.amazon.com/WWZMDiB-SG90-Control-Servos-Arduino/dp/B0BKPL2Y21/ref=sr_1_1_sspa?crid=3LGHV5FBGR2AV&dib=eyJ2IjoiMSJ9.DO_8huDXG-WCdEl_xxmMGHDTUq8Gy0sMBJu8P0uFAgVHfguxcLm-es5P-FvLGv7ZFLbQs728JUKzUYPSqLilJ34yfALPhjS2x3xBGbr20Rcpy1aIBJ8HEQO-xsrA73LAvcGZBewwm7jlB5SxSdFJn3W0X7gluehcf5C_zYp1ndrp8Oyq2HJW5fDzaSggXAYKAj_RqE8-SDqptAcyOjPpajbCZFb4gUVCW_DmVkG6G6HbHUmML0xpKWUY9MV_7QnHxgCBH_v6m29wKqQAlrqTZQZenrvijjeoNHHZ2BLzbCE.Q6oll216eiWYECWTkge5HCzG5rESRvwy2SgFtREe_SU&dib_tag=se&keywords=SG90%2BMicro%2BServos&qid=1780096440&sprefix=sg90%2Bmicro%2Bservos%2Caps%2C194&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| 12V 5A DC Power Supply (Wall Adapter) | To power the components | $9.99 | <a href="https://www.amazon.com/12V-Power-Supply-Universal-5-5x2-5mm/dp/B0DLWB2TPR/ref=sr_1_5?crid=4KELCBG9T8FL&dib=eyJ2IjoiMSJ9.I-GoS26sjdlZnxZX9e1QcYYs3utuQNgVCYe1WgQTnlDFSrXTL35X2mS4-CWOMNo37ln2uBmeJsvh2BNKTWNxBQwJzKG8IkYRtFGpgtE35rbaExRPsNfkBauDUqIns7GnwM3Lqum0VsibKQQxtOh4YdN20NwVPMZ9dGFUF46BO2Bk-jfG4_x8xlzrzLkFCTSpK3Z2aGuou8P0TFuSOHJ7p121ibBbmAGGhLBU7izjJi8.fKnRh-Kv7fA8dpwEceH91oT--DA2TKWKJ8A6V7tjp1Q&dib_tag=se&keywords=12V+5A+DC+Power+Supply+%28Wall+Adapter%29&qid=1780096499&sprefix=12v+5a+dc+power+supply+wall+adapter+%2Caps%2C172&sr=8-5"> Link </a> |
| 5V 10A High-Current Step-Down Buck Converter | To convert the 12V to 5V for safe use with the breadboard and electronic components | $9.99 | <a href="https://www.amazon.com/VOLRANTISE-Converter-Voltage-Regulator-Transformer/dp/B09WZ9DC9W/ref=sr_1_1_sspa?crid=NSF1XV6TXJ5O&dib=eyJ2IjoiMSJ9.yGT2lPXJJM_DsY7QdywxJh69O7uW6kZCL6rUSllxNBfOlAISfZV7CCz3fEYFzzT6roK84_OM8VKMp5jlIoerM84e8Bj-87Tzn86px70iV52rfbw0WKolnYwn9PuyKU84WWSCyUT8COpehBOzvvTf6NUa1ujN4EQEFHed_EhlUxUOkyPlV-GesMb4KcRtKIVGR1_38qPT4okSkuP7RMLcaujTakdCIcQZRFsG8MMpw8s.ATftOQY3U3pFoiN-UlWexG-aCvCalTiNrDFalvjm_Zs&dib_tag=se&keywords=5V%2B10A%2BHigh-Current%2BStep-Down%2BBuck%2BConverter&qid=1780096626&sprefix=5v%2B10a%2Bhigh-current%2Bstep-down%2Bbuck%2Bconverter%2Caps%2C198&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&th=1"> Link </a> |
| Solderless Breadboard & Jumper Wire Bundle | For prototyping and testing | $9.99 | <a href="https://www.amazon.com/HUAREW-Breadboard-Jumper-Include-Points/dp/B09VKYLYN7/ref=sr_1_1_sspa?crid=17ZYWIAPHAH0H&dib=eyJ2IjoiMSJ9.KciiFgkRrEIcipCiSmynt5kPOvtwmLnrQaK2dyIWS9ZrvtumZOqZL0tW_pem3YrZ44cPRqH2HhiKe0vxIBTKk-GL_cxM4MMrgliGS1zMGe-yodx6y3Rozmw3s3rwuqiouQoMDjOifTsqVUzaHX7zE7h6XpqSKbNzFJt8YldQ48ykmUBmB3XYpD-9LKk95iUCTKVYBl0JOGDhORHSu_dK5_auKNlwK_RIH-T9zz_uhjE.IyUa_69Lprv46KEavo0FFvtegG7YXMegcms2yw01FyQ&dib_tag=se&keywords=Solderless+Breadboard+%26+Jumper+Wire+Bundle&qid=1780096663&sprefix=solderless+breadboard+%26+jumper+wire+bundle%2Caps%2C141&sr=8-1-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1"> Link </a> |



# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
