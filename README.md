<p align="center">
  <img src="assets/logo.svg" width="180" alt="Darhan Calculator logo">
</p>

<h1 align="center">Darhan Calculator</h1>
<p align="center"><strong>Guided seismic hanger and brace design for engineering teams.</strong></p>
<p align="center"><a href="https://darhan-gilt.vercel.app/">Open the live application</a></p>

## Product overview

Darhan Calculator is an engineering platform that turns seismic hanger and brace design into a structured, repeatable workflow. It combines project inputs, company-approved component catalogs, calculation results, and professional reporting in one application.

## Product highlights

- Guide engineers through hanger and brace design inputs step by step.
- Match engineering requirements with company catalog components.
- Present clear result states and compatible brace-kit recommendations.
- Save projects and reuse common inputs across calculation sessions.
- Support role-based workflows for engineering users and administrators.
- Generate branded technical PDF reports for project records and review.
- Keep administrative catalog management separate from the calculation experience.

## Data and calculation protection

The proprietary calculation engine and catalog data remain behind server-side endpoints. The browser receives the options and results needed for the active workflow without exposing the underlying product logic. Authentication and role data are managed through Supabase, while production error monitoring is configured without session replay or browser tracing.

## Technology

| Area | Technology |
| --- | --- |
| Web application | React 19, Vite 7, React Router, and Tailwind CSS |
| Calculation services | Vercel serverless endpoints |
| Identity and roles | Supabase authentication and profile roles |
| Reporting | PDF-Lib and Fontkit |
| Monitoring | Sentry browser error reporting with privacy-conscious settings |
| Quality | Vitest, Testing Library, and Playwright |
| Deployment | Vercel |

## Product direction

Darhan Calculator is designed to reduce repetitive engineering work, standardize component selection, and produce consistent project documentation. Its public showcase focuses on the product outcome; the calculation engine, catalog, and production source remain private.

## Availability

The current application is available at [darhan-gilt.vercel.app](https://darhan-gilt.vercel.app/).
