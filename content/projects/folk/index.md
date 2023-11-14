---
title: Folk
summary: |
  Folk provides easy access to datasets that can be used to benchmark machine learning algorithms. The    goal of Folk is to facilitate and encourage work on fair machine learning among R users.
date: 2023-11-14
categories:
  - R package

links:
  - icon: github
    icon_pack: fab
    name: source
    url: https://github.com/george-wood/folk
---

Folk provides easy access to datasets that can be used to benchmark machine learning algorithms. The goal of Folk is to facilitate and encourage work on fair machine learning among R users.

The Folk package has three key features:

| Feature      | Description                                                                                                                                                                                                                                                                                 |
|--------------|---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| `get_()`     | The `get_()` functions provide easy access to data. Currently, there is only one `get_()` function, `get_acs()`, which provides access to the US Census Bureau’s American Community Survey's [Public Use Microdata Sample](https://www.census.gov/programs-surveys/acs/microdata.html). |
| `set_task()` | The `set_task()` function preprocesses data for pre-defined prediction tasks. Pre-defined tasks can be viewed with `show_tasks()`.                                                                                                                                                          |
| `new_task()` | The `new_task()` function allows users to create custom tasks. A custom task created via `new_task()` returns an object consistent with that returned by `set_task()`.                                                                                                                      |

Folk is inspired by the
[folktables](https://github.com/socialfoundations/folktables) Python
package. For more information on folktables see Ding, Hardt, Miller, and
Schmidt (2022), [Retiring Adult: New Datasets for Fair Machine
Learning](https://arxiv.org/pdf/2108.04884.pdf). The pre-defined
prediction tasks for the American Community Survey data are
implementations of the tasks introduced in this paper.
