---
---

# SKHS Game Design & Programming Playtests

After you have built your game, publish it by adding your game in the ```Games``` folder and creating a link to your game on the playtest page, ```index.md``` in this repository.

To do this:

1. **Fork this repository** so that you have a copy to work with.
1. **Clone your fork to your computer** so that you can add your game.
1. But first, **click on the index.md file** and explore a bit to see how it works.
1. Then **click on the edit pencil** so you can see the HTML and Markdown coding of the file. You will see that each game is wrapped in a set of HTML ```<details>...</details>``` tags that look something like this:

``` html
<details>
  <summary markdown="span">
    Defender
  </summary>
  
  * [Defender: Doug Urner](https://douglasurner.github.io/prototypes/Defender/index.html) --- I modified this
    game to use the night sky background, I thought that that would look better with the laser. The next thing
    I want to fix is the way the game ends.
  
</details>
```

This file is a mixture of Markdown and HTML. Each section consists of some HTML markup to create the collapsing sections around a Markdown list of games. You will be adding an entry to the list for your game. Your entry will look like this:

``` markdown
* [GAME_NAME: YOUR_NAME](GAME_URL) --- Short description of your game.
```

4. After you have edited the `index.md` file in your fork of the Playtest repository, **commit the changes and test that the link to your game works.**
1. When every thing looks good and is working, **create a pull request**:
   - **Click on the `Pull requests` tab** near the top of the page --- it's between `Issues` and `Projects`.
   - On the right, **click on the green `New pull request` button**.
   - **Enter a description of your pull request.**
   - **Click on the Create pull request button.**
