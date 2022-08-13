It's a strong 1v1 bot of generals.io.

It's the second generals.io bot made by zzd.

Open the html file in chrome or maybe firefox to run the bot.

Warning: There is a memory-leaking issue in this bot. The bot will use a lot of memory if it has run for a long time. So you should close and reopen the html to release the memory if it has run for over an hour.
(If your computer is strong enough and has a large memory capacity, just ignore this warning. XD)

The bot will initially be at custom room "http://generals.io/games/abcd".

The bot can only play 1v1 and it will surrender as soon as it enters a ffa or 2v2 game.

If you want to push it into NA 1v1 queue, just use play(join_1v1) in console. Warning: This action will sometimes make others feel bad, so you should think carefully before doing it.

When the bot is in 1v1 queue or it's in any custom rooms, use unjoin() to leave.

When the bot is in game:
* use Surrender() to make it surrender
* use keep_playing = false to let it not join the 1v1 queue again (use keep_playing = true, then it will automatically join the queue again).
