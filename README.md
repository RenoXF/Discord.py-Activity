<h1 align="center">
  Discord.py Activity
  <br>
</h1>


This code for `Python`:


Setting Playing status
```python
await bot.change_presence(activity=discord.Game(name="a game"))
```

Setting Streaming status
```python
await bot.change_presence(activity=discord.Streaming(name="My Stream", url=my_twitch_url))
```

Setting Listening status
```python
await bot.change_presence(activity=discord.Activity(type=discord.ActivityType.listening, name="a song"))
```

Setting Watching status
```python
await bot.change_presence(activity=discord.Activity(type=discord.ActivityType.watching, name="a movie"))
```
