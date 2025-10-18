## 🚀 playwright-mentoria

### Automação de Testes End-to-End com Playwright (Mentoria 2.0)

Este repositório foi desenvolvido com o objetivo de servir como um **guia prático e demonstrativo** para os alunos da **Mentoria 2.0**, mostrando o processo completo de automação de testes End-to-End (E2E) utilizando o  **Playwright**.


---

### 🛠️ Guia de Instalação e Execução

Para configurar e executar os testes em sua máquina local, siga os passos abaixo.

#### Pré-requisitos

Certifique-se de ter o [Node.js](https://nodejs.org/) (versão LTS) e o `npm` instalados em seu sistema.

#### 1. Clonar o Repositório

Abra seu terminal ou *prompt* de comando e clone o projeto do GitHub:

```bash
git clone [https://github.com/IaraStevani/playwright-mentoria.git](https://github.com/IaraStevani/playwright-mentoria.git)
cd playwright-mentoria
````

#### 2. Instalar as Dependências
Todas as dependências (incluindo o Playwright) estão listadas no arquivo package.json.
```
npm install
```
Este comando fará o download e a instalação de todos os pacotes necessários e dos browsers suportados pelo Playwright.


#### 3. Execução dos Testes
O projeto pode ser executado usando os seguintes comandos pré-configurados:
```
npx playwright test
- Executa todos os testes E2E em modo headless (sem abrir a interface gráfica do navegador).
npx playwright test --headed
- Executa todos os testes E2E com a interface gráfica do navegador visível (headed), ideal para depuração
```


#### 4. Visualizar o Relatório
Após a execução, utilize o comando para abrir o relatório:
```
npm run show-report
```
O relatório será aberto em seu navegador, permitindo a visualização de steps e screenshots (se configurado).





