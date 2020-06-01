# vacantthinker.example.docusaurus.v2

---

package.json
```
  "scripts": {
    "windows-deploy": "cmd /C \"set \"GIT_USER=vacantthinker\" && yarn deploy\""
  },

```

docusaurus.config.js
```

module.exports = {
  title: 'My Site',
  tagline: 'The tagline of my site',

  url: 'https://vacantthinker-examples.github.io/vacantthinker.example.docusaurus.v2',
  baseUrl: '/vacantthinker.example.docusaurus.v2/',
  projectName: 'vacantthinker.example.docusaurus.v2', // Usually your repo name.
  organizationName: 'vacantthinker-examples', // Usually your GitHub org/user name.

```

---
end