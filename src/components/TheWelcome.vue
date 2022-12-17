<script setup lang="ts">
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Who am I?</template>
    I am a developer really passionate about Python programming langage,
    Artificial Intelligence, Data Science, Blockchain, and IoT. I am one of those who believe that
    code can save us. 
  </WelcomeItem>


  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>How to reach me</template>

    Mail 1: 
    <a href="mailto:dera.amedee@gmail.com" target="_blank" rel="noopener">dera.amedee@gmail.com</a><br />

    Mail 2: 
    <a href="mailto:dera.amedee@outlook.com" target="_blank" rel="noopener">dera.amedee@outlook.com</a><br />

    Mail 3: 
    <a href="mailto:dera.amedee@a-dera.com" target="_blank" rel="noopener">dera.amedee@a-dera.com</a><br />

    Phone 
    <a href="tel:+22656833675" target="_blank" rel="noopener">+22656833675</a> *-* 
    <a href="https://api.whatsapp.com/send/?phone=22656833675" target="_blank" rel="noopener">Whatsapp</a><br />

    Github
    <a href="https://github.com/a-dera/" target="_blank" rel="noopener">@a-dera</a><br />



  </WelcomeItem>

</template>
