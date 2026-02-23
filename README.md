# Cephalon Slowbot - Desktop 

<img align="right" src="CephalonSlowbot.png" width="200" alt="Cephalon Slowbot Logo">

Hi! Welcome to Cephalon Slowbot. This project is meant to become a linux native alternative to AlecaFrame. It's built on a JS front-end and Rust back-end with Tauri providing the overlay and is designed to be lightweight and unintrusive. As of right now, there is nothing I'm comfortable sharing with the broader community as I'd like to ensure I've got at least the base functionality online before I take this thing public.

## Features
* Relic Selection Screen Helper: It provides an overlay over the relic screen that provides you with the ducat value and plat value (based on the lowest seller on warframe.market) of your options. It also presents what components of the rest of the set you already own, and dynamically updates your inventory using your session file.
* Riven Grader and Pricer: It allows you to visualise how well your riven rolled based on its deviation from the mean roll. It also compares your rivens to ones available on warframe.market so you can get a rough price estimate, though remember that usually, if a riven's still up on warframe market it means that people don't want to buy it at that price.

## Pros and Cons

Pros: <br> It's linux native! <br> It doesn't use overwolf to read your RAM which saves your computer a fair few resources! <br> It's open-source and ad-free! <br> Despite no one having ever been actually banned for using AlecaFrame this is technically slightly less intrusive! 

Cons: <br> It's pretty much worse than AlecaFrame in every measurable way.

## Challenges

The essential problem that any warframe companion app for linux faces is that I haven't even bothered to check whether there's any way for linux to read your RAM because I frankly have no interest in having my RAM read. This means that this app will be a lot more manual than AlecaFrame can be. You'll have to manually trigger an inventory scan by navigating to your prime parts collection. If you aren't running it while in a session, you'll have to rescan it if you acquire any more prime parts. You play on another platform and get prime parts and guess what? You need to scan your inventory again. This is pretty much the reality of what a less intrusive non RAM reading alternative to AlecaFrame will always entail unless you want to try something extraordinarily stupid like polling warframe's mobile API for your inventory. 

## Community Contributions

So, because we all have to live with the reality that there's no way to match the usefulness of AlecaFrame without using something incredibly intrusive and resource heavy, I hope that the broader warframe community on both Linux and Windows can group together and brainstorm features that prevent this bot from being something that isn't a fundamentally worse AlecaFrame clone. To that end, if you'd like to contribute to the development of Cephalon Slowbot, please do feel free to join my discord in any capacity you like; be it development, testing, ideating or even just observing. You can find me here:
<br><br><a href="https://discord.gg/yctkNhnbeH">
    <img title="" src="https://cdn.prod.website-files.com/6257adef93867e50d84d30e2/66e3d74e9607e61eeec9c91b_Logo.svg" alt="Discord">
</a><br>