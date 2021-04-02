## Contents
- [About](#about)
- [How to edit?](#how-to-edit-)
  - [The table of anomalies](#the-table-of-anomalies)
  - [Possible solutions](#possible-solutions)
  - [The _False Alarms_ page](#the--false-alarms--page)
  - [Add a news post](#add-a-news-post)
  - [Others](#others) 


## About
This website aims to keep a comprehensive, up-to-date list of anomalies in high energy physics. If you notice some anomalies/proposed solutions/references are missing or any incorrect information, please don't hesitate to create a pull request to propose changes. The step-by-step guide below will show you how to edit the table of anomalies and the pages for proposed explanations. Also, please feel free to utilize GitHub Discussions to ask a questions or share your opinions about the anomalies and the website design.

## How to edit ?
_This guide assumes the readers know how to create pull requests. If you do not have any experience, please read [this tutorial](https://www.earthdatascience.org/courses/intro-to-earth-data-science/git-github/github-collaboration/how-to-submit-pull-requests-on-github/) (or any similar tutorial) before you proceed._
 
### The table of anomalies

1. Go to the `/_includes` directory. Download the [`ListofAnomalies.html`](https://github.com/hepcomm/hepmist/blob/main/_includes/ListofAnomalies.html) file.
2. Open the `ListofAnomalies.html` with a word processor (Google Docs is recommended) and make any desired changes.
3. Save the edited document as `ListofAnomalies.html` and upload it to the `/_includes` directory.

### Possible solutions

1. Go to the `/solutions` directory. Edit the [anomaly].md file (e.g. [`muon-g-2.md`](https://github.com/hepcomm/hepmist/blob/main/solutions/muon-g-2.md), [`LFUV-B.md`](https://github.com/hepcomm/hepmist/blob/main/solutions/LFUV-B.md) etc.). 

### The _False Alarms_ page

1. Go to the `/_includes` directory. Download the [`Lessons-past.html`](https://github.com/hepcomm/hepmist/blob/main/_includes/Lessons-past.html) file.
2. Open the `Lessons-past.html` with a word processor (Google Docs is recommended) and make any desired changes.
3. Save the edited document as `Lessons-past.html` and upload it to the `/_includes` directory.

### Add a news post

1. Go to the `/_posts` directory. Create your news post with a filename in the following format: `YYYY-MM-DD-[news-title].md`.
2. The post should be written in a format similar to [`2021-03-19-muonnews.md`](https://github.com/hepcomm/hepmist/edit/main/_posts/2021-03-19-muonnews.md) file.

### Others

This websites adopted the [_Alembic_](https://alembic.darn.es/) theme. It allows the users to configure colors, typography, navigation menu etc. and provides many useful tools. If you are interested in making some more elaborated changes, please refer to the [documentations](https://github.com/daviddarnes/alembic/blob/main/README.md) of the _Alembic_ theme. 
