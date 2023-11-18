Free Sniper:
https://github.com/workframes/personals-sniper


UGCDrops "redrops" (puts the item on sale again) the same item when someone buys with USD. 
Find one of these groups, look at the admins/ owners and look at their groups
You should find more.
To search for individual items, they usually put /ugcdrops at the end of the title.
Since they redrop the items you can find the item you want.

Lets say I want the RSTF (red sparkle time fedora)
Found the group through the owner (https://www.roblox.com/users/1487516489/profile)
Group: https://www.roblox.com/groups/33369053/RSTF-join-ugcdrops#!/store
Store shows nothing, click see all, and select the filter "show unavailable items"
There is now 2 items, the red kippah and the red halo, both offsale. click on them
Links:
https://www.roblox.com/catalog/15319853645/The-Red-Kippah
https://www.roblox.com/catalog/15319848869/The-Red-Halo

Now lets make the config.
"cookie" is your roblox cookie.
Under items, you put it in the format of
        "item_id": max_price,
RSTF has 2 items, and i dont want to spend more than 150 robux (per item)
        "15319853645": 150,
        "15319848869": 150,
"watch_speed" is how fast the page refreshes to check.
I want it to be every second (1 second)

Final example config:


{
    "cookie": "_|WARNING:-DO-NOT-SHARE-THIS.--Sharing-this-will-allow-someone-to-log-in-as-you-and-to-steal-your-ROBUX-and-items.|_",
    "items": {
        "15319853645": 150,
        "15319848869": 150
    },
    "watch_speed": 1
}

At the last item id, dont include a , 
