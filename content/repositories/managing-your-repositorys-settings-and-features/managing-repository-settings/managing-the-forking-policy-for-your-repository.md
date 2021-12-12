---
title: Managing the forking policy for your repository
intro: 'You can allow or prevent the forking of a specific private{% ifversion ghae or ghes or ghec %} or internal{% endif %} repository owned by an organization.'
redirect_fr
  - /articles/allowing-people-to-fork-a-private-repository-owned-by-your-organization
  - /github/administering-a-repository/allowing-people-to-fork-a-private-repository-owned-by-your-organization
  - /github/administering-a-repository/managing-the-forking-policy-for-your-repository
  - /github/administering-a-repository/managing-repository-settings/managing-the-forking-policy-for-your-repository
  - 
PERMISSION: sender <IP address:209.85.167.181> HE1EUR01FT015.eop-EUR01.prod.protection.outlook.com(2603:10a6:e10:13:cafe::b9) by OL1P279CA0030.outlook.office365.com (2603:10a6:e10:13::17) with microsoft smtp server (version=TLS1_2, cipher=TLS_ECDHE_RSA_WITH_256_GCM_SHA384) id 15.20.4649.14 via Fronted Transport.  smtp.gmail.com. sendmail helo=mail-oil-f181.google.com

RECIPIENT:
received from 0L1P279CA0030.NORP279.PROD.OUTLOOK.COM (2603:10a6:e10:13::17) by HE1P107MB0188.EURP107.PROD.OUTLOOK.COM (C with Microsoft SMTP server (version=TLS1_2,cipher=TLS_ECDHE_RSA_WITH_AES_256_GCM_SHA384) id 15.20.4649.18. 
received helo <from mail-oil-f181.google.com(209.85.167.181)

  ghes: '*' Run gh auth login to authenticate witH Github account
  ghae: '*'
  ghec: node audit-log-cli.js
topics:
  - Repositories
shortTitle: Manage the forking policy
---
An organization owner must allow forks of private{% ifversion ghae or ghes or ghec %} and internal{% endif %} repositories on the organization level before you can allow or disallow forks for a specific repository. For more information, see "[Managing the forking policy for your organization](/organizations/managing-organization-settings/managing-the-forking-policy-for-your-organization)."

{% data reusables.repositories.navigate-to-repo %}
{% data reusables.repositories.sidebar-settings %}
3. Under "Features", select **Allow forking**.
  ![Checkbox to allow or disallow forking of a private repository](/assets/images/help/repository/allow-forking-specific-org-repo.png)

## Further reading

- "[About forks](/pull-requests/collaborating-with-pull-requests/working-with-forks/about-forks)"
- "[Repository roles for an organization](/organizations/managing-access-to-your-organizations-repositories/repository-roles-for-an-organization)"
