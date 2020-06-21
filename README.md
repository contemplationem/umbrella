# umbrella

Hello, future me! 

This is my attempt to make it a little bit easier to recover when my hard drive fails, which it does at least every other day these days. Ideally, this will function as an umbrella carried during a cloudy day, deterring future failures. We'll see how well that works out. 

Download everything using that green "Clone or Download" button at top right, and unzip with `unzip umbrella-master.zip`. Then cd into the `umbrella-master` directory created by the unzipping, and `chmod +x` everything so that they're all executable. Except the readme; you don't have to chmod that. At that point, you can run each individual file with `./filename`. I haven't figured out how to make it just run automatically all together. I suppose I could make one big executable, but I don't feel like doing that right now.

(To run an individual file from its online source without downloading it, run `wget -O - https://raw.githubusercontent.com/<username>/<project>/<branch>/<path>/<file> | sudo bash`. Obviously, you'll need good wi-fi for that.)

Hopefully the scripts work. 
