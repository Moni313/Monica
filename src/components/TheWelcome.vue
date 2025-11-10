<script setup>
import WelcomeItem from './WelcomeItem.vue'
import DocumentationIcon from './icons/IconDocumentation.vue'
import ToolingIcon from './icons/IconTooling.vue'
import EcosystemIcon from './icons/IconEcosystem.vue'
import CommunityIcon from './icons/IconCommunity.vue'
import SupportIcon from './icons/IconSupport.vue'

const openReadmeInEditor = () => fetch('/__open-in-editor?file=README.md')
</script>

<template>
  <WelcomeItem>
    <template #icon>
      <DocumentationIcon />
    </template>
    <template #heading>Research</template>

    My current PhD work involves designing a workshop on the Miro platform to understand clinicians’ preferences for the content, visualization styles, interactions, and layout of clinical decision support systems (CDSS). Informed by prior studies, I present prototype concepts that clinicians review and improve through collaborative discussion.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Previous studies</template>

    The first stage of my PhD involved a systematic literature review to understand how clinical decision support (CDS) systems present AI predictions to clinicians. We found substantial variation in presentation methods, influenced by both the numerical outputs and how systems are integrated into clinical workflows, roles, and care teams.<br />

Believing in the importance of co-design, I conducted 22 interviews with Australian clinicians to explore their experiences with current patient deterioration tools and gather ideas for a system presenting multiple concurrent AI predictions. Preferences varied by role, setting, institution, and location.<br />

Building on this, I designed two surveys to investigate how clinicians prefer predictions to be stratified (e.g., severity levels or trends) and which explainability tools they would use. This study is not yet published; please contact me for more details.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Ecosystem</template>
    I feel very fortunate to be supervised by excellent people.
<a href="https://about.uq.edu.au/experts/27971" target="_blank" rel="noopener">Dr. Anton van der Vegt</a> is my principal supervisor, supporting me on the AI side of the project (although I am not developing AI models; my focus is on visualising their outputs).
<br /><a href="https://about.uq.edu.au/experts/33792" target="_blank" rel="noopener">Prof. Maxime Cordeil</a> guides me on the visual and design aspects of the project, and <a href="https://about.uq.edu.au/experts/6954" target="_blank" rel="noopener">Prof. Ian A. Scott</a> contributes extensive medical knowledge.<br />
Although <a href="https://www.researchgate.net/scientific-contributions/Victoria-Campbell-2175852354" target="_blank" rel="noopener">Victoria Cambpell</a> is not part of my advisory team, she provides valuable insights and partnerships for this PhD.<br />

I also collaborated with <a href="https://www.sydney.edu.au/medicine-health/about/our-people/academic-staff/audrey.wang1.html" target="_blank" rel="noopener">Dr Audrey P. Wang</a> and <a href="https://www.hospitalmanagementasia.com/speakers/amith-shetty/" target="_blank" rel="noopener">Prof Amith Shetty</a> on the systematic literature review.<br />

  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Community</template>

    I am part of the Queensland Digital Health Centre (QDHeC) and funded by the University of Queensland Scholarship through the UQ–QH HDR Alliance Program.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Publications</template>
    <a href="" target="_blank" rel="noopener">List of publications</a>.
  </WelcomeItem>
</template>
