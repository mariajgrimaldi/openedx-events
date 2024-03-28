# Repository Coverage

[Full report](https://htmlpreview.github.io/?https://github.com/mariajgrimaldi/openedx-events/blob/python-coverage-comment-action-data/htmlcov/index.html)

| Name                                                           |    Stmts |     Miss |   Branch |   BrPart |   Cover |   Missing |
|--------------------------------------------------------------- | -------: | -------: | -------: | -------: | ------: | --------: |
| openedx\_events/\_\_init\_\_.py                                |        1 |        0 |        0 |        0 |    100% |           |
| openedx\_events/analytics/\_\_init\_\_.py                      |        0 |        0 |        0 |        0 |    100% |           |
| openedx\_events/analytics/data.py                              |        8 |        0 |        2 |        0 |    100% |           |
| openedx\_events/analytics/signals.py                           |        3 |        0 |        0 |        0 |    100% |           |
| openedx\_events/apps.py                                        |       44 |        0 |       22 |        0 |    100% |           |
| openedx\_events/content\_authoring/\_\_init\_\_.py             |        0 |        0 |        0 |        0 |    100% |           |
| openedx\_events/content\_authoring/data.py                     |       51 |        0 |       18 |        0 |    100% |           |
| openedx\_events/content\_authoring/signals.py                  |       17 |        0 |        0 |        0 |    100% |           |
| openedx\_events/data.py                                        |       41 |        0 |       18 |        1 |     98% |  130->129 |
| openedx\_events/event\_bus/\_\_init\_\_.py                     |       59 |        0 |       20 |        4 |     95% |77->76, 116->115, 134->133, 184->183 |
| openedx\_events/event\_bus/avro/\_\_init\_\_.py                |        0 |        0 |        0 |        0 |    100% |           |
| openedx\_events/event\_bus/avro/custom\_serializers.py         |       61 |        0 |       32 |       16 |     83% |22->24, 23->22, 24->23, 27->29, 28->27, 29->28, 42->41, 47->46, 65->64, 70->69, 84->83, 89->88, 103->102, 108->107, 122->121, 127->126 |
| openedx\_events/event\_bus/avro/deserializer.py                |       52 |        0 |       18 |        1 |     99% |    54->65 |
| openedx\_events/event\_bus/avro/schema.py                      |       45 |        0 |       22 |        0 |    100% |           |
| openedx\_events/event\_bus/avro/serializer.py                  |       49 |        0 |       14 |        0 |    100% |           |
| openedx\_events/event\_bus/avro/tests/\_\_init\_\_.py          |        0 |        0 |        0 |        0 |    100% |           |
| openedx\_events/event\_bus/avro/tests/test\_avro.py            |       86 |        0 |       16 |        1 |     99% |  149->148 |
| openedx\_events/event\_bus/avro/tests/test\_deserializer.py    |      153 |        0 |       10 |        5 |     97% |183->exit, 233->exit, 248->exit, 253->255, 262->exit |
| openedx\_events/event\_bus/avro/tests/test\_schema.py          |       64 |        0 |        8 |        4 |     94% |243->exit, 250->253, 253->256, 256->exit |
| openedx\_events/event\_bus/avro/tests/test\_serializer.py      |      101 |        0 |        2 |        1 |     99% |  194->196 |
| openedx\_events/event\_bus/avro/tests/test\_utilities.py       |       76 |        0 |       22 |        2 |     98% |120->119, 124->123 |
| openedx\_events/event\_bus/avro/types.py                       |        2 |        0 |        0 |        0 |    100% |           |
| openedx\_events/event\_bus/tests/test\_loader.py               |       76 |        0 |       34 |       17 |     85% |18->17, 19->22, 32->37, 40->39, 41->46, 49->48, 50->58, 61->60, 62->71, 74->73, 75->84, 87->86, 88->97, 103->102, 109->exit, 121->120, 127->exit |
| openedx\_events/exceptions.py                                  |       15 |        1 |        0 |        0 |     93% |        45 |
| openedx\_events/learning/\_\_init\_\_.py                       |        0 |        0 |        0 |        0 |    100% |           |
| openedx\_events/learning/data.py                               |      141 |        0 |       36 |        0 |    100% |           |
| openedx\_events/learning/signals.py                            |       28 |        0 |        0 |        0 |    100% |           |
| openedx\_events/management/\_\_init\_\_.py                     |        0 |        0 |        0 |        0 |    100% |           |
| openedx\_events/management/commands/\_\_init\_\_.py            |        0 |        0 |        0 |        0 |    100% |           |
| openedx\_events/management/commands/consume\_events.py         |       20 |        0 |        0 |        0 |    100% |           |
| openedx\_events/management/commands/generate\_avro\_schemas.py |       38 |        0 |       14 |        1 |     98% |    90->70 |
| openedx\_events/tests/\_\_init\_\_.py                          |        0 |        0 |        0 |        0 |    100% |           |
| openedx\_events/tests/test\_consume\_events\_command.py        |       20 |        0 |       14 |        7 |     79% |17->19, 18->17, 19->18, 30->29, 49->51, 50->49, 51->50 |
| openedx\_events/tests/test\_data.py                            |       21 |        0 |       10 |        4 |     87% |33->40, 39->33, 40->39, 41->exit |
| openedx\_events/tests/test\_generate\_avro\_schemas.py         |       49 |        0 |       31 |       12 |     85% |20->19, 27->26, 30->exit, 54->53, 56->exit, 58->62, 62->56, 69->68, 74->exit, 80->79, 83->87, 85->83 |
| openedx\_events/tests/test\_producer\_config.py                |       68 |        0 |       42 |       20 |     82% |32->31, 58->60, 59->58, 60->59, 81->83, 82->81, 83->82, 100->104, 101->100, 104->108, 105->104, 108->112, 109->108, 112->118, 114->112, 118->126, 123->118, 126->exit, 134->126, 141->140 |
| openedx\_events/tests/test\_tooling.py                         |      149 |        1 |       80 |       35 |     84% |25->24, 86->exit, 89->93, 90->89, 91->90, 92->91, 93->92, 118->121, 119->118, 120->119, 121->120, 145->151, 150->145, 151->150, 160->exit, 163->165, 164->163, 165->164, 185->188, 186->185, 187->186, 188->187, 198->201, 215->214, 232->231, 261->279, 278->261, 279->278, 287->exit, 301->exit, 315->exit, 319->318, 343->exit, 368->370, 370->373, 386 |
| openedx\_events/tests/utils.py                                 |       52 |       25 |       28 |        8 |     44% |14->13, 23->22, 38->37, 42-43, 46->45, 50-51, 54->53, 61-71, 74->73, 84-94, 113->112, 117-118, 121->120, 125-127 |
| openedx\_events/tooling.py                                     |       81 |        2 |       22 |        3 |     95% |69->68, 76->75, 266, 294 |
| openedx\_events/utils.py                                       |       14 |        4 |        4 |        2 |     67% | 26-30, 32 |
| tests/test\_openedx\_events.py                                 |        2 |        0 |        0 |        0 |    100% |           |
|                                                      **TOTAL** | **1687** |   **33** |  **539** |  **144** | **92%** |           |


## Setup coverage badge

Below are examples of the badges you can use in your main branch `README` file.

### Direct image

[![Coverage badge](https://raw.githubusercontent.com/mariajgrimaldi/openedx-events/python-coverage-comment-action-data/badge.svg)](https://htmlpreview.github.io/?https://github.com/mariajgrimaldi/openedx-events/blob/python-coverage-comment-action-data/htmlcov/index.html)

This is the one to use if your repository is private or if you don't want to customize anything.

### [Shields.io](https://shields.io) Json Endpoint

[![Coverage badge](https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/mariajgrimaldi/openedx-events/python-coverage-comment-action-data/endpoint.json)](https://htmlpreview.github.io/?https://github.com/mariajgrimaldi/openedx-events/blob/python-coverage-comment-action-data/htmlcov/index.html)

Using this one will allow you to [customize](https://shields.io/endpoint) the look of your badge.
It won't work with private repositories. It won't be refreshed more than once per five minutes.

### [Shields.io](https://shields.io) Dynamic Badge

[![Coverage badge](https://img.shields.io/badge/dynamic/json?color=brightgreen&label=coverage&query=%24.message&url=https%3A%2F%2Fraw.githubusercontent.com%2Fmariajgrimaldi%2Fopenedx-events%2Fpython-coverage-comment-action-data%2Fendpoint.json)](https://htmlpreview.github.io/?https://github.com/mariajgrimaldi/openedx-events/blob/python-coverage-comment-action-data/htmlcov/index.html)

This one will always be the same color. It won't work for private repos. I'm not even sure why we included it.

## What is that?

This branch is part of the
[python-coverage-comment-action](https://github.com/marketplace/actions/python-coverage-comment)
GitHub Action. All the files in this branch are automatically generated and may be
overwritten at any moment.