---
name: Pull Request Template - WIP
about: General Template for all PR's as using different Templates for different Types is broken for years now.
label: "Status: Work In Progress"

---

# DO NOT REMOVE THE "Status: Work In Progress" LABEL FOR TRANSLATION PR's!
Please do not remove the Label if you are adding or updating a Translation! It will interfere with the "WIP" Probot!

I will remove the Label when I am ready to merge your Pull Request! Thank you!

## Use the Letter X to mark a checkbox
To make sure an Item is checked, put the Letter X between the '[]' Parentheses. This is important. Unless the required checkboxes are enabled, your PR can not be merged!

## Please use different Pull Requests if you want to add multiple new Features!
Otherwise it will get unnecessary convoluted.

If you want to add a new Option or multiple new Options for an existing Feature, you can combine them usually in one PR.

## You confirm that you have read and agree to follow the Contribution Rules and the Code of Conduct!
Everyone is required to read and follow the Contribution Rules and the Code of Conduct. Removing this Part does not change that!
- [] I have read and agree to follow the [Contribution Rules](../blob/main/CONTRIBUTING.md)<br/>
- [] I have read and agree to follow the [Code of Conduct](../blob/main/CODE_OF_CONDUCT.md)<br/>

## Is there already an open Pull Request for this specific Issue?
- [] I have checked the open Pull Requests and there is no open Pull Request for this specific Issue<br/>

## Type of Pull Request
[] Bug Fixes<br/>
[] Features or Options<br/>
[] Support for a specific Operating System<br/>
[] Translations<br/>
[] UI / UX<br/>

## If there is an open Issue for this PR, please reference it here. Type the Symbol '#' and GitHub should automatically start listing all Issues.

- [] There is no Issue for this Pull Request<br/>

## Describe your change or addition as precisely as possible.


## Will this change effect other Operating Systems in any way? Please describe potential Issues as detailed as possible!


## For Translations only - Manual checks will take time
- [] Translation File encoding is correctly set to UTF-8 WITHOUT Byte-Order-Mark ("BOM")
- [] Translation does get correctly detected and loaded
- [] Translation is Work-In-Progress. PR is NOT ready to be merged!
- [] Translation is only 50 Percent or more completed. Please check and merge my PR as it is
- [] Translation is complete. PR only need final check for "bad words"

Hint: As Translations will be manually checked, integrating them will take time. All changes which are not based on German or English, will be double checked because of the obvious reasons.

If you have contributed enough and I can be sure that you are trustworthy, I can limit the checks to the technical ones. Thank you for your understanding!

# For UI / UX only
- [] Tabbing through UI Elements is in the correct order
- [] All UI Elements have an Accessibility Descriptor where possible (Not required until Ultimate++ has full Accessibility Support added!)
- [] All UI Elements work on all officially supported Operating Systems

## Anything else you think is important to know about your PR?
