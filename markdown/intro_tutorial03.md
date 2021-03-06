## intro/tutorial03

- [ ] response to the following requests by displaying `question_id`
 - *`/polls/{question_id}/`*
 - *`/polls/{question_id}/results/`*
 - *`/polls/{question_id}/vote/`*

 Tip: [Named Capturing Groups](http://www.regular-expressions.info/named.html)

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/9eaad4bcfc951ed72c17041b894b58f78559a144),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/9eaad4bcfc951ed72c17041b894b58f78559a144)

- [ ] response to the following request by displaying
latest 5 poll questions,
separated by commas,
according to publication date
 - *`/polls/`*

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/b26f352d570b99d053da891a14015111479e8d19),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/b26f352d570b99d053da891a14015111479e8d19)

- [ ] create a template to render latest 5 poll questions

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/f4553b589fc60d9b60ad817606fb35c3616706d8),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/f4553b589fc60d9b60ad817606fb35c3616706d8)

- [ ] use `render` function from `django.shortcuts` to simplify template rendering

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/a724a7dcac4e98660f3d3e6499c42d53a043451b),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/a724a7dcac4e98660f3d3e6499c42d53a043451b)

- [ ] update detail view to raise exception if the requested question `DoesNotExist`

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/0e09e7347c5faf4e1f40c7c15eaf4ded30753f42),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/0e09e7347c5faf4e1f40c7c15eaf4ded30753f42)

- [ ] use `get_object_or_404` function from `django.shortcuts` to simplify exception handling

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/ae8dbeb620431fc5509df771099ea92c870d87a5),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/ae8dbeb620431fc5509df771099ea92c870d87a5)

- [ ] update detail template to display question and its choices

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/c83c5e78efa1836c4bf8d68a1c2d4b5d1a036a85),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/c83c5e78efa1836c4bf8d68a1c2d4b5d1a036a85)

- [ ] remove hardcoded URLs to simplify changing it later

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/ec2d59cd7e74628de10525be33b7b7cf07f45eb2),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/ec2d59cd7e74628de10525be33b7b7cf07f45eb2)

- [ ] add app namespace to differentiate URL names between other apps

 [code difference](https://github.com/bkmagnetron/django-tutorial-docker/commit/eec00b0235ef9dc7f47104494191d5f52e746f35),
 [repository at this point](https://github.com/bkmagnetron/django-tutorial-docker/tree/eec00b0235ef9dc7f47104494191d5f52e746f35)
