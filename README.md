# LoL-Grubs

![voidgrubs.jpg](attachment:voidgrubs.jpg)

(Image source: Riot Games)

In January 2024, the video game **League of Legends** (LoL) moved to Season 14. Each season brings new changes to the competitive metagame, such as item reworks, map modifications, balance changes, and new objectives to obtain each game. One of the new objectives to be added this season is known as [**void grubs**](https://leagueoflegends.fandom.com/wiki/Voidgrub_camp). As of patch 14.6, 3 grubs spawn at the 5:00 minute mark, then another 3 spawn 4 minutes after the first grub camp is taken. Each grub taken grants extra damage to towers to the team that takes them. Grabbing 5 or 6 grubs will spawn 1 or 2 [**void mites**](https://leagueoflegends.fandom.com/wiki/Voidgrub_camp#Voidmite) respectively when hitting towers, which are especially useful in building large pushes.

However, void grubs spawn on the opposite side of the map as [dragons](https://leagueoflegends.fandom.com/wiki/Dragon_pit_(League_of_Legends)), another game-defining objective. Furthermore, grubs require a lot of time to complete, often requiring help from other teammates to defend their jungler as they take the grubs. Therefore, understanding the impact of prioritizing or a*void*ing grubs is incredibly important in mastering the game. As a jungle main myself, I am curious to see the effect of the new objective on the metagame. Specifically,

**What effect does obtaining grubs have on the outcome of the match?**

---

This dataset from [Oracle's Elixir](https://oracleselixir.com/tools/downloads) contains all professional matches played in 2024 so far, including players and team results. The description of the relevant columns are:
- `league`: which professional league the match was played in
- `teamname`: name of the professional team
- `result`: the result of the game. `1` means a win, while `0` means a loss.
- `playoffs`: whether or not the game was played during playoffs. `1` means yes, while `0` means no.
- `void_grubs`: the number of void grubs taken by that team
- `opp_void_grubs`: the number of void grubs taken by the opposing team
- `heralds`: whether or not a team took the [rift herald](https://leagueoflegends.fandom.com/wiki/Rift_Herald/LoL). `1` means the team obtained the rift herald, `0` means they did not.
