The only place you can contribute to this wiki is through the [Github](https://github.com/Kryeit/holiwis), via a **Pull Request (PR)**.

### How to modify the wiki

1. Download [Visual Studio Code](https://code.visualstudio.com) and Github Desktop app.
2. Create a Fork of this repository.
3. Open the folder with Visual Studio Code.
4. See the file that you need to modify by opening [`mkdocs.yml`](https://github.com/Kryeit/holiwis/blob/main/mkdocs.yml), for example the Getting Started page would be [`docs/server/getting-started.md`](https://github.com/Kryeit/holiwis/blob/main/docs/server/getting-started.md).
5. Modify page contents using Markdown or HTML

### Modify the wiki on phone
The Github app actually lets you modify the page and create a pull request really easy!

### Helpful tips
- You can use any emoji from [here](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/#search) like `:material-cog:` which is a :material-cog:
- If you want to see how your edition would look, you can go to [Markdown Editor](https://stackedit.io/app#) but if you want to test if locally keep reading!

### Test locally
- Install [Python](https://www.python.org/downloads/)
- Open the project folder
- Go to `Terminal` > `New Terminal`
- Install *holiwis'* dependencies:
```python
pip install mkdocs
pip install mkdocs-material
pip install mkdocs-glightbox
```
- Run `python -m mkdocs serve` or `mkdocs serve`
- Go to http://localhost:8000/