# Third-party notices

@buun_group/plotwork-mcp 0.5.0 is licensed under the MIT licence, in the file LICENSE. The single file plotwork-mcp.mjs also contains code and data from other people. This file lists them, with the licence each is used under and the full licence text. Those licences apply to that material. The MIT licence of @buun_group/plotwork-mcp does not replace them, and it does not cover the vendor artwork described under "Trademarks and official icons".

The build writes this file from the contents of the bundle. Do not edit it.

## TL;DR

| Question | Answer |
|---|---|
| Which licence covers the Plotwork code? | MIT, in the file LICENSE. |
| Which third-party code is in the bundle? | 4 npm packages: @modelcontextprotocol/core 2.3.1, @modelcontextprotocol/server 2.3.1, elkjs 0.12.0, zod 4.6.6. |
| Which third-party data is in the bundle? | Lucide icons; Simple Icons; SVG Logos, through @iconify-json/logos; Devicon, through @iconify-json/devicon; Kubernetes community icons, through @iconify-json/k8s; IBM Carbon icons, through @iconify-json/carbon; Inter font metrics and glyphs; JetBrains Mono font metrics and glyphs. |
| Are official vendor icons in the bundle? | Yes: AWS, Microsoft Azure, Google Cloud. They are not covered by the MIT licence. |
| Where is the full text of each licence? | Under "Licence texts" at the end of this file. |

## Components

| Component | Version | Kind | Used under | Licence text |
|---|---|---|---|---|
| @modelcontextprotocol/core | 2.3.1 | Code | MIT AND Apache-2.0 | [text 1](#licence-text-1) |
| @modelcontextprotocol/server | 2.3.1 | Code | MIT AND Apache-2.0 | [text 1](#licence-text-1) |
| elkjs | 0.12.0 | Code | EPL-2.0 | [text 2](#licence-text-2), [text 3](#licence-text-3) |
| zod | 4.6.6 | Code | MIT | [text 4](#licence-text-4) |
| Lucide icons | 1.49.0 | Data | ISC | [text 5](#licence-text-5) |
| Simple Icons | 16.35.0 | Data | CC0-1.0 | [text 6](#licence-text-6) |
| SVG Logos, through @iconify-json/logos | 1.2.17 | Data | CC0-1.0 | [text 7](#licence-text-7) |
| Devicon, through @iconify-json/devicon | 1.2.71 | Data | MIT | [text 8](#licence-text-8) |
| Kubernetes community icons, through @iconify-json/k8s | 1.2.2 | Data | Apache-2.0 | [text 9](#licence-text-9) |
| IBM Carbon icons, through @iconify-json/carbon | 1.2.28 | Data | Apache-2.0 | [text 10](#licence-text-10) |
| Inter font metrics and glyphs | 5.3.0 | Data | OFL-1.1 | [text 11](#licence-text-11) |
| JetBrains Mono font metrics and glyphs | 5.3.0 | Data | OFL-1.1 | [text 12](#licence-text-12) |

## Software in the bundle

### @modelcontextprotocol/core 2.3.1

- Licence declared: Apache-2.0
- Used under: MIT AND Apache-2.0
- Repository: https://github.com/modelcontextprotocol/typescript-sdk
- Copyright: Copyright (c) 2024-2025 Model Context Protocol a Series of LF Projects, LLC.
- NOTICE file: none shipped
- Licence text: [text 1](#licence-text-1)
- The package.json says MIT. The licence file says the project is moving from MIT to Apache-2.0: new code is Apache-2.0, and code whose authors have not agreed to relicense stays MIT. Both licences are reproduced and both apply.
- The same file licenses the project's documentation under CC-BY-4.0. No documentation is part of the bundle.

### @modelcontextprotocol/server 2.3.1

- Licence declared: Apache-2.0
- Used under: MIT AND Apache-2.0
- Repository: https://github.com/modelcontextprotocol/typescript-sdk
- Copyright: Copyright (c) 2024-2025 Model Context Protocol a Series of LF Projects, LLC.
- NOTICE file: none shipped
- Licence text: [text 1](#licence-text-1)
- The package.json says MIT. The licence file says the project is moving from MIT to Apache-2.0: new code is Apache-2.0, and code whose authors have not agreed to relicense stays MIT. Both licences are reproduced and both apply.
- The same file licenses the project's documentation under CC-BY-4.0. No documentation is part of the bundle.

### elkjs 0.12.0

- Licence declared: EPL-2.0 OR GPL-3.0-or-later
- Used under: EPL-2.0
- Repository: https://github.com/kieler/elkjs
- Copyright: No copyright line in the licence file. The package names Ulf Rüegg as its author.
- NOTICE file: none shipped
- Licence text: [text 2](#licence-text-2), [text 3](#licence-text-3)
- No ELK source was edited. The build bundles the package's files into plotwork-mcp.mjs with esbuild, which prints the code again: spacing and quote style change, and what the code does does not.
- Plotwork distributes the EPL-2.0 components in object code form, inside plotwork-mcp.mjs, which is licensed under the MIT licence of Buun Group. As the Eclipse Public License 2.0 requires of a distribution under another licence: Buun Group disclaims, on behalf of all other Contributors, all warranties and conditions, express or implied, including warranties or conditions of title, non-infringement, merchantability, and fitness for a particular purpose; Buun Group excludes, on behalf of all Contributors, all liability for damages, including direct, indirect, special, incidental, and consequential damages; any provision of the MIT licence that differs from the Eclipse Public License 2.0 is offered by Buun Group alone and not by any other party; and the source code of the EPL-2.0 components is available from the locations named in this section.
- Source code of the version in this package: https://www.npmjs.com/package/elkjs/v/0.12.0 and https://github.com/kieler/elkjs. The layout code in it is compiled from the Java sources of the Eclipse Layout Kernel (ELK), available at https://github.com/eclipse-elk/elk.
- The package is offered under EPL-2.0 or GPL-3.0-or-later. Plotwork relies on the EPL-2.0 option.
- The compiled layout code also contains classes of the Eclipse Modeling Framework (EMF) and the Eclipse Xtext Xbase library, which are licensed under EPL-2.0, and of Google Guava and the Google Web Toolkit (GWT) runtime, which are licensed under Apache-2.0. The text of Apache-2.0 is in the licence texts below.
- Also contains: Google Guava (com.google.common) and the GWT runtime, compiled into elkjs, Apache-2.0, https://github.com/google/guava and https://github.com/gwtproject/gwt
- Also contains: Eclipse Modeling Framework (org.eclipse.emf) and Xtext Xbase library classes, compiled into elkjs, EPL-2.0, https://eclipse.dev/modeling/emf/ and https://eclipse.dev/Xtext/

### zod 4.6.6

- Licence declared: MIT
- Used under: MIT
- Repository: https://github.com/colinhacks/zod
- Copyright: Copyright (c) 2025 Colin McDonnell
- NOTICE file: none shipped
- Licence text: [text 4](#licence-text-4)

## Data in the bundle

### Lucide icons (lucide-static 1.49.0)

- Licence declared: ISC
- Used under: ISC
- Repository: https://github.com/lucide-icons/lucide
- What is in the bundle: The path data of each icon, copied by gen:icons into a generated module and drawn as inline SVG.
- Copyright: Copyright (c) 2026 Lucide Icons and Contributors
- Copyright: Copyright (c) 2013-present Cole Bemis
- NOTICE file: none shipped
- Licence text: [text 5](#licence-text-5)
- The licence file holds ISC for Lucide and MIT for the icons that derive from the Feather project. Both texts are reproduced.

### Simple Icons (simple-icons 16.35.0)

- Licence declared: CC0-1.0
- Used under: CC0-1.0
- Repository: https://github.com/simple-icons/simple-icons
- What is in the bundle: The path data of each brand mark, copied by gen:icons into a generated module and drawn as inline SVG. gen:icon-art splits it into the catalog the bundle holds, with the paths of the marks most diagrams draw, and the shards in icons/simple/ beside the bundle, which hold every path.
- Copyright: No copyright line in the licence file. The package names Simple Icons Collaborators as its author.
- NOTICE file: none shipped
- Licence text: [text 6](#licence-text-6)
- Simple Icons is released under CC0 1.0. Its disclaimer states that this does not mean every icon within it is CC0, and that brand logos remain trademarks of their owners. See https://github.com/simple-icons/simple-icons/blob/develop/DISCLAIMER.md.
- A mark under a non-commercial licence is not bundled: the brand draws a generic glyph instead.
- The marks are used only to refer to the technologies they name. Their inclusion does not imply endorsement by, or affiliation with, their owners.

92 of these marks carry a licence of their own, named by its SPDX identifier. Each is credited here with the place its artwork comes from:

- AIOHTTP (`aiohttp`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://github.com/aio-libs/aiohttp/blob/fb5fe72b1bca3b899af579d376f5fe45745410e4/docs/aiohttp-plain.svg
- Airbrake (`airbrake`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://github.com/airbrake/slate/blob/c116f2968bcf4dfda126511de0a2d0f0dc8b6a8e/source/images/logo.svg
- Android (`android`): CC-BY-3.0 (https://spdx.org/licenses/CC-BY-3.0). Source: https://partnermarketinghub.withgoogle.com/brands/android/visual-identity/visual-identity/logo-lock-ups
- Angular (`angular`): CC-BY-4.0 (https://spdx.org/licenses/CC-BY-4.0). Source: https://angular.dev/press-kit
- Apache (`apache`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://www.apache.org/foundation/press/kit
- Apache Airflow (`apacheairflow`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Arrow (`apachearrow`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://arrow.apache.org/visual_identity
- Apache Avro (`apacheavro`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Cassandra (`apachecassandra`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://www.apache.org/logos
- Apache CloudStack (`apachecloudstack`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache CouchDB (`apachecouchdb`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache DolphinScheduler (`apachedolphinscheduler`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Doris (`apachedoris`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Druid (`apachedruid`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache ECharts (`apacheecharts`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Flink (`apacheflink`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Groovy (`apachegroovy`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Guacamole (`apacheguacamole`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Hadoop (`apachehadoop`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache HBase (`apachehbase`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Hive (`apachehive`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache JMeter (`apachejmeter`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Kafka (`apachekafka`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Kylin (`apachekylin`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Lucene (`apachelucene`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Maven (`apachemaven`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache NiFi (`apachenifi`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Parquet (`apacheparquet`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Pulsar (`apachepulsar`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache RocketMQ (`apacherocketmq`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Solr (`apachesolr`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Spark (`apachespark`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Storm (`apachestorm`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Superset (`apachesuperset`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Apache Tomcat (`apachetomcat`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://apache.org/logos
- Aspire (`aspire`): CC0-1.0 (https://spdx.org/licenses/CC0-1.0). Source: https://github.com/microsoft/aspire-brand/blob/f9eb464dec47870de23d55dd7b3c00d39122813d/logo/developer-tools/aspire-plain.svg
- Authelia (`authelia`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://github.com/authelia/authelia/blob/8316cd4eb7a6f0778c8f480c61ad76a88416fc3a/docs/static/images/branding/logo.svg
- Bootstrap (`bootstrap`): MIT (https://spdx.org/licenses/MIT). Source: https://getbootstrap.com/docs/5.3/about/brand
- Broadcom (`broadcom`): custom (https://logorequest.broadcom.com/Home.aspx). Source: https://www.broadcom.com/support
- Canonical (`canonical`): CC-BY-SA-3.0 (https://spdx.org/licenses/CC-BY-SA-3.0). Source: https://design.ubuntu.com/resources
- Codeberg (`codeberg`): CC0-1.0 (https://spdx.org/licenses/CC0-1.0). Source: https://codeberg.org/Codeberg/Design/src/commit/ac514aa9aaa2457d4af3c3e13df3ab136d22a49a/logo/special/codeberg-logo_special_fake-transaprency.svg
- Contentstack (`contentstack`): custom (https://www.contentstack.com/legal/terms-of-service). Source: https://www.contentstack.com
- Debian (`debian`): CC-BY-SA-3.0 (https://spdx.org/licenses/CC-BY-SA-3.0). Source: https://www.debian.org/logos
- Deno (`deno`): MIT (https://spdx.org/licenses/MIT). Source: https://github.com/denoland/docs/blob/5dee713844c7447f80acd4093caa9d350d80bf36/static/img/logo.svg
- Dify (`dify`): custom (https://dify.ai/end-user-license-agreement). Source: https://github.com/langgenius/dify/blob/48f6b2e885eb40230dfe318fe4d3fb71b50dbc02/web/public/logo/logo.svg
- .NET (`dotnet`): CC0-1.0 (https://spdx.org/licenses/CC0-1.0). Source: https://github.com/dotnet/brand/blob/c7d0f51b8ec59531332d05fb27a5b758a7a3d689/logo/dotnet-logo.svg
- Fedora (`fedora`): custom (https://docs.fedoraproject.org/en-US/project/brand/). Source: https://docs.fedoraproject.org/en-US/project/brand/
- Fluentd (`fluentd`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://docs.fluentd.org/quickstart/logo
- Flux (`flux`): custom (https://www.linuxfoundation.org/legal/trademark-usage). Source: https://github.com/cncf/artwork/blob/c2e619cdf85e8bac090ceca7c0834c5cfedf9426/projects/flux/icon/black/flux-icon-black.svg
- Forgejo (`forgejo`): CC-BY-SA-4.0 (https://spdx.org/licenses/CC-BY-SA-4.0). Source: https://codeberg.org/forgejo/meta/raw/branch/readme/branding/logo/forgejo-monochrome.svg
- Git (`git`): CC-BY-3.0 (https://spdx.org/licenses/CC-BY-3.0). Source: https://git-scm.com/community/logos
- GitHub Copilot (`githubcopilot`): MIT (https://spdx.org/licenses/MIT). Source: https://primer.style/foundations/icons/copilot-24
- Gleam (`gleam`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://gleam.run
- GNU Bash (`gnubash`): MIT (https://spdx.org/licenses/MIT). Source: https://github.com/odb/official-bash-logo/tree/61eff022f2dad3c7468f5deb4f06652d15f2c143
- GNU Emacs (`gnuemacs`): GPL-2.0-or-later (https://spdx.org/licenses/GPL-2.0-or-later). Source: https://git.savannah.gnu.org/cgit/emacs.git/tree/etc/images/icons/hicolor/scalable/apps/emacs.svg
- GNU Privacy Guard (`gnuprivacyguard`): GPL-3.0-or-later (https://spdx.org/licenses/GPL-3.0-or-later). Source: https://git.gnupg.org/cgi-bin/gitweb.cgi?p=gnupg.git;a=tree;f=artwork/icons
- Harbor (`harbor`): custom (https://www.linuxfoundation.org/legal/trademark-usage). Source: https://github.com/cncf/artwork/blob/ff2b2b5216e22f001ddd444ca580c484dd10302e/projects/harbor/icon/black/harbor-icon-black.svg
- JavaScript (`javascript`): MIT (https://spdx.org/licenses/MIT). Source: https://github.com/voodootikigod/logo.js/blob/1544bdeed6d618a6cfe4f0650d04ab8d9cfa76d9/js.svg
- Jenkins (`jenkins`): CC-BY-SA-3.0 (https://spdx.org/licenses/CC-BY-SA-3.0). Source: https://get.jenkins.io/art/
- JHipster (`jhipster`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://github.com/jhipster/jhipster-artwork/blob/1085d85ab6d819b9ef7f6cc710ec8a4977b95e90/logos/JHipster%20bowtie.svg
- Kedro (`kedro`): custom (https://www.linuxfoundation.org/trademark-usage). Source: https://github.com/kedro-org/kedro-brand-identity/blob/7f7b380cb1a2951c06ca292f0d2b442db895f804/icon/black/kedro-icon-svgo-black.svg
- Keycloak (`keycloak`): custom (https://www.linuxfoundation.org/legal/trademark-usage). Source: https://github.com/keycloak/keycloak-misc/blob/dee033f2d6d6b5c3a6ce8eb84e285f7e5626dbf6/logo/icon-black.svg
- Markdown (`markdown`): CC0-1.0 (https://spdx.org/licenses/CC0-1.0). Source: https://github.com/dcurtis/markdown-mark/tree/360a3657fef7f6ad0b303296a95ad52985caa0d3
- Mercurial (`mercurial`): GPL-2.0-or-later (https://spdx.org/licenses/GPL-2.0-or-later). Source: https://www.mercurial-scm.org/hg-logo/
- MiniMax (`minimax`): custom (https://github.com/simple-icons/simple-icons/pull/13982#issuecomment-3531627803). Source: https://github.com/MiniMax-AI/MiniMax-01/blob/57cf223b177e99636c7711a0f179e9fdc9c38e8a/figures/minimax.svg
- Neovim (`neovim`): CC-BY-SA-3.0 (https://spdx.org/licenses/CC-BY-SA-3.0). Source: https://neovim.io
- NixOS (`nixos`): CC-BY-4.0 (https://spdx.org/licenses/CC-BY-4.0). Source: https://brand.nixos.org/logos/nixos-logomark-black-flat-minimal.svg
- OCaml (`ocaml`): Unlicense (https://spdx.org/licenses/Unlicense). Source: https://ocaml.org/logo
- OpenBao (`openbao`): CC-BY-SA-4.0 (https://spdx.org/licenses/CC-BY-SA-4.0). Source: https://github.com/openbao/artwork/blob/8f75904040f9ca4fcba2b7a46581ecee536315b5/black/openbao-single-black.svg
- OpenJDK (`openjdk`): BSD-3-Clause (https://spdx.org/licenses/BSD-3-Clause). Source: https://hg.openjdk.java.net/duke/duke/file/ca00f100dafc/vector/Agent.svg
- OpenTelemetry (`opentelemetry`): CC-BY-4.0 (https://spdx.org/licenses/CC-BY-4.0). Source: https://cncf-branding.netlify.app/projects/opentelemetry/
- Packagist (`packagist`): MIT (https://spdx.org/licenses/MIT). Source: https://github.com/composer/packagist/issues/1147#issuecomment-747951608
- PHP (`php`): CC-BY-SA-4.0 (https://spdx.org/licenses/CC-BY-SA-4.0). Source: https://php.net/download-logos.php
- RocksDB (`rocksdb`): CC-BY-4.0 (https://spdx.org/licenses/CC-BY-4.0). Source: https://github.com/facebook/rocksdb/blob/9ed96703d11a1cf4af0e1c1db0e4a6057a8e5d42/docs/static/logo.svg
- Rocky Linux (`rockylinux`): CC-BY-SA-4.0 (https://spdx.org/licenses/CC-BY-SA-4.0). Source: https://github.com/rocky-linux/branding/blob/94e97dd30b87d909cc4f6a6838a2926f77f9ac47/logo/src/icon-black.svg
- Rook (`rook`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://github.com/rook/artwork/blob/d252db9f43753e6abf64db0ce12d38916a5de464/logo/Rook_Icon.svg
- Ruby (`ruby`): CC-BY-SA-2.5 (https://spdx.org/licenses/CC-BY-SA-2.5). Source: https://www.ruby-lang.org/en/about/logo/
- Rust (`rust`): CC-BY-SA-4.0 (https://spdx.org/licenses/CC-BY-SA-4.0). Source: https://www.rust-lang.org
- Salt Project (`saltproject`): Apache-2.0 (https://spdx.org/licenses/Apache-2.0). Source: https://saltproject.io
- Sanity (`sanity`): MIT (https://spdx.org/licenses/MIT). Source: https://github.com/sanity-io/logos/blob/e298a1ac2757c83910fe08b496a115bc9aef06bd/src/sanityMonogram.tsx
- Sidekiq (`sidekiq`): CC-BY-SA-4.0 (https://spdx.org/licenses/CC-BY-SA-4.0). Source: https://sidekiq.org/about.html
- Solidity (`solidity`): CC-BY-4.0 (https://spdx.org/licenses/CC-BY-4.0). Source: https://docs.soliditylang.org/en/v0.8.6/brand-guide.html
- SourceHut (`sourcehut`): CC0-1.0 (https://spdx.org/licenses/CC0-1.0). Source: https://sourcehut.org/logo/
- SQLAlchemy (`sqlalchemy`): MIT (https://spdx.org/licenses/MIT). Source: https://commons.wikimedia.org/wiki/File:SQLAlchemy.svg
- Storybook (`storybook`): MIT (https://spdx.org/licenses/MIT). Source: https://github.com/storybookjs/brand/tree/6f4d67f65f8275c53c310a73a8da6c6e96c8488c
- TypeORM (`typeorm`): MIT (https://spdx.org/licenses/MIT). Source: https://github.com/typeorm/typeorm/blob/e7649d2746f907ff36b1efb600402dedd5f5a499/resources/logo_big.png
- Webex (`webex`): custom (https://www.cisco.com/c/en/us/about/legal/trademarks.html). Source: https://github.com/momentum-design/momentum-ui/blob/970c5bec962a3f72e17e0b7ed69f2c38d298c405/icons-rebrand/svg/webex-helix-filled.svg
- WebGPU (`webgpu`): CC-BY-4.0 (https://spdx.org/licenses/CC-BY-4.0). Source: https://www.w3.org/2023/02/webgpu-logos.html
- Webpack (`webpack`): custom (https://js.foundation/about/governance/trademark-policy). Source: https://webpack.js.org/branding
- Yarn (`yarn`): CC-BY-4.0 (https://spdx.org/licenses/CC-BY-4.0). Source: https://github.com/yarnpkg/assets/blob/76d30ca2aebed5b73ea8131d972218fb860bd32d/yarn-kitten-circle.svg
- Zig (`zig`): CC-BY-SA-4.0 (https://spdx.org/licenses/CC-BY-SA-4.0). Source: https://github.com/ziglang/logo/blob/6446ba8e37a0651da720d8869e1ce9264fa0c0b9/zig-mark.svg
- Zod (`zod`): MIT (https://spdx.org/licenses/MIT). Source: https://github.com/colinhacks/zod/blob/ff89187172ac6aa4a6264592980d1628ee785242/logo/Logo%20White.ai

### SVG Logos, through @iconify-json/logos (@iconify-json/logos 1.2.17)

- Licence declared: CC0-1.0
- Used under: CC0-1.0
- Repository: https://github.com/gilbarbara/logos
- What is in the bundle: The full colour file of each of a few brand marks that Simple Icons does not publish, copied by gen:icons into a generated module as the text of a standalone SVG and drawn unmodified, as an image, on a light tile. gen:icon-art keeps the files most diagrams draw in the bundle and every file in the shards in icons/simple/ beside it.
- Copyright: No copyright line in the licence file.
- Licence file: the package ships none, so the licence text its authors publish is used, from https://raw.githubusercontent.com/gilbarbara/logos/master/LICENSE.txt
- NOTICE file: none shipped
- Licence text: [text 7](#licence-text-7)
- The package info.json names Gil Barbara as the author and CC0 1.0 as the licence, and the package ships no licence file, so the licence text its authors publish is used.
- Brand logos remain trademarks of their owners, and a CC0 dedication does not license a trademark. The marks are used only to refer to the technologies and services they name. Their inclusion does not imply endorsement by, or affiliation with, their owners.

### Devicon, through @iconify-json/devicon (@iconify-json/devicon 1.2.71)

- Licence declared: MIT
- Used under: MIT
- Repository: https://github.com/devicons/devicon
- What is in the bundle: The full colour file of each of a few brand marks that neither Simple Icons nor SVG Logos publishes, such as HAProxy and Teleport, copied by gen:icons into the same generated module as the SVG Logos marks, as the text of a standalone SVG, and drawn unmodified, as an image, on a light tile. gen:icon-art keeps the files most diagrams draw in the bundle and every file in the shards in icons/simple/ beside it.
- Copyright: Copyright (c) 2015 konpa
- Licence file: the package ships none, so the licence text its authors publish is used, from https://github.com/devicons/devicon/blob/master/LICENSE
- NOTICE file: none shipped
- Licence text: [text 8](#licence-text-8)
- The package info.json names konpa as the author and MIT as the licence, and the package ships no licence file, so the licence file of the Devicon project, from the devicon package on npm, is used.
- Only a few marks that neither Simple Icons nor SVG Logos publishes are taken from Devicon; scripts/logos-manifest.ts names each one with pack devicon.
- Brand logos remain trademarks of their owners, and the MIT licence of the collection does not license a trademark. The marks are used only to refer to the technologies they name. Their inclusion does not imply endorsement by, or affiliation with, their owners.

### Kubernetes community icons, through @iconify-json/k8s (@iconify-json/k8s 1.2.2)

- Licence declared: Apache-2.0
- Used under: Apache-2.0
- Repository: https://github.com/kubernetes/community/tree/master/icons
- What is in the bundle: The full colour file of each Kubernetes resource kind and cluster part in the k8s set, copied by gen:icons into a generated module as the text of a standalone SVG and drawn unmodified, as an image, on a light tile. gen:icon-art keeps the files most diagrams draw in the bundle and every file in the shards in icons/k8s/ beside it.
- Copyright: No copyright line in the licence file.
- Licence file: the package ships none, so the licence text its authors publish is used, from https://github.com/kubernetes/community/blob/master/LICENSE
- NOTICE file: none shipped
- Licence text: [text 9](#licence-text-9)
- The package info.json names The Kubernetes Authors as the author and Apache-2.0 as the licence, and the package ships no licence file, so the licence file of the kubernetes/community repository the icons come from is used.
- The Kubernetes Icons Set is offered under Apache-2.0 or CC-BY-4.0, at the user's choice. Plotwork relies on the Apache-2.0 option.
- The Kubernetes logo is a registered trademark of The Linux Foundation, and the licence of the icons does not license a trademark. The icons are used only to refer to the Kubernetes objects they name.

### IBM Carbon icons, through @iconify-json/carbon (@iconify-json/carbon 1.2.28)

- Licence declared: Apache-2.0
- Used under: Apache-2.0
- Repository: https://github.com/carbon-design-system/carbon/tree/main/packages/icons
- What is in the bundle: The path data of the glyph for each kind of cloud service and of the IBM Cloud pictograms, copied by gen:icons into a generated module and drawn as inline SVG.
- Copyright: Copyright 2015 IBM Corp.
- Licence file: the package ships none, so the licence text its authors publish is used, from https://github.com/carbon-design-system/carbon/blob/main/LICENSE
- NOTICE file: none shipped
- Licence text: [text 10](#licence-text-10)
- The package info.json names IBM as the author and Apache-2.0 as the licence. IBM trademark rules for the IBM logo still apply.

### Inter font metrics and glyphs (@fontsource/inter 5.3.0)

- Licence declared: OFL-1.1
- Used under: OFL-1.1
- Repository: https://github.com/fontsource/font-files (directory fonts/google/inter)
- What is in the bundle: Advance widths of Inter at weights 400, 500, and 600 for the code points 32 to 255 and 18 further symbols, measured by gen:metrics and stored as numbers; and the font tables and glyph outlines of the latin subset at the same weights, copied by gen:font-glyphs. Each picture embeds a subset of the font holding only the characters it draws, with the copyright line and the licence's name and address in its name table.
- Copyright: Copyright 2016 The Inter Project Authors (https://github.com/rsms/inter) Inter-Italic[opsz,wght].ttf: Copyright 2016 The Inter Project Authors (https://github.com/rsms/inter)
- NOTICE file: none shipped
- Licence text: [text 11](#licence-text-11)
- The SIL Open Font License 1.1 allows the font to be subset and embedded. Inter declares no Reserved Font Name. This licence covers the font data and the subsets in pictures, not code.

### JetBrains Mono font metrics and glyphs (@fontsource/jetbrains-mono 5.3.0)

- Licence declared: OFL-1.1
- Used under: OFL-1.1
- Repository: https://github.com/fontsource/font-files (directory fonts/google/jetbrains-mono)
- What is in the bundle: One advance width, the width of the letter m as a fraction of the em, measured by gen:metrics and stored as a number; and the font tables and glyph outlines of the latin subset at weight 400, copied by gen:font-glyphs. Each picture embeds a subset holding only the characters it draws, with the copyright line and the licence's name and address in its name table.
- Copyright: Copyright 2020 The JetBrains Mono Project Authors (https://github.com/JetBrains/JetBrainsMono) JetBrainsMono-Italic[wght].ttf: Copyright 2020 The JetBrains Mono Project Authors (https://github.com/JetBrains/JetBrainsMono)
- NOTICE file: none shipped
- Licence text: [text 12](#licence-text-12)
- The SIL Open Font License 1.1 allows the font to be subset and embedded. JetBrains Mono declares no Reserved Font Name.

## Trademarks and official icons

AWS, Microsoft Azure, Google Cloud, and the names, logos, and icons of other providers are trademarks of their respective owners. Plotwork uses them only to depict those providers' services in architecture diagrams, shows the official icons unmodified, and is not affiliated with, endorsed by, or sponsored by any of them.

The vendor artwork below is NOT covered by the MIT licence of @buun_group/plotwork-mcp. It is the property of the vendors, it is included unmodified, and the vendors' terms govern its use. Nothing in the MIT licence grants a right to it.

### AWS

- Provider key: aws
- Pack: AWS Architecture Icons, release 07312026
- Icon files used: 809, products added to the provider set: 778
- Retrieved: 2026-10-09
- Terms: https://aws.amazon.com/architecture/icons/
- Guidelines for the vendor's marks: https://aws.amazon.com/trademark-guidelines/
- The vendor's own wording, copied unchanged from the page named in each entry:
  - "We allow customers and partners to use these toolkits and assets to create architecture diagrams." (permits; https://aws.amazon.com/architecture/icons/)
  - "You can also put icons in materials like whitepapers, presentations, data sheets, and posters." (permits; https://aws.amazon.com/architecture/icons/)
  - "You will not alter the logo images in any manner, including but not limited to changing the proportion, color" (forbids; https://aws.amazon.com/trademark-guidelines/)
  - "Check that you’re using up-to-date icons, because some libraries may contain legacy icon sets." (note; https://aws.amazon.com/architecture/icons/)

### Microsoft Azure

- Provider key: azure
- Pack: Azure Public Service Icons V24
- Icon files used: 627, products added to the provider set: 624
- Retrieved: 2026-10-09
- Terms: https://learn.microsoft.com/en-us/azure/architecture/icons/
- The vendor's own wording, copied unchanged from the page named in each entry:
  - "Microsoft permits the use of these icons in architectural diagrams, training materials, or documentation. You can copy, distribute, and display the icons only for the permitted use unless granted explicit permission by Microsoft. Microsoft reserves all other rights." (permits; https://learn.microsoft.com/en-us/azure/architecture/icons/)
  - "Use the icon to illustrate how products can work together." (asks; https://learn.microsoft.com/en-us/azure/architecture/icons/)
  - "In diagrams, we recommend including the product name somewhere close to the icon." (asks; https://learn.microsoft.com/en-us/azure/architecture/icons/)
  - "Use the icons as they would appear within Azure." (asks; https://learn.microsoft.com/en-us/azure/architecture/icons/)
  - "Don't crop, flip, or rotate icons." (forbids; https://learn.microsoft.com/en-us/azure/architecture/icons/)
  - "Don't distort or change icon shape in any way." (forbids; https://learn.microsoft.com/en-us/azure/architecture/icons/)
  - "Don't use Microsoft product icons to represent your product or service." (forbids; https://learn.microsoft.com/en-us/azure/architecture/icons/)

### Google Cloud

- Provider key: gcp
- Pack: Google Cloud product icons (core and category), retrieved 2026-10-09
- Icon files used: 45, products added to the provider set: 36
- Retrieved: 2026-10-09
- Terms: https://cloud.google.com/icons
- The vendor's own wording, copied unchanged from the page named in each entry:
  - "Welcome to the official library for Google Cloud product icons. Here you can find the Google Cloud product icons you need for your diagrams, technical documentation, and more." (permits; https://cloud.google.com/icons)

## Licence texts

### Licence text 1

Licences in this text: Apache-2.0, MIT. Used by: @modelcontextprotocol/core 2.3.1, @modelcontextprotocol/server 2.3.1.

```text
The MCP project is undergoing a licensing transition from the MIT License to the Apache License, Version 2.0 ("Apache-2.0"). All new code and specification contributions to the project are licensed under Apache-2.0. Documentation contributions (excluding specifications) are licensed under CC-BY-4.0.

Contributions for which relicensing consent has been obtained are licensed under Apache-2.0. Contributions made by authors who originally licensed their work under the MIT License and who have not yet granted explicit permission to relicense remain licensed under the MIT License.

No rights beyond those granted by the applicable original license are conveyed for such contributions.

---

                                 Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to the Licensor for inclusion in the Work by the copyright
      owner or by an individual or Legal Entity authorized to submit on behalf
      of the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

---

MIT License

Copyright (c) 2024-2025 Model Context Protocol a Series of LF Projects, LLC.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

---

Creative Commons Attribution 4.0 International (CC-BY-4.0)

Documentation in this project (excluding specifications) is licensed under
CC-BY-4.0. See https://creativecommons.org/licenses/by/4.0/legalcode for
the full license text.
```

### Licence text 2

Licences in this text: EPL-2.0. Used by: elkjs 0.12.0.

```text
# Eclipse Public License - v 2.0

THE ACCOMPANYING PROGRAM IS PROVIDED UNDER THE TERMS OF THIS ECLIPSE
PUBLIC LICENSE (“AGREEMENT”). ANY USE, REPRODUCTION OR DISTRIBUTION OF
THE PROGRAM CONSTITUTES RECIPIENT'S ACCEPTANCE OF THIS AGREEMENT.

## 1. DEFINITIONS

“Contribution” means:

-   a\) in the case of the initial Contributor, the initial content
    Distributed under this Agreement, and
-   b\) in the case of each subsequent Contributor:
    -   i\) changes to the Program, and
    -   ii\) additions to the Program;

    where such changes and/or additions to the Program originate from
    and are Distributed by that particular Contributor. A Contribution
    “originates” from a Contributor if it was added to the Program by
    such Contributor itself or anyone acting on such Contributor's
    behalf. Contributions do not include changes or additions to the
    Program that are not Modified Works.

“Contributor” means any person or entity that Distributes the Program.

“Licensed Patents” mean patent claims licensable by a Contributor which
are necessarily infringed by the use or sale of its Contribution alone
or when combined with the Program.

“Program” means the Contributions Distributed in accordance with this
Agreement.

“Recipient” means anyone who receives the Program under this Agreement
or any Secondary License (as applicable), including Contributors.

“Derivative Works” shall mean any work, whether in Source Code or other
form, that is based on (or derived from) the Program and for which the
editorial revisions, annotations, elaborations, or other modifications
represent, as a whole, an original work of authorship.

“Modified Works” shall mean any work in Source Code or other form that
results from an addition to, deletion from, or modification of the
contents of the Program, including, for purposes of clarity any new file
in Source Code form that contains any contents of the Program. Modified
Works shall not include works that contain only declarations,
interfaces, types, classes, structures, or files of the Program solely
in each case in order to link to, bind by name, or subclass the Program
or Modified Works thereof.

“Distribute” means the acts of a) distributing or b) making available in
any manner that enables the transfer of a copy.

“Source Code” means the form of a Program preferred for making
modifications, including but not limited to software source code,
documentation source, and configuration files.

“Secondary License” means either the GNU General Public License, Version
2.0, or any later versions of that license, including any exceptions or
additional permissions as identified by the initial Contributor.

## 2. GRANT OF RIGHTS

-   a\) Subject to the terms of this Agreement, each Contributor hereby
    grants Recipient a non-exclusive, worldwide, royalty-free copyright
    license to reproduce, prepare Derivative Works of, publicly display,
    publicly perform, Distribute and sublicense the Contribution of such
    Contributor, if any, and such Derivative Works.
-   b\) Subject to the terms of this Agreement, each Contributor hereby
    grants Recipient a non-exclusive, worldwide, royalty-free patent license
    under Licensed Patents to make, use, sell, offer to sell, import and
    otherwise transfer the Contribution of such Contributor, if any, in
    Source Code or other form. This patent license shall apply to the
    combination of the Contribution and the Program if, at the time the
    Contribution is added by the Contributor, such addition of the
    Contribution causes such combination to be covered by the
    Licensed Patents. The patent license shall not apply to any other
    combinations which include the Contribution. No hardware per se is
    licensed hereunder.
-   c\) Recipient understands that although each Contributor grants the
    licenses to its Contributions set forth herein, no assurances are
    provided by any Contributor that the Program does not infringe the
    patent or other intellectual property rights of any other entity. Each
    Contributor disclaims any liability to Recipient for claims brought by
    any other entity based on infringement of intellectual property rights
    or otherwise. As a condition to exercising the rights and licenses
    granted hereunder, each Recipient hereby assumes sole responsibility to
    secure any other intellectual property rights needed, if any. For
    example, if a third party patent license is required to allow Recipient
    to Distribute the Program, it is Recipient's responsibility to acquire
    that license before distributing the Program.
-   d\) Each Contributor represents that to its knowledge it has sufficient
    copyright rights in its Contribution, if any, to grant the copyright
    license set forth in this Agreement.
-   e\) Notwithstanding the terms of any Secondary License, no Contributor
    makes additional grants to any Recipient (other than those set forth in
    this Agreement) as a result of such Recipient's receipt of the Program
    under the terms of a Secondary License (if permitted under the terms of
    Section 3).

## 3. REQUIREMENTS

3.1 If a Contributor Distributes the Program in any form, then:

-   a\) the Program must also be made available as Source Code, in accordance
    with section 3.2, and the Contributor must accompany the Program with a
    statement that the Source Code for the Program is available under this
    Agreement, and informs Recipients how to obtain it in a reasonable
    manner on or through a medium customarily used for software exchange;
    and
-   b\) the Contributor may Distribute the Program under a license different
    than this Agreement, provided that such license:
    -   i\) effectively disclaims on behalf of all other Contributors all
        warranties and conditions, express and implied, including warranties or
        conditions of title and non-infringement, and implied warranties or
        conditions of merchantability and fitness for a particular purpose;
    -   ii\) effectively excludes on behalf of all other Contributors all
        liability for damages, including direct, indirect, special, incidental
        and consequential damages, such as lost profits;
    -   iii\) does not attempt to limit or alter the recipients' rights in the
        Source Code under section 3.2; and
    -   iv\) requires any subsequent distribution of the Program by any party to
        be under a license that satisfies the requirements of this section 3.

3.2 When the Program is Distributed as Source Code:

-   a\) it must be made available under this Agreement, or if the Program (i)
    is combined with other material in a separate file or files made
    available under a Secondary License, and (ii) the initial Contributor
    attached to the Source Code the notice described in Exhibit A of this
    Agreement, then the Program may be made available under the terms of
    such Secondary Licenses, and
-   b\) a copy of this Agreement must be included with each copy of
    the Program.

3.3 Contributors may not remove or alter any copyright, patent,
trademark, attribution notices, disclaimers of warranty, or limitations
of liability (‘notices’) contained within the Program from any copy of
the Program which they Distribute, provided that Contributors may add
their own appropriate notices.

## 4. COMMERCIAL DISTRIBUTION

Commercial distributors of software may accept certain responsibilities
with respect to end users, business partners and the like. While this
license is intended to facilitate the commercial use of the Program, the
Contributor who includes the Program in a commercial product offering
should do so in a manner which does not create potential liability for
other Contributors. Therefore, if a Contributor includes the Program in
a commercial product offering, such Contributor (“Commercial
Contributor”) hereby agrees to defend and indemnify every other
Contributor (“Indemnified Contributor”) against any losses, damages and
costs (collectively “Losses”) arising from claims, lawsuits and other
legal actions brought by a third party against the Indemnified
Contributor to the extent caused by the acts or omissions of such
Commercial Contributor in connection with its distribution of the
Program in a commercial product offering. The obligations in this
section do not apply to any claims or Losses relating to any actual or
alleged intellectual property infringement. In order to qualify, an
Indemnified Contributor must: a) promptly notify the Commercial
Contributor in writing of such claim, and b) allow the Commercial
Contributor to control, and cooperate with the Commercial Contributor
in, the defense and any related settlement negotiations. The Indemnified
Contributor may participate in any such claim at its own expense.

For example, a Contributor might include the Program in a commercial
product offering, Product X. That Contributor is then a Commercial
Contributor. If that Commercial Contributor then makes performance
claims, or offers warranties related to Product X, those performance
claims and warranties are such Commercial Contributor's responsibility
alone. Under this section, the Commercial Contributor would have to
defend claims against the other Contributors related to those
performance claims and warranties, and if a court requires any other
Contributor to pay any damages as a result, the Commercial Contributor
must pay those damages.

## 5. NO WARRANTY {#warranty}

EXCEPT AS EXPRESSLY SET FORTH IN THIS AGREEMENT, AND TO THE EXTENT
PERMITTED BY APPLICABLE LAW, THE PROGRAM IS PROVIDED ON AN “AS IS”
BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, EITHER EXPRESS OR
IMPLIED INCLUDING, WITHOUT LIMITATION, ANY WARRANTIES OR CONDITIONS OF
TITLE, NON-INFRINGEMENT, MERCHANTABILITY OR FITNESS FOR A PARTICULAR
PURPOSE. Each Recipient is solely responsible for determining the
appropriateness of using and distributing the Program and assumes all
risks associated with its exercise of rights under this Agreement,
including but not limited to the risks and costs of program errors,
compliance with applicable laws, damage to or loss of data, programs or
equipment, and unavailability or interruption of operations.

## 6. DISCLAIMER OF LIABILITY {#disclaimer}

EXCEPT AS EXPRESSLY SET FORTH IN THIS AGREEMENT, AND TO THE EXTENT
PERMITTED BY APPLICABLE LAW, NEITHER RECIPIENT NOR ANY CONTRIBUTORS
SHALL HAVE ANY LIABILITY FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL,
EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING WITHOUT LIMITATION LOST
PROFITS), HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OR DISTRIBUTION OF THE PROGRAM OR THE
EXERCISE OF ANY RIGHTS GRANTED HEREUNDER, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGES.

## 7. GENERAL

If any provision of this Agreement is invalid or unenforceable under
applicable law, it shall not affect the validity or enforceability of
the remainder of the terms of this Agreement, and without further action
by the parties hereto, such provision shall be reformed to the minimum
extent necessary to make such provision valid and enforceable.

If Recipient institutes patent litigation against any entity (including
a cross-claim or counterclaim in a lawsuit) alleging that the Program
itself (excluding combinations of the Program with other software or
hardware) infringes such Recipient's patent(s), then such Recipient's
rights granted under Section 2(b) shall terminate as of the date such
litigation is filed.

All Recipient's rights under this Agreement shall terminate if it fails
to comply with any of the material terms or conditions of this Agreement
and does not cure such failure in a reasonable period of time after
becoming aware of such noncompliance. If all Recipient's rights under
this Agreement terminate, Recipient agrees to cease use and distribution
of the Program as soon as reasonably practicable. However, Recipient's
obligations under this Agreement and any licenses granted by Recipient
relating to the Program shall continue and survive.

Everyone is permitted to copy and distribute copies of this Agreement,
but in order to avoid inconsistency the Agreement is copyrighted and may
only be modified in the following manner. The Agreement Steward reserves
the right to publish new versions (including revisions) of this
Agreement from time to time. No one other than the Agreement Steward has
the right to modify this Agreement. The Eclipse Foundation is the
initial Agreement Steward. The Eclipse Foundation may assign the
responsibility to serve as the Agreement Steward to a suitable separate
entity. Each new version of the Agreement will be given a distinguishing
version number. The Program (including Contributions) may always be
Distributed subject to the version of the Agreement under which it was
received. In addition, after a new version of the Agreement is
published, Contributor may elect to Distribute the Program (including
its Contributions) under the new version.

Except as expressly stated in Sections 2(a) and 2(b) above, Recipient
receives no rights or licenses to the intellectual property of any
Contributor under this Agreement, whether expressly, by implication,
estoppel or otherwise. All rights in the Program not expressly granted
under this Agreement are reserved. Nothing in this Agreement is intended
to be enforceable by any entity that is not a Contributor or Recipient.
No third-party beneficiary rights are created under this Agreement.

## Exhibit A – Form of Secondary Licenses Notice {#exhibit-a}

“This Source Code may also be made available under the following
Secondary Licenses when the conditions for such availability set forth
in the Eclipse Public License, v. 2.0 are satisfied: GNU General Public License v3.0 or later”

> Simply including a copy of this Agreement, including this Exhibit A is
> not sufficient to license the Source Code under Secondary Licenses.
>
> If it is not possible or desirable to put the notice in a particular
> file, then You may include the notice in a location (such as a LICENSE
> file in a relevant directory) where a recipient would be likely to
> look for such a notice.
>
> You may add additional accurate notices of copyright ownership.
```

### Licence text 3

Licences in this text: Apache-2.0. Used by: elkjs 0.12.0.

```text
Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS
```

### Licence text 4

Licences in this text: MIT. Used by: zod 4.6.6.

```text
MIT License

Copyright (c) 2025 Colin McDonnell

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Licence text 5

Licences in this text: ISC, MIT. Used by: lucide-static 1.49.0.

```text
ISC License

Copyright (c) 2026 Lucide Icons and Contributors

Permission to use, copy, modify, and/or distribute this software for any
purpose with or without fee is hereby granted, provided that the above
copyright notice and this permission notice appear in all copies.

THE SOFTWARE IS PROVIDED "AS IS" AND THE AUTHOR DISCLAIMS ALL WARRANTIES
WITH REGARD TO THIS SOFTWARE INCLUDING ALL IMPLIED WARRANTIES OF
MERCHANTABILITY AND FITNESS. IN NO EVENT SHALL THE AUTHOR BE LIABLE FOR
ANY SPECIAL, DIRECT, INDIRECT, OR CONSEQUENTIAL DAMAGES OR ANY DAMAGES
WHATSOEVER RESULTING FROM LOSS OF USE, DATA OR PROFITS, WHETHER IN AN
ACTION OF CONTRACT, NEGLIGENCE OR OTHER TORTIOUS ACTION, ARISING OUT OF
OR IN CONNECTION WITH THE USE OR PERFORMANCE OF THIS SOFTWARE.

---

The following Lucide icons are derived from the Feather project:

airplay, alert-circle, alert-octagon, alert-triangle, aperture, arrow-down-circle, arrow-down-left, arrow-down-right, arrow-down, arrow-left-circle, arrow-left, arrow-right-circle, arrow-right, arrow-up-circle, arrow-up-left, arrow-up-right, arrow-up, at-sign, calendar, cast, check, chevron-down, chevron-left, chevron-right, chevron-up, chevrons-down, chevrons-left, chevrons-right, chevrons-up, circle, clipboard, clock, code, columns, command, compass, corner-down-left, corner-down-right, corner-left-down, corner-left-up, corner-right-down, corner-right-up, corner-up-left, corner-up-right, crosshair, database, divide-circle, divide-square, dollar-sign, download, external-link, feather, frown, hash, headphones, help-circle, info, italic, key, layout, life-buoy, link-2, link, loader, lock, log-in, log-out, maximize, meh, minimize, minimize-2, minus-circle, minus-square, minus, monitor, moon, more-horizontal, more-vertical, move, music, navigation-2, navigation, octagon, pause-circle, percent, plus-circle, plus-square, plus, power, radio, rss, search, server, share, shopping-bag, sidebar, smartphone, smile, square, table-2, tablet, target, terminal, trash-2, trash, triangle, tv, type, upload, x-circle, x-octagon, x-square, x, zoom-in, zoom-out

The MIT License (MIT) (for the icons listed above)

Copyright (c) 2013-present Cole Bemis

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

### Licence text 6

Licences in this text: CC0-1.0. Used by: simple-icons 16.35.0.

```text
# CC0 1.0 Universal

## Statement of Purpose

The laws of most jurisdictions throughout the world automatically confer exclusive Copyright and Related Rights (defined below) upon the creator and subsequent owner(s) (each and all, an “owner”) of an original work of authorship and/or a database (each, a “Work”).

Certain owners wish to permanently relinquish those rights to a Work for the purpose of contributing to a commons of creative, cultural and scientific works (“Commons”) that the public can reliably and without fear of later claims of infringement build upon, modify, incorporate in other works, reuse and redistribute as freely as possible in any form whatsoever and for any purposes, including without limitation commercial purposes. These owners may contribute to the Commons to promote the ideal of a free culture and the further production of creative, cultural and scientific works, or to gain reputation or greater distribution for their Work in part through the use and efforts of others.

For these and/or other purposes and motivations, and without any expectation of additional consideration or compensation, the person associating CC0 with a Work (the “Affirmer”), to the extent that he or she is an owner of Copyright and Related Rights in the Work, voluntarily elects to apply CC0 to the Work and publicly distribute the Work under its terms, with knowledge of his or her Copyright and Related Rights in the Work and the meaning and intended legal effect of CC0 on those rights.

1. Copyright and Related Rights. A Work made available under CC0 may be protected by copyright and related or neighboring rights (“Copyright and Related Rights”). Copyright and Related Rights include, but are not limited to, the following:
    1. the right to reproduce, adapt, distribute, perform, display, communicate, and translate a Work;
    2. moral rights retained by the original author(s) and/or performer(s);
    3. publicity and privacy rights pertaining to a person’s image or likeness depicted in a Work;
    4. rights protecting against unfair competition in regards to a Work, subject to the limitations in paragraph 4(i), below;
    5. rights protecting the extraction, dissemination, use and reuse of data in a Work;
    6. database rights (such as those arising under Directive 96/9/EC of the European Parliament and of the Council of 11 March 1996 on the legal protection of databases, and under any national implementation thereof, including any amended or successor version of such directive); and
    7. other similar, equivalent or corresponding rights throughout the world based on applicable law or treaty, and any national implementations thereof.

2. Waiver. To the greatest extent permitted by, but not in contravention of, applicable law, Affirmer hereby overtly, fully, permanently, irrevocably and unconditionally waives, abandons, and surrenders all of Affirmer’s Copyright and Related Rights and associated claims and causes of action, whether now known or unknown (including existing as well as future claims and causes of action), in the Work (i) in all territories worldwide, (ii) for the maximum duration provided by applicable law or treaty (including future time extensions), (iii) in any current or future medium and for any number of copies, and (iv) for any purpose whatsoever, including without limitation commercial, advertising or promotional purposes (the “Waiver”). Affirmer makes the Waiver for the benefit of each member of the public at large and to the detriment of Affirmer’s heirs and successors, fully intending that such Waiver shall not be subject to revocation, rescission, cancellation, termination, or any other legal or equitable action to disrupt the quiet enjoyment of the Work by the public as contemplated by Affirmer’s express Statement of Purpose.

3. Public License Fallback. Should any part of the Waiver for any reason be judged legally invalid or ineffective under applicable law, then the Waiver shall be preserved to the maximum extent permitted taking into account Affirmer’s express Statement of Purpose. In addition, to the extent the Waiver is so judged Affirmer hereby grants to each affected person a royalty-free, non transferable, non sublicensable, non exclusive, irrevocable and unconditional license to exercise Affirmer’s Copyright and Related Rights in the Work (i) in all territories worldwide, (ii) for the maximum duration provided by applicable law or treaty (including future time extensions), (iii) in any current or future medium and for any number of copies, and (iv) for any purpose whatsoever, including without limitation commercial, advertising or promotional purposes (the “License”). The License shall be deemed effective as of the date CC0 was applied by Affirmer to the Work. Should any part of the License for any reason be judged legally invalid or ineffective under applicable law, such partial invalidity or ineffectiveness shall not invalidate the remainder of the License, and in such case Affirmer hereby affirms that he or she will not (i) exercise any of his or her remaining Copyright and Related Rights in the Work or (ii) assert any associated claims and causes of action with respect to the Work, in either case contrary to Affirmer’s express Statement of Purpose.

4. Limitations and Disclaimers.
    1. No trademark or patent rights held by Affirmer are waived, abandoned, surrendered, licensed or otherwise affected by this document.
    2. Affirmer offers the Work as-is and makes no representations or warranties of any kind concerning the Work, express, implied, statutory or otherwise, including without limitation warranties of title, merchantability, fitness for a particular purpose, non infringement, or the absence of latent or other defects, accuracy, or the present or absence of errors, whether or not discoverable, all to the greatest extent permissible under applicable law.
    3. Affirmer disclaims responsibility for clearing rights of other persons that may apply to the Work or any use thereof, including without limitation any person’s Copyright and Related Rights in the Work. Further, Affirmer disclaims responsibility for obtaining any necessary consents, permissions or other rights required for any use of the Work.
    4. Affirmer understands and acknowledges that Creative Commons is not a party to this document and has no duty or obligation with respect to this CC0 or use of the Work.

For more information, please see <https://creativecommons.org/publicdomain/zero/1.0>.
```

### Licence text 7

Licences in this text: CC0-1.0. Used by: @iconify-json/logos 1.2.17.

```text
CC0 1.0 Universal

Statement of Purpose

The laws of most jurisdictions throughout the world automatically confer
exclusive Copyright and Related Rights (defined below) upon the creator and
subsequent owner(s) (each and all, an "owner") of an original work of
authorship and/or a database (each, a "Work").

Certain owners wish to permanently relinquish those rights to a Work for the
purpose of contributing to a commons of creative, cultural and scientific
works ("Commons") that the public can reliably and without fear of later
claims of infringement build upon, modify, incorporate in other works, reuse
and redistribute as freely as possible in any form whatsoever and for any
purposes, including without limitation commercial purposes. These owners may
contribute to the Commons to promote the ideal of a free culture and the
further production of creative, cultural and scientific works, or to gain
reputation or greater distribution for their Work in part through the use and
efforts of others.

For these and/or other purposes and motivations, and without any expectation
of additional consideration or compensation, the person associating CC0 with a
Work (the "Affirmer"), to the extent that he or she is an owner of Copyright
and Related Rights in the Work, voluntarily elects to apply CC0 to the Work
and publicly distribute the Work under its terms, with knowledge of his or her
Copyright and Related Rights in the Work and the meaning and intended legal
effect of CC0 on those rights.

1. Copyright and Related Rights. A Work made available under CC0 may be
protected by copyright and related or neighboring rights ("Copyright and
Related Rights"). Copyright and Related Rights include, but are not limited
to, the following:

  i. the right to reproduce, adapt, distribute, perform, display, communicate,
  and translate a Work;

  ii. moral rights retained by the original author(s) and/or performer(s);

  iii. publicity and privacy rights pertaining to a person's image or likeness
  depicted in a Work;

  iv. rights protecting against unfair competition in regards to a Work,
  subject to the limitations in paragraph 4(a), below;

  v. rights protecting the extraction, dissemination, use and reuse of data in
  a Work;

  vi. database rights (such as those arising under Directive 96/9/EC of the
  European Parliament and of the Council of 11 March 1996 on the legal
  protection of databases, and under any national implementation thereof,
  including any amended or successor version of such directive); and

  vii. other similar, equivalent or corresponding rights throughout the world
  based on applicable law or treaty, and any national implementations thereof.

2. Waiver. To the greatest extent permitted by, but not in contravention of,
applicable law, Affirmer hereby overtly, fully, permanently, irrevocably and
unconditionally waives, abandons, and surrenders all of Affirmer's Copyright
and Related Rights and associated claims and causes of action, whether now
known or unknown (including existing as well as future claims and causes of
action), in the Work (i) in all territories worldwide, (ii) for the maximum
duration provided by applicable law or treaty (including future time
extensions), (iii) in any current or future medium and for any number of
copies, and (iv) for any purpose whatsoever, including without limitation
commercial, advertising or promotional purposes (the "Waiver"). Affirmer makes
the Waiver for the benefit of each member of the public at large and to the
detriment of Affirmer's heirs and successors, fully intending that such Waiver
shall not be subject to revocation, rescission, cancellation, termination, or
any other legal or equitable action to disrupt the quiet enjoyment of the Work
by the public as contemplated by Affirmer's express Statement of Purpose.

3. Public License Fallback. Should any part of the Waiver for any reason be
judged legally invalid or ineffective under applicable law, then the Waiver
shall be preserved to the maximum extent permitted taking into account
Affirmer's express Statement of Purpose. In addition, to the extent the Waiver
is so judged Affirmer hereby grants to each affected person a royalty-free,
non transferable, non sublicensable, non exclusive, irrevocable and
unconditional license to exercise Affirmer's Copyright and Related Rights in
the Work (i) in all territories worldwide, (ii) for the maximum duration
provided by applicable law or treaty (including future time extensions), (iii)
in any current or future medium and for any number of copies, and (iv) for any
purpose whatsoever, including without limitation commercial, advertising or
promotional purposes (the "License"). The License shall be deemed effective as
of the date CC0 was applied by Affirmer to the Work. Should any part of the
License for any reason be judged legally invalid or ineffective under
applicable law, such partial invalidity or ineffectiveness shall not
invalidate the remainder of the License, and in such case Affirmer hereby
affirms that he or she will not (i) exercise any of his or her remaining
Copyright and Related Rights in the Work or (ii) assert any associated claims
and causes of action with respect to the Work, in either case contrary to
Affirmer's express Statement of Purpose.

4. Limitations and Disclaimers.

  a. No trademark or patent rights held by Affirmer are waived, abandoned,
  surrendered, licensed or otherwise affected by this document.

  b. Affirmer offers the Work as-is and makes no representations or warranties
  of any kind concerning the Work, express, implied, statutory or otherwise,
  including without limitation warranties of title, merchantability, fitness
  for a particular purpose, non infringement, or the absence of latent or
  other defects, accuracy, or the present or absence of errors, whether or not
  discoverable, all to the greatest extent permissible under applicable law.

  c. Affirmer disclaims responsibility for clearing rights of other persons
  that may apply to the Work or any use thereof, including without limitation
  any person's Copyright and Related Rights in the Work. Further, Affirmer
  disclaims responsibility for obtaining any necessary consents, permissions
  or other rights required for any use of the Work.

  d. Affirmer understands and acknowledges that Creative Commons is not a
  party to this document and has no duty or obligation with respect to this
  CC0 or use of the Work.

For more information, please see
<http://creativecommons.org/publicdomain/zero/1.0/>
```

### Licence text 8

Licences in this text: MIT. Used by: @iconify-json/devicon 1.2.71.

```text
The MIT License (MIT)

Copyright (c) 2015 konpa

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```

### Licence text 9

Licences in this text: Apache-2.0. Used by: @iconify-json/k8s 1.2.2.

```text
Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "{}"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright {yyyy} {name of copyright owner}

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

### Licence text 10

Licences in this text: Apache-2.0. Used by: @iconify-json/carbon 1.2.28.

```text
Apache License
                           Version 2.0, January 2004
                        http://www.apache.org/licenses/

   TERMS AND CONDITIONS FOR USE, REPRODUCTION, AND DISTRIBUTION

   1. Definitions.

      "License" shall mean the terms and conditions for use, reproduction,
      and distribution as defined by Sections 1 through 9 of this document.

      "Licensor" shall mean the copyright owner or entity authorized by
      the copyright owner that is granting the License.

      "Legal Entity" shall mean the union of the acting entity and all
      other entities that control, are controlled by, or are under common
      control with that entity. For the purposes of this definition,
      "control" means (i) the power, direct or indirect, to cause the
      direction or management of such entity, whether by contract or
      otherwise, or (ii) ownership of fifty percent (50%) or more of the
      outstanding shares, or (iii) beneficial ownership of such entity.

      "You" (or "Your") shall mean an individual or Legal Entity
      exercising permissions granted by this License.

      "Source" form shall mean the preferred form for making modifications,
      including but not limited to software source code, documentation
      source, and configuration files.

      "Object" form shall mean any form resulting from mechanical
      transformation or translation of a Source form, including but
      not limited to compiled object code, generated documentation,
      and conversions to other media types.

      "Work" shall mean the work of authorship, whether in Source or
      Object form, made available under the License, as indicated by a
      copyright notice that is included in or attached to the work
      (an example is provided in the Appendix below).

      "Derivative Works" shall mean any work, whether in Source or Object
      form, that is based on (or derived from) the Work and for which the
      editorial revisions, annotations, elaborations, or other modifications
      represent, as a whole, an original work of authorship. For the purposes
      of this License, Derivative Works shall not include works that remain
      separable from, or merely link (or bind by name) to the interfaces of,
      the Work and Derivative Works thereof.

      "Contribution" shall mean any work of authorship, including
      the original version of the Work and any modifications or additions
      to that Work or Derivative Works thereof, that is intentionally
      submitted to Licensor for inclusion in the Work by the copyright owner
      or by an individual or Legal Entity authorized to submit on behalf of
      the copyright owner. For the purposes of this definition, "submitted"
      means any form of electronic, verbal, or written communication sent
      to the Licensor or its representatives, including but not limited to
      communication on electronic mailing lists, source code control systems,
      and issue tracking systems that are managed by, or on behalf of, the
      Licensor for the purpose of discussing and improving the Work, but
      excluding communication that is conspicuously marked or otherwise
      designated in writing by the copyright owner as "Not a Contribution."

      "Contributor" shall mean Licensor and any individual or Legal Entity
      on behalf of whom a Contribution has been received by Licensor and
      subsequently incorporated within the Work.

   2. Grant of Copyright License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      copyright license to reproduce, prepare Derivative Works of,
      publicly display, publicly perform, sublicense, and distribute the
      Work and such Derivative Works in Source or Object form.

   3. Grant of Patent License. Subject to the terms and conditions of
      this License, each Contributor hereby grants to You a perpetual,
      worldwide, non-exclusive, no-charge, royalty-free, irrevocable
      (except as stated in this section) patent license to make, have made,
      use, offer to sell, sell, import, and otherwise transfer the Work,
      where such license applies only to those patent claims licensable
      by such Contributor that are necessarily infringed by their
      Contribution(s) alone or by combination of their Contribution(s)
      with the Work to which such Contribution(s) was submitted. If You
      institute patent litigation against any entity (including a
      cross-claim or counterclaim in a lawsuit) alleging that the Work
      or a Contribution incorporated within the Work constitutes direct
      or contributory patent infringement, then any patent licenses
      granted to You under this License for that Work shall terminate
      as of the date such litigation is filed.

   4. Redistribution. You may reproduce and distribute copies of the
      Work or Derivative Works thereof in any medium, with or without
      modifications, and in Source or Object form, provided that You
      meet the following conditions:

      (a) You must give any other recipients of the Work or
          Derivative Works a copy of this License; and

      (b) You must cause any modified files to carry prominent notices
          stating that You changed the files; and

      (c) You must retain, in the Source form of any Derivative Works
          that You distribute, all copyright, patent, trademark, and
          attribution notices from the Source form of the Work,
          excluding those notices that do not pertain to any part of
          the Derivative Works; and

      (d) If the Work includes a "NOTICE" text file as part of its
          distribution, then any Derivative Works that You distribute must
          include a readable copy of the attribution notices contained
          within such NOTICE file, excluding those notices that do not
          pertain to any part of the Derivative Works, in at least one
          of the following places: within a NOTICE text file distributed
          as part of the Derivative Works; within the Source form or
          documentation, if provided along with the Derivative Works; or,
          within a display generated by the Derivative Works, if and
          wherever such third-party notices normally appear. The contents
          of the NOTICE file are for informational purposes only and
          do not modify the License. You may add Your own attribution
          notices within Derivative Works that You distribute, alongside
          or as an addendum to the NOTICE text from the Work, provided
          that such additional attribution notices cannot be construed
          as modifying the License.

      You may add Your own copyright statement to Your modifications and
      may provide additional or different license terms and conditions
      for use, reproduction, or distribution of Your modifications, or
      for any such Derivative Works as a whole, provided Your use,
      reproduction, and distribution of the Work otherwise complies with
      the conditions stated in this License.

   5. Submission of Contributions. Unless You explicitly state otherwise,
      any Contribution intentionally submitted for inclusion in the Work
      by You to the Licensor shall be under the terms and conditions of
      this License, without any additional terms or conditions.
      Notwithstanding the above, nothing herein shall supersede or modify
      the terms of any separate license agreement you may have executed
      with Licensor regarding such Contributions.

   6. Trademarks. This License does not grant permission to use the trade
      names, trademarks, service marks, or product names of the Licensor,
      except as required for reasonable and customary use in describing the
      origin of the Work and reproducing the content of the NOTICE file.

   7. Disclaimer of Warranty. Unless required by applicable law or
      agreed to in writing, Licensor provides the Work (and each
      Contributor provides its Contributions) on an "AS IS" BASIS,
      WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or
      implied, including, without limitation, any warranties or conditions
      of TITLE, NON-INFRINGEMENT, MERCHANTABILITY, or FITNESS FOR A
      PARTICULAR PURPOSE. You are solely responsible for determining the
      appropriateness of using or redistributing the Work and assume any
      risks associated with Your exercise of permissions under this License.

   8. Limitation of Liability. In no event and under no legal theory,
      whether in tort (including negligence), contract, or otherwise,
      unless required by applicable law (such as deliberate and grossly
      negligent acts) or agreed to in writing, shall any Contributor be
      liable to You for damages, including any direct, indirect, special,
      incidental, or consequential damages of any character arising as a
      result of this License or out of the use or inability to use the
      Work (including but not limited to damages for loss of goodwill,
      work stoppage, computer failure or malfunction, or any and all
      other commercial damages or losses), even if such Contributor
      has been advised of the possibility of such damages.

   9. Accepting Warranty or Additional Liability. While redistributing
      the Work or Derivative Works thereof, You may choose to offer,
      and charge a fee for, acceptance of support, warranty, indemnity,
      or other liability obligations and/or rights consistent with this
      License. However, in accepting such obligations, You may act only
      on Your own behalf and on Your sole responsibility, not on behalf
      of any other Contributor, and only if You agree to indemnify,
      defend, and hold each Contributor harmless for any liability
      incurred by, or claims asserted against, such Contributor by reason
      of your accepting any such warranty or additional liability.

   END OF TERMS AND CONDITIONS

   APPENDIX: How to apply the Apache License to your work.

      To apply the Apache License to your work, attach the following
      boilerplate notice, with the fields enclosed by brackets "{}"
      replaced with your own identifying information. (Don't include
      the brackets!)  The text should be enclosed in the appropriate
      comment syntax for the file format. We also recommend that a
      file or class name and description of purpose be included on the
      same "printed page" as the copyright notice for easier
      identification within third-party archives.

   Copyright 2015 IBM Corp.

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
```

### Licence text 11

Licences in this text: OFL-1.1. Used by: @fontsource/inter 5.3.0.

```text
Copyright 2016 The Inter Project Authors (https://github.com/rsms/inter) Inter-Italic[opsz,wght].ttf: Copyright 2016 The Inter Project Authors (https://github.com/rsms/inter)

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide
development of collaborative font projects, to support the font creation
efforts of academic and linguistic communities, and to provide a free and
open framework in which fonts may be shared and improved in partnership
with others.

The OFL allows the licensed fonts to be used, studied, modified and
redistributed freely as long as they are not sold by themselves. The
fonts, including any derivative works, can be bundled, embedded,
redistributed and/or sold with any software provided that any reserved
names are not used by derivative works. The fonts and derivatives,
however, cannot be released under any other type of license. The
requirement for fonts to remain under this license does not apply
to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright
Holder(s) under this license and clearly marked as such. This may
include source files, build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the
copyright statement(s).

"Original Version" refers to the collection of Font Software components as
distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to, deleting,
or substituting -- in part or in whole -- any of the components of the
Original Version, by changing formats or by porting the Font Software to a
new environment.

"Author" refers to any designer, engineer, programmer, technical
writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted, free of charge, to any person obtaining
a copy of the Font Software, to use, study, copy, merge, embed, modify,
redistribute, and sell modified and unmodified copies of the Font
Software, subject to the following conditions:

1) Neither the Font Software nor any of its individual components,
in Original or Modified Versions, may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled,
redistributed and/or sold with any software, provided that each copy
contains the above copyright notice and this license. These can be
included either as stand-alone text files, human-readable headers or
in the appropriate machine-readable metadata fields within text or
binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font
Name(s) unless explicit written permission is granted by the corresponding
Copyright Holder. This restriction only applies to the primary font name as
presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font
Software shall not be used to promote, endorse or advertise any
Modified Version, except to acknowledge the contribution(s) of the
Copyright Holder(s) and the Author(s) or with their explicit written
permission.

5) The Font Software, modified or unmodified, in part or in whole,
must be distributed entirely under this license, and must not be
distributed under any other license. The requirement for fonts to
remain under this license does not apply to any document created
using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are
not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.
```

### Licence text 12

Licences in this text: OFL-1.1. Used by: @fontsource/jetbrains-mono 5.3.0.

```text
Copyright 2020 The JetBrains Mono Project Authors (https://github.com/JetBrains/JetBrainsMono) JetBrainsMono-Italic[wght].ttf: Copyright 2020 The JetBrains Mono Project Authors (https://github.com/JetBrains/JetBrainsMono)

This Font Software is licensed under the SIL Open Font License, Version 1.1.
This license is copied below, and is also available with a FAQ at:
http://scripts.sil.org/OFL


-----------------------------------------------------------
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007
-----------------------------------------------------------

PREAMBLE
The goals of the Open Font License (OFL) are to stimulate worldwide
development of collaborative font projects, to support the font creation
efforts of academic and linguistic communities, and to provide a free and
open framework in which fonts may be shared and improved in partnership
with others.

The OFL allows the licensed fonts to be used, studied, modified and
redistributed freely as long as they are not sold by themselves. The
fonts, including any derivative works, can be bundled, embedded,
redistributed and/or sold with any software provided that any reserved
names are not used by derivative works. The fonts and derivatives,
however, cannot be released under any other type of license. The
requirement for fonts to remain under this license does not apply
to any document created using the fonts or their derivatives.

DEFINITIONS
"Font Software" refers to the set of files released by the Copyright
Holder(s) under this license and clearly marked as such. This may
include source files, build scripts and documentation.

"Reserved Font Name" refers to any names specified as such after the
copyright statement(s).

"Original Version" refers to the collection of Font Software components as
distributed by the Copyright Holder(s).

"Modified Version" refers to any derivative made by adding to, deleting,
or substituting -- in part or in whole -- any of the components of the
Original Version, by changing formats or by porting the Font Software to a
new environment.

"Author" refers to any designer, engineer, programmer, technical
writer or other person who contributed to the Font Software.

PERMISSION & CONDITIONS
Permission is hereby granted, free of charge, to any person obtaining
a copy of the Font Software, to use, study, copy, merge, embed, modify,
redistribute, and sell modified and unmodified copies of the Font
Software, subject to the following conditions:

1) Neither the Font Software nor any of its individual components,
in Original or Modified Versions, may be sold by itself.

2) Original or Modified Versions of the Font Software may be bundled,
redistributed and/or sold with any software, provided that each copy
contains the above copyright notice and this license. These can be
included either as stand-alone text files, human-readable headers or
in the appropriate machine-readable metadata fields within text or
binary files as long as those fields can be easily viewed by the user.

3) No Modified Version of the Font Software may use the Reserved Font
Name(s) unless explicit written permission is granted by the corresponding
Copyright Holder. This restriction only applies to the primary font name as
presented to the users.

4) The name(s) of the Copyright Holder(s) or the Author(s) of the Font
Software shall not be used to promote, endorse or advertise any
Modified Version, except to acknowledge the contribution(s) of the
Copyright Holder(s) and the Author(s) or with their explicit written
permission.

5) The Font Software, modified or unmodified, in part or in whole,
must be distributed entirely under this license, and must not be
distributed under any other license. The requirement for fonts to
remain under this license does not apply to any document created
using the Font Software.

TERMINATION
This license becomes null and void if any of the above conditions are
not met.

DISCLAIMER
THE FONT SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO ANY WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT
OF COPYRIGHT, PATENT, TRADEMARK, OR OTHER RIGHT. IN NO EVENT SHALL THE
COPYRIGHT HOLDER BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY,
INCLUDING ANY GENERAL, SPECIAL, INDIRECT, INCIDENTAL, OR CONSEQUENTIAL
DAMAGES, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF THE USE OR INABILITY TO USE THE FONT SOFTWARE OR FROM
OTHER DEALINGS IN THE FONT SOFTWARE.
```
