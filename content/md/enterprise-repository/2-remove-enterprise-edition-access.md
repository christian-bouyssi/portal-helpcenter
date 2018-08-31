---
id: remove-enterprise-edition-access
themes: get-source-code
title: "**Remove access** to Akeneo PIM Enterprise Edition (EE) repository"
popular: true
related: 
---

# Remove the accesses to the Enterprise Repository

## Remove a public key access of a user

As a project manager, you can delete the contact key access for any user of your company.

1. First from the menu, go to `Projects console / Projects` and select your project.
2. Go to `Enterprise Repository` tab, and `SSH Key Access` subtab.
3. Click on the trash icon in Contact Key Access list

[screenshot remove]

::: info
The access removal takes a couple of minutes.
During this time, you can see that action is in progress with the status `Pending deletion`.
:::

## What happens when the system integrator changes?

On a project, when the system integrator changes, there is a transition phase where both system integrators need to have access to the Enterprise Repository.
You can see the current system integrator on your project. 

1. First from the menu, go to `Projects console / Projects` and select your project.
2. Open the `Enterprise Repository / Properties` sub-tab.

[Screenshot project actor]

Once the System Integrator is changed by Akeneo, only the current System Integrator manages the accesses to the Enterprise Repository.
Previous System Integrator access is preserved.

::: tips
Once the transition phase is done, ask your Akeneo customer success manager to remove the access to the previous system integrator.
:::