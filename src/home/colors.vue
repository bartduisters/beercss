<template lang="pug">
#colors
  .large-space
  h4 
    span Colors
    a.chip.circle(data-ui="#modal-colors")
      i code
  nav
    button(data-ui="#modal-colors") Colors

  #modal-colors.modal.right.medium
    header.fixed
      nav
        h5.max Colors
        button.circle.transparent(data-ui="#modal-colors")
          i close
          
    .grid
      .s12
        h5 Theme
        .primary primary
        .primary-container primary-container
        .secondary secondary
        .secondary-container secondary-container
        .tertiary tertiary
        .tertiary-container tertiary-container
        .error error
        .error-container error-container
        .background background
        .surface surface
        .surface-variant surface-variant
        .inverse-surface inverse-surface
        .primary-border.border primary-border
        .secondary-border.border secondary-border
        .tertiary-border.border tertiary-border
        .error-border.border error-border
        .primary-text primary-text
        .secondary-text secondary-text
        .tertiary-text tertiary-text
        .error-text error-text
      .s12
        h5 Red
        .black-text.red1 red1
        .black-text.red2 red2
        .black-text.red3 red3
        .black-text.red4 red4
        .black-text.red5 red5
        .black-text.red red6 / red
        .black-text.red7 red7
        .black-text.red8 red8
        .black-text.red9 red9
        .black-text.red10 red10
        .red-border.border red-border
        .red-text red-text
      .s12
        h5 Pink
        .black-text.pink1 pink1
        .black-text.pink2 pink2
        .black-text.pink3 pink3
        .black-text.pink4 pink4
        .black-text.pink5 pink5
        .black-text.pink pink6 / pink
        .black-text.pink7 pink7
        .black-text.pink8 pink8
        .black-text.pink9 pink9
        .black-text.pink10 pink10
        .pink-border.border pink-border
        .pink-text pink-text
      .s12
        h5 Purple
        .black-text.purple1 purple1
        .black-text.purple2 purple2
        .black-text.purple3 purple3
        .black-text.purple4 purple4
        .black-text.purple5 purple5
        .black-text.purple purple6 / purple
        .black-text.purple7 purple7
        .black-text.purple8 purple8
        .black-text.purple9 purple9
        .black-text.purple10 purple10
        .purple-border.border purple-border
        .purple-text purple-text
      .s12
        h5 Deep-purple
        .black-text.deep-purple1 deep-purple1
        .black-text.deep-purple2 deep-purple2
        .black-text.deep-purple3 deep-purple3
        .black-text.deep-purple4 deep-purple4
        .black-text.deep-purple5 deep-purple5
        .black-text.deep-purple deep-purple6 / deep-purple
        .black-text.deep-purple7 deep-purple7
        .black-text.deep-purple8 deep-purple8
        .black-text.deep-purple9 deep-purple9
        .black-text.deep-purple10 deep-purple10
        .deep-purple-border.border deep-purple-border
        .deep-purple-text deep-purple-text
      .s12
        h5 Indigo
        .black-text.indigo1 indigo1
        .black-text.indigo2 indigo2
        .black-text.indigo3 indigo3
        .black-text.indigo4 indigo4
        .black-text.indigo5 indigo5
        .black-text.indigo indigo6 / indigo
        .black-text.indigo7 indigo7
        .black-text.indigo8 indigo8
        .black-text.indigo9 indigo9
        .black-text.indigo10 indigo10
        .indigo-border.border indigo-border
        .indigo-text indigo-text
      .s12
        h5 Blue
        .black-text.blue1 blue1
        .black-text.blue2 blue2
        .black-text.blue3 blue3
        .black-text.blue4 blue4
        .black-text.blue5 blue5
        .black-text.blue blue6 / blue
        .black-text.blue7 blue7
        .black-text.blue8 blue8
        .black-text.blue9 blue9
        .black-text.blue10 blue10
        .blue-border.border blue-border
        .blue-text blue-text
      .s12
        h5 Light-blue
        .black-text.light-blue1 light-blue1
        .black-text.light-blue2 light-blue2
        .black-text.light-blue3 light-blue3
        .black-text.light-blue4 light-blue4
        .black-text.light-blue5 light-blue5
        .black-text.light-blue light-blue6 / light-blue
        .black-text.light-blue7 light-blue7
        .black-text.light-blue8 light-blue8
        .black-text.light-blue9 light-blue9
        .black-text.light-blue10 light-blue10
        .light-blue-border.border light-blue-border
        .light-blue-text light-blue-text
      .s12
        h5 Cyan
        .black-text.cyan1 cyan1
        .black-text.cyan2 cyan2
        .black-text.cyan3 cyan3
        .black-text.cyan4 cyan4
        .black-text.cyan5 cyan5
        .black-text.cyan cyan6 / cyan
        .black-text.cyan7 cyan7
        .black-text.cyan8 cyan8
        .black-text.cyan9 cyan9
        .black-text.cyan10 cyan10
        .cyan-border.border cyan-border
        .cyan-text cyan-text
      .s12
        h5 Teal
        .black-text.teal1 teal1
        .black-text.teal2 teal2
        .black-text.teal3 teal3
        .black-text.teal4 teal4
        .black-text.teal5 teal5
        .black-text.teal teal6 / teal
        .black-text.teal7 teal7
        .black-text.teal8 teal8
        .black-text.teal9 teal9
        .black-text.teal10 teal10
        .teal-border.border teal-border
        .teal-text teal-text
      .s12
        h5 Green
        .black-text.green1 green1
        .black-text.green2 green2
        .black-text.green3 green3
        .black-text.green4 green4
        .black-text.green5 green5
        .black-text.green green6 / green
        .black-text.green7 green7
        .black-text.green8 green8
        .black-text.green9 green9
        .black-text.green10 green10
        .green-border.border green-border
        .green-text green-text
      .s12
        h5 Light-green
        .black-text.light-green1 light-green1
        .black-text.light-green2 light-green2
        .black-text.light-green3 light-green3
        .black-text.light-green4 light-green4
        .black-text.light-green5 light-green5
        .black-text.light-green light-green6 / light-green
        .black-text.light-green7 light-green7
        .black-text.light-green8 light-green8
        .black-text.light-green9 light-green9
        .black-text.light-green10 light-green10
        .light-green-border.border light-green-border
        .light-green-text light-green-text
      .s12
        h5 Lime
        .black-text.lime1 lime1
        .black-text.lime2 lime2
        .black-text.lime3 lime3
        .black-text.lime4 lime4
        .black-text.lime5 lime5
        .black-text.lime lime6 / lime
        .black-text.lime7 lime7
        .black-text.lime8 lime8
        .black-text.lime9 lime9
        .black-text.lime10 lime10
        .lime-border.border lime-border
        .lime-text lime-text
      .s12
        h5 Yellow
        .black-text.yellow1 yellow1
        .black-text.yellow2 yellow2
        .black-text.yellow3 yellow3
        .black-text.yellow4 yellow4
        .black-text.yellow5 yellow5
        .black-text.yellow yellow6 / yellow
        .black-text.yellow7 yellow7
        .black-text.yellow8 yellow8
        .black-text.yellow9 yellow9
        .black-text.yellow10 yellow10
        .yellow-border.border yellow-border
        .yellow-text yellow-text
      .s12
        h5 Amber
        .black-text.amber1 amber1
        .black-text.amber2 amber2
        .black-text.amber3 amber3
        .black-text.amber4 amber4
        .black-text.amber5 amber5
        .black-text.amber amber6 / amber
        .black-text.amber7 amber7
        .black-text.amber8 amber8
        .black-text.amber9 amber9
        .black-text.amber10 amber10
        .amber-border.border amber-border
        .amber-text amber-text
      .s12
        h5 Orange
        .black-text.orange1 orange1
        .black-text.orange2 orange2
        .black-text.orange3 orange3
        .black-text.orange4 orange4
        .black-text.orange5 orange5
        .black-text.orange orange6 / orange
        .black-text.orange7 orange7
        .black-text.orange8 orange8
        .black-text.orange9 orange9
        .black-text.orange10 orange10
        .orange-border.border orange-border
        .orange-text orange-text
      .s12
        h5 Deep-orange
        .black-text.deep-orange1 deep-orange1
        .black-text.deep-orange2 deep-orange2
        .black-text.deep-orange3 deep-orange3
        .black-text.deep-orange4 deep-orange4
        .black-text.deep-orange5 deep-orange5
        .black-text.deep-orange deep-orange6 / deep-orange
        .black-text.deep-orange7 deep-orange7
        .black-text.deep-orange8 deep-orange8
        .black-text.deep-orange9 deep-orange9
        .black-text.deep-orange10 deep-orange10
        .deep-orange-border.border deep-orange-border
        .deep-orange-text deep-orange-text
      .s12
        h5 Brown
        .black-text.brown1 brown1
        .black-text.brown2 brown2
        .black-text.brown3 brown3
        .black-text.brown4 brown4
        .black-text.brown5 brown5
        .black-text.brown brown6 / brown
        .black-text.brown7 brown7
        .black-text.brown8 brown8
        .black-text.brown9 brown9
        .black-text.brown10 brown10
        .brown-border.border brown-border
        .brown-text brown-text
      .s12
        h5 Grey
        .black-text.grey1 grey1
        .black-text.grey2 grey2
        .black-text.grey3 grey3
        .black-text.grey4 grey4
        .black-text.grey5 grey5
        .black-text.grey grey6 / grey
        .black-text.grey7 grey7
        .black-text.grey8 grey8
        .black-text.grey9 grey9
        .black-text.grey10 grey10
        .grey-border.border grey-border
        .grey-text grey-text
      .s12
        h5 Blue-grey
        .black-text.blue-grey1 blue-grey1
        .black-text.blue-grey2 blue-grey2
        .black-text.blue-grey3 blue-grey3
        .black-text.blue-grey4 blue-grey4
        .black-text.blue-grey5 blue-grey5
        .black-text.blue-grey blue-grey6 / blue-grey
        .black-text.blue-grey7 blue-grey7
        .black-text.blue-grey8 blue-grey8
        .black-text.blue-grey9 blue-grey9
        .black-text.blue-grey10 blue-grey10
        .blue-grey-border.border blue-grey-border
        .blue-grey-text blue-grey-text
      .s12
        h5 Black
        .black.white-text black
        .black-border.border black-border
        div black-text
      .s12
        h5 White
        .white.black-text white
        .white-border.border white-border
        div white-text
      .s12
        h5 Transparent
        .transparent transparent
        .transparent-border.border transparent-border
        div transparent-text
</template>

<script setup lang="ts">
import domain from "./domain";
import data from "./data";
</script>