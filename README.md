# 👋 Xin chào! Tôi là Bao – Frontend Developer

## 🚀 Kỹ năng 

- 💻 Ngôn ngữ: HTML5, CSS3, JavaScript (ES6+), TypeScript
- ⚙️ Framework: React.js, Next.js, Vue.js (cơ bản)
- 🎨 Thiết kế: Tailwind CSS, Bootstrap, Figma (cắt giao diện)
- 🛠️ Công cụ: Git, VSCode, Chrome DevTools, npm, yarn, pnpm

---

## 📫 Kết nối

[![Facebook](https://img.shields.io/badge/Facebook-1877F2?style=flat-square&logo=facebook&logoColor=white)](https://www.facebook.com/bao.huynh.276909)  
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/baohuynh123)  
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white)](ghttps://github.com/huynhbao123)  
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:baobbbb2@gmail.com)


_“Code is like humor. When you have to explain it, it’s bad.” – Cory House_




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
