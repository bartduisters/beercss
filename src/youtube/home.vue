<template lang="pug">
main.responsive(v-show="data.isLoaded")
  .page.right.active
    nav.scroll
      a.chip.border.fill
        i.small done
        span The best of 2020
      a.chip.border Documentaries
      a.chip.border Rock and roll
      a.chip.border Others
    .space
    .grid
      .s12.m6.l3(v-for="(item, i) in data.itens")
        article.no-padding.transparent
          a.wave
            img.responsive(:src="item.image")
            .absolute.right.bottom.small-margin.black.white-text.small-text &nbsp;00:00:00&nbsp;
          .small-padding
            nav
              .max.truncate
                .bold {{ item.title }}
                div 10k views
              button.circle.transparent(:data-ui="'#dropdown-' + i")
                i more_vert
                .dropdown.left.no-wrap(
                  :id="'dropdown-' + i",
                  :data-ui="'#dropdown-' + i"
                )
                  a Save to library
                  a Watch later
                  a Like it

    .large-divider
    h5 What's hot
    .row.scroll
      .min(v-for="item in data.whatsHot")
        article.no-padding.border.transparent.small-width
          a.wave
            img.responsive(:src="item.image")
            .absolute.right.bottom.small-margin.black.white-text.small-text &nbsp;00:00:00&nbsp;
          .padding
            nav
              .max.truncate
                .bold {{ item.title }}
                div 10k views
              button.circle.transparent
                i thumb_up

    .large-divider
    h5 Your videos
    .row.scroll
      .min(v-for="item in data.yourVideos")
        article.no-padding.border.transparent.small-width
          a.wave
            img.responsive(:src="item.image")
            .absolute.right.bottom.small-margin.black.white-text.small-text &nbsp;00:00:00&nbsp;
          .padding
            nav
              .max.truncate
                .bold {{ item.title }}
                div 10k views
              button.circle.transparent
                i thumb_up
</template>

<script setup lang="ts">
import data from "./data";
</script>