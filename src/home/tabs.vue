<template lang="pug">
#tabs
  .large-space
  h4
    span Tabs
    a.chip.circle(
      @click="domain.showSamples(data, '#tabs > div:not(.large-space)', 'Tabs', null, 'https://github.com/beercss/beercss/blob/main/docs/TABS.md')"
    )
      i code
  nav.wrap
    label.radio
      input(
        type="radio",
        name="align-tabs",
        checked,
        @click="domain.updateAlign('#tabs .tabs')"
      )
      span default
    label.radio
      input(type="radio", name="align-tabs", @click="domain.updateAlign('#tabs .tabs', 'left-align')")
      span left-align
    label.radio
      input(type="radio", name="align-tabs", @click="domain.updateAlign('#tabs .tabs', 'center-align')")
      span center-align
    label.radio
      input(type="radio", name="align-tabs", @click="domain.updateAlign('#tabs .tabs', 'right-align')")
      span right-align
    label.radio
      input(
        type="radio",
        name="page-tabs",
        checked,
        @click="domain.updatePosition('#tabs .page')"
      )
      span page default
    label.radio
      input(type="radio", name="page-tabs", @click="domain.updatePosition('#tabs .page', 'left')")
      span page left
    label.radio
      input(type="radio", name="page-tabs", @click="domain.updatePosition('#tabs .page', 'right')")
      span page right
    label.radio
      input(type="radio", name="direction-tabs", @click="domain.updateDirection('#tabs .tabs > a', '')", checked)
      span horizontal
    label.radio
      input(type="radio", name="direction-tabs", @click="domain.updateDirection('#tabs .tabs > a', 'vertical')")
      span vertical
  p.space
  div
    .tabs
      a.active(data-ui="#tab1", no-direction="") Tab 1
      a(data-ui="#tab2", no-direction="") Tab 2
      a(data-ui="#tab3", no-direction="") Tab 3
    #tab1.page.padding.active
      h5 Tab 1
    #tab2.page.padding
      h5 Tab 2
    #tab3.page.padding
      h5 Tab 3
  div
    .tabs
      a.active(data-ui="#tab4")
        i home
        span Tab 1
      a(data-ui="#tab5")
        i home
        span Tab 2
      a(data-ui="#tab6")
        i home
        span Tab 3
    #tab4.page.padding.active
      h5 Tab 1
    #tab5.page.padding
      h5 Tab 2
    #tab6.page.padding
      h5 Tab 3
  div
    .tabs
      a.active(data-ui="#tab7") 
        img.circle(:src="'/favicon.png'")
        span Tab 1
      a(data-ui="#tab8")
        img.circle(:src="'/favicon.png'")
        span Tab 2
      a(data-ui="#tab9")
        img.circle(:src="'/favicon.png'")
        span Tab 3
    #tab7.page.padding.active
      h5 Tab 1
    #tab8.page.padding
      h5 Tab 2
    #tab9.page.padding
      h5 Tab 3
</template>

<script setup lang="ts">
import domain from "./domain";
import data from "./data";
</script>