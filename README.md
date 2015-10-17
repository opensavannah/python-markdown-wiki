# Python Markdown Wiki for Heroku
---

[Heroku][1]에서 바로 올려서 쓸 수 있는 [Markdown][2] [Wiki][3]가 필요해서 만들어보았습니다.

별 기능 없지만 차차 추가하겠습니다. 필요한 기능은 이슈에 올려주시거나 Pull Request 보내주세요.

# How to Use
---
Terminal에서 아래와 같이 치면 바로 쓸 수 있습니다.

    $ git clone git@github.com:shinvee/python-markdown-wiki.git
    $ heroku create NAME --stack cedar
    $ git push heroku master
    $ heroku run python create_db.py

# 제공하는 기능
---
 - [Bootstrap][4]로 디자인
 - [Markdown]으로 내용 작성
 - `[[Topic]]` 문법 추가. `[Topic](/Topic)`으로 바꿔줍니다.

  [1]: http://heroku.com/
  [2]: http://en.wikipedia.org/wiki/Wiki
  [3]: http://daringfireball.net/projects/markdown/
  [4]: http://getbootstrap.com/
