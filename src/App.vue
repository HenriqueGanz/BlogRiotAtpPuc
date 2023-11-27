<template>

  <div class="bg-gray-900">
    <MenuBar />
    <div id="sessao" class="m-auto w-10/12 bg-gray-800 flex flex-col justify-center items-center">
      <section id="nossahistoria" class="mr-10 ml-10 flex h-screen items-center max-[780px]:flex-col max-[780px]:h-full">
        <div id="imgNossaHistoria">
          <img src="./assets/Ashe (essa ta mt boa).png" class="max-w-md max-[780px]:w-60 max-[780px]:pt-20">
        </div>
        <div>
          <h1 class="text-2xl font-bold text-white text-center">Nossa História</h1>
          <p class="p-4 text-lg text-justify text-white max-[780px]:text-sm">
          &emsp; Concebida no ano de 2006 em Los Angeles com o intuito de inovar o desenvolvimento e distribuição de jogos, a Riot Games é uma marca mundialmente notável,
          que se faz conhecida desde a sua fundação até os dias de hoje através do lançamento do MOBA League of Legends, em 2009. Já em 2021, o LoL atingiu a meta de 180 milhões de jogadores simultâneos,
          fato apurado pela própria empresa que demonstra a popularidade do jogo e, por consequência, da marca.</p>
          <p class="p-4 pt-1 text-lg text-justify text-white max-[780px]:text-sm">&emsp; A. Dylan Jadeja, Marc Merrill e Brandon Beck são alguns dos nomes mais emblemáticos no que se refere à criação e representação da Riot,
          que juntamente com a equipe composta por mais de 4.500 ‘’Rioters’’ em mais de 20 escritórios espalhados pelo mundo, apontam que o foco da empresa está na experiência do jogador, isto é, na disposição,
          por parte dos funcionários, de interagir, cooperar e praticar a empatia para com os clientes ou jogadores. Além disso, a empresa traz pautas como diversidade e inclusão, ousar sonhar, excelência, empatia, otimismo
          e responsabilidade corporativa, através de atitudes que promovem a boa cidadania.
          </p>
        </div>
      </section>

      <section id="noticia" class="mr-10 ml-10 h-screen flex items-center max-[780px]:text-sm max-[780px]:flex-col max-[780px]:h-full">
        <div>
          <h1 class="text-2xl font-bold text-white text-center">Notícia</h1>
          <p class="p-4 text-lg text-justify text-white max-[780px]:text-sm">
            &emsp;A votação para Escolha Da Instituição Do Impacto Social da Riot Games está aberta
            Desde 2019, ano em que a empresa criou, em parceria com a ImpactAssets, o Fundo de Impacto Social com intuito de aumentar a capacidade de impacto em causas globais,
            a Riot vem promovendo edições do programa todos os anos. Neste momento, está aberta a votação brasileira referente ao ano de 2023, que inclui as Instituições Rede Cidadã,
            Arca de Noé e +1Code, atuantes nos âmbitos de desenvolvimento pessoal, assistência social e educação, respectivamente.</p>
          <p class="p-4 text-lg pt-1 text-justify text-white max-[780px]:text-sm">&emsp;Nesse sentido, a Instituição que obtiver o maior número de votos na modalidade de votos abertos, disponível no 
            <a href="https://charityvote.riotgames.com/pt-br/vote/br/" target="_blank" class="text-red-500">link</a>, será beneficiada com 50%
          (cinquenta por cento) dos fundos arrecadados. A outra metade será distribuída igualmente para as outras instituições participantes. 
          </p>
        </div>
        <div id="imgNoticia">
          <img src="./assets/Social Impact (Notícia).png" class="max-w-xl max-[780px]:w-60">
        </div>
      </section>

      <section id="portfolio" class="flex h-screen items-center max-[780px]:text-sm max-[780px]:flex-col max-[780px]:h-full">
        <div id="imgPortfolio">
          <img src="./assets/TFT Capeteemo.png" class="max-w-xl max-[780px]:w-60 ">
        </div>
        <div>
          <h1 class="text-2xl font-bold text-white text-center">
            Portfólio
          </h1>
          <p class="p-4 pt-1 text-lg text-justify text-white max-[780px]:text-sm">
            &emsp; Além do LoL, outros jogos foram desenvolvidos e disponibilizados posteriormente, como Legends of Runeterra, Valorant, Teamfight Tactics, Ruined King e o mobile Wild Rift, além de outros que estão sendo desenvolvidos,
            como o project L.</p>
          <p class="p-4 pt-1 text-lg text-justify text-white max-[780px]:text-sm"> &emsp; Nessa perspectiva, a empresa busca ampliar o universo criado dentro dos jogos através do desenvolvimento de produtos multimídia como músicas
            em parceria com artistas e bandas. Ademais, os quadrinhos e jogos de tabuleiro, além da série animada Arcane, 
            disponibilizada em parceria com a Netflix, também são produtos mais recentes da Riot.
            Além disso, as transmissões e competições dos jogos também são organizadas pela empresa, e compreendem grandes conferências que reúnem times 
            profissionais dos e-sports e a plateia.</p>
          <p class="p-4 pt-1 text-lg text-justify text-white max-[780px]:text-sm">&emsp; Todos esses produtos são desenvolvidos com o intuito de atingir tanto os consumidores dos jogos, que estão inseridos no universo fictício criado pela empresa,
            quanto os usuários fora deste âmbito, que também são potenciais consumidores dos produtos multimídia produzidos.
          </p>
        </div>
      </section>

      <section id="comunicacao" class="flex h-screen items-center max-[780px]:text-sm max-[780px]:flex-col max-[780px]:h-full">
        <div>
          <h1 class="p-4 text-2xl font-bold text-white text-center">Comunicação</h1>
          <p class="p-4 pt-1 text-lg text-justify text-white max-[780px]:text-sm">&emsp; A comunicação empática, inclusiva e atenciosa é um dos alvos empresariais da Riot Games, de acordo com eles. Assim, estabelecer boas relações entre a rede de funcionários,
          os Rioters, de consumidores dos produtos e dos líderes da empresa é uma das missões mais enfatizadas.</p>
          <p class="p-4 pt-1 text-lg text-justify text-white max-[780px]:text-sm">&emsp; Nesse sentido, observa-se, de acordo com os aspectos transparecidos pela Riot, que entre os ‘’rioters’’ ocorre um fluxo comunicacional que é parte vertical descendente,
          tendo em vista a necessidade de estabelecimento de metas e demandas, e parte horizontal, considerando o empreendimento em relações empáticas, respeitosas e que contribuem para o crescimento de cada indivíduo dentro da empresa.
          Já a relação entre os funcionários da Riot e consumidores, por sua vez, configura-se pendente entre horizontal e informal, tendo em vista a intenção de uma troca de informações mais coloquial, isto é, acolhedora e confortável,
          mantendo o compromisso entre produtor e consumidor.</p>
          <p class="p-4 pt-1 text-lg text-justify text-white max-[780px]:text-sm">&emsp; Levando em conta estes aspectos e a grande soma de indivíduos que compõem a rede social da Riot Games, um possível impasse é a grande demanda de atendimentos, tanto internos quanto externos. Esta condição é superada, no que diz respeito à solução de demandas de consumidores, através do auxílio da tecnologia e de BOTs, que identificam e respondem às dúvidas frequentes e simples de serem solucionadas. Já entre a equipe de Rioters,
          a grande demanda é solucionada por meio da designação de sub-lideranças, que lideram pequenas equipes dentro do todo da empresa, já que a Riot se configura como uma empresa internacional e, por consequência, plural e numerosa.</p>
        </div>
      </section>

      <section class="flex flex-col gap-20 h-screen items-center max-[780px]:text-sm max-[780px]:flex-col max-[780px]:h-full">
        <h1 class="text-2xl font-bold text-white text-center">
          Infográfico
        </h1>
        <div class="flex justify-center gap-32 max-[780px]:flex-col max-[780px]:h-full">
          <div id="Infografico">
            <button id="buttonInfografico"><img id="infograficoImg" src="./assets/Blog - comunicação - Infográfico (PNG).png" class="max-[780px]:w-60"></button>
          </div>
          <div>
            <img src="./assets/Astra Valorant.png" class="max-w-sm max-[780px]:w-60">
          </div>
        </div>
      </section>
      
      <section id="faleconosco" class="flex h-screen items-center justify-center max-[780px]:text-sm max-[780px]:flex-col max-[780px]:h-full">
        <div id="canais de comunicacao">
          <ul class="p-4 text-xl text-white flex gap-8 bg-red-950 pr-8 pl-8 max-[780px]:text-sm max-[780px]:flex-col max-[780px]:h-full ">
            <li class="text-center font-semibold text-2xl">
              <a href="https://support.riotgames.com/hc/pt-br" target="blank">Suporte</a>
              <img src="./assets/QR suporte para jogadores.png" class="">
            </li>
            <li class="text-center font-semibold text-2xl">
              <a href="https://www.facebook.com/RiotGames/" target="blank">Facebook</a>
              <img src="./assets/QR Facebook.png" class="">              
            </li>
            <li class="text-center font-semibold text-2xl">
              <a href="https://twitter.com/riotgames" target="blank">X</a>
              <img src="./assets/QR Twitter.png" class="">
            </li>
            <li class="text-center font-semibold text-2xl">
              <a href="https://www.linkedin.com/company/riot-games/" target="blank">Linked-in</a>
              <img src="./assets/QR Linkedin.png" class="">
            </li>
            <li class="text-center font-semibold text-2xl">
              <a href="https://www.youtube.com/riotgames" target="blank">Youtube</a>
              <img src="./assets/QR Youtube.png" class="">              
            </li>
          </ul>
        </div>
      </section>
    </div>
    <FooterBar />
  </div>
</template>

<script>
//importar component
import MenuBar from './components/MenuBar.vue';
import FooterBar from './components/FooterBar.vue'



export default {
  name: 'App',
  components: {
  //inserir component
  MenuBar,
  FooterBar
  
}
}
</script>

<style scoped>
  #infograficoImg {
    width: 240px;
    height: 580px;
  }

  #infograficoImg:hover {
    position: absolute;
    margin: 0;
    z-index: 1;
    width: 400px;
    height: 1000px;
  }

  @media only screen and (max-width: 768px) {
    #infograficoImg:hover {
    width: 240px;
    height: 580px;
    position: static;
  }
}

</style>
