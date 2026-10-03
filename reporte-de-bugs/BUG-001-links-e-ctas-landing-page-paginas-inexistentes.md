# BUG-001 — Links e CTAs da landing page direcionam para páginas inexistentes

## Informações

| Campo               | Valor                                  |
| ------------------- | -------------------------------------- |
| ID                  | BUG-001                                |
| Módulo              | Navegação da Landing Page              |
| Funcionalidade      | Links e CTAs                           |
| Severidade          | Média                                  |
| Prioridade          | Média                                  |
| Ambiente            | Ambiente público disponível ao usuário |
| Navegador           | Brave                                  |
| Sistema Operacional | Windows 11                             |
| Status              | Aberto                                 |

---

## Descrição

Diversos links e botões presentes na landing page direcionam o usuário para páginas inexistentes, exibindo a mensagem:

> "This Page Does Not Exist
> Sorry, the page you are looking for could not be found. It's just an accident that was not intentional."

O comportamento foi identificado nas opções **Case** e **Contato**, além dos diversos botões de **"Fale com um especialista"** presentes ao longo da página.

---

## Pré-condições

* Usuário acessando a landing page do site QuatroDois.
* Página disponível publicamente para navegação.

---

## Passos para reprodução

1. Acessar a landing page do site [QuatroDois](https://quatrodois.com.br/).
2. Localizar um dos links ou botões de navegação mencionados.
3. Clicar em **"Case"**, **"Contato"** ou em um dos botões **"Fale com um especialista"**.
4. Observar a página carregada.

---

## Resultado esperado

Cada link ou CTA deve direcionar o usuário para a página ou seção correspondente à sua finalidade.

* **Case** → página de cases.
* **Contato** → página ou seção de contato.
* **Fale com um especialista** → fluxo ou página destinada ao contato com um especialista.

---

## Resultado obtido

Os links e CTAs direcionam para uma página inexistente, que apresenta a mensagem:

> "This Page Does Not Exist"

O usuário não consegue acessar o conteúdo ou fluxo associado ao link selecionado.

---

## Impacto

O problema impede o acesso a conteúdos e fluxos importantes da landing page.

Além de prejudicar a navegação, os CTAs **"Fale com um especialista"** deixam de cumprir sua finalidade de direcionar potenciais clientes para um canal de contato, podendo resultar em perda de conversões e dificultando o contato com a empresa.

---

## Evidências

- [Vídeo — Case](https://github.com/user-attachments/assets/4866b229-86eb-4e74-99ed-9dfdc2c41057)
- [Vídeo - Contato](https://github.com/user-attachments/assets/ee6f9adb-585e-4da9-8821-80cde82389e7)
- [Vídeo - Fale com um Especialista](https://github.com/user-attachments/assets/273abf0a-27b9-4ae5-93eb-12505e1ac137)
