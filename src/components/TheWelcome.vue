<script setup>
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
    <template #heading>Education</template>

    I studied at elementary school at SDN 61 Pekanbaru, and continued my primary school at SMP
    Kartika Pekanbaru, then continued high school at
    <a href="https://sman11-pekanbaru.sch.id/" target="_blank" rel="noopener">SMAN 11 Pekanbaru</a>,
    and currently I am studying at
    <a href="https://uir.ac.id/" target="_blank" rel="noopener">Riau Islamic University</a>,
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <ToolingIcon />
    </template>
    <template #heading>Personal Data</template>

    <p>Nama :M Fatahur Rahman</p>
    <p>TTL :Pekanbaru,21 Juni 2004</p>
    <p>Jenis Kelamin :Laki-Laki</p>
    <p>Npm :223510134</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <EcosystemIcon />
    </template>
    <template #heading>Tentang Saya</template>

    I am a person who likes to socialize, meet and even work together with people I have just met. I
    am also known as a good listener so I am able to grasp the essence of the problem and provide
    the right solution.
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <CommunityIcon />
    </template>
    <template #heading>Hobi</template>
    <p>Main Pubg</p>
    <p>Main epep</p>
  </WelcomeItem>

  <WelcomeItem>
    <template #icon>
      <SupportIcon />
    </template>
    <template #heading>Support Social Media </template>
    <p>
      <a href="https://www.instagram.com/fatahurr.r?igsh=MnpidmhlZDA5cWhl&utm_source=qr"
        >Kunjungin Instagram</a
      >
    </p>
    <p>
      <a href="https://www.facebook.com/m.fatahurRahman.21?mibextid=LQQJ4d">Kunjungi Facebook</a>
    </p>
  </WelcomeItem>
</template>
