# A Simple OBS (browser source) Timer

A simple webpage to embed a custom timer in your video/stream.  


# Examples & Usage

  * Vanilla  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Timer/493f0d78a4c6e9070bd33fde9c5136665ce92f8a/index.html`

  * White text  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Timer/493f0d78a4c6e9070bd33fde9c5136665ce92f8a/index.html?style=font: bold 30px monospace; color: white;`

  * Rounded rectangle  
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Timer/493f0d78a4c6e9070bd33fde9c5136665ce92f8a/index.html?style=font: bold 30px monospace; color: lightgray; display: inline-block; border-radius: 5px; padding: 2px 5px; background-color: rgba(0, 0, 0, 0.5);`

  * Preload Alerts
    `https://rawcdn.githack.com/IAmSeraph/Simple-OBS-Timer/493f0d78a4c6e9070bd33fde9c5136665ce92f8a/index.html?alerts=300,false;1800,true`


# Parameters

Use `style` to customize the font, size, color, etc  
Use `bodyStyle` to customize the body of the webpage  
Use `alerts` to automatically set the alert time (in seconds)  
    e.g. `alerts={time},{notify}` add a `;` to add more alerts