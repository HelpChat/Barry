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
    "name": "PluginName",
    "title": "Useful Links & Information:",
    "colour": "16725857",
    "description": "Awesome plugin!",
    "img": "https://link.to.the.img.png",
    "Words": "Need more words? Just type them",
    "Spigot": "https://www.spigotmc.org/resources/"
}
```

`name` - Plugin/Link name that supports different case.

`title` - The title of the embed (defaults to: `Useful Links & Information:`).

`colour` or `color` - Colour of the embed, suggest using something like [this](https://leovoel.github.io/embed-visualizer/) to get the right format.

`decription` - Desctiption of the embed

`img` - Direct link to an image used in the embed author spot.

`/versions/pluginname.json`
```
{
    "img": "https://link.to.the.img.png",
    "1.8": "v1.0.0",
    "1.12.2": "v1.3.4",
    "1.13.2": "v1.8.6",
    "1.14.3": "v1.9.2 - Latest"
}
```

Just need to follow the JSON format seen in the other plugins.
  - file names should be in lowercase and end in .json
  - All links need to either start with https:// or http:// for Barry to pickup
  - You can have any amount links and information, but try to only put the useful ones in.
  
Once your request is pulled a staff member will need to run an update command to get any changes made. :)
