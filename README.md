![Barry](https://helpch.at/resources/barry_header.png)

/Links/
Used for the `=links <plugin/service>` command.

/versions/
Used for the `=ver <plugin>` command.

Got a plugin you want to add? Feel free to submit a pull request.

**Example Templates:**

`/links/pluginname.json`
```
{
    "Description": "Awesome plugin!",
    "img": "https://link.to.the.img.png",
    "Words": "Need more words? Just type them",
    "Spigot": "https://www.spigotmc.org/resources/"
}
```

`/versions/pluginname.json`
```
{
    "img": "https://link.to.the.img.png",
    "1.8": "v1.0.0",
    "1.12.2": "v1.3.4",
    "1.13.2": "v1.8.6 - Latest"
}
```

Just need to follow the JSON format seen in the other plugins.
  - 'img' needs to be lowercase if you wish to use it. (Shows in the top left of the embed)
  - file names should be in lowercase and end in .json
  - All links need to either start with https:// or http:// for Barry to pickup
  - You can have any amount links and information, but try to only put the useful ones in.
  
Once your request is pulled a staff member will need to run an update command to get any changes made. :)
