yo I am `Wilder`

and I am Peruvian trying to be a great developer.



![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=Call4han&show_icons=true&theme=radical)


Here a little about me:
- 📝 You can contact me by: ccasarider@gmail.com
- 🖥️ I am a universal constant
- 📚 I try to learn from everything
- 😊 Aliasses: Callahan/Wukong



[![GitHub Streak](http://github-readme-streak-stats.herokuapp.com?user=Callahan&theme=dark&date_format=j%2Fn%5B%2FY%5D&background=201E1E&border=867815&stroke=E0E0E0&ring=268586&fire=DD401D&currStreakNum=ADDD8E&sideNums=76CBD5AA&currStreakLabel=6DBADD&sideLabels=6DBADD&dates=D0D0D0)](https://git.io/streak-stats)


name: Waka Readme

on:
  workflow_dispatch: # for manual workflow trigger
  schedule:
    - cron: '0 0 * * *' # runs at every 12AM UTC

jobs:
  update-readme:
    name: WakaReadme DevMetrics
    runs-on: ubuntu-latest
    steps:
      - uses: athul/waka-readme@master
        with:
          WAKATIME_API_KEY: ${{ secrets.WAKATIME_API_KEY }}
