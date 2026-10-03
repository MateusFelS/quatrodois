# BUG-002 — Artigos do blog direcionam para páginas inexistentes

## Informações

| Campo               | Valor                                  |
| ------------------- | -------------------------------------- |
| ID                  | BUG-002                                |
| Módulo              | Blog                                   |
| Funcionalidade      | Acesso aos artigos                     |
| Severidade          | Média                                  |
| Prioridade          | Média                                  |
| Ambiente            | Ambiente público disponível ao usuário |
| Navegador           | Brave                                  |
| Sistema Operacional | Windows 11                             |
| Status              | Aberto                                 |

---

## Descrição

A página do **Blog** pode ser acessada normalmente pela landing page, porém os artigos listados nela direcionam para páginas inexistentes.

Ao selecionar qualquer um dos artigos disponíveis, o usuário é direcionado para uma página que apresenta a mensagem:

> "This Page Does Not Exist
> Sorry, the page you are looking for could not be found. It's just an accident that was not intentional."

---

## Pré-condições

* Usuário acessando a landing page do site QuatroDois.
* Página do Blog disponível para acesso.

---

## Passos para reprodução

1. Acessar a landing page do site QuatroDois.
2. Acessar a seção ou página **Blog**.
3. Selecionar qualquer um dos artigos disponíveis.
4. Observar a página carregada.

---

## Resultado esperado

Ao clicar em um artigo, o usuário deve ser direcionado para a respectiva página do conteúdo, podendo visualizar o artigo selecionado.

---

## Resultado obtido

Ao acessar os artigos, o usuário é direcionado para uma página inexistente, que apresenta a mensagem:

> "This Page Does Not Exist"

O conteúdo do artigo não fica disponível.

---

## Impacto

O problema impede o acesso aos conteúdos publicados no Blog, comprometendo a navegação e a utilização dessa área do site.

Além disso, usuários que chegam ao conteúdo por meio de mecanismos de busca, compartilhamentos ou links internos podem encontrar uma página inexistente em vez do artigo esperado.

---

## Evidências

- [Vídeo — Blog](https://github.com/user-attachments/assets/2a08f702-aa95-4b0b-a39f-99f99c48a4a8)
