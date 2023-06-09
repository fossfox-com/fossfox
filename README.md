# [Fossfox](https://fossfox.com/): Open Database of Available Engineering Jobs

[![Github Actions](https://img.shields.io/github/actions/workflow/status/fossfox-com/fossfox/tests.yml?style=flat-square)](https://github.com/fossfox-com/fossfox/actions)
[![Dependency Status](https://deps.rs/repo/github/fossfox-com/fossfox/status.svg?style=flat-square)](https://deps.rs/repo/github/fossfox-com/fossfox)

## 🦊 What Is Fossfox

[Fossfox](https://fossfox.com/) is a **job board for software engineers**.

It lists available engineering positions of companies whose products are open-source. The goal is to get software engineers better jobs.

[![Fossfox](static/img/fossfox.webp)](https://fossfox.com/)

## 🧐 Why Post On Fossfox

1. Posting jobs is free
1. Our audience is tech-savvy software engineers
1. Unlimited posts + more traffic to your website

## 👩‍💻 How To Post

There are 2 ways to post new jobs on Fossfox:

### Option 1: CLI Wizard (requires [Rust](https://www.rust-lang.org/tools/install))

1. Clone this repo
1. Run `cargo run` and follow the wizard
1. [Create a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) so we can merge your changes

### Option 2: Sample template

1. Clone this repo
1. Copy contents of [data/SAMPLE_COMPANY_TEMPLATE.json](data/SAMPLE_COMPANY_TEMPLATE.json) into a new file (eg: `data/SAMPLE_COMPANY_TEMPLATE.json` → `data/companies/m/my-company.json`)
1. Fill it out with your company details & available engineering roles
1. [Create a pull request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) so we can merge your changes

> ℹ️ The job posts will automatically appear on [Fossfox](https://fossfox.com/) after your PR will be accepted. Please note that other websites can use this data to display your job posts.

## 🙋‍♂️ FAQs

<details>
  <summary>How much does it cost?</summary>
  Free.
</details>

<details>
  <summary>How long will Fossfox stay free?</summary>
  Forever.
</details>

<details>
  <summary>How many jobs can I post?</summary>
  We do not have a limit on the number of positions you can list. However, not all jobs are guaranteed to automatically appear on the homepage.
</details>

<details>
  <summary>How long do the posts stay up?</summary>
  30 days. After that you can update the timestamp to extend.
</details>

<details>
  <summary>Can I post non-engineering related job posts?</summary>
  No, sorry. This is a tech-only job board.
</details>

## 🍻 Attribution

You can use Fossfox data as long as you give attribution. Attribution needs to have 2 components:

1. Source: "Fossfox"
2. Link: https://fossfox.com

Optional:

If you find this work helpful, feel free to encourage others to add data here. For example:

> If you're growing your engineering team, [submit your open roles](https://github.com/fossfox-com/fossfox) to Fossfox for free.

<ins>Sample attribution</ins>

Data Source: [Fossfox](https://fossfox.com)

If you're growing your engineering team, [submit your open roles](https://github.com/fossfox-com/fossfox) to Fossfox for free.
