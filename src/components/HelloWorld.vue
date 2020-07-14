<template>
 <v-card
      class="d-flex align-content-space-around flex-wrap"
      color="yellow accent-4"
      flat
      tile
      min-height="200"
    >
  <v-container
   class="spacing-playground pa-8"
   fluid
  >
    <v-row class="text-center">
    <v-col cols="12">
    </v-col>

  <v-hover>
  <template v-slot="{ hover }">
  <v-card
    class="d-flex pa-md-6 mx-lg-auto ma-3"
    color = "green darken-3"
    :elevation="hover ? 24 : 6"
    outlined
    tile
  >
      <v-col class="mb-4">
        <h1 class="display-1 font-weight-bold mb-2 yellow--text">
          Título: Aprendizagem Baseada em Jogos (Game Based Learning) e Gamificação
        </h1>

      <p class="subheading font-weight-bold text-justify black--text">
        Tudo no mundo mudou, menos a educação. A escola ficou parada no mesmo formato do século XIX, enquanto a nova geração já nasceu adaptada às mudanças, demandado-as constantemente.</p>

<p class="subheading font-weight-bold text-justify black--text">O reflexo disso é a desmotivação e queda gradativa no engajamento dos jovens em sala de aula, desinteressados em aprender.</p>

<p class="subheading font-weight-bold text-justify black--text">E por incrível que pareça, muitos educadores ainda acham que o problema está com os alunos que não conseguem se manter focados e não querem saber de nada.</p>

<p class="subheading font-weight-bold text-justify black--text">Mas será mesmo que o problema está com o jovens ou a forma como buscamos atrair a atenção e nos comunicamos com eles?</p>

<p class="subheading font-weight-bold text-justify black--text">É nesse contexto que o universo dos games começou a entrar nas escolas. </p>
    
</v-col>
  </v-card>
  </template>
 </v-hover>

<v-row>
 <v-hover>
  <template v-slot="{ hover }">
  <v-card
    class="d-flex pa-md-6 mx-lg-auto ma-3 "
    :elevation="hover ? 24 : 6"
    color = "yellow lighten-4"
    outlined
    tile
  >
      <v-col
        class="mb-4"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3 green darken-3 amber--text">
         Game Based Learning VS Gamificação
        </h2>


<p class="subheading font-weight-bold text-justify black--text">Os jogos tem uma grande capacidade de engajar as pessoas, pois eles geralmente seguem alguns preceitos básicos e tem mecânicas específicas que cativam os jogadores.</p>

<p class="subheading font-weight-bold text-justify black--text">Yu-Kai Chou – um dos grandes estudiosos e precursores da ideia de Gamificação – extraiu esses elementos fundamentais dos jogos para que pudessem ser aplicados à interações cotidianas com o objetivo de gerar mais engajamento.</p>

<p class="subheading font-weight-bold text-justify black--text">Ele elencou 8 pilares da gamificação que juntos criam mais motivação; trabalham com a ideia de conquistas e recompensas proporcionais; evolução e progressão das habilidades de cada indivíduo; geram competição e superação; exploram a criatividade; fortalecem o senso de comunidade e pertencimento; dão a sensação de urgência para manter o progresso conquistado e mais.</p>

<p class="subheading font-weight-bold text-justify black--text">Porém, a Gamificação na educação é sobre como manter a motivação e interação. É preciso aplicar isso na prática de uma maneira que gere aprendizado. Isso pode ser feito criando um jogo aliado ao conteúdo a ser abordado em sala. Esse é o Aprendizado Baseado em Jogos, ou game-based learning em inglês.</p> 
  </v-col>
  </v-card>
  </template>
 </v-hover>
 
 
   <v-hover>
  <template v-slot="{ hover }">
  <v-card
    class="d-flex pa-md-6 mx-lg-auto ma-3"
    :elevation="hover ? 24 : 6"
    color = "yellow lighten-4"
    outlined
    tile
  >
      <v-col
        class="mb-4"
        cols="12"
      >
        <h2 class="headline font-weight-bold mb-3 green darken-3 amber--text">
         Game Based Learning: o que é
        </h2>

        
<p class="subheading font-weight-bold text-justify black--text"> É importante ressaltar que o jogo precisa ter uma intenção didático-pedagógica bem clara antes de ser aplicado. Eles podem ser usados tanto para passar o conteúdo, quanto para praticar o que foi aprendido, ajudando a sedimentar o conhecimento e aplicá-lo em situações do dia-a-dia. Isso contribui para que os jovens tenham uma capacidade analítica e de resolução de problemas mais desenvolvida.</p>

<p class="subheading font-weight-bold text-justify black--text">Uma forma simples de aplicar jogos em sala é criando competições através de quizes (ou outro formato de perguntas e respostas), jogos de tabuleiro modificados ou adaptação de jogos tradicionais (por exemplo, um jogo da velha que para marcar a lacuna desejada com X ou O, o aluno precisa resolver a equação daquele espaço). Premiações (ponto extra, certificados, medalha, chocolate, etc) aliada a feedbacks positivos ou construtivos são fundamentais nesse processo. </p>

<p class="subheading font-weight-bold text-justify black--text">Existem também plataformas digitais de uso de games e gamificação na aprendizagem dentro ou fora de sala de aula. A grande vantagem de usar essas ferramentas digitais é que os alunos utilizam o celular para isso, que é um dispositivo que eles se sentem mais à vontade. Além disso, elas possuem o conteúdo e dinâmicas já prontos, facilitando o trabalho do professor que às vezes não tem tempo para montar uma aula dessas.</p>
       
    </v-col>
  </v-card>
  </template>
 </v-hover>
</v-row>
<v-hover>
  <template v-slot="{ hover }">
    <v-card
    class="d-flex pa-md-6 mx-lg-auto ma-3"
    :elevation="hover ? 24 : 6"
    color = "yellow lighten-4"
    outlined
    tile
  >

      <v-col
        class="mb-4"
        cols="12"
      >
         <h2 class="headline font-weight-bold mb-3 green darken-3 amber--text">
          Game Based Learning: para quem é?
        </h2>

        <p class="subheading font-weight-bold text-justify black--text">Outra vantagem dessa abordagem para a sala de aula é que a gamificação e aulas com games podem ser aplicadas desde o Fundamental I até o Ensino Médio, sem restrição de idade.</p>

<p class="subheading font-weight-bold text-justify black--text">Escolas no Brasil e no mundo que já estão utilizando essa abordagem em sala de aula já tem colhido ótimos resultados. Um exemplo é uma escola no Rio de Janeiro, onde começaram a usar a plataforma digital de aprendizagem através de Gamificação – a Jovens Gênios – e não somente o engajamento e a aprendizagem aumentaram, como algo a mais aconteceu.</p>

<p class="subheading font-weight-bold text-justify black--text">Uma das alunas da turma tem mutismo seletivo e por conta disso possui mais dificuldades de interação com os colegas de turma e com os professores. Ao aplicar uma modalidade de aula gamificada da plataforma (Modalidade de Desafio), ela ficou em primeiro lugar no ranking geral. Isso foi uma grande surpresa para todos, pois o seu rendimento nunca era tão excepcional, mas aquela maneira de realizar questões através de um jogo despertou algo que fez ela se destacar.</p>

       
    </v-col>
    </v-card>
    </template>
 </v-hover>

    <v-hover>
  <template v-slot="{ hover }">
    <v-card
    class="d-flex pa-md-6 mx-lg-auto ma-3"
    :elevation="hover ? 24 : 6"
    color = "yellow lighten-4"
    outlined
    tile
  >
      <v-col
        class="mb-4"
        cols="12"
      >
         <h2 class="headline font-weight-bold mb-3 green darken-3 amber--text">
         Game Based Learning: conclusão
        </h2>
       
          <p class="subheading font-weight-bold text-justify black--text">
        A grande sacada da gamificação e do game-based learning é o poder de se comunicar com os jovens em uma “linguagem” que faz sentido para eles e que já usam. Os resultados são alunos mais engajados e um aprendizado mais efetivo, pois existe um real interesse e vantagem em aprender nos olhos dos jovens.</p>
<p class="subheading font-weight-bold text-center black--text"> Para saber mais como levar gamificação para a sua escola,
        
         <a
            href="https://community.vuetifyjs.com"
            target="_blank"
          >acesse o link aqui</a>.
          </p>
       
      </v-col>
     </v-card>
      </template>
 </v-hover>
    </v-row>
  </v-container>
   </v-card>


</template>

<script>
  export default {
    name: 'HelloWorld',

   data: () => ({
    //
  }),
};
  
</script>
