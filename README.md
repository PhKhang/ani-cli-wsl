# ani-cli

A cli to browse and watch anime.

This tool scrapes the site [gogoanime](https://gogoanime.vc).

# ani-cli-wsl

This version allows you to use it in wsl, and video output shows in mpv that's installed in windows.

## Instalation

- Install [mpv](https://mpv.io/installation/) in Windows
- go into your wsl and type:
	-  git clone https://github.com/game1men/ani-cli-wsl
	-  cd ani-cli-wsl/
	-  chmod +x ani-cli-wsl 
- now you can run it with ./ani-cli-wsl

## Usage

	# watch anime
	ani-cli <query>

	# download anime
	ani-cli -d <query>

	# resume watching anime
	ani-cli -H

Multiple episodes can be viewed/downloaded by giving the episode range like so

	Choose episode [1-13]: 1 6

This would open/download episodes 1 2 3 4 5 6

## Dependencies

* grep
* curl
* sed
* mpv (in Windows)
