# Meu Portfólio

Pequeno site de portfólio com design "bubblegum" (tema rosa) — contém uma página principal (`index.html`) e páginas de projeto individuais.

## Estrutura

- `index.html` — página principal traduzida para português (pt-BR).
- `style.css` — estilos com tema rosa/fofo (bubblegum).
- `projeto-um.html`, `projeto-dois.html`, `projeto-tres.html`, `projeto-quatro.html`, `projeto-cinco.html` — páginas de projeto simples.

## Como ver localmente

1. Abra `index.html` no navegador (duplo clique) ou rode um servidor local rápido:

```bash
python3 -m http.server 8000
```

E abra http://localhost:8000

## Como commitar e enviar para o GitHub

Se quiser que eu faça os commits e o push automaticamente, confirme. Caso prefira fazer manualmente, aqui estão os comandos:

```bash
# 1. adicionar arquivos novos e modificados
git add .

# 2. criar um commit com uma mensagem clara
git commit -m "Atualiza site: traduz, adiciona 5 projetos e estilo bubblegum"

# 3. enviar para o repositório remoto
git push origin main
```

> Observação: os links no `index.html` atualmente apontam para a visualização dos arquivos no GitHub. Se os arquivos não estiverem no remoto, a visualização mostrará 404.

## Próximas sugestões

- Adicionar screenshots/thumbnails para cada projeto.
- Melhorar acessibilidade (contraste/tamanhos) conforme necessário.
- Inserir um formulário de contato (backend) ou links de redes sociais.

---

Se quiser, eu mesmo executo os comandos de git (add/commit/push) agora usando a mensagem sugerida. Confirma?