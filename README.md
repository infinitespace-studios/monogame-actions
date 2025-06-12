# monogame-actions

A Repo to hold MonoGame related github actions

```yml
- uses install-wine@v1
- uses install-fonts@v1
- uses publish-itchio@v1
  with:
    game_id: '123456'
    channel: 'ubuntu'
    token: ${{ secrets.ITCHIO_TOKEN }}
    file: 'path/to/game.zip'
    version: '1.0.0'
```
