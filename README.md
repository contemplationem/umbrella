# umbrella
This is my attempt to make it a little bit easier to recover when my hard drive fails. Ideally, this will function as an umbrella carried during a cloudy day, deterring future failures. We'll see how well that works out. 

Some of these files are meant for my Chromebook GalliumOS dual booting, while the file titled `setting up crostinit` is meant for the Chromebook Linux beta VM (called penguin). That's because I gave up on GalliumOS a while back. 

# get started
Run this stuff to get going, probably:
```
git clone https://github.com/radradix/umbrella.git
cd umbrella-master
chmod +x *
```
Now you can run each individual file with `./filename`. I haven't figured out how to make it just run automatically all together. I suppose I could make one big executable, but I don't feel like doing that right now.

(To run an individual file from its online source without downloading it, run `wget -O - https://raw.githubusercontent.com/<username>/<project>/<branch>/<path>/<file> | sudo bash`. Obviously, you'll need good wi-fi for that.)

Hopefully the scripts work.

# license
I like licenses, but honestly, nobody's going to use this other than me, so who cares. Do whatever you want.
