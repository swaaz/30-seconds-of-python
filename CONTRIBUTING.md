## Contributing

**30 seconds of python code** is a community effort, so feel free to contribute in any way you can. Every contribution helps!

Here's what you can do to help:

- [Open issues](https://github.com/30-seconds/30-seconds-of-python/issues/new) for things you want to see added or modified.
- Be part of the discussion by helping out with [existing issues](https://github.com/30-seconds/30-seconds-of-python/issues) or talking on our [gitter channel](https://gitter.im/30-seconds-of-python/Lobby).
- Submit [pull requests](https://github.com/30-seconds/30-seconds-of-python/pulls) with snippets you have created (see below for guidelines).
- Fix typos in existing snippets, improve snippet descriptions and explanations or provide better examples.
- Before submitting a PR for any new snippets go through [this](https://github.com/30-seconds/30-seconds-of-python/projects/1) project. If your snippet is not there, then go ahead and submit a PR. Else if it is in the done column, sorry it has been already implemented. If it is in any other column submit a PR and give the card's link in the description section of PR.
- **Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

### Snippet submission and Pull request guidelines

- **DO NOT MODIFY THE README.md FILE!** Make changes to individual snippet files. The `travis_ci` automatically builds the `README.md` file when your pull request is merged.
- **Snippet filenames** must correspond to the title of the snippet and to the function name. For example, if your snippet is titled `### awesome_snippet` the filename should be `awesome_snippet.md` and the function name should be `awesome_snippet`.
  - Use `snake_case`, not `kebab-case` or `camelCase`.
  - Avoid capitalization of words.
  -  Please follow the [PEP8](https://www.python.org/dev/peps/pep-0008/) guidelines.
- **Snippet metadata** must be included in all snippets in the form of frontmatter.
  - All snippets must contain a title.
  - All snippets must contain tags, prefixed with `tags:` and separated by commas (optional spaces in-between).
  - Make sure the first tag in your snippet's tags is one of the main categories, as seen in the `README.md` file or the website.
  - Snippet tags must include a difficulty setting (`begginer`, `intermediate` or `advanced`), preferrably at the end of the list.
- **Snippet titles** should be the same as the name of the component or hook that is present in the snippet.
  - All snippet titles must be prefixed with `title:` and be at the very first line of your snippet's frontmatter.
  - Snippet titles must be unique (although if you cannot find a better title, just add some placeholder at the end of the filename and title and we will figure it out).
  - Follow snippet titles with an empty line.
- **Snippet descriptions** must be short and to the point. Try to explain *what* the snippet does and *how* the snippet works and what **inbuilt** features/modules are used. Remember to include what functions you are using and why.
  - Follow snippet descriptions with an empty line.
- **Snippets _CAN NOT_ use any external modules**. Only the modules and function inbuilt in `python 3.6` shall be used.
- **Snippet code** must be enclosed inside ` ```py ` and ` ``` `.
  - Remember to start your snippet's code on a new line below the opening backticks.
  - You can write the code in any style you like but eventually it will be formated by our prettifier so the formatting will change. Just make sure to have consistent spacing.
  - Try to keep your snippets' code short and to the point. Use modern techniques and features. Make sure to test your code before submitting.
  - All snippets must be followed by one (more if necessary) test case after the code, in a new block enclosed inside ` ```python ` and ` ``` `. The syntax for this is `my_function('test_input') # 'test_output'`. Use multiline examples only if necessary.
  - Try to make your function name unique, so that it does not conflict with existing snippets.
  - Snippet functions do not have to handle errors in input, unless it's necessary (e.g. a mathematical function that cannot be extended to negative numbers should handle negative input appropriately).
- Snippets should be short (usually below 20 - 30 lines). If your snippet is longer than that, you can still submit it, and we can help you shorten it or figure out ways to improve it.
- Snippets *should* solve real-world problems, no matter how simple.
- Snippets *should* be abstract enough to be applied to different scenarios.
- It is not mandatory but highly appreciated if you provide **test cases** and/or performance tests.
- You can start creating a new snippet, by using the [snippet template](snippet_template.md) to format your snippets.
- Updating the README.md file should only be done by altering the scripts in the **scripts** folder or altering their relative static parts in the **static-parts** folder.
