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

O comportamento foi identificado nos links **Case** e **Contato**, nos diversos botões de **"Fale com um especialista"** presentes na página e, no rodapé, nos links **Política de Privacidade** e **Termos de Serviço**.

---

## Pré-condições

* Usuário acessando a landing page do site QuatroDois.
* Página disponível publicamente para navegação.

---

## Passos para reprodução

1. Acessar a landing page do site QuatroDois.
2. Localizar um dos links ou botões afetados.
3. Clicar em um dos seguintes elementos:
   * **Case**
   * **Contato**
   * **Fale com um especialista**
   * **Política de Privacidade**
   * **Termos de Serviço**
4. Observar a página carregada.

---

## Resultado esperado

Cada link ou CTA deve direcionar o usuário para a página, seção ou fluxo correspondente à sua finalidade.

* **Case** → página de cases.
* **Contato** → página ou seção de contato.
* **Fale com um especialista** → fluxo ou página destinada ao contato com um especialista.
* **Política de Privacidade** → página contendo a política de privacidade.
* **Termos de Serviço** → página contendo os termos de serviço.

---

## Resultado obtido

Os links e CTAs direcionam para uma página inexistente, que apresenta a mensagem:

> "This Page Does Not Exist"

O usuário não consegue acessar o conteúdo ou fluxo associado aos links selecionados.

---

## Impacto

O problema impede o acesso a conteúdos e fluxos importantes da landing page.

Além de prejudicar a navegação, os CTAs **"Fale com um especialista"** deixam de cumprir sua finalidade de direcionar potenciais clientes para um canal de contato.

Os links de **Política de Privacidade** e **Termos de Serviço** também ficam inacessíveis, impedindo o usuário de consultar informações importantes relacionadas ao uso do site e aos serviços oferecidos.

---

## Evidências

- [Vídeo — Case](https://github.com/user-attachments/assets/4866b229-86eb-4e74-99ed-9dfdc2c41057)
- [Vídeo - Contato](https://github.com/user-attachments/assets/ee6f9adb-585e-4da9-8821-80cde82389e7)
- [Vídeo - Fale com um Especialista](https://github.com/user-attachments/assets/273abf0a-27b9-4ae5-93eb-12505e1ac137)
- [Vídeo - Política de Privacidade](https://github.com/user-attachments/assets/f52a2ea1-bbfa-448c-827d-d27952b892cd)
- [Vídeo - Termos de Serviço](https://github.com/user-attachments/assets/a491b6da-7af5-483d-b563-464a51ba99b5)
