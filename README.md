# CaratCalc
A Umamusume: Pretty Derby carat calculator. Access the website [here.](https://yuberz.github.io/caratcalc.github.io/)

## Features
- Calculates guaranteed income between banners.
- Features banners up to first banner of MANT.
- Allows customization for income (Team trials rating and monthly pass ownership).

## Caveats
- Does not currently have all banners listed.
- Does not currently account for future event income very accurately. (Has to be entered manually, and cygames could change carats earned).
- Janky site behavior in general. Lots is subject to change.

## TODO
- Add all of the upcoming banners up to JP.
- Continue to update images to English as they become available.
- Restyle the site to look better/more umamusume-like?
- Add HELP button to explain how to use the calculator and some of its eccentricities.
- Add a credit at the bottom that links to this repository.

## FAQ
### What are some of the calculator's "eccentricities"?
- The calculator uses the END date of the banner to calculate income, giving the user the best odds possible to obtain the most amount of carats from dailies and stuff before the banner ends which is realistic if you're running on a budget.
- For a similar reason, story events are calculated based on their START date. This is because you could theoretically spam stamina refills in order to finish the event on the day it's released to get the carats. Obviously, that's not realistic but it is possible.
- Certain calculations are made in a simplified way.
    - For example, the daily login bonus carats are assumed to be given on Monday, Wednesday, Friday, and Sunday with 25,25,25,75 carats respectively.
    - It also assumes that the user has JUST bought the monthly pass and includes the purchase bonus in their initial carat count, then 30 days from now it gives the +500 carats. It technically means it's desynced but it'd clutter things up to enter the "date of monthly pass purchase" to try and make it more accurate.
    - When Champions Meeting calculations occur, the options will be Graded/Open and Finals Group A/B. It will also use the 3rd place carats for each group because that's guaranteed.
- The calculator also cannot account for randomness (like random 1500 carat gifts/very small events) or "bouncing" between team trial ranks / club ranks, so the recommended thing to do in that situation is use the lower rank in order to show the "worst case scenario", and assume this is the LOWEST amount of carats/rolls you can possibly earn.
- The calculator also doesn't account for tickets from events and gifts, though that may be added as a toggle in the future-- to switch from carats only to carats + tickets. That feature is kind of strange though since I'd have to make it either wait until the user has at least 10 tickets and does like that (optimal pulling so you don't overpull on sparks) or just make it immediately spend tickets (unoptimal, but some people may do that as a desperation move).

## Credits
- All images are pulled from [Gametora](https://gametora.com/umamusume/gacha) in order to have a consistent appearance.
- Date predictions for future banners are taken from [uma.moe](https://uma.moe).
- Some carat predictions are taken from [Henry Handsome's Carat Calculator](https://www.youtube.com/@HenryHandsomeDerby).
