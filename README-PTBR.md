<h1 align="center">
Ignite Call 
</h1>

<div align="right">
  Click <a href="https://github.com/luc-ribeiro/ignite-call-next/blob/main/README.md">here</a> to view the english version.
</div>

<h2 align="center">Preview <a href="https://ignite-call-next-phi.vercel.app" target="_blank">Ignite Call</a></h2>

## 📄 Projeto
O Ignite Call é um projeto desenvolvido para facilitar o agendamento de compromissos, utilizando um calendário com integração ao Google Agenda. 
Os usuários têm a praticidade de se cadastrar no aplicativo através de suas contas do Google, podendo então indicar os dias da semana e os horários nos quais estão disponíveis para agendar compromissos.

Uma das principais vantagens do Ignite Call é a sua sincronização automática com o Google Agenda. Isso significa que qualquer compromisso agendado na aplicação é imediatamente refletido no calendário do Google do usuário. 
Essa integração simplifica significativamente o acompanhamento dos compromissos, permitindo que os usuários visualizem suas agendas consolidadas em um único lugar, diretamente na plataforma do Google.

Por exemplo, suponha que um usuário do Ignite Call tenha uma consulta médica marcada para segunda-feira às 10h. Após realizar o agendamento no aplicativo, 
esse compromisso será automaticamente adicionado ao seu calendário do Google. Assim, ele pode facilmente acessar todos os seus compromissos, sejam eles profissionais ou pessoais, 
através da interface familiar e intuitiva do Google Agenda.

## 💻 Tecnologias

- **React**
- **Next.js**
- **Typescript**
- **Node.js**
- **Prisma**
- **Google APIs**
- **Google Cloud Platform**
- **Docker**
- **Axios**
- **Next SEO**
- **Nookies**
- **React Hook Form**
- **Zod**
- **Design System**
- **Stitches (CSS-in-JS)**
- **Phosphor icons**
- **ESLint**
- **date-fns**

## 🔖 Layout
### [Ignite Call - Figma](https://www.figma.com/file/1fBgGauyyzAeE9AA8w7Dzi/Ignite-Call--%E2%80%A2-Projeto-React?type=design&node-id=339-74&mode=design)

<div align="center">
  
![image](https://github.com/luc-ribeiro/ignite-call-next/assets/69688077/780d3506-7e22-4856-b8f2-1d878e44ffb6)

![Screenshot_5](https://github.com/luc-ribeiro/ignite-call-next/assets/69688077/d4fb317b-5876-4017-962e-f648d27d7bc9)

![Screenshot_6](https://github.com/luc-ribeiro/ignite-call-next/assets/69688077/c1a383bc-6b7c-4558-bef1-869e7740a982)
</div>

## 🚀 Executando o projeto

Para executar a aplicação, será preciso estabelecer uma conexão com um banco de dados local ou um contêiner Docker, integrando-o à ferramenta Prisma.io. 
Também é necessário criar um projeto no Google Cloud Platform para obter as credenciais essenciais para o login e a integração com os serviços do Google, conforme detalhado no arquivo ```.env.example```. 
Este arquivo também inclui a URL de conexão que o Prisma utilizará para se conectar ao banco de dados.

```bash
1. Clone este repositório em sua máquina
$ git clone https://github.com/luc-ribeiro/ignite-call-next.git

2. Instale as dependências
$ npm i

3. Rode o projeto através do comando:
$ npm run dev

- A aplicação estará disponível no endereço `http://localhost:3000`
