Reflection HW 1

1. The steps that an HTTP request takes from a browser to my Github Pages site is that it first performs a DNS lookup to find the IP address of my Github pages site. Then, the browser sends an HTTP GET request that travels through the network until it reaches Github's servers. Once it reaches the servers it will then retrieve the files by sending the index.html and styles.css files back to the to browser. After it does this, the browser will display the website with the specified files that it retrieved from the servers.

2. A Docker Container differs from the environment provided by Github Pages because Github Pages is a static hosting environment which means it can host HTML, CSS, and Javascript files but i cannot run backend code such as python script. It also cannot use databases or contain server logic. It is mainly used for simple websites. A Docker Container, on the other hand is a virtualized environment that can package code, libraries, system tools, and the operating system setup. It is able to run servers, databases, backend code, and APIs. It is much more customizable than Github pages and allows full control of the environment.

3. I used generative AI to help me add the picture to the website since my code wasn't working. I asked the AI how to reference an image in a subfolder since the picture that I am using is in an assets folder that is outside the html file. One logic error the AI made was suggesting an absolute file path from its own environment, which I had to manually fix to a relative path (assets/web_pic.jpg) to make it work on Github.


Reflection HW 2

1. The CSS property 'flex-direction: row' places items next to each other horizontally from left to right. On the other hand, 'flex-direction: column' stacks the items on top of each other vertically from top to bottom.

2. It is important to use relative units like %, vh, or rem instead of fixed pixels because they automatically adjust to the size of the user's screen. If a user uses fixed pixels, the items will stay the exact same size which may cause them to be too large and break the layout of the website when viewing it on a smaller device such as a phone.

3. I used generative AI to help with the media query because it wasn't working at first. The prompt I gave to the AI was: "why isn't my media query max-width 768px working on my phone to stack my links". The AI pointed out that my CSS code was fine, but I forgot to add the "<meta name="viewport" content="width=device-width, initial-scale=1.0">" tag in my HTML code so the browser would know that it was on a phone.
