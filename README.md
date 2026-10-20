# Aprovação de Posts – Afro Amparo e Saúde

App de aprovação de artes para social media (estilo Aprova Post).

## Arquivos
- `aprovacao-v2.html` – página de aprovação (visão da cliente + visão de edição)
- `painel-clientes.html` – painel com a lista de clientes e o perfil

## Importante
Os dois arquivos foram feitos para rodar dentro do Claude (claude.ai) e usam o banco de dados,
o envio de imagens e o login do Claude (`claude.use("db")`, `claude.use("assets")`, `claude.use("user")`).
Fora do Claude (por exemplo no GitHub Pages) a tela abre, mas **não salva posts, imagens nem aprovações**.

Para rodar fora do Claude é preciso trocar essas partes por um backend próprio (Firebase, Supabase etc.).

## Versão em funcionamento
- Aprovação: https://claude.ai/artifact/WcdcnCbzg8ows1g7p9KRGj
- Painel de clientes (uso pessoal): https://claude.ai/artifact/FpM2hFXjWwikJJbxTsm7X8
