# Quarter Section

**A family, a homestead, a century.** 1890 to 2060, one household on 160 acres, and a clock
that stops to ask.

A standalone historical life-sim by **Raven Iron**. The source lives in a separate private
repository; this one holds **releases only**.

Made for Skadi.

---

## Play it

- **In the browser:** <https://ravenirongames.com/play/quarter-section/>. Chrome, Edge or Firefox
  on a desktop. About 17 MB loads once; nothing is installed, and the page takes each new build on
  its own, so reload if the title still names an older version.
- **On Windows:** grab `QuarterSection-<version>-windows.zip` from
  [Releases](https://github.com/RavenIron-Games/QuarterSection/releases/latest), unzip anywhere and
  run `QuarterSection.exe`.

The build is not signed, so Windows may show *"Windows protected your PC"*: click **More info**,
then **Run anyway**.

**Saves are per family**, one slot each. In the browser they live in this site's storage; on Windows
they are files under `%USERPROFILE%\AppData\LocalLow\Raven Iron\Quarter Section\quarter-section.saves`.
While the game saves itself, which the settings menu can turn off, a save is written at every
season's start, after every answered card, and, on Windows, when you leave. **Save the game** writes
one whenever you like, whether or not that is on. Every save from 0.8 onward is brought forward.

**Clearing this site's data clears the browser saves with it.**

---

## What it is

A quarter section is the 160 acres a family got under the Homestead Act, if they could hold it.
You get one in 1890: a log house, a well, an outhouse, three plots, and a town a day's walk away.
Every decade after gives a little more.

**The 1890s are meant to hurt.** Water is carried by the bucket, the housework takes half of every
day, and a birth or a fever with the man away in town can undo a year. Then the doctor comes to
town, the car cuts the road to three hours, the wire reaches the street, and the century's own
troubles arrive on schedule: the flu of 1918, the crash, the wars, the long summer.

**The land is yours to add to, or to part with.** Five years' residence earns the patent. From then
the build list offers the north forty for cash and the west forty for sale at four-fifths of what
the acres are worth, and once a decade a neighbour quits and offers their forty on a note: a third
down, the January payment taken before the county's due, and three missed Januaries in a row and the
note is called in and the parcel goes back. Tax follows the acres you hold, and the estate's worth
sits on the place line.

**The ground pays in money.** Break the prairie, at 45 hours an acre by hand and 12 behind a team,
and sow winter wheat: drilled from mid September, standing ripe on 15 June, cut in a window that
shuts on 10 July, threshed until the end of August. What is not cut in its window is lost for the
year. An eighth build track runs from the walking plough to the autonomous rig, each rung cutting
the hours an acre takes, and a machine's keep runs at about a seventh of its price a year, which is
what makes buying it before you have the acres a trap.

**The cart asks what goes on it.** Name the bushels of wheat and the days of food and the prompt
tells you what the load fetches and the hours the road takes out of the days that follow. Since
0.12.0 a named sale may run to several loads, capped by the hands you can spare before the next
weekly trip; since 0.12.4 the sale pays the fare, so an empty tin can still send its cellar to town.

**The clock stops to ask.** A fever, the first snow with the pile short, the harvest week with a
thin larder, the county's due the tin could not cover. The game stops and offers one to four
answers, each priced in what the house actually holds. Every birth can be named; every death is
noted, with its cause and its cost.

**The household keeps your standing orders.** How much wood to hold on the pile, how many hours a
day for game and fish, what a trip tops the larder up to, the cash the tin must not go below, the
acres in the cash crop, the acres of prairie to break each spring, whether spare hours mend the
house or clear another plot, and whether the family takes the children as they come or stops at so
many. Set them once at the foot of the settings menu and the household runs them until you change
them. A family that has the children it wants holds back by restraint until the 1960s birth-control
rung, which fails about one year in ten, and by birth control after it, about one year in nineteen.

**The settings menu is yours, not the family's.** Escape opens it while you are playing, and closes
it anywhere. The speed the clock goes back to after a card or a season's morning, whether new
families stop at each season, whether the game saves itself, the text and panel size from 85% to
130%, full screen, and the list of saved families with where they live. There is no OK and no
Cancel: every change is written the moment it is made.

**The numbers are real.** Every wage, price and tax is a published series in constant 1890
dollars: a farm hand's day, a gallon of kerosene, 160 acres of county tax, a doctor's call, the
Model T. The people are not; every name comes from a list.

---

## This is an alpha

Every run is reproducible from its number.

### How to report a problem

Open an issue with three things from the title and naming screens, and what happened:

- the **version**, in the title screen's corner and at the foot of the settings menu
- the **land's number**, the number you gave the family
- the **year**

> *"0.12.4, land 17, 1903, the county's due card said I owed twelve dollars I had"*

That is enough to replay the exact run.

If a saved family will not open, the settings menu lists it anyway, with the reason underneath, and
its **Copy** button puts the raw save text on your clipboard. That is the only way a browser
player's century can reach us, so paste it into the issue.

Also welcome: where it was boring, where a card asked something you had no way to judge, and what
you wished the household could do. The 1890s are meant to hurt, so say if they hurt for a reason
that felt unfair.

---

## Versions

| Version | Date | What changed |
|---|---|---|
| 0.12.4 | 2026-09-08 | The sale pays the fare: a cart with something to sell goes from an empty tin. The books close, the trip line is honest, and the title carries a dedication. |
| 0.12.3 | 2026-09-08 | The children's order is a tick-box and a count. Nought means no more, and the order holds in every decade. |
| 0.12.2 | 2026-09-08 | The browser player starts at a 256 MB heap, which fixed the crash on 0.12.1. |
| 0.12.1 | 2026-09-08 | The log bar at the foot of the screen grew, with its text a size up. |
| 0.12.0 | 2026-09-08 | A named sale may run past one cartload. |
| 0.11.0 | 2026-09-08 | The cart asks what goes on it, the standing orders move into the settings menu, and a hundred acres of prairie a spring. |
| 0.10.0 | 2026-09-08 | The field: prairie broken, winter wheat sown, and an eighth build track of machinery. |
| 0.9.1 | 2026-09-07 | Continuing a long game draws the interface again. No save was ever corrupt. |
| 0.9.0 | 2026-09-07 | The estate: land bought, sold and mortgaged, a settings menu, and saves per family. |

---

More at [ravenirongames.com/games/quarter-section](https://ravenirongames.com/games/quarter-section/).
