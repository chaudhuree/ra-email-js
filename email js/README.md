## instructions to follw code

- go to email.js website and create an account first
- go to email service menu in emailjs site
- create a new service 
  - add  gmail  service

- create a new template from email js website 
  - email templates menu item

> format for templates

```html

From :  {{user_name}}
Email : {{user_email}}


{{message}}

```

- then we can add receipent email address and name
- as gmail is already added so the receipent email address should already be there


> then install emailjs-com package

```bash
  npm install @emailjs/browser
```

> go to this link and get the reference code 

```bash
  https://www.emailjs.com/docs/examples/reactjs/
```

> service_id, template_id and public_key is required to make it work

> service id can be found in email service menu item
 when we create a gmail service a service id is auto generated

 > template id can be found in email templates menu item
  click on the template and go to the setting tab
  there it can be found

> public api key can be found in account menu item

## add them in the contact.jsx file and it will work fine