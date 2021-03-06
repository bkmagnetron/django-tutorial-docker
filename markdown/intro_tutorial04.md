## intro/tutorial04

- [ ] create a `form` to `post` the user selected `choice` of a question
to the following URL:
 - `/polls/{question_id}/vote/`

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/3d112ef42bad3772a77da876f1caa23dd0c4a905),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/3d112ef42bad3772a77da876f1caa23dd0c4a905)

- [ ] increment *votes* for the user selected option

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/25348c9fdd0f306a3434619df64dc42bbdc05c58),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/25348c9fdd0f306a3434619df64dc42bbdc05c58)
- [ ] create template for *results* view, which should be like below

```
Question?

* Choice One -- 1 vote
* Choice Two -- 2 votes
Vote again?
```

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/d8e857f45f0854827f94113a0b119b05deb393fe),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/d8e857f45f0854827f94113a0b119b05deb393fe)

__Bonus:__ use [F() expressions](https://docs.djangoproject.com/en/1.10/ref/models/expressions/#f-expressions) to avoid [race conditions](https://docs.djangoproject.com/en/1.10/ref/models/expressions/#avoiding-race-conditions-using-f)

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/4142c80fb583828bf46051608f4eb82fcef4278e),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/4142c80fb583828bf46051608f4eb82fcef4278e)

- [ ] use generic views

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/5ea9faf8b2c0c46f3697e08d21f21a15bde8f771),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/5ea9faf8b2c0c46f3697e08d21f21a15bde8f771)
