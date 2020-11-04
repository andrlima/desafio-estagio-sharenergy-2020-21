# Desafio para processo seletivo de estágio SHARENERGY 2020
   Esse repositório se destina aos interessados em participar do processo seletivo para estagiários da SHARENERGY 2020. As vagas são voltadas para desenvolvimento de aplicação para Web.
## Sobre a SHARENERGY
Acreditamos que as energias renováveis terão um lugar dominante em nossa economia pelo resto de nossas vidas. Trabalhamos no sentido de ampliar o impacto positivo que as energias renováveis podem ter no meio ambiente e nas nossas vidas. O sucesso da SHARENERGY é resultado de nossa equipe apaixonada, juntamente com nosso compromisso de oferecer a melhor solução.

## Sobre a vaga
Já pensou em potencializar o setor que mais cresce na galáxia e trabalhar com uma solução que utiliza tecnologia web de ponta, altamente distribuída com foco em performance e disponibilidade? 👀

Os desenvolvedores da Sharenergy são responsáveis por criar e manter aplicações para clientes internos e externos, prover soluções escaláveis, resilientes e altamente disponíveis que sustentem picos de acesso além de atuar como referência técnica e tutores de outros desenvolvedores. Procuramos por pessoas dinâmicas e que queiram estar aprendendo sempre. Nossa equipe é jovem, motivada e estamos sempre em busca de soluções criativas para alcançar os resultados que nossos clientes esperam. Se você tem esse perfil, é autoconfiante e tem facilidade para lidar com desafios diários, essa vaga é para você! 
## O desafio
   Criar um aplicativo para Web que atenda às demandas listadas abaixo. O aplicativo deve apresentar uma interface amigável e bonita.
### Parte 1: visualização de dados de uma usina fotovoltaica
   O aplicativo deve ser capaz de ler dados de um arquivo fornecido pelo usuário / objeto (ou array) que forneci. 
   Plotar gráfico das variáveis em função do tempo
   Opção de escolher curva que será mostrada. Usuário deve escolher em lista suspensa ou check box qual dos parâmetros será mostrado no gràfico.
### Parte 2: gerenciamento de clientes
   Clientes...
   Usar dados de arquivo... iniciar banco de dados
   CRUD...
### Parte 3: receita de clientes
   Calcular energia produzida no dia a partir das informações de potência.
   Calcular receita de cada cliente... considerar R$0,95 / kWh.
   Lembre-se que, por definição, a potência P (kW) é a derivada no tempo t (h) da energia E (kWh), P = dE/dt. Portanto, a energia pode ser calculada a partir da potência por: 
      
   ![Equação para ΔE](equation.jpg)
   <!--
      Imagem gerada pelo site: http://www.sciweavers.org/free-online-latex-equation-editor
      Foi usado o comando LaTeX: " \Delta E = \int_{t_0}^{t_f}P(t)dt  \approx \Delta t  \sum_{i = 1}^{N-1} P(t_i) "
      Font: Arev (padrão), Font size: 12 (padrão)
   -->
   Em que ΔE é a energia gerada (kWh), t<sub>0</sub> é o instante de tempo inicial (h), t<sub>f</sub> é o instante de tempo final (h), Δt é o intervalo de tempo em que os dados são amostrados (h), i indica a posição do dado no registro (i = 1, ..., N) e N é o número total de dados amostrados.  
### Opcional
   O aplicativo do desafio pode ser enriquecido com recursos pensados por você. Algumas sugestões:
* Documentação
* Responsividade
* Contas de usuário
   * Proteção contras modiificações de pessoas não autorizadas
* Estatística descritiva dos dados dos gráficos
* Formulário de clientes com mais campos
* Implementação de fórmula mais precisa de integração numérica para o cálculo de ΔE
* Validação dos dados 
### Quais ferramentas posso usar?
   Não será especificado... código que já faça o mesmo...
   Não obstante. usar as mesmas ferramentas que trabalhamos será um diferencial. 
### Mas, afinal, quais ferramentas a Sharenergy utiliza?
   Atualmente, nossas aplicações são desenvolvidas usando a plataforma [Meteor JS](https://www.meteor.com/). Mais especificadamente, nossas aplicações se caracterizam por:
* Gerenciador de pacotes: [npm](https://www.npmjs.com/get-npm)
* Para back-end: [Node.js](https://nodejs.org/en/)
* Banco de dados: [MongoDB](https://www.mongodb.com/) do lado do servidor e [Minimongo](https://guide.meteor.com/collections.html) do lado do cliente (cache)
* Validação de dados: [Schema-utils](https://www.npmjs.com/package/schema-utils) 
* Framework para front-end: [React JS](https://pt-br.reactjs.org/)
* UI: [CSS 3](https://www.w3.org/Style/CSS/), [Material-UI](https://material-ui.com/pt/) e [Reflexbox](https://rebassjs.org/reflexbox/)
* Gráficos: [Victory](https://formidable.com/open-source/victory/)
* Roteamento: [react-router-dom](https://www.npmjs.com/package/react-router-dom)
## O que entregar?
   Esperamos de você duas entregas: o código da aplicação no Git-Hub e um vídeo explicativo no YouTube 
### Instruções sobre aplicação
   Clone esse repositório. Fetch... branch... request pull...
   Incluir arquivo de texto listando todas as dependências usadas e instrução de instalação/uso da aplicação criado.
### Instruções sobre vídeo explicativo no YouTube
   O vídeo duração aproximada de 5 min... não indexado...  link em arquivo...
   Não é necessário mostrar sua face na vídeo, embora seja bom.
### Prazo limite de entrega
   O envio do que foi solicitado deve ser feito até o dia XX/YY/2020.
