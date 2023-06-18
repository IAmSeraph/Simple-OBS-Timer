# A Simple OBS (browser source) Timer

A simple webpage to embed a custom timer in your video/stream.  

# Other projects like this

[Simple-OBS-Overlay](https://github.com/IAmSeraph/Simple-OBS-Overlay.git)
[Simple-OBS-Clock](https://github.com/IAmSeraph/Simple-OBS-Clock.git)

# Examples & Usage

  * Vanilla  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Timer/c9c298c86ec7b57939d76a2dbef567a0cc2e8d17/index.html`

  * White text  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Timer/c9c298c86ec7b57939d76a2dbef567a0cc2e8d17/index.html?style=font: bold 30px monospace; color: white;`

  * Rounded rectangle  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Timer/c9c298c86ec7b57939d76a2dbef567a0cc2e8d17/index.html?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5);`

  * Preload Alerts  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Timer/c9c298c86ec7b57939d76a2dbef567a0cc2e8d17/index.html?alerts=300,false;1800,true`


# Parameters

Use `style` to customize the font, size, color, etc  
Use `bodyStyle` to customize the body of the webpage  
Use `alerts` to automatically set the alert time (in seconds)  
    e.g. `alerts={time},{notify}` add a `;` to add more alerts
