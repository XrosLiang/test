# Measuring Massive Multitask Language Understanding
This is the repository for [Measuring Massive Multitask Language Understanding](https://arxiv.org/pdf/xxxx.yyyy) by [Dan Hendrycks](https://people.eecs.berkeley.edu/~hendrycks/), [Collin Burns](http://collinpburns.com), Steven Basart, Andy Zou, Mantas Mazeika, [Dawn Song](https://people.eecs.berkeley.edu/~dawnsong/), and [Jacob Steinhardt](https://www.stat.berkeley.edu/~jsteinhardt/).

This repository contains OpenAI API evaluation code, and the test is in `/data`.

<img align="center" src="size_and_accuracy.png" width="500">

## Test Leaderboard

If you want to have your model added to the leaderboard, please reach out to us or submit a pull request.


Results of the test:
|                Method               |  Humanities |  Social Science  | STEM | Other | Average |
|------------------------------------|:-------:|:-------:|:-------:|:-------:|:-------:|
| [GPT-3](https://arxiv.org/abs/2005.14165) | 40.8 | 50.4 | 36.7 | 48.8 | 43.9
| [UnifiedQA](https://arxiv.org/abs/2005.00700) | 38.0 | 41.5 | 32.2 | 42.1 | 38.5
| Random Baseline           | 25.0 | 25.0 | 25.0 | 25.0 | 25.0 | 25.0


## Citation

If you find this useful in your research, please consider citing the test and also the ETHICS dataset it draws from:

    @article{hendryckstest2020,
      title={Measuring Massive Multitask Language Understanding},
      author={Dan Hendrycks and Collin Burns and Steven Basart and Andy Zou and Mantas Mazeika and Dawn Song and Jacob Steinhardt},
      journal={arXiv preprint arXiv:xxxx.yyyy},
      year={2020}
    }

    @article{hendrycksethics2020,
      title={Aligning AI With Shared Human Values},
      author={Dan Hendrycks and Collin Burns and Steven Basart and Andrew Critch and Jerry Li and Dawn Song and Jacob Steinhardt},
      journal={arXiv preprint arXiv:2008.02275},
      year={2020}
    }
