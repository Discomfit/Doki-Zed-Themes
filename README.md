# Unofficial Doki Theme Port for Zed

Cute anime character themes, now in Zed. This is an unofficial port of the original Doki Theme suite from VS Code to the Zed editor.

> This project is not affiliated with or endorsed by the original Doki Theme author or project.

---

<!-- ## Theme Preview

![Astolfo Theme]()

<div align="center"> 
  <h3>Recommended Code Font: <a href="https://rubjo.github.io/victor-mono/">Victor Mono</a></h3>
</div>

--- -->

## Features

- Over **60** character‑themed color schemes, inspired by popular anime, manga, and visual novels.  
- Dark and light variants, matching the style of the original VS Code Doki themes as closely as Zed’s theming model allows.  
- Theme configuration through Zed’s `settings.json` and `theme_overrides`, so you can tweak backgrounds, accents, and syntax details.  

<!-- Example of a theme in use:

![Megumin's Theme Usage]() -->

---

## Included Series

You can pick themes based on characters from:

<details>
<summary>All Featured Titles</summary>

- AzurLane
- Blend S
- Charlotte
- Chuunibyou, Love, & Other Delusions
- Code Geass
- Daily life with a monster girl
- DanganRonpa
- Darling in the Franxx
- Doki-Doki Literature Club
- Don't Toy With Me, Miss Nagatoro
- EroManga Sensei
- Fate
- Future Diary
- Gate
- Guilty Crown
- Haikyu!!
- High School DxD
- Jahy-sama Will Not Be Discouraged!
- Kakegurui
- Kill La Kill
- KonoSuba
- Love Live!
- Lucky Star
- Miss Kobayashi's Dragon Maid
- Monogatari
- NekoPara
- Neon Genesis Evangelion
- One Punch Man
- OreGairu
- OreImo
- Quintessential Quintuplets
- Rascal does not dream of bunny girl senpai
- Re:Zero
- Rising of the Shield Hero
- Sewayaki Kitsune no Senko-san
- Shokugeki no Soma
- Steins Gate
- Sword Art Online
- That Time I Got Reincarnated as a Slime
- Toaru Majutsu no Index
- Yuru Camp

</details>

---

## Installation

1. Install Zed (latest version recommended).  
2. Clone this repository into your Zed extensions directory or follow any Zed extension installation flow you’ve set up locally.  
3. Open Zed and run `theme selector: toggle` from the command palette.  
4. Choose your preferred Doki theme from the list and apply it.  

Your selected theme will be stored in `settings.json` under the `theme` key:

```jsonc
// ~/.config/zed/settings.json
{
  "theme": {
    "mode": "system",
    "light": "Doki – Megumin Light",
    "dark": "Doki – Astolfo Dark"
  }
}
