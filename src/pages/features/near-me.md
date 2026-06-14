---
layout: '@/layouts/PageLayout.astro'
title: Near Me
description: Find the saved coordinates closest to a position.
activeHeaderLink: Features
---

[Back to all features](/features/)

# /near-me

## What It Does

Find the saved coordinates closest to a position. You can use this when you are somewhere in your Minecraft world and want to know which saved location is nearby.

## Syntax

```txt
/near-me
```

## Fields

- X: current X coordinate
- Y: current Y coordinate
- Z: current Z coordinate
- Dimension: world dimension, such as Overworld, Nether, or End
- Limit: optional number of nearby saved coordinates to show

## Example

<div class="not-prose rounded-md border border-[#3f4147] bg-[#313338] p-4 text-sm text-[#dbdee1]">
  <div class="mb-3 text-xs font-semibold uppercase text-[#b5bac1]"># coordinates</div>
  <div class="flex gap-3">
    <div class="flex h-10 w-10 shrink-0 items-center justify-center rounded-full bg-[#5865f2] font-semibold text-white">A</div>
    <div>
      <div>
        <span class="font-semibold text-white">Average</span>
        <span class="ml-1 text-xs text-[#949ba4]">Today at 18:42</span>
      </div>
      <div class="mt-1 rounded-md bg-[#2b2d31] px-3 py-2">/near-me x: 120 y: 64 z: -340 dimension: Overworld</div>
    </div>
  </div>

  <div class="mt-4 flex gap-3">
    <div class="flex h-10 w-10 shrink-0 items-center justify-center rounded-full bg-[#23a559] font-semibold text-white">N</div>
    <div class="min-w-0">
      <div>
        <span class="font-semibold text-white">Nauta</span>
        <span class="ml-1 rounded bg-[#5865f2] px-1 text-[10px] font-semibold text-white">BOT</span>
        <span class="ml-1 text-xs text-[#949ba4]">Today at 18:42</span>
      </div>
      <div class="mt-2 rounded-md border-l-4 border-[#57f287] bg-[#2b2d31] p-3">
        <div class="font-semibold text-white">Nearest saved coordinates</div>
        <div class="mt-2 grid gap-2">
          <div><span class="font-semibold text-[#b5bac1]">Spawn Portal</span><br />X: 100, Y: 63, Z: -300</div>
          <div><span class="font-semibold text-[#b5bac1]">Village</span><br />X: 180, Y: 70, Z: -410</div>
        </div>
      </div>
    </div>
  </div>
</div>

## Previous / Next

[Continue to /register](/features/register/)
