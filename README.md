# YTTV
Simple app for fast  forwarding to Twitch or Youtube

You can use it for example on Raspberry pi

How to download (on Raspbian):

- sudo apt install apt-transport-https dirmngr gnupg ca-certificates
- sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 3FA7E0328081BFF6A14DA29AA6A19B38D3D831EF
- echo "deb https://download.mono-project.com/repo/debian stable-raspbianbuster main" | sudo tee /etc/apt/sources.list.d/mono-official-stable.list
- sudo apt update
- sudo apt install mono-devel

And use "Launcher.sh" to open app (you must edit that file if .exe file isn't on Desktop)

On Windows you must to download .exe file
