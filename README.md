# alex-folio

My personal site: who I am, what I work on, and a timeline of how I got here.

**Live site:** [alexbui7.github.io/alex-folio](https://alexbui7.github.io/alex-folio/)

I'm Alex (Bui Minh Anh), a Cloud & Infrastructure Automation Engineer in Hanoi. I build automation-first data and ML platforms on AWS and Databricks.

## Built with Claude 🙂

I built this whole repo with [Claude](https://claude.ai/code), and I'm proud of that. The pages, the work timeline, the CV, and the styling all came out of working with Claude.

## What's here

| Where                        | What it is                                                          |
| ---------------------------- | ------------------------------------------------------------------- |
| `_pages/about.md`            | Home page intro                                                     |
| `_data/timeline.yml`         | The work timeline (jobs on the right, learning & certs on the left) |
| `_includes/timeline*.liquid` | How the timeline is rendered                                        |
| `_data/cv.yml`               | CV page content                                                     |
| `assets/img/work/`           | Photos shown on the work timeline                                   |

## Running it locally

```bash
docker compose pull && docker compose up
# then open http://localhost:8080/alex-folio/
```

## Credits

Built on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme (MIT license). The theme's own docs are still in this repo: [INSTALL.md](INSTALL.md), [CUSTOMIZE.md](CUSTOMIZE.md), [TROUBLESHOOTING.md](TROUBLESHOOTING.md).
