# Animal Grill 🍔🐱

A cute pastel restaurant game. You're the chef cat — walk around your grill, cook
burgers, fries, soda and milkshakes, and serve every hungry animal that comes through
the door.

**▶ [Play it here](https://swinktxut.github.io/animal-grill/)**

## How to play

- **Move** with the arrow keys or `WASD`. On a tablet or phone, touch and drag anywhere
  on the floor and your cat walks toward your finger.
- **Cook** by walking up to a machine with a bouncing `!` — it starts by itself.
- **Serve** by scooping food off the pick-up counter (you can carry 3) and walking it
  over to a hungry animal, or to the drive-thru window for a car.
- **Grow** the place: more tables, more machines, more crew.

## Things to try

- Set your own prices — each menu item has its own demand, so cheap food is popular and
  pricey food earns more per sale. Ingredients cost money, so what you keep is the price
  minus the food cost.
- Watch the **Pantry**. You buy ingredients before you cook with them, and an empty shelf
  takes that food off the menu until you restock. Better **suppliers** make it cheaper forever.
- Sign a **branding deal**. Animal businesses pay to put their name in your restaurant —
  you pay a one-off fee, it runs 30 days, and it only brings extra customers if it genuinely
  suits you. Check the fit meter first.
- Learn who likes what: dogs love burgers, bunnies love fries, hamsters love soda and cats
  love milkshakes — and each of them turns their nose up at something too.
- Hire **cooks** to run machines, **waiters** to carry food to tables, and **drive-thru
  staff** to serve cars.
- Buy a **Milkshake Machine** to unlock milkshakes, and a **Drive-Thru** for a second
  stream of customers who never need a table.
- Every 30 days, crown one of your crew **Employee of the Month** — they get a gold
  crown and work faster for the next 30 days.
- Open and close whenever you like in Settings ⚙️. Longer days earn more but take
  longer to play.

## Notes

Single self-contained HTML file — no build step, no external assets, no dependencies.
All the art is drawn with Canvas 2D and the music is synthesised with the Web Audio API,
so it works offline. Progress auto-saves to `localStorage`.

Installable to your Home Screen on iPad/iPhone and Android (manifest + service worker),
after which it runs fully offline.
