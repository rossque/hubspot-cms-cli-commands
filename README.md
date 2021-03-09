# Hubspot CMS, CLI commands
List of useful CLI commands to work with HubSpot CMS

### Install HubSpot CLI
``` shell
npm install @hubspot/cli
```

### Setup config
``` shell
npx hs init
```

### Create a theme
``` shell
npx @hubspot/create-cms-project demo
```

### Upload a theme
``` shell
npx hs upload demo/src demo
```

### Create a template
``` shell
npx hs create template demo/src/templates/basic-template-demo
```

### Upload a template
``` shell
npx hs upload demo/src/templates/basic-template-demo.html demo/templates/basic-template-demo.html
```

### Watch Entire Source Directory
``` shell
npx hs watch demo/src demo
```

### Fetch demo and create a new project
``` shell
npx hs fetch demo new-demo
```
