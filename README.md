# Neopets AOB Codes

Array of Bytes patches for Neopets Flash games. Apply both **Find** and **Replace** for each patch using an AOB patcher on the game's SWF.

---

<a href="https://www.neopets.com/games/game.phtml?game_id=987"><img src="https://images.neopets.com/games/pages/icons/ctp/c-987.png" width="300" /></a>

<details>
<summary><b>200m Peanut Dash</b></summary>

<br>

**Power Doesnt Decrease**

> <details>
> <summary>Find</summary>
>
> ```
> 5E 9A 01 60 9A 01 2F 03 A2 68 9A 01
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 5E 9A 01 60 9A 01 68 9A 01 02 02 02
> ```
>
> </details>

**Walk Through Obstacles**

> <details>
> <summary>Find</summary>
>
> ```
> 60 B4 03 60 A0 03 66 9F 03 46 BB 05 01 76
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 27 02 02 02 02 02 02 02 02 02 02 02 02 02
> ```
>
> </details>

**Obstacle Bonus Without Jump**

> <details>
> <summary>Find</summary>
>
> ```
> 60 B3 03 46 B3 06 00 60 A5 03 AB 96
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 26 02 02 02 02 02 02 02 02 02 02 02
> ```
>
> </details>

**Always Get +10 Point Bonus**

> <details>
> <summary>Find</summary>
>
> ```
> 60 A0 03 4F FD 03 00 60 B3 03 2C 90 02 4F B7 06 01
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 60 B3 03 24 02 4F C3 01 01 02 02 02 02 02 02 02 02
> ```
>
> </details>

**Always Catch the Peanut**

> <details>
> <summary>Find</summary>
>
> ```
> 63 04 60 B4 01 12 8E 00 00
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 63 04 26 02 02 12 8E 00 00
> ```
>
> </details>

</details>

---

<a href="https://www.neopets.com/games/game.phtml?game_id=204"><img src="https://images.neopets.com/games/pages/icons/ctp/c-204.png" width="300" /></a>

<details>
<summary><b>Advert Attack</b></summary>

<br>

**Go! Button Fixed Position**

Locks the Go! button in place so it doesn't move.

> **Fixed X Position**
>
> <details>
> <summary>Find</summary>
>
> ```
> 96 04 00 04 01 08 0F 4E 96 19 00 08 10 07 B8 01 00 00 06 00 00 00 00 00 00 00 00 07 02 00 00 00 04 01 08 15 52 96 04 00 04 01 08 0F 4E 96 02 00 08 12 4E 0C 4F
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 96 04 00 04 01 08 0F 4E 96 0E 00 08 10 06 00 00 00 00 00 80 6B 40 04 01 08 0F 4E 96 02 00 08 12 4E 0C 4F 96 05 00 07 00 00 00 00 17 96 05 00 07 00 00 00 00 17
> ```
>
> </details>
>
> **Fixed Y Position**
>
> <details>
> <summary>Find</summary>
>
> ```
> 96 04 00 04 01 08 0F 4E 96 19 00 08 11 07 A0 00 00 00 06 00 00 00 00 00 00 00 00 07 02 00 00 00 04 01 08 15 52 96 04 00 04 01 08 0F 4E 96 02 00 08 12 4E 0C 4F
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 96 04 00 04 01 08 0F 4E 96 0E 00 08 11 06 00 00 00 00 00 00 54 40 04 01 08 0F 4E 96 02 00 08 12 4E 0C 4F 96 05 00 07 00 00 00 00 17 96 05 00 07 00 00 00 00 17
> ```
>
> </details>

</details>

---

<a href="https://www.neopets.com/games/game.phtml?game_id=1347"><img src="https://images.neopets.com/games/pages/icons/ctp/c-1347.png" width="300" /></a>

<details>
<summary><b>Assignment 53</b></summary>

<br>

### Cheats

**No Player Hit Damage**

> <details>
> <summary>Find</summary>
>
> ```
> D0 30 D0 66 D8 02 66 9C 06 12 71 00 00
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> D0 30 47 02 02 02 02 02 02 02 02 02 02
> ```
>
> </details>

**Unlimited Lives**

> <details>
> <summary>Find</summary>
>
> ```
> D0 66 D8 02 2A D5 66 9F 06 C1 D6 D1 D2 61 9F 06 08 02 08 01
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> D0 66 D8 02 2A D5 66 9F 06 02 D6 D1 D2 61 9F 06 08 02 08 01
> ```
>
> </details>

### Fixes

**Force Live Server Defaults**

Makes the server finder default to the live Neopets server group instead of offline/dev. This should let image/script/game asset URLs build normally from the existing code.

> <details>
> <summary>Find</summary>
>
> ```
> D0 30 5E BF 05 27 68 BF 05 5E C1 05 60 C0 05 24 00 66 A8 1B 68 C1 05 47
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> D0 30 5E BF 05 26 68 BF 05 5E C1 05 60 C0 05 24 01 66 A8 1B 68 C1 05 47
> ```
>
> </details>

</details>

---

<a href="https://www.neopets.com/games/game.phtml?game_id=527"><img src="https://images.neopets.com/games/pages/icons/ctp/c-527.png" width="300" /></a>

<details>
<summary><b>Attack of the Revenge</b></summary>

<br>

**Unlimited Lives**

> <details>
> <summary>Find</summary>
>
> ```
> 96 0E 00 07 FF FF FF FF 07 01 00 00 00 04 01 08 5B 52 17
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 96 0E 00 07 00 00 00 00 07 01 00 00 00 04 01 08 5B 52 17
> ```
>
> </details>

</details>

---

<a href="https://www.neopets.com/games/game.phtml?game_id=685"><img src="https://images.neopets.com/games/pages/icons/ctp/c-685.png" width="300" /></a>

<details>
<summary><b>Attack of the Gummy Dice</b></summary>

<br>

**Any Placed Dice Counts as Combo**

> <details>
> <summary>Find</summary>
>
> ```
> 96 04 00 04 04 08 94 4E 96 04 00 04 01 08 2B 4E 96 05 00 07 06 00 00 00 4E 96 04 00 04 01 08 2B 4E 96 09 00 06 00 00 00 00 00 00 00 00 4E 0D 48 12 12 9D 02 00 29 01
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 96 04 00 04 04 08 94 4E 96 04 00 04 01 08 2B 4E 96 05 00 07 06 00 00 00 4E 96 04 00 04 01 08 2B 4E 96 09 00 06 00 00 00 00 00 00 00 00 4E 0D 17 17 27 9D 02 00 29 01
> ```
>
> </details>

</details>

---

<a href="https://www.neopets.com/games/game.phtml?game_id=1026"><img src="https://images.neopets.com/games/pages/icons/ctp/c-1026.png" width="300" /></a>

<details>
<summary><b>Barf Boat</b></summary>

<br>

**Unlimited Lives**

> <details>
> <summary>Find</summary>
>
> ```
> D0 30 24 00 D6 24 00 D7 60 97 06 73 D6 D1 73 D7 D3 D2 0E 11 00 00 D3 60 98 06 0E 05 00 00 60 98 06 73 D7 10 10 00 00 D3 D2 0C 0A 00 00 D3 24 00 0C 03 00 00 24 00 D7 60 23 60 C1 06 D3 4F CD 0A 02 47
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> D0 30 60 23 60 C1 06 60 98 06 4F CD 0A 02 47 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02 02
> ```
>
> </details>

**Slow Petpet Slide**

> <details>
> <summary>Find</summary>
>
> ```
> 5E FB 0F 2F 11 68 FB 0F
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 5E FB 0F 24 01 68 FB 0F
> ```
>
> </details>

</details>

---

<a href="https://www.neopets.com/games/game.phtml?game_id=315"><img src="https://images.neopets.com/games/pages/icons/ctp/c-315.png" width="300" /></a>

<details>
<summary><b>Mynci Beach Volleyball</b></summary>

<br>

**Opponent Cant Move**

> <details>
> <summary>Find</summary>
>
> ```
> 96 04 00 04 01 08 0E 4E 96 06 00 08 2B 04 01 08 0E 4E 96 02 00 08 2B 4E 96 04 00 04 01 08 0E 4E 96 02 00 08 3F 4E 47 4F
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 96 04 00 04 01 08 0E 4E 96 06 00 08 2B 04 01 08 0E 4E 96 02 00 08 2B 4E 96 05 00 07 00 00 00 00 02 02 02 02 02 02 47 4F
> ```
>
> </details>

**Opponent Cant Jump**

> <details>
> <summary>Find</summary>
>
> ```
> 4E 96 02 00 08 3F 4E 96 07 00 07 01 00 00 00 08 2C 1C 96 02 00 08 54 52 96 05 00 07 0F 00 00 00 67 12 12 9D 02 00 33 00 96 04 00 04 01 08 0E 4E 96 0F 00 08 0B 06 00 00 00 00 00 00 00 00 04 01 08 0E 4E 96 02 00 08 0C 4E 0B 4F 96 04 00 04 01 08 0E 4E 96 04 00 08 0A 05 01 4F
> ```
>
> </details>
>
> <details>
> <summary>Replace</summary>
>
> ```
> 4E 96 02 00 08 3F 4E 96 07 00 07 01 00 00 00 08 2C 1C 96 02 00 08 54 52 96 05 00 07 0F 00 00 00 67 12 12 9D 02 00 33 00 96 04 00 04 01 08 0E 4E 96 0F 00 08 0B 06 00 00 00 00 00 00 00 00 04 01 08 0E 4E 96 02 00 08 0C 4E 0B 4F 96 04 00 04 01 08 0E 4E 96 04 00 08 0A 05 00 4F
> ```
>
> </details>

</details>

---
