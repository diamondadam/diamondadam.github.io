<head>
    <meta charset="UTF-8">
    <link rel = "stylesheet"
          type = "text/css"
          href = "main.css" /><title>My Projects</title>
</head>

<div class="dropdown">
    <button class="projects">Menu</button>
    <div class="dropdown-content">
        <a href="https://diamondadam.github.io/">About Me</a>
        <a href="https://diamondadam.github.io/myprojects">My Projects</a>
        <a href="https://diamondadam.github.io/contact">Contact Me</a>
    </div>
</div>

# My Projects 

##### [Data Entry Android Application](https://github.com/diamondadam/CustomTool)
In the above repository I built an android application to interact with a workplace server for logging times. For instance, in the particular manufacturing shop this was designed for, there were barcodes on workplace documents designating operations to be logged into. With this application a user would be able to simply scan a barcode and log in remotely, rather than using a terminal that could be a significant distance away. I created this in the hopes that workers would more accurately record job times, since previously they would not. [Example Screens can be found here.](https://diamondadam.github.io/contact)

##### [Server File](https://github.com/diamondadam/DataCollectionServer)
This is the server program, that would handle the requests sent by the application. For security reasons, I was not allowed to interact with the onsite database directly and had to resort to using a Seleium Web Driver to interact with the web application that was available. In addition, it would obtain job descriptions and parse them into features for a machine learning algorithm.

##### [Data Analysis Program](https://github.com/diamondadam/DataAnalysis)
This program connects with the database on the server. It then encodes the various features as integers and uses k-closest neighbors to find the most similar part previously ran. Using this I was able to estimate the setup and runtimes for various parts based just off of their features.
