<script>
import liveVue from './main-container/live.vue'
import articleVue from './main-container/article.vue'
import leagueTableVue from './main-container/league-table.vue'
import playersVue from './main-container/players.vue'
import calendarVue from './main-container/calendar.vue'
import sponsorVue from './main-container/sponsor.vue'



export default {
  name : 'main',
  components: {
    sponsorVue,
    liveVue,
    articleVue,
    leagueTableVue,
    playersVue,
    calendarVue
  }
}
</script>

<template>
  <div>
    <liveVue />
    <calendarVue />
    <playersVue />
    <league-table-vue />
    <sponsorVue/>
    <articleVue />
  </div>
</template>

<style lang="scss" scoped>

</style>