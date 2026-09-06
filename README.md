# ultracine-config

Repositório de configuração remota do app Roku UltraCine.

O app busca em:
```
https://raw.githubusercontent.com/SEU_USUARIO/ultracine-config/main/roku/v1/config.json
```

Edite `roku/v1/config.json` pelo painel Vercel ou direto no GitHub. Após commit, o Roku busca a nova config no Splash e no botão "Recarregar aplicativo" (até 2 min de cache do raw.githubusercontent).

## Estrutura
```
roku/v1/config.json  -> config usada pelo Roku
```

## Edição manual (sem painel)
1. Abra `roku/v1/config.json` no GitHub > Edit
2. Altere `dns_list` (até 5) ou `backgrounds` (URLs https)
3. Incremente `version` e atualize `updated_at`
4. Commit

Veja `panel/` no projeto UltraCine para o painel web.