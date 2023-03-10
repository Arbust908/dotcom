<p align="center">
<img src="https://user-images.githubusercontent.com/10366059/207662097-031385a2-4fb1-4645-a370-4b335b90de45.png" width="300" alt="Refraction_logo_notion"/>
</p>

## Refraction

<pre align="center">
๐งช Working in Progress
</pre>

A base schafolding for web projects based in [Vitesse-nuxt3](https://github.com/antfu/vitesse-nuxt3)

### Stack

- ๐ [Nuxt 3](https://v3.nuxtjs.org) - SSR, ESR, File-based routing, components auto importing, modules, etc.

- โก๏ธ [Vite](https://vitejs.dev) - Instant HMR

- ๐จ [UnoCSS](https://github.com/antfu/unocss) - The instant on-demand atomic CSS engine.

- ๐ Use icons from any icon sets in Pure CSS, powered by [UnoCSS](https://github.com/antfu/unocss)

- ๐ [State Management via Pinia](https://pinia.esm.dev), see [./composables/user.ts](./composables/user.ts)

- ๐ฅ [VueUse](https://vueuse.org)

- ๐ฆพ [TypeScript](https://www.typescriptlang.org), of course

- ๐: ORM via [Prisma.io](https://www.prisma.io)

- ๐ [Planetscale DB](https://planetscale.com/)

---

``` bash
npx prisma init --datasource-provider mysql
postgresql, mysql, sqlite, sqlserver, mongodb, cockroachdb

npx prisma migrate dev --name init
npx prisma studio
```
