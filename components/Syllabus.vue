<template>
  <div class="syllabus-data">
    <div v-for="section in syllabus.sections" :key="section.id" class="toggle" :class="sectionId == section.id ? 'active': ''">
      <div class="header bg-light-gray" @click="setSectionId(section.id)">
        <div class="icon-group">
          <font-awesome-icon v-if="sectionId == 1" :icon="['fas', 'chevron-down']" />
          <font-awesome-icon v-else :icon="['fas', 'chevron-right']" />
          <h6 class="text">
            {{ section.name }}
          </h6>
        </div>
        <h6 class="lecture-count">
          {{ section.sessions.length }} Lectures
        </h6>
      </div>
      <div class="content">
        <div v-for="session in section.sessions" :key="session.id" class="class">
          <div class="icon-group">
            <font-awesome-icon :icon="['fas', 'play-circle']" />
            <h6 class="text">
              {{ session.title }}
            </h6>
          </div>
          <p class="count">
            {{ session.duration }}
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  props: ['syllabus'],
  data () {
    return {
      sectionId: 1
    }
  },
  methods: {
    setSectionId (id) {
      this.sectionId = id
    }
  }
}
</script>

<style>

</style>
