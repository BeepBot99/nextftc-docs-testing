---
layout: home

hero:
    name: "Welcome"
    text: "to NextFTC"
    tagline: Simple but powerful library for FTC
    image:
        dark: /images/NextFTC-Banner-Dark-Transparent-FullColor.png
        light: /images/NextFTC-Banner-Light-Transparent-FullColor.png
        alt: NextFTC Logo
    actions:
        - theme: brand
          text: Get Started
          link: /installation
        - theme: alt
          text: Reference
          link: https://beepbot99.github.io/nextftc-docs-testing/reference/

features:
    - title: Easy to use
      details: NextFTC doesn't require you to write commands as classes, like you do in FTCLib.
    - title: Gamepad bindings
      details: Easy to bind commands to gamepad buttons.
    - title: Subsystems
      details: Subsystems help you organize your code and prevent conflicts by ensuring that no two commands using the same subsystem run simultaneously.
    - title: Commands
      details: Commands are units of code that can be executed. They consist of several steps and can be grouped into command groups, allowing them to run sequentially or simultaneously.
    - title: Built-In Commands
      details: You almost never need to write your own commands, as dozens of pre-built commands are available. Examples include running a motor to a position using a custom PID controller, following a path, or driving during TeleOp.
    - title: PedroPathing
      details: NextFTC integrates with [PedroPathing](https://pedropathing.com), an autonomous pathing library. Compared to Roadrunner, PedroPathing is faster, smoother, and easier to tune.
---

## A note on these docs

NextFTC was written in Kotlin, a JVM programming language. You can use either Kotlin or Java, but there are small advantages to using Kotlin. Each section with code examples will offer both Kotlin and Java tabs. It's recommended to choose one language for your project to avoid compatibility issues.

To use Kotlin, configure it in your project. I recommend the Kotlin Gradle Plugin version `1.9.25`. (Kotlin is pre-installed in the Quickstart template.)

<script setup>
import { VPTeamMembers } from 'vitepress/theme'

const members = [
  {
    avatar: 'https://github.com/rowan-mcalpin.png',
    name: 'Rowan McAlpin',
    title: 'NextFTC Lead Dev',
    links: [
      { icon: 'github', link: 'https://github.com/rowan-mcalpin' },
      { 
        icon: {svg: '<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6"><path stroke-linecap="round" stroke-linejoin="round" d="M21.75 6.75v10.5a2.25 2.25 0 0 1-2.25 2.25h-15a2.25 2.25 0 0 1-2.25-2.25V6.75m19.5 0A2.25 2.25 0 0 0 19.5 4.5h-15a2.25 2.25 0 0 0-2.25 2.25m19.5 0v.243a2.25 2.25 0 0 1-1.07 1.916l-7.5 4.615a2.25 2.25 0 0 1-2.36 0L3.32 8.91a2.25 2.25 0 0 1-1.07-1.916V6.75" /></svg>'}, 
        link: 'mailto:contact@rowanmcalpin.com',
        ariaLabel: 'email' 
      },
      { icon: 'linkedin', link: 'https://www.linkedin.com/in/rowan-mcalpin/'},
      {
        icon: { 'svg': '<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6"><path stroke-linecap="round" stroke-linejoin="round" d="M12 21a9.004 9.004 0 0 0 8.716-6.747M12 21a9.004 9.004 0 0 1-8.716-6.747M12 21c2.485 0 4.5-4.03 4.5-9S14.485 3 12 3m0 18c-2.485 0-4.5-4.03-4.5-9S9.515 3 12 3m0 0a8.997 8.997 0 0 1 7.843 4.582M12 3a8.997 8.997 0 0 0-7.843 4.582m15.686 0A11.953 11.953 0 0 1 12 10.5c-2.998 0-5.74-1.1-7.843-2.918m15.686 0A8.959 8.959 0 0 1 21 12c0 .778-.099 1.533-.284 2.253m0 0A17.919 17.919 0 0 1 12 16.5c-3.162 0-6.133-.815-8.716-2.247m0 0A9.015 9.015 0 0 1 3 12c0-1.605.42-3.113 1.157-4.418" /></svg>'},
        link: 'https://rowanmcalpin.com',
        ariaLabel: 'website'
      }
    ]
  }
]
</script>

## Our Team

<VPTeamMembers size="small" :members="members" />
