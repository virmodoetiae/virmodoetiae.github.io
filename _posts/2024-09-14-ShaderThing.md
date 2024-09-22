---
title: "ShaderThing"
tags:
  - ShaderThing
  - Shaders
  - Programming
  - Digital art
excerpt:
  A tool for shader programming I have been developing since 2022
background_image: "/assets/images/post-st-thumbnail.png"
background: 'rgba(0, 0, 0, 0.5)'
comments: true
share: false
related: false
---

This post is under construction! In the meantime, you can check the ShaderThing project [github page](https://github.com/virmodoetiae/shaderthing).

<figure>
  <img src="/assets/images/st-light-transport.gif" alt="Light transport with ShaderThing" />
  <figcaption>An example of what can be rendered with ShaderThing. What you see is the result of pure GLSL code, and there are no 'assets' in the traditional sense: the geometry is not described as a collection of vertices with a certain connectivity (mesh), rather, it is described via a time-varying <a href="https://en.wikipedia.org/wiki/signed_distance_function" target="_blank" rel="noopener noreferrer">signed distance field</a> and resolved with a custom Monte Carlo-based <a href="https://en.wikipedia.org/wiki/ray_marching#Sphere_tracing" target="_blank" rel="noopener noreferrer">ray marching</a> technique to resolve the principal light transport modes (diffuse reflection, specular reflection, transmission through dielectric media such as glass).</figcaption>
</figure>