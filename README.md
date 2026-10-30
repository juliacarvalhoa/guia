# Guia IELBV: Conectando Olhares e Negócios

Guia de fornecedores locais da **Igreja Evangélica Livre do Boa Vista** (Curitiba, PR).
Reúne os pequenos negócios e serviços dos membros da igreja em uma vitrine simples, que funciona no celular.

Projeto de extensão de **Julia Carvalho**, Engenharia de Software (ODS 9: Indústria, Inovação e Infraestrutura).

## Como funciona

```
Google Forms  →  Google Sheets  →  esta página (GitHub Pages)
 cadastro         revisão e           vitrine pública
                  aprovação
```

- O empreendedor se cadastra pelo formulário e autoriza a divulgação.
- A responsável revisa cada cadastro antes de publicar.
- A página lê apenas os cadastros aprovados e apenas os dados públicos do negócio.
- Tudo usa ferramentas gratuitas, sem servidor e sem custo de manutenção.

## Privacidade

Dados como nome do responsável e e-mail ficam fora da página pública.
Para corrigir ou remover um cadastro, escreva para **juliacarvalho.software@gmail.com**.

A IELBV apenas divulga os negócios de seus membros e não intermedia nem garante produtos ou serviços.

## Quer fazer um guia igual na sua comunidade?

1. Crie um Google Forms com: nome do negócio, categoria, descrição, WhatsApp, Instagram, região de atendimento, condição especial e uma autorização obrigatória de divulgação.
2. Vincule a uma planilha e crie uma coluna **Aprovado** (`S`/`N`).
3. Crie uma aba **Vitrine** com uma fórmula `QUERY` que selecione só as linhas aprovadas e só os campos públicos, com estes rótulos de coluna: `nome`, `categoria`, `descricao`, `whatsapp`, `instagram`, `endereco`, `condicao`.
4. Publique **só a aba Vitrine** como CSV (Arquivo → Compartilhar → Publicar na Web).
5. Faça uma cópia deste `index.html`, preencha `CSV_URL`, `FORM_URL` e `CONTATO` perto do fim do arquivo e ajuste textos, cores e logo para a sua comunidade.
6. Publique no GitHub Pages (Settings → Pages → Branch `main`).

Atenção: publique só a aba com dados autorizados e aprovados. Tudo o que estiver nela fica público.
