# TC39 Vulnerability Disclosure Policy

## Reporting Guidelines

- If a security issue is present in an implementation, then [report it directly](#reporting-to-projects) to the relevant project.
- If a security issue is present in a TC39 specification, [let us know](#reporting-to-tc39).
  - Include any relevant links to corroborative information, e.g. vulnerability reports, reference IDs, etc.
- If you are unable to determine whether a security issue is implementation-specific, [let us know](#reporting-to-tc39).

## Reporting to TC39

Report using GitHub by visiting the security advisories page of the relevant repository, such as:

- [ECMA-262: ECMAScript® Language Specification](https://github.com/tc39/ecma262/security/advisories)
- [ECMA-402: ECMAScript® Internationalization API Specification](https://github.com/tc39/ecma402/security/advisories)
- If you are unable to determine the relevant repository, you can [report here](https://github.com/tc39/.github/security/advisories).

Alternately, send an email to `security@tc39.es`

## Reporting to Projects

> [!NOTE]
> This list is not exhaustive.

| Engine/Runtime | Used In                            | Link to Report                                             |
| -------------- | ---------------------------------- | ---------------------------------------------------------- |
| JavaScriptCore | Safari, Bun                        | [Report](https://webkit.org/security-policy/)              |
| SpiderMonkey   | Firefox                            | [Report](https://www.mozilla.org/security/)                |
| V8             | Chrome, Chromium, Edge, Node, Deno | [Report](https://v8.dev/docs/security-bugs)                |
| Node           |                                    | [Report](https://nodejs.dev/en/about/security/)            |
| Deno           |                                    | [Report](https://github.com/denoland/deno/security/policy) |
| Bun            |                                    | [Report](https://github.com/oven-sh/bun/security/policy)   |
