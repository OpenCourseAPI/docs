---
home: true
# heroImage: https://v1.vuepress.vuejs.org/hero.png
# heroImage: https://avatars0.githubusercontent.com/u/40309595?s=200&v=4
tagline: Open Course API's mission is to teach students how to make data driven applications.
actionText: Quick Start →
actionLink: /guide/
features:
- title: OwlAPI
  details: An open source REST API written in Python to scrape and serve Foothill / De Anza course data 📒
- title: Tools
  details: There's a lot that's in Open Course API! Stay tuned for our latest updates.
- title: Data Analysis
  details: With a plethora of data and tools for you to get your feet wet, we're just looking for folks that wan't to start exploring!
footer: Made with ❤️ by Madhav and Kishan
---

## Start Hacking

We have a lot you can do! Try some of the following to get your feet wet.

### OwlAPI

[Live Demo](https://opencourse.dev), [View on GitHub](https://github.com/OpenCourseAPI/OwlAPI)

```bash
git clone https://github.com/OpenCourseAPI/OwlAPI.git
cd OwlAPI && pipenv install

pipenv run python scrape_term.py
pipenv run python server.py

# Go to https://localhost:8080 and enjoy!
```

### Data Analysis

[View on GitHub](https://github.com/OpenCourseAPI/LiveMyPortalData)

#### Setup
``` bash
git clone https://github.com/OpenCourseAPI/LiveMyPortalData.git
git clone https://github.com/OpenCourseAPI/DataAnalysis.git

cd DataAnalysis
```

#### Let's get going!

```
pipenv install
pipenv run python .
```

::: tip
Open Course API requires [Python 3](https://www.python.org/) and [pipenv](https://github.com/pypa/pipenv) to be installed in your system.
:::
