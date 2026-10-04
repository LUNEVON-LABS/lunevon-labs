# How Can an Android App Be Just 95 KB?

**Published:** 2026-09-29  
**Type:** Engineering teardown  
**Topics:** Android · APK · Java · Native Android · Software size

## Research question

How small can a modern Android application remain when it relies directly on the platform and avoids shipping heavy additional software layers?

## Reference build

The investigation examines a specific LUNEVON DI build whose APK size is:

**95,166 bytes — 95.17 decimal kB / 92.94 KiB**

The measurement refers to the APK distribution file, not RAM usage or a universal installed size.

## What the publication examines

- APK composition;
- compressed DEX contribution;
- Android resources;
- signing and ZIP overhead;
- native platform APIs;
- Java and Canvas;
- the effect of minimizing bundled dependencies.

## Important limitation

The article describes one identified build. It does not claim that smaller APK size automatically means lower memory use, better performance or superior software quality.

## Read

- [English publication](https://lunevon.com/en/labs/publications/android-app-95-kb/)
- [Русская публикация](https://lunevon.com/labs/publications/android-app-95-kb/)

---

Canonical full article: **lunevon.com**
