![logo do projeto](assets/logo.png){ width="300" .center}
# Notas Musicas

## como usar?

Você pode chamar as escalas via linha de comando. Por Exemplo:

```bash
poetry run escalas
```
Retornando os graus e as notas correspondentes a essa escala:

```
┏━━━┳━━━━┳━━━━━┳━━━━┳━━━┳━━━━┳━━━━━┓
┃ I ┃ II ┃ III ┃ IV ┃ V ┃ VI ┃ VII ┃
┡━━━╇━━━━╇━━━━━╇━━━━╇━━━╇━━━━╇━━━━━┩
│ C │ D  │ E   │ F  │ G │ A  │ B   │
└───┴────┴─────┴────┴───┴────┴─────┘

```

### Alteração na tônica da escala

O primeiro parâmetro do CLI é a tônica da escala que seja exibir. 
Dessa forma, `F#`
```bash
poetry run escalas F#
```