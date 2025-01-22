# Sincere pack
Sincere pack because phantom thought it's funny 👍

![Example](https://github.com/user-attachments/assets/d668056a-4811-4a5f-bf51-a91e66e74cc4)

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

![Sincere pack's folder](https://github.com/user-attachments/assets/638e2b6a-2e8c-4df8-b916-96b894d854c5)
---

You can rename the pack's folder to whatever you want to distinguish between your version and a default one - I'll rename it to `Sincere Fryy_55 pack`

![Renamed Sincere pack](https://github.com/user-attachments/assets/cef02353-3c19-49ff-885b-7c1ea542aa7e)
---

Inside the `sincere stuff` folder you can find all source sprites of the texture pack. Now go to GD Colon's website [GD spritesheet splitter](https://gdcolon.com/gdsplitter/) and follow these steps:

### 1) Click `Merge sprites` and import all **34** source sprites.

![sincere stuff folder](https://github.com/user-attachments/assets/32cc4188-7e16-40a0-a835-87ec7b632760)
---
![Merge sprites button](https://github.com/user-attachments/assets/95b58c37-221c-4e20-be48-0a58f04ac714)
---
![Uploaded sprites](https://github.com/user-attachments/assets/be96fb9b-0de0-4418-962d-d04ce58eb367)
---

### 2) Click `Continue!` -> `Make from base .plist`.

![Continue button](https://github.com/user-attachments/assets/ae148330-75dd-4b79-9f35-f1e318fd3a0d)
---
![Make from base .plist button](https://github.com/user-attachments/assets/f8f250f3-1dc8-430d-9548-05107dc11709)
---

### 3) Upload `GJ_GameSheet03-uhd.plist` and `GJ_GameSheet03-uhd.png` files **FROM YOUR TEXTURE PACK** as `Base .plist` and `Backup sheet`. If your texture pack doesn't have a `GJ_GameSheet03-uhd.plist` file just use the one from your GD's `\Resources` folder.

![Files to upload](https://github.com/user-attachments/assets/28e9a227-dace-42f4-ab5e-7b57954d7867)
---
![Final configuration](https://github.com/user-attachments/assets/ccf21a4b-c079-4f21-a823-fb20d197c500)
---

### 4) Click `Create spritesheet!`.

![Create spritesheet button](https://github.com/user-attachments/assets/f300f93a-3882-4ecf-9657-589e599fdbcb)
---

### 5) Download your sheet and re-download the `.plist` with the buttons below (you can use the old `.plist` from your texture pack as well, I'll re-download it for demonstration.

![Download buttons](https://github.com/user-attachments/assets/15fb76a2-59d7-435f-8f84-38811f971e70)
---

### 6) Move these 2 files to your modified pack's folder and _chose to replace all files_.

![Move the files](https://github.com/user-attachments/assets/7665a5e3-4684-4101-804c-13a1b35b3b52)
---
![Replace the files](https://github.com/user-attachments/assets/41fc4bdd-6c03-4ff0-9058-863c9e56d6a7)
---

### 7) Move and enable your new texture pack!

![Move the texture pack](https://github.com/user-attachments/assets/f670dc6a-cbb6-4b8f-b210-59976f34d814)
---
![Enable the texture pack](https://github.com/user-attachments/assets/b4a56f71-a8f8-4b36-8f3e-6eedba7b19d6)
---
![Enjoy!](https://github.com/user-attachments/assets/adf94e02-a93f-4a12-8072-0ff7ef40b042)

## Known issues
### **Rated lists' difficulties don't align with the featured background**
 
![Issue #1](https://github.com/user-attachments/assets/2667c5f4-1c77-43dd-8df8-3d084f1bad49)

Won't fix. This seems too tedious and unimportant enough to not care.

Consider it a feature - sincerelies now have a shadow! If you actually care enough to fix it - open a PR and I'll merge it if it works.

## License

This project is distributed under the **MIT license**.

See `LICENSE` for permissions, conditions and limitations.
