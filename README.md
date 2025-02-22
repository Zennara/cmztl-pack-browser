# How to Create a Pack:
- Download the example pack.
- Edit `Textures.png` to your desired textures.
- Edit `Icon.png` to your desired icon.
  - *Must be 256 x 256 pixels, or it will be cropped.*
- Edit `PackInfo.xml` with your pack information.
  - *Currently there is no support for Metal or Diffuse textures, and `UseSimpleShaders` should always be `True`.*
- Zip the folder (see below)

### PackInfo.xml Details
```xml
<PackInfo>
  <PackName>Example Pack</PackName> <!-- The pack name, variable screen length limit -->
  <PackAuthor>Zennara</PackAuthor> <!-- Who made the pack, variable screen length limit -->
  <PackDate>02/22/2025</PackDate> <!-- The date the pack was last updated. mm/dd/yyy format required -->
  <PackDesc>An example pack. Use this to make your packs!</PackDesc> <!-- The pack description- cut off after 5 lines on screen -->
  <UseSimpleShaders>true</UseSimpleShaders>
</PackInfo>
```

### Example Folder Structure:
- Example_Pack.zip
  - Example Pack (folder)
    - PackInfo.xml
    - Icon.png
    - Textures.png

# Adding a Pack to the In-Game Browser
Send your pack [here](https://discord.com/channels/566984586618470411/1110001959840272435) for review. [Discord Invite](https://www.discord.com/invite/cJH7DFb)
Once accepted, I will add it to `packs.json` and it will be instantly available for all players to use!
