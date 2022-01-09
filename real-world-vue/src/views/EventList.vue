<template>
  <div>
    <h1>Events Listing</h1>
    <event-card />
    <base-icon />
  </div>
</template>

<script>
import EventCard from '@/components/EventCard.vue'
import BaseIcon from '../components/BaseIcon.vue'

export default {
  components: {
    EventCard,
    BaseIcon,
  },
}
</script>
