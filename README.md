# Repositório F-Droid do Home Maiden

Daqui se instala e se atualiza o app Android do Home Maiden, pelo F-Droid ou pelo Droid-ify.

## Adicionar o repositório

No F-Droid (ou no Droid-ify), em *Repositórios → Adicionar*, cole:

```
https://angelogcapra.github.io/home-maiden-fdroid/repo?fingerprint=B8AE9405CF73193DDD930B72B5CF3A990552DBF2705FC8C923CFD96B69076144
```

A impressão digital confere que o índice foi assinado pela chave do Home Maiden. Sem ela, o app
de loja não tem como saber se alguém trocou os arquivos no caminho.

## Antes de instalar

- **O aparelho precisa estar autorizado.** No Brasil, desde 30/09/2026, o Android só instala app
  de pacote registrado. O Home Maiden é registrado em distribuição limitada: o dono do sistema
  autoriza cada aparelho, e só então a instalação passa.
- **A conta é criada pelo dono do sistema.** Na primeira abertura, o app pede o endereço do
  sistema e o login.

## Como este repositório é feito

Não edite à mão. A cada versão nova do app, o CI do Home-Maiden publica aqui o APK assinado e o
índice, e reescreve o histórico com um commit só, para os APKs antigos não se acumularem.
