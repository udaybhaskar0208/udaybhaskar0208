# About me
## Hey there 👋, I'm P Uday Bhaskar

I'am a final year Electronics and Communication 
aabhi bana rha hu ruko....<br>  
cobalt
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=udaybhaskar0208&layout=compact&theme=cobalt)](https://github.com/anuraghazra/github-readme-stats)

![Uday's GitHub stats](https://github-readme-stats.vercel.app/api?username=udaybhaskar0208&show_icons=true&theme=cobalt)

<br>
```dart
// tools_I_use organized
class About extends Me { 
  const myTools = {  
    "ProgramingLanguages" : { "Java", "Dart", "C++", "C", "Python", "Javascript" },
    "OtherLanguages" : { "HTML", "CSS", "Bash", "Json", "Markdown" },
    "Database" : { "Firebase", "Sqlite" },
    "Editors" : { "Vscode", "Sublime", "Neovim" },
    "Platforms" : { "GNU/Linux", "Windows" },
    "OtherTools" : { "Git", "Figma", "Photoshop", "Gimp", "Lightroom" }
  };
}
```
<br>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=udaybhaskar0208&theme=cobalt" alt="mystreak"/>


---

### Snake animation

```
![Snake animation](https://github.com/madushadhanushka/github-readme/blob/output/github-contribution-snake.svg)
```
Use the following GitHub action yml definition:
```
name: Contribution snake

on:
  schedule: # execute every 12 hours
    - cron: "* */12 * * *"
  workflow_dispatch:

jobs:
  build:
    name: Jobs to update snake grid
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@master
        id: snake-gif
        with:
          github_user_name: madushadhanushka
          svg_out_path: dist/github-contribution-snake.svg

      - uses: crazy-max/ghaction-github-pages@v2.1.3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
```

![Snake animation](https://github.com/madushadhanushka/github-readme/blob/output/github-contribution-snake.svg)

---