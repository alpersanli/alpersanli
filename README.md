### Hello World 🌎👋

<!--
**alpersanli/alpersanli** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: alpersanli16@gmail.com
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->

  <li><a style="text-decoration:none; color:grey;" href="https://alpersanli.github.io">My Website</a></li></li>
  
  <li><a href = "mailto:alpersanli16@gmail.com"><img src="https://img.shields.io/badge/-Gmail-%23333?style=for-the-badge&logo=gmail&logoColor=blue" target="_blank"></a></li>
  
 <div>
  <a href="https://github.com/alpersanli">
  <img height="180em" src="https://github-readme-stats.vercel.app/api?username=alpersanli&show_icons=true&theme=dracula&include_all_commits=true&count_private=true"/>
  <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=alpersanli&layout=compact&langs_count=7&theme=dracula"/>
</div>
 
- uses: Platane/snk@v3
  with:
    # github user name to read the contribution graph from (**required**)
    # using action context var `github.repository_owner` or specified user
    github_user_name: ${{ github.repository_owner }}

    # list of files to generate.
    # one file per line. Each output can be customized with options as query string.
    #
    #  supported options:
    #  - palette:     A preset of color, one of [github, github-dark, github-light]
    #  - color_snake: Color of the snake
    #  - color_dots:  Coma separated list of dots color.
    #                 The first one is 0 contribution, then it goes from the low contribution to the highest.
    #                 Exactly 5 colors are expected.
    outputs: |
      dist/github-snake.svg
      dist/github-snake-dark.svg?palette=github-dark
      dist/ocean.gif?color_snake=orange&color_dots=#bfd6f6,#8dbdff,#64a1f4,#4b91f1,#3c7dd9

  env:
    # a github token is required to fetch the contribution calendar from github API
    GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
 
</div>
01100010 01101100 01110101 01100101 00100000 01100101 01101110 01100111 01101001 01101110 01100101 01100101 01110010
