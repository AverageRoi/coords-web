---
layout: '@/layouts/PageLayout.astro'
title: List
description: Browse the coordinates saved for a Discord server.
activeHeaderLink: Features
---

[Back to all features](/features/)

# /list

## What It Does

Browse the coordinates saved for a Discord server. You can use this to quickly review stored locations without remembering each alias.

## Syntax

```txt
/list
```

## Fields

- Dimension: optional dimension filter
- Page: optional page number if the server has many saved coordinates
- Search: optional text filter for aliases or names

## Example

<div class="not-prose rounded-md border border-[#3f4147] bg-[#313338] p-4 text-sm text-[#dbdee1]">
  <div class="mb-3 text-xs font-semibold uppercase text-[#b5bac1]"># coordinates</div>
  <div class="flex gap-3">
    <div class="flex h-10 w-10 shrink-0 items-center justify-center rounded-full bg-[#5865f2] font-semibold text-white">P</div>
    <div>
      <div>
        <span class="font-semibold text-white">Pipo</span>
        <span class="ml-1 text-xs text-[#949ba4]">Today at 18:51</span>
      </div>
      <div class="mt-1 rounded-md bg-[#2b2d31] px-3 py-2">/list dimension: Overworld</div>
    </div>
  </div>

  <div class="mt-4 flex gap-3">
    <img
      class="h-10 w-10 shrink-0 rounded-full object-cover"
      src="https://cdn.discordapp.com/avatars/1515786853356277820/b2b885ed92e1845f6c3d893ff61509dc.webp?size=1024"
      alt="Nauta avatar"
    />
    <div class="min-w-0">
      <div>
        <span class="font-semibold text-white">Nauta</span>
        <span class="ml-1 rounded bg-[#5865f2] px-1 text-[10px] font-semibold text-white">BOT</span>
        <span class="ml-1 text-xs text-[#949ba4]">Today at 18:51</span>
      </div>
      <div class="mt-2 rounded-md border-l-4 border-[#57f287] bg-[#2b2d31] p-3">
        <div class="font-semibold text-white">Saved coordinates</div>
        <div class="mt-2 grid gap-2">
          <div><span class="font-semibold text-[#b5bac1]">iron-farm</span><br />X: 420, Y: 72, Z: -128</div>
          <div><span class="font-semibold text-[#b5bac1]">spawn-portal</span><br />X: 100, Y: 63, Z: -300</div>
        </div>
      </div>
    </div>
  </div>
</div>


## Previous / Next

[Back to /delete](/features/delete/)
