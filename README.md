# Url Builder

Built using [Zendesk App Tools](https://developer.zendesk.com/apps/docs/developer-guide/zat) and [Handlebars](http://handlebarsjs.com/).

URL templates are retrieved from the App Configurations, and the appropriate ticket information is extracted and inserted into the URL template.

### URL Template

An example URL template is as shown:

```
[
  {
    'title': 'Label for link 1',
    'url': 'https://www.sample-url.com/{{identifier from ticket}}'
  },
  {
    'title': 'User Profile',
    'url': 'https://www.your-website.com/{{ticket.requester.email}}'
  }
]
```

### Screenshot(s):

[put your screenshots down here.]
