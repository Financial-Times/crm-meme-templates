#CRM templates and snippets for MeMe

##Snippets
1. All CRM snippets should have *crm_* as a prefix

2. All CRM snippets should be compatible with the master-template.html

3. All CRM snippets should begin within self contained tables. 

##Coding conventions
1. Indentation should be 2 spaces

2. All snippets must open with `<table style="table-layout: fixed; max-width:640px;" class="responsive-table" width="100%" align="center" border="0" cellpadding="0" cellspacing="0" role="presentation">`

3. Where possible padding should be applied to the first td eg `<table><tr><td style="padding: {padding}">`

4. all images should include the following attributes: `<img src="{image}" width="{width}" height="{height}" style="margin:0; padding:0; border:none; display:block;" border="0" alt="{alt}" /> `

5. all links should include the following attributes: `<a href="{link}" target="_blank">`
  * in-text links should be styled as `<a href="{link}" target="_blank" style="text-decoration: none; font-weight: bold; color: #2e6e9e">`
