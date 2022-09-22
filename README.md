## Snipe-It on Docker Compose

# Setup

First Clone and extract the archive.

Then open a terminal and CD into the newly extracted folder.

You will need to change the app url in the `env_file`, the default is `http://127.0.0.1` (This should work if you don't plan on running it externally, I recommend setting it as a dns entry such as "snipeit.example.com".  It makes it much easier that way if you need to move your machine.)

Then once all is in order in the env_file all you have to do is run the command 
```docker-compose up -d```

This should bring you to the default setup page and you should be set
