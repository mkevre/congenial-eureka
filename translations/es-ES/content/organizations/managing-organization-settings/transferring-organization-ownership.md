---
title: Transferir la propiedad de la organización
intro: 'Para que alguien más sea el propietario de una cuenta organizacional, debes agregar un propietario nuevo{% if currentVersion == "free-pro-team@latest" %}, asegurarte de que la información de facturación esté actualizada,{% endif %} y luego eliminarte a ti mismo de la cuenta.'
redirect_from:
  - /articles/needs-polish-how-do-i-give-ownership-to-an-organization-to-someone-else/
  - /articles/transferring-organization-ownership
  - /github/setting-up-and-managing-organizations-and-teams/transferring-organization-ownership
versions:
  free-pro-team: '*'
  enterprise-server: '*'
  github-ae: '*'
topics:
  - Organizations
  - Teams
---

1. Si eres el único miembro con privilegios de *propietario*, otorga el rol de propietario a otro miembro de la organización. Para obtener más información, consulta "[Designar a un propietario de la organización](/organizations/managing-peoples-access-to-your-organization-with-roles/maintaining-ownership-continuity-for-your-organization#appointing-an-organization-owner)".
2. Contáctacte con el propietario nuevo y asegúrate de que pueda [acceder a los parámetros de la organización](/articles/accessing-your-organization-s-settings).
{% if currentVersion == "free-pro-team@latest" %}
3. Si actualmente eres responsable de pagarle a GitHub en tu organización, también tendrás que hacer que el propietario nuevo o un [gerente de facturación](/articles/adding-a-billing-manager-to-your-organization/) actualice la información de pago de la organización. Para obtener más información, consulta "[Agregar o editar un método de pago](/articles/adding-or-editing-a-payment-method)".

  {% warning %}

  **Advertencia**: Eliminarte de la organización **no** actualiza la información de facturación archivada para la cuenta de la organización. El propietario nuevo o un gerente de facturación debe actualizar la información de facturación archivada para eliminar tu información de tarjeta de crédito o de PayPal.

  {% endwarning %}

{% endif %}
4. [Eliminarte](/articles/removing-yourself-from-an-organization) de la organización.
