## The Marriage Couselor

The key issue in most marriages is lack of communication.

The marriage counsellor uses a non-intrusive mechanism to trigger a little less conversation and a little more action to break the barrier to communication.

- Step 1: Partner A pushes their designated button to indicate a "ready" state
- Step 2: Partner B pushes their designated button in reponse to the "ready" state
- Step 3: It's on!

It's that easy! The marriage counsellor takes care of the rest by setting mood lighting and music (based on a dropbox location) enabling quality distraction free communication

The marriage counsellor then turns all the lights off after an hour, ensuring next best action - sleep!

## Devices

You will need:
- Particle (formerly Spark) Photon, or other similar model (https://www.particle.io)
- Build as per the following Schematic
- A computer with particle-cli and VLC installed (https://github.com/spark/particle-cli)
- Wink based lighting setup
- IFTTT recipe

### Installation/Usage
#### Laptop for Music
`npm install -g particle-cli`
- Install VLC

`brew cask install vlc`

- Run run.py on your Laptop
 
`python run.py`

#### Particle for the Device Interface
- Copy marriagecouselor.ino for your device under https://build.particle.io/

#### Wink App Settings
WIP

#### IFTTT
WIP

#### Circuit Schematic
WIP - schematic diagram

### Testing
- Use the Particle publish messages to test
```particle publish "message"```
```particle publish "play_music"```
