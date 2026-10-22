<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Liam — HeyItWorked. Open source. Connected care. FHIR, DICOM and clinical tools." src="assets/header-light.svg" width="100%">
</picture>

I work on healthcare software and the small tools around it. Most of my open-source work starts with a bug I can reproduce, then a fix and a test someone else can run.

<p align="center">
  <a href="https://liamnguyenn.com">Website</a> &nbsp; / &nbsp;
  <a href="https://liamnguyenn.com/portfolio/">Portfolio</a> &nbsp; / &nbsp;
  <a href="https://liamnguyenn.com/contact/">Contact</a>
</p>

## Work that landed upstream

- **[Nocturne](https://github.com/nightscout/nocturne/pull/2267)** — Made the C# time-query echo use the same filter parsing as the time endpoints, with regression tests for repeated parameters and other edge cases. [Merged PRs](https://liamnguyenn.com/portfolio/nocturne/) also cover API capability reporting and shared test setup.
- **[VetLog](https://github.com/josdem/py-vetlog-calendar/pull/150)** — Fixed Python reminder filtering so pets with existing medical logs stay out of the missing-log list. The test includes a household where only one pet needs a reminder.

I also have proposals open for [Firely .NET SDK](https://github.com/FirelyTeam/firely-net-sdk/pull/3643), [fo-dicom](https://github.com/fo-dicom/fo-dicom/pull/2197), and [CARLOS EMR](https://github.com/carlos-emr/carlos/pull/5123). Those are **under review**, not shipped fixes.

## Things I build

- **[ContextPack](https://github.com/HeyItWorked/ContextPack)** packs project files into a fixed input limit and reports what it left out. Python.
- **[RiverRoot](https://github.com/HeyItWorked/RiverRoot)** is a small self-hosted CI server that runs pipeline steps on the host or in containers. Go.
- **[MedCVE](https://github.com/HeyItWorked/MedCVE)** explores healthcare-tagged CVE records in a static dashboard. Python and pandas.

## GitHub activity

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-summary-card-output/github_dark/0-profile-details.svg">
  <img alt="GitHub contribution history and profile summary for HeyItWorked" src="profile-summary-card-output/github/0-profile-details.svg" width="100%">
</picture>

<details>
<summary>More activity cards</summary>
<br>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-summary-card-output/github_dark/3-stats.svg">
  <img alt="GitHub repository and contribution statistics" src="profile-summary-card-output/github/3-stats.svg" width="420">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-summary-card-output/github_dark/4-productive-time.svg">
  <img alt="Distribution of commit times in UTC, not hours worked" src="profile-summary-card-output/github/4-productive-time.svg" width="420">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-summary-card-output/github_dark/1-repos-per-language.svg">
  <img alt="Languages by repository" src="profile-summary-card-output/github/1-repos-per-language.svg" width="420">
</picture>
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="profile-summary-card-output/github_dark/2-most-commit-language.svg">
  <img alt="Languages by commits" src="profile-summary-card-output/github/2-most-commit-language.svg" width="420">
</picture>
</details>

<sub>Cards show the last successful public-activity snapshot from <a href="https://github.com/vn7n24fzkq/github-profile-summary-cards">Summary Cards</a>. Commit times use UTC, not hours worked; language mix is not proficiency.</sub>
