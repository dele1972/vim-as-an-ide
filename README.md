# vim-as-an-ide

A presentation to give Vim a thought to use it like an IDE

Status: Information gathering

## Motivation

- I was on the search for a nice IDE/Editor which is less ressource intensive but you can still
  work well with it.
  - PyCharm is an awesome IDE, I love JetBrains IDEs
    - but sometimes I need multiple instances (parallel editing of Frontend and Testing Code)
      and additionally I have to run a Backend Environment with Docker and two Node Instances
      for running the Frontend and the Testing Environment.
      - at this point my Notebook is getting out of order and freezes are is becoming veeeery slooooooow.
  - Visual Studio Code was my first alternative try
    - it is hip, highly configurable, a great community
    - but for me
      - the git implementation isn't so good so I didn't get along with that
      - and the filetree is confusing for me
- During my search and customizing options for that IDEs/Editors more and more often Articles and
  Videos of using Vim appears in my search results.


## BUT VIM?!

- the purism of Vim is in the beginning scary
  - `nvim --clean`` will start Vim without any user settings
  - there is no menu bar
  - A very often asked question on the internet (google and Stackoverflow) is how to close Vim again.
- Vim comes with a total different concept like all other Editors/IDE's

## Why

- It is very fast (because it is only a terminal application without a graphical UI)
- Vim uses very few resources
- high configurable (tons of plugins available)
- a realy great git implementation (with plugins)
- a realy great community (goolge and Stackoverflow will answer nearly every question)
- I love the way of editing

cons

- yes, Vim is highly configurable - but in most cases you have to add plugins with additionally scripting
- for me its total OK, but the look of Vim is not that fancy like Visual Studio Code - its a terminal application
- learning curve?
  - "I love Vim. It’s not easy to use. I love Vim anyway."
    (Max Cantor, “How to Do 90% of What Plugins Do (With Just Vim)“, 05.10.2016)

## Because

- The Mouse: Your false best friend
  - all IDEs have huge number of shortcuts
    - I have visited multiple JetBrains Talks and viewed a lot of Videos about JetBrains IDEs
      - they are all recomment
        - keep your view clean
          - no tabs
          - distraction free mode
        - use Keyboard Shortcuts as often as possible
- But how to navigate without Mouse and possibly without Arrow Keys?
  - benefit: this will also be an issue if you work exclusively on a notebook

## How to start

Don't be scared (of the learning curve)

1. Install (Neo)Vim
2. vimtutor
3. Play [VimGolf](https://www.vimgolf.com/)

## Further on

- [“How to Do 90% of What Plugins Do (With Just Vim)“ (Max Cantor, 05.10.2016)](https://youtu.be/XA2WjJbmmoM)
- [Ultimate Vim TypeScript Setup](https://pragmaticpineapple.com/ultimate-vim-typescript-setup/)
