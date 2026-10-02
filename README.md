# Sistema de Logística — versão standalone

Esta versão é um wireframe visual estático e navegável, com áreas livres no lugar de campos obrigatórios. Não usa Manus, React, Express, tRPC, Drizzle, OAuth, banco de dados, variáveis secretas ou serviços externos.

## Como executar

### Opção 1 — navegador
Abra o arquivo `index.html` diretamente no navegador.

### Opção 2 — servidor local
No terminal, dentro desta pasta, rode:

```bash
python3 -m http.server 8000
```

Depois acesse `http://localhost:8000`.

Também funciona com qualquer servidor estático, como `npx serve .`, `php -S localhost:8000` ou o servidor de arquivos do seu sandbox.

## Observações

O login é demonstrativo: qualquer e-mail e senha válidos no formulário entram no sistema. A navegação entre telas e os botões são demonstrativos. As áreas de login, cadastro, pesquisa, novo produto e saída estão livres de campos obrigatórios, porque este pacote é um wireframe. Para usar dados reais, será necessário conectar um backend próprio posteriormente.
