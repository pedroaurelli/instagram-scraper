# Instagram followers scraper

### Aplicação em Node.Js que permite visualizar quais seguidores não te segue de volta no Instagram. 

### A API oficial do aplicativo não disponibiliza essa função, entretanto TODAS as aplicações que se aproveitam desse recurso são com base em APIs privadas, scrapers ou Android Virtual Devices que são irregulares pela política de privacidade e termos de uso da rede. 

### Esta aplicação possui como principal objeitvo a aprendizagem. De maneira alguma o código será exposto, ou consumindo por alguma aplicação terceira.
> "Não há caminho errado. O aprendizado e a experiência estão em todos os caminhos." - Zíbia Gasparetto

## Requisitos
- Usuario não precisa fazer login na conta do instagram para a aplicação funcionar
- Usuario deve apenas fornecer dados básicos sobre a conta, como username 
- Aplicação deve ser em Node.JS
- Aplicação deve retornar uma lista com username dos followers que não seguem o usuario inputado
  
## Casos de uso
Os casos de uso são usados para capturar e especificar requisitos funcionais do sistema, definir os limites do sistema e identificar as principais funcionalidades e interações com os usuários.

Use Case Diagram (UML):
![image](https://user-images.githubusercontent.com/88735972/225017137-9dabd97a-986f-4865-a708-1db8f1f520ad.png)

## Tecnologias
| Package |  Descrição  |
| ------------------- | ------------------- |
| [TypeScript](https://www.typescriptlang.org) | Superset do Javascript, adicionando tipagem à linguagem |
| [Node.Js](https://nodejs.org/en/) | Interpretar código javascript fora do navegador  |
| [Express.js](https://expressjs.com/pt-br/) |  Framework para Node.js |
| [Puppeteer](https://pptr.dev/) | Realizar automação na web  |
| [TurboRepo](https://turbo.build/) |  Sistema de compilação otimizado para JavaScript e TypeScript |

## Aprendizados
Com esse projeto, tive a oportunidade de aprender mais sobre monorepo, automação e scraper de dados
