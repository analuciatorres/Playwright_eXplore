# Playwright_eXplore
Playwright eXplorer: Testando o clone do Spotify

Automação de teste E2E com o Framework Playwright do Curso Playwright-eXplore da [QAx Academy](https://qaxperience.com/)

Nesse repositório encontram-se os testes E2E para tocar uma música na aplicação [Parodify](https://parodify.vercel.app/)

## Tecnologias aplicadas
- Playwright
- TypeScript


## Automação
Para rodar a automação é preciso seguir os seguntes passos:

1. Clonar o repositório, instalar as dependências
```
npm install
```

2. Executar testes em Headless
```
npx playwright test 
```
ou para abrir a interface do Playwrigt
```
npx playwright test  --ui
```
3. Executar ver o relatório dos testes
```
npx playwright show-report
```
