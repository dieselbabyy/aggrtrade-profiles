# dieselbaby's custom profiles for `aggr.trade` 

This repo is a work in progress, thus far, the only such profile is the one that I have spent a slight bit of time on, perfecting it for my personal desires/likes.

**To use, simply download the json file and then load it into the templates control panel on the `aggr.trade` app.**

### Changes made/customizations added:

* Added a dual-bar crawler/ticker feature at the bottom of the window, as you can see demonstrated in the below screenshot/video.  It is modeled after the kinds of lower-third crawls you see on cable TV channels like CNBC, Bloomberg, ESPN, etc.  The upper bar contains assorted crypto prices from different assets within the top 300 (ranked by market cap) and features real-time updating and shows the logo, current price and the change over the past 24 hours, colored either in green or red depending upon the performance.  Underneath that, is a slightly slower moving ticker crawl with various news headlines that were custom aggregated from a handful of different sources for crypto-related news providers (I did my best to filter out any of the kind of BS paid promotion nonsense and "DOGE to rise 8000%" speculative garbage posts, and use only quality sources).  **Note:** Both bars are interactive; you can hover your mouse over them and it'll pause the animation and you can click on the individual crypto prices to open up a new tab/window with further information and charts, and the bottom bar will also pause and open up the linked article for the repsective headline.
* Changed the spacing and coloring of all of the different components/indicators.  This design is intended for use by those who love dark-mode, though I intend on releasing an alterate version with some different color scheming soon.  In fact, the current name "cyberpunk" is just a holdover, as it no longer really contains a cyberpunk aesthetic/color scheme IMO.
* Added some animations and flair for different events.

### Future planned changes

* Plan on adding a few more interactive features and external data sources, with more information on liquidations and open interest across the various DEX and CEX perpetuals markets and futures markets for BTC (and other pairs).
* Plan on removing the current hacked-together liquidation scroll box (which is just a reworked version of the trades scroll box/pane) and replacing it with a custom-designed, live-updating, animated tabbed pane that utilizes more of a "card" design, with tabs at the top of the pane allowing you to click to see a "Worst Wipeouts" list of the biggest liquidations over the last X days/hours, a tab with a heatmap/bubblemap type representation of the largest exchange-specific liquidation totals for the token/coin in question (BTC to start with), and the main/default tab will contain a live-updating feed that can be custom-set by the end user to show above a threshold of X dollars liquidated (e.g. over $20k, 50k, 100k, etc.) with background animations enabled and optional sound effects as well.  See below for a very early, rudimentary mockup of what this might look like, in the earliest "alpha" version possible.

--------------

More to come later, I want to save this before I forget or close the browser and not have it saved lol
