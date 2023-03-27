# PCbee_solar_light
 PCbee - Bee Shaped PCB - solar LED light
                <h2> Motivation </h2><br />
Spring weather wakes up my desire to combine stuff I tend to enjoy. As for the plant sitting on the window sill, they grow and start blooming once the first warmer days appear and  that\'s when I thought I should design something pleasing to the eye. 

<p align=\"right\"><img style=\"max-width: 100%;\" src="https://github.com/petl/PCbee_solar_light/blob/main/images_videos/IMG_20230318_181300.jpg" alt=\"\" />Glamor shot of the final product around tulips.</p>


The thing can be bought on my tindie store as prototype:  <a href='https://www.tindie.com/products/petl/bee-pcb-pcbee-solar-led-light/'>Tindie PCbee shop.</a>  

<p><h2> Schematics </h2> </p><br /><br />

The circuit is quite straight forwardly built around the <a href='https://github.com/petl/PCbee_solar_light/blob/main/documentation/QF5252F.pdf'>QX5252</a> solar controller. It uses two brand name solar cells which provide the necessary charging current for a 1.2V 40mAh NIMh battery. The cell should be fully charged within 2h of full brightness sun, but probably takes a bit longer due to the non-ideal position indoors. <br>
After the voltage of the solar cell has fallen below 0.3·Vbatt, the controller starts the built in step-up converter feeding the blinking LEDs. Each LED has a separate resistor to be able to use different colors and mix blinking and non-blinking LEDs. With the default configuration, the battery should last for a bit more than 2.5h, practically I\'ve seen it running for 2h on my windows sill. 

<p align=\"right\"><img style=\"max-width: 100%;\" src="https://github.com/petl/PCbee_solar_light/blob/main/documentation/2023_bee_pcb_v2.png" alt=\"\" />Schematics v2 for the PCbee</p>


<p><h2> PCB </h2> </p><br /><br />

The PCB was a lot of tedious work to get it to the shape of a bee. I\'m an engineer, artsy stuff without a technical drawing and dimensions makes me uneasy. Luckily my pretty lady helped me there and together we found a contour that fits. The PCB uses a lot of layer trickery, with exposed copper, silkscreen color, solder mask color, polygon stop and strategically placed mounting holes. <br>
On the bottom there is an unreasonably expensive M3 threaded pole connector. It can be used with sharpened bamboo sticks or just any other M3 screw or rod. Feel free to post your mounting positions, I\'m curious to find out. <br> 
Due to the prototypiness, there are a bunch of additional footprints, to add extra capacitors, inductors or different controller footprints. It can even be used with an external LDR to adapt the light levels used to switch on the LEDs. <br>

<p align=\"right\"><img style=\"max-width: 100%;\" src="https://github.com/petl/PCbee_solar_light/blob/main/documentation/v2_top_bot.png" alt=\"\" />PCB screenshot top and bottom.</p><br><br>


<h2> Conclusion </h2> 

Obviously there needs to be a video, so you can also enjoy the view. 

https://user-images.githubusercontent.com/19415945/227951758-8d3980f3-9893-4360-85f1-a487ad4de044.mp4




The project itself is really interesting and in my opinion looks quite pleasing. The parts used turned out to be surprisingly expensive though. The PCB has to be manufactured at a special place due to the uncommon specs, the parts are unusual and hard to get and the solar cells only available from one supplier. This makes it a nice gift for someone really into electronics and not so much of a mass manufactured item. <br>


So that\'s that, I hope this guide didn't get too long. If you have any questions or feedback just write a message or leave a comment <3            
