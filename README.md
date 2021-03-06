<!-- Autogenerated from composer.json - All changes will be overridden if generated again! -->

# SrJiraProcessHelper ILIAS Plugin

srag jira process helper

This is an OpenSource project by studer + raimann ag, CH-Burgdorf (https://studer-raimann.ch)

This project is licensed under the GPL-3.0-only license

## Requirements

* ILIAS 6.0 - 6.999
* PHP >=7.2

## Installation

Start at your ILIAS root directory

```bash
mkdir -p Customizing/global/plugins/Services/UIComponent/UserInterfaceHook
cd Customizing/global/plugins/Services/UIComponent/UserInterfaceHook
git clone https://github.com/fluxfw/SrJiraProcessHelper.git SrJiraProcessHelper
```

Update, activate and config the plugin in the ILIAS Plugin Administration

## Description

### Jira WebHook

When: Issue created

URL: https://your-domain/goto.php?target=uihk_srjiprohe

Payload:

```json
{
  "issue_key": "${issue.key}",
  "secret": "..."
}
```

## Adjustment suggestions

You can report bugs or suggestions at https://plugins.studer-raimann.ch/goto.php?target=uihk_srsu_PJPH

There is no guarantee this can be fixed or implemented

## ILIAS Plugin SLA

We love and live the philosophy of Open Source Software! Most of our developments, which we develop on behalf of customers or on our own account, are publicly available free of charge to all interested parties at https://github.com/studer-raimann.

Do you use one of our plugins professionally? Secure the timely availability of this plugin for the upcoming ILIAS versions via SLA. Please inform yourself under https://studer-raimann.ch/produkte/ilias-plugins/plugin-sla.

Please note that we only guarantee support and release maintenance for institutions that sign a SLA.
