# Matheus Fraga

**Desenvolvedor Backend Java · Fullstack quando necessário**

Construo sistemas que resolvem problemas reais de negócio — do domínio ao deploy.  
Formando em Análise e Desenvolvimento de Sistemas, com projetos comercials rodando em produção.  
Background em atendimento e operações: entendo o negócio antes de abrir o editor.

📍 Brasil · SP &nbsp;|&nbsp; 📬 [matheusfragadev@gmail.com](mailto:matheusfragadev@gmail.com) &nbsp;|&nbsp; 💼 [LinkedIn](https://linkedin.com/in/matheusfragadev) &nbsp;|&nbsp; 🌐 [matheusfragadev.com.br](https://matheusfragadev-gfnr.vercel.app)

---

**Backend**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=springsecurity&logoColor=white)
![Spring Web](https://img.shields.io/badge/Spring_Web-6DB33F?style=flat-square&logo=spring&logoColor=white)
![Spring Data JPA](https://img.shields.io/badge/Spring_Data_JPA-6DB33F?style=flat-square&logo=spring&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Flyway](https://img.shields.io/badge/Flyway-CC0200?style=flat-square&logo=flyway&logoColor=white)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat-square&logo=swagger&logoColor=black)
![Lombok](https://img.shields.io/badge/Lombok-BC4521?style=flat-square&logoColor=white)
![Java Mail](https://img.shields.io/badge/Java_Mail-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Gradle](https://img.shields.io/badge/Gradle-02303A?style=flat-square&logo=gradle&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)

**Frontend**  
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=flat-square&logo=shadcnui&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![React Hook Form](https://img.shields.io/badge/React_Hook_Form-EC5990?style=flat-square&logo=reacthookform&logoColor=white)

**Infra**  
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![VPS](https://img.shields.io/badge/VPS-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Cloud](https://img.shields.io/badge/Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

## Projetos em Produção

### LaLouise — Plataforma de Controle de Validade para Restaurantes

> Restaurantes japoneses gerenciam validade de pescados crus com margem de erro zero — qualquer falha é risco sanitário.

Sistema SaaS multi-tenant que automatiza o ciclo completo de etiquetas de validade, desde o recebimento até o descarte, com rastreabilidade por lote e impressão automática via protocolo ZPL em impressoras Zebra.

**Decisões técnicas relevantes:**
- Arquitetura com monólito Spring Boot (API REST) + microsserviço local de impressão, comunicando de forma assíncrona via RabbitMQ
- Multi-tenancy por `restaurant_id` resolvido via contexto JWT — sem configuração adicional no frontend
- Rate limiting com Redis e brute-force protection no login
- CI/CD com GitHub Actions + deploy em VPS Linux via Docker Compose

`Java 21` `Spring Boot` `PostgreSQL` `RabbitMQ` `Redis` `Next.js` `TypeScript` `Docker` `Nginx`

[📂 Repositório](https://github.com/FragaTheus/lalouiseprinter) · [🚀 Demo](https://lalouiseprinter-upsj.vercel.app)

---

### Caldeiraria Realiza — Site Institucional

> A empresa dependia de indicações e WhatsApp. Não tinha presença digital e perdia oportunidades que não conseguia nem medir.

Site institucional que virou canal 24h de captação: vitrine dos serviços, portfólio de obras e formulário com suporte a anexos para solicitação de orçamentos — integrado a um microserviço de e-mail com validação server-side.

**Decisões técnicas relevantes:**
- Monorepo com frontend Next.js e backend Spring Boot desacoplados
- Backend dedicado para processamento de formulários com anexos e envio via SMTP
- SEO on-page estruturado para ranqueamento local
- Analytics com Google Analytics 4

`Next.js` `TypeScript` `Tailwind` `Framer Motion` `Spring Boot` `Jakarta Validation` `SMTP`

[📂 Repositório](https://github.com/FragaTheus/caldeiraria-realiza-site-institucional) · [🌐 Site](https://caldeirariarealiza.com.br)

---

### Paulo Carvalho — Perito Judicial

> Perito trabalhista sem presença digital, invisível para advogados que buscam laudo técnico online.

Site institucional focado em conversão: posicionamento do profissional, apresentação de competências e formulário de contato integrado para captação de clientes.

`TypeScript` `React` `Next.js` `CSS`

[📂 Repositório](https://github.com/FragaTheus/paulo-carvalho-perito) · [🌐 Site](https://paulocarvalhoperitojudicial.com)

---

### Profissão do Século — Landing Page

> Substituição de uma página feita no Canva por uma solução de alta performance com mensuração real de conversão.

Landing page com 100/98 no PageSpeed (desktop/mobile), rastreamento via GA4 + GTM e scripts próprios para automação de coleta de métricas via PageSpeed API.

`Next.js` `TypeScript` `Tailwind CSS` `GA4` `GTM`

[📂 Repositório](https://github.com/FragaTheus/landing-page-profissao-do-seculo) · [🌐 Site](https://profissaodoseculo.com.br)

---

*Aberto a oportunidades como Desenvolvedor Backend Java ou Fullstack. Entre em contato pelo [LinkedIn](https://linkedin.com/in/matheusfragadev) ou [e-mail](mailto:matheusfragadev@gmail.com).*
