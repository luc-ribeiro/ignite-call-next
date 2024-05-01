<h1 align="center">
Ignite Call 
</h1>

![image](https://github.com/luc-ribeiro/ignite-call-next/assets/69688077/01cb55b7-7f94-4ec1-bb7d-1195933fbf3b)

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

## 🚀 Executando o projeto

Para executar a aplicação, será preciso estabelecer uma conexão com um banco de dados local ou um contêiner Docker, integrando-o à ferramenta Prisma.io. 
Também é necessário criar um projeto no Google Cloud Platform para obter as credenciais essenciais para o login e a integração com os serviços do Google, conforme detalhado no arquivo ```.env.example```. 
Este arquivo também inclui a URL de conexão que o Prisma utilizará para se conectar ao banco de dados.

```bash
1. Clone este repositório em sua máquina
$ git clone https://github.com/luc-ribeiro/ignite-call-react.git

2. Instale as dependências
$ npm i

3. Rode o projeto através do comando:
$ npm run dev

- A aplicação estará disponível no endereço `http://localhost:3000`