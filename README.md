# monogame-actions

A Repo to hold MonoGame related github actions

```yml
- uses install-wine@v1
- uses install-fonts@v1
- uses publish-itchio@v1
  with:
    channel: 'ubuntu'
    tag: '-latest'
    file: 'path/to/game.zip'
    version: '1.0.0'
    ITCHIO_USER: ${{ secrets.ITCHIO_USER }}
    ITCHIO_GAME: ${{ secrets.ITCHIO_GAME }}
    ITCHIO_TOKEN: ${{ secrets.ITCHIO_TOKEN }}
```
