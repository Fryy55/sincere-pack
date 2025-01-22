# Sincere pack
Sincere pack because phantom thought it's funny 👍

Download the latest version from [releases](https://github.com/Fryy55/sincere-pack/releases).

> [!NOTE]
> This texture pack is extra compatible with Adya's `Godlike Faces`
>
> (not yet but it's in the works)

Bonus: rename `pack_wtf.png` in the pack's folder to `pack.png` to get a funnier pack icon.

## Table of contents

- [Installation](#installation)
	- [Default pack](#default-pack)
	- [Adding to your texture pack](#adding-to-your-texture-pack)
- [Known issues](#known-issues)
- [License](license)

## Installation

> [!IMPORTANT]
> The texture pack is made for `High` texture quality _only_ (aka `-uhd`). If you're unsure about what quality you're using - ignore this message. Otherwise, to make it work with other qualities you need to manually resize source textures and implement them into your/default spritesheet - the process of sheet editing is explained in [#Adding to your texture pack](#adding-to-your-texture-pack). If you want to do translate this pack to other qualities - this is your chance to contribute! Open a PR with these changes and I'll merge it if it works.

## Default pack
If you're not using any other texture pack **or if your texture pack does NOT have a file `GJ_GameSheet03-uhd.png`** there's a pre-made pack for the latest GD version found in [releases](https://github.com/Fryy55/sincere-pack/releases). Just download the `Sincere.pack.zip` file found in Assets.

You need to install it as you would install all other packs - install the `Texture Loader` mod from Geode, drop the texture pack into your `packs` folder (either as a `.zip` file or unzip it and put the `Sincere pack` folder there instead) and enable it.

## Adding to your texture pack
In case you're already using a texture pack **that HAS the `GJ_GameSheet03-uhd.png` file** and want to merge it with Sincere pack, the process is a bit more complicated than just downloading and installing it - you need to modify a spritesheet.

"But couldn't you make it override specific sprites with Alpha's `Happy Textures`???" - No, I couldn't. Level difficulties use _batch nodes_ for sprite creation, and these pull textures directly from static spritesheets, so the majority of textures then just wouldn't work.

I'll be modifying [my own texture pack](https://github.com/Fryy55/fryy_55-pack) as an example, so just follow along with your pack. In order to merge your packs you still need to download the latest version from [releases](https://github.com/Fryy55/sincere-pack/releases). Once you've done it, unzip the file and you should end up with this folder:

(image here)

You can rename the pack's folder to whatever you want to distinguish between your version and a default one - I'll rename it to `Sincere Fryy_55 pack`

(image here)

Inside the `sincere stuff` folder you can find all source sprites of the texture pack. Now go to GD Colon's website [GD spritesheet splitter](https://gdcolon.com/gdsplitter/) and follow these steps:

1) Click `Merge sprites` and import all **34** source sprites.

(2 images here)

2) Click `Continue!` -> `Make from base .plist`.

(2 images here)

3) Upload `GJ_GameSheet03-uhd.plist` and `GJ_GameSheet03-uhd.png` files **FROM YOUR TEXTURE PACK** as `Base .plist` and `Backup sheet`. If your texture pack doesn't have a `GJ_GameSheet03-uhd.plist` file just use the one from your GD's `\Resources` folder.

(x images here)

4) Click `Create spritesheet!`.

(image here)

5) Download your sheet and re-download the `.plist` with the buttons below (you can use the old `.plist` from your texture pack as well, I'll re-download it for demonstration.

(x images here)

6) Move these 2 files to your modified pack's folder and _chose to replace all files_.

(x images here)

7) Enable your new texture pack!

(x images here)

## Known issues
### **Rated lists' difficulties don't align with the featured background**
 
(image here)

Won't fix. This seems too tedious and unimportant enough to not care.

Consider it a feature - sincerelies now have a shadow! If you actually care enough to fix it - open a PR and I'll merge it if it works.

## License

This project is distributed under the **MIT license**.

See `LICENSE` for permissions, conditions and limitations.
