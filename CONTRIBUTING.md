# 🤝 Guia de Contribuição

Este repositório é vivo e deve crescer conforme o estudo avança. Siga as orientações abaixo para manter a qualidade e a rastreabilidade do conteúdo.

## Princípios

1. **Objetividade e criticidade:** todo conteúdo deve ser analítico, não promocional.
2. **Rastreabilidade:** sempre cite a fonte de dados numéricos (link, data de acesso, autor).
3. **Verificação:** dados sensíveis (taxas, comissões, rankings) devem vir acompanhados de aviso de verificação humana.
4. **Clareza:** use tabelas comparativas, listas e exemplos concretos.

## Como adicionar um novo documento

1. Crie o arquivo em `docs/` seguindo a numeração sequencial (ex: `09-novo-topico.md`).
2. Adicione o link no `README.md` na seção **Estrutura do Conteúdo**.
3. Atualize a data de "Última atualização" no `README.md`.
4. Se o conteúdo for numérico, adicione a fonte em `docs/07-fontes-e-verificacoes.md`.
5. Faça o commit com mensagem descritiva: `docs: adiciona análise de nicho X`.

## Formato recomendado de commit

```
<tipo>: <descrição curta>

<corpo opcional explicando o que foi feito>
```

Tipos: `docs` (conteúdo), `fix` (correção), `feat` (novo tópico), `chore` (estrutura).

## Checklist antes do commit

- [ ] Fontes citadas e datadas
- [ ] Avisos de verificação humana incluídos (quando aplicável)
- [ ] Link no README atualizado
- [ ] Tabelas renderizam corretamente no GitHub
- [ ] Nenhum dado sensível ou confidencial de terceiros

## Padrão de citação de fontes

```
> Fonte: [Nome da fonte](URL) — acessado em DD/MM/AAAA.
> Observação: [contexto ou ressalva]