# Guia de estudos GH-100 — administração do GitHub

Índice de documentação oficial para estudar os temas que aparecem no guia do exame e no simulado de administração. Este arquivo reúne referências e caminhos para o conteúdo já mantido neste repositório; não reproduz o texto integral da documentação oficial.

> **Importante:** o guia de certificação e o conteúdo do GitHub Docs podem mudar. Confira o guia oficial para o escopo e os pesos atuais do exame. O simulado é material comunitário, não oficial, e algumas perguntas podem refletir versões antigas ou conter imprecisões.

## Fontes do estudo

- [Guia oficial de estudos GH-100 (Microsoft)](https://learn.microsoft.com/pt-br/credentials/certifications/resources/study-guides/gh-100)
- [Simulado GH-100 — questões de administração](https://github.com/v-fidelusaleksander/ghcertified/tree/main/questions/en/admin) (97 questões no momento deste levantamento)

## 1. GitHub Enterprise e administração

- [Sobre o GitHub para empresas e opções de implantação](https://docs.github.com/en/enterprise-cloud@latest/admin/overview/about-github-for-enterprises#about-deployment-options)
- [Sobre o GitHub Enterprise Cloud](https://docs.github.com/en/enterprise-cloud@latest/admin/overview/about-github-enterprise-cloud)
- [Sobre o GitHub Enterprise Server](https://docs.github.com/en/enterprise-server@latest/admin/overview/about-github-enterprise-server)
- [Referência da API REST de administração empresarial](https://docs.github.com/en/rest/enterprise-admin)
- [Administração no conteúdo deste repositório](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/admin)

## 2. Identidade, autenticação e acesso

- [Autenticação SAML SSO](https://docs.github.com/en/enterprise-cloud@latest/authentication/authenticating-with-saml-single-sign-on/about-authentication-with-saml-single-sign-on)
- [Gerenciar SAML SSO para uma organização](https://docs.github.com/en/organizations/managing-saml-single-sign-on-for-your-organization)
- [Configurar SAML SSO na organização](https://docs.github.com/en/organizations/granting-access-to-your-organization-with-saml-single-sign-on)
- [Métodos de autenticação no GitHub](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/about-authentication-to-github)
- [Exigir autenticação de dois fatores na organização](https://docs.github.com/en/organizations/keeping-your-organization-secure/managing-two-factor-authentication-for-your-organization)
- [Papéis em uma organização](https://docs.github.com/en/organizations/managing-peoples-access-to-your-organization-with-roles/roles-in-an-organization)
- [Gerenciar acesso de usuários aos repositórios da organização](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories)
- [Conteúdo local de autenticação](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/authentication)
- [Conteúdo local de organizações](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/organizations)

## 3. Organizações, equipes e permissões

- [Sobre organizações](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/about-organizations)
- [Sobre equipes](https://docs.github.com/en/organizations/organizing-members-into-teams/about-teams)
- [Gerenciar acesso de equipes a repositórios da organização](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/managing-team-access-to-an-organization-repository)
- [Gerenciar associação à organização](https://docs.github.com/en/organizations/managing-membership-in-your-organization)
- [Gerenciar configurações da organização](https://docs.github.com/en/organizations/managing-organization-settings)
- [Funções e permissões — conteúdo local](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/organizations/managing-peoples-access-to-your-organization-with-roles)
- [Equipes — conteúdo local](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/organizations/organizing-members-into-teams)

## 4. Segurança e políticas

- [Configurações de segurança da organização](https://docs.github.com/en/organizations/keeping-your-organization-secure/managing-security-settings-for-your-organization)
- [Reforçar a segurança da empresa](https://docs.github.com/en/enterprise-cloud@latest/admin/configuring-settings/hardening-security-for-your-enterprise)
- [Aplicar políticas para a empresa](https://docs.github.com/en/enterprise-cloud@latest/admin/enforcing-policies/enforcing-policies-for-your-enterprise)
- [Gráfico de dependências](https://docs.github.com/en/code-security/concepts/supply-chain-security/dependency-graph)
- [GitHub Advanced Security](https://docs.github.com/en/get-started/learning-about-github/about-github-advanced-security)
- [Remover dados sensíveis de um repositório](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/removing-sensitive-data-from-a-repository)
- [Práticas de segurança para GitHub Actions](https://docs.github.com/en/actions/security-guides/security-hardening-for-github-actions)
- [Conteúdo local de segurança de código](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/code-security)

## 5. GitHub Actions e runners

- [Sobre runners auto-hospedados](https://docs.github.com/en/actions/hosting-your-own-runners/managing-self-hosted-runners/about-self-hosted-runners)
- [Adicionar runners auto-hospedados](https://docs.github.com/en/actions/how-tos/manage-runners/self-hosted-runners/add-runners)
- [Gerenciar acesso a runners auto-hospedados](https://docs.github.com/en/actions/how-tos/manage-runners/self-hosted-runners/manage-access)
- [Cobrança do GitHub Actions](https://docs.github.com/en/billing/concepts/product-billing/github-actions)
- [Ação actions/checkout](https://github.com/actions/checkout) — consulte especialmente `fetch-depth` e o histórico Git disponível no workflow.
- [Conteúdo local de Actions](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/actions)
- [Conteúdo local de cobrança](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/billing)

## 6. GitHub Apps, OAuth Apps e integrações

- [Instalar um GitHub App do Marketplace para uma organização](https://docs.github.com/en/apps/using-github-apps/installing-a-github-app-from-github-marketplace-for-your-organization)
- [Diferenças entre GitHub Apps e OAuth Apps](https://docs.github.com/en/apps/oauth-apps/building-oauth-apps/differences-between-github-apps-and-oauth-apps)
- [Usar webhooks com GitHub Apps](https://docs.github.com/en/apps/creating-github-apps/registering-a-github-app/using-webhooks-with-github-apps)
- [Gerenciar acesso programático à organização](https://docs.github.com/en/organizations/managing-programmatic-access-to-your-organization)
- [Conteúdo local de Apps](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/apps)
- [Conteúdo local de integrações](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/integrations)

## 7. Packages, API e limites de taxa

- [Introdução ao GitHub Packages](https://docs.github.com/en/packages/learn-github-packages/introduction-to-github-packages)
- [Limites de taxa da API REST](https://docs.github.com/en/rest/using-the-rest-api/rate-limits-for-the-rest-api)
- [Conteúdo local de Packages](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/packages)
- [Conteúdo local da API REST](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/rest)

## 8. Suporte e resolução de problemas

- [Sobre o suporte do GitHub](https://docs.github.com/en/enterprise-server/support/learning-about-github-support/about-github-support)
- [Fornecer dados ao suporte do GitHub](https://docs.github.com/en/enterprise-server@3.15/support/contacting-github-support/providing-data-to-github-support)
- [Conteúdo local de suporte](https://github.com/brunosilvaJava/copilot-knowledge-base/tree/main/github-docs/content/support)

## 9. Integração complementar citada no simulado

- [HashiCorp Vault com GitHub Actions](https://developer.hashicorp.com/vault/docs/platform/github-actions)

## Roteiro sugerido

1. Estude primeiro identidade, SAML, papéis, equipes e permissões organizacionais.
2. Revise governança empresarial, políticas, segurança e diferenças entre Enterprise Cloud e Server.
3. Estude administração de Actions: runners, permissões, segurança e cobrança.
4. Revise Apps/OAuth, Packages, API REST e limites de taxa.
5. Resolva o simulado por tema e use os links de documentação de cada questão para confirmar a resposta na documentação oficial vigente.
