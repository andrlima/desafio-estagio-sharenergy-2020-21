# Desafio para processo seletivo de estágio Sharenergy 2020
   Esse repositório se destina aos interessados em participar do processo seletivo para estagiários da Sharenergy 2020. As vagas são voltadas para desenvolvimento de aplicação para Web.
## O que fazemos
   A [Sharenergy](https://sharenergy.com.br/) é uma start-up que atua no ramo de usinas solares compartilhadas de pequeno porte. Nesse setor, a receita gerada pela venda da energia elétrica gerada por uma usina fotovotaica é divida por vários investidores. O modelo de negócios compartilhado é especialmente interessante em setores cujos investimentos requerme alto capital e demandam longo tempo para retorno do invesimento, pois reduz o capital inicial necessário de cada investidor.
## O desafio
   Criar um aplicativo para Web que atenda às demandas listadas abaixo. O aplicativo deve apresentar uma interface amigável e bonita.
### Parte 1: visualização de dados de uma usina fotovoltaica
   O aplicativo deve ser capaz de ler dados de um arquivo fornecido pelo usuário / objeto (ou array) que forneci. 
   Plotar gráfico das variáveis em função do tempo
   Opção de escolher curva que será mostrada. Usuário deve escolher em lista suspensa ou check box qual dos parâmetros será mostrado no gràfico.
### Parte 2: gerenciameno de clientes
   Clientes...
   Usar dados de arquivo... iniciar banco de dados
   CRUD...
### Parte 3: receita de clientes
   Calcular energia produzida no dia a partir das informações de potência.
   Calcular receita de cada cliente... considerar R$0,95 / kWh.
   Lembre-se que, por definição, a potência P (kW) é a derivada no tempo t (h) da energia E (kWh), P = dE/dt. Portanto, a energia pode ser calculada a partir da potência por:  
   ![Equação para ΔE](http://www.sciweavers.org/tex2img.php?eq=%20%5CDelta%20E%20%3D%20%5Cint_%7Bt_0%7D%5E%7Bt_f%7DP%28t%29dt%20%20%5Capprox%20%5CDelta%20t%20%20%5Csum_%7Bi%20%3D%201%7D%5E%7BN-1%7D%20P%28t_i%29%20&bc=White&fc=Black&im=jpg&fs=12&ff=arev&edit=0)
   <!--
      Imagem gerada pelo site: http://www.sciweavers.org/free-online-latex-equation-editor
      Foi usado o comando LaTeX: " \Delta E = \int_{t_0}^{t_f}P(t)dt  \approx \Delta t  \sum_{i = 1}^{N-1} P(t_i) "
      Font: Arev (padrão), Font size: 12
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
* Implementação de fórmula mais precisa de integral numérica para o cálculo de ΔE
* Validação dos dados 
* ...
### Quais ferramentas posso usar?
   Não será especificado... código que já faça o mesmo...
   Não obstante. usar as mesmas ferramentas que trabalhamos será um diferencial. 
### Mas, afinal, quais ferramentas a Sharenergy utiliza?
   Atualmente, nossas aplicações são desenvolvidas usando a plataforma [Meteor JS](https://www.meteor.com/). Mais especificadamente, nossas aplicações se caracterizam por:
* Gerenciador de pacotes: [npm](https://www.npmjs.com/get-npm)
* Para back-end: [Node.js](https://nodejs.org/en/)
* Banco de dados: [MongoDB](https://www.mongodb.com/) do lado do servidor e [Minimongo](https://guide.meteor.com/collections.html) do lado do cliente
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
   O vídeo duração aproximada de 30 min... não indexado...  link em arquivo...
### Prazo limite de entrega
   O envio do que foi solicitado deve ser feito até o dia XX/YY/2020.