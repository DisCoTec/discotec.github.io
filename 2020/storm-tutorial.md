# Getting Storm for this presentation


We will use a [Docker container](https://www.docker.com/) based on
[Jupyter Notebook](https://jupyter.org/) throughout the tutorial.
You can follow along the interactive presentation and try out Storm by
yourself. Please perform the following installation steps.


## Installation steps

1. Install Docker for your OS according to [these instructions](https://docs.docker.com/get-docker/).

2. Download and start the Docker container from the command line:
`
docker run -it -p 8080:8080 --name stormpyter movesrwth/stormpyter:discotec2020
`
Please note that the download with >1GB might take a while.

3. Open the Jupyter website which is indicated in the command line and
starts with `127.0.0.1:8080/?token=...`

4. On the website, open the file `discotec_storm.ipynb`

5. The presentation should start automatically now.


## Hands-on presentation

- The presentation will be interactive. You can execute all commands by yourself!
- Navigate with spacebar and shift+spacebar.
- All interactive commands can be executed with shift+enter.
- Switch between presentation and notebook with alt+r.