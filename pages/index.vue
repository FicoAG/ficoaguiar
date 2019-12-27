<template>
  <div>
    <HeroBanner />
    <Experience />
    <Education />
    <Skills />
    <Article />
  </div>
</template>

<script>
import HeroBanner from '@/components/HeroBanner'
import Article from '@/components/Article'
import Education from '@/components/Education'
import Experience from '@/components/Experience'
import Skills from '@/components/Skills'

export default {
  components: {
    HeroBanner,
    Article,
    Education,
    Experience,
    Skills
  }
}
</script>
