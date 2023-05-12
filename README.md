<h1 align="center">
   Alura Challenge Back-End <br>
   4ª Edição
</h1>
<h3 align="center">API Controle Financeiro 💸 Concluído! 🚀</h3>
<div>
   <p>
      Um <i>challenge</i> incrível para praticar seus conhecimentos, além de ser uma motivação para pesquisar, estudar, revisar mais. <br>
      Através desse projeto, pude por em prática o que estudei e vi nos projetos práticos do estágio, desenvolver novas habilidades e aprimorar conhecimentos em .NET, da criação do projeto a realização do deploy da aplicação. <br>
   </p>
</div>
<div>
   <h2>
      Descrição do projeto 📖
   </h2>
</div>
<div>
   <p>
      Endpoints desenvolvidos para um controle financeiro, sendo possível cadastrar receitas e despesas. <br/>
      Temos a possibilidade de buscar, tanto receitas quanto despesas, pela descrição, por ID. Podemos também  gerar um resumo de gastos e ganhos utilizando uma data específica. 
   <h4>No entanto...</h4>
   Para utilizar os endpoints disponibilizados, o usuário deve, primeiramente, criar uma conta, se já não possuir, e confirmar essa através do e-mail de confirmação que chegará após a criação da conta e realizar o <i>login</i> na aplicação de controle de usuário. <br/>
   Com o <i>login</i> feito, um <i>TOKEN</i> será disponibilizado, para que você o utilize na aplicação de controle financeiro. 
   </p>
</div>
<div>
   <h2>Features 👨‍💻</h2>
   <p>- ✅ <i>CRUD</i> de Receitas </p>
   <p>- ✅ <i>CRUD</i> de Despesas </p>
   <p>- ✅  Resumo de receitas e despesas </p>
   <p>- ✅ Criação de conta</p> 
   <p>- ✅ Login para acessar sistema de controle financeiro</p>
   <p>- ✅ Endpoint para alterar a senha </p>
</div>
<div>
   <h2>Tecnologias e Recursos 🔧</h2>
   <div>
      <p>- .NET 6</p>
      <p>- C#</p>
      <p>- Banco de Dados Relacional (SQLServer)</p>
      <p>- Visual Studio </p>
   </div>
</div>
<div>
   <h2>Como usar 🤔</h2>
      <div>
         <p>
            Basta abrir os endpoints disponibilizados. Como padrão, a aplicação utiliza o Swagger, 
            mas as requisições podem ser feitas através de outras plataformas, como o Postman.
         </p>
         </br>
         <p>
            Primeiro abra o link da aplicação <a href="https://usercontrol.up.railway.app/swagger/index.html">UserControl</a>, 
            crie a conta e efetue o login. Feito isso, um TOKEN será gerado, este é necessário para te autenticar e autorizar as ações
            conforme as permissões de seu usuário.
            
            <img 
                 width="950" 
                 alt="Swagger_UserControl_Login" 
                 src="https://github.com/LucassPimentel/ChallengeAluraBackend/assets/95232367/f6cfe649-9699-48e8-be18-99754b30d5f6"
            >
         </p>
         </br>
         <p>
           Pronto, agora você pode acessar a aplicação de <a href="https://financecontrol.up.railway.app/swagger/index.html">FinanceControl</a>, 
            inserir o TOKEN gerado no passo anterior no campo "Authorize" e executar as atividades disponíveis.
   
            <img 
                 width="950" 
                 alt="Swagger_FinanceControl_TOKEN" 
                 src="https://github.com/LucassPimentel/ChallengeAluraBackend/assets/95232367/3d96fa78-d3ab-4de9-9185-dc8286c8cce7"
            >
         </p>
      </div>
</div>
