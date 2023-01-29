![timer preview image](https://github.com/alessandro-somigli/java-timer-cli/blob/main/timer-preview.png?raw=true)

# java-timer-cli
Instructions to use the timer on your machine. 

You can check the project in this repository: [github.com/alessandro-somigli/java-timer-cli-project/](https://github.com/alessandro-somigli/java-timer-cli-project/)

Right now this project is only available for Windows, but Linux and Mac OS X are coming soon.

## Usage
`timer -t [number] -d [number] -s`

### Options
- `-t [number]` (timer): Specify how long the timer should run in seconds.
- `-d [number]` (delay): Specify if the timer should loop, and if so, specify the delay before restarting.
- `-s` (silent): Specify if the timer should not produce any sound when finished.

# Windows
 - download the repository
 - place it where you keep your applications installed (no /Program Files directory, since ir causes some permission issues).
 - go to the environment variables
 - add the timer to the PATH environment variable like this: C:\path\to\timer\Timer\src
 - restart your pc
 - go to the console and type `timer -t 60`. A timer of 60 seconds should start counting.

# Docker
 - download the repository and enter in the directory
 - open the terminal
 - type `docker build -t timer .`
 - type `docker run timer -t 60`. A timer of 60 seconds should start counting.

The sounds are still not working properly from docker but changes are coming soon.