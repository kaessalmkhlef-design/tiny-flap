# Tiny Crumbs: CrazyGames application

CrazyGames publishes browser games and shares the ad money they earn with the developer. You apply by uploading your game through their developer portal. They review it and decide whether to publish it.

Their rules and form fields change from time to time. If anything below doesn't match what the form asks for, follow the form.

## Before you apply

- Make a developer account at https://developer.crazygames.com.
- Payouts need payment and tax details, and usually someone 18 or older on the account.
- Read their **Game requirements** page in the portal before submitting. Two things to check there:
  - **Their SDK.** CrazyGames has its own SDK (a small script) for ads and saving. Games usually start without it and add it later if CrazyGames wants to publish them fully. If they ask for it, send the requirements to Claude and it can be added.
  - **Outside requests.** The game loads its fonts from Google Fonts. If CrazyGames asks for a fully self-contained game, the fonts can be built into the file. The game also works without them, falling back to built-in fonts.

## Files in this folder

| File | Use it for |
|---|---|
| `tiny-crumbs-html5.zip` | Game build (HTML5, `index.html` at the top level) |
| `images/cover-landscape-1920x1080.png` | Landscape cover |
| `images/cover-portrait-800x1200.png` | Portrait cover |
| `images/cover-square-800x800.png` | Square cover |
| `images/screenshot-*.png` | Extra screenshots, if asked |

## Answers for the form

| Field | Answer |
|---|---|
| Game title | Tiny Crumbs |
| Engine | HTML5 (plain JavaScript and Canvas, no engine) |
| Category | Clicker |
| Tags | Clicker, Idle, Incremental, Casual, Cookie, 1 Player |
| Orientation | Both (plays in landscape and portrait) |
| Mobile support | Yes |
| Languages | English |
| Multiplayer | No |
| In-game purchases | No |
| Ads in the build | No (none yet) |
| External links in the game | None |
| Saving | Automatic, in the browser (localStorage) |
| Uses AI-generated content | Yes: the code was written with an AI assistant. The game's design and balancing are by the developer. |

### Short description

> Bake cookies, hire helpers and rebirth for Golden Crumbs in this cozy clicker.

### Full description

> Tiny Crumbs is a cozy clicker set on the lid of a butter-cookie tin. Tap the cookie to bake, then spend your cookies on helpers who bake for you, from Tappers with wooden spoons to a full Cookie Lab.
>
> Every helper you buy is stronger than the last. Level up Stronger Hands for bigger clicks, with bonus jumps at levels 25, 55 and 85. Unlock upgrades that multiply your production, and catch gilded biscuits for Oven Rush, Hot Hands or a Windfall of cookies.
>
> When you're ready, rebirth for Golden Crumbs: a permanent bonus that makes every new run faster. Spend them on Refined Recipes to make every upgrade stronger.
>
> Progress saves automatically, and your helpers keep baking while you're away.

### Controls

> Click or tap the cookie to bake. Click items in the price list to buy them. Keyboard: Tab to the cookie and press Enter or Space.

## After you submit

- Reviews can take a few weeks. Test the uploaded build in their preview first, on a phone too if you can.
- If they reject it, the email usually says why. Send it to Claude and it can fix what they asked for.
- Don't publish the same game on other ad-based game sites while CrazyGames is reviewing it. Some sites ask for a period of exclusivity. itch.io is usually fine, but check their terms.
