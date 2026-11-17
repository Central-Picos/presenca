# Presença de Culto – Central Picos

Ferramenta de lançamento e painel de presença dos cultos (Sábado 19h, Domingo 17h e Domingo 19h30).

- **Página:** GitHub Pages (este repositório).
- **Dados e login:** Supabase. Só e-mails cadastrados na tabela `autorizados` e com conta criada em *Authentication › Users* conseguem editar.
- **Painel:** aberto a qualquer pessoa com o link.
- `supabase/schema.sql`: criação das tabelas, regras de acesso e registro de alterações.
- `.github/workflows/manter-ativo.yml`: evita que o projeto gratuito do Supabase seja pausado por inatividade.
