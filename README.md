___
> This build targets **SPT 4.1.2** (compatible with the 4.1.x line). It is not compatible with SPT 4.0.x.
___

#### What does it do?

In the grand tradition of making life marginally easier (and infinitely more entertaining), this mod allows you to **instantly sell items** from your inventory to traders or the flea market using a configurable keyboard shortcut combined with whichever mouse button you feel most emotionally connected to.  

By default, the universe is arranged thus:

- **Q + Left-click** → Sell to trader (the financially sensible option)  
- **Q + Right-click** → Sell on flea market (the entrepreneurial-but-risky option)  
- **Q + Middle-click** → Sell at *the best price*, as determined by arcane calculation and a faint whiff of magic  

All relevant configuration settings from the venerable **Show Me The Money** mod are automatically applied, as if by an invisible accountant lurking in the background.

If you’re using [UIFixes](https://sp-mod.com/mod/1342/ui-fixes) v5.0.2 or later (Tyfon’s delightful gift to humanity), you can even select **multiple items** and sell them all at once. When selling on the flea market, items of the same type are automatically bundled. Like socks in a dryer, except these actually stay together.

#### Requirements

- You must possess the mighty **[Show Me The Money](https://sp-mod.com/mod/2299/show-me-the-money)** SPT-mod, version **2.2.0 or newer**, without which this quick-sell addon would spend its days staring listlessly into the void.

#### SPT 4.x Installation 

Extract the contents of the `.zip` or `.7z` file into your SPT directory with all the elegance and grace of a caffeinated space hamster.

After that, you should find exactly this file in your SPT installation:
```
- C:\yourSPTfolder\BepInEx\plugins\com.swiftxp.spt.showmethemoney.quicksell\SwiftXP.SPT.ShowMeTheMoney.QuickSell.Client.dll
```

#### SPT 3.11.x Installation 

Extract the contents of the `.zip` or `.7z` file into your SPT directory with all the elegance and grace of a caffeinated space hamster.

After that, you should find exactly this file in your SPT installation:
```
- C:\yourSPTfolder\BepInEx\plugins\SwiftXP.SPT.ShowMeTheMoney.QuickSell.dll
```

##### If you use the Fika headless client

Splendidly simple advice: **do not install this mod there.** Nothing good will come from doing so. The client will ignore it, you’ll think it’s broken, and the universe will sigh. If you’re using [Corter’s Mod Sync](https://github.com/c-orter/ModSync), please add this mod to your `Exclusions.json`.

#### Configuration

Adjust all settings through the BepInEx configurator (summonable through **F12** or **F1**, assuming the stars are aligned and your keyboard cooperates):

![BepInEx Plugin Configuration](https://raw.githubusercontent.com/swiftxp-hub/spt-show-me-the-money-quick-sell/refs/heads/main/Assets/plugin-configuration.png)

#### Remarks

- Quick-selling is currently possible **only from the inventory screen**, likely because attempting to do it mid-raid would tear a hole in the fabric of space-time (and also be wildly unbalanced).

#### Known compatibility

- [UIFixes](https://sp-mod.com/mod/1342/ui-fixes) v6.0.0 or later for SPT 4.1.x by Tyfon  

---

##### Support and feature requests

All support and requests for new features will be handled as time permits, often between cups of tea and existential reflection. Please be patient. The universe is large, confusing, and full of bugs.
