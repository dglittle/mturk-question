mturk-question
==============

for asking questions on mturk

commands to set it up on heroku:

```
heroku apps:create mturk-question
heroku addons:add mongohq:sandbox

heroku config:set HOST=http://mturk-question.herokuapp.com
heroku config:set SESSION_SECRET=change_me

git push heroku master
```
