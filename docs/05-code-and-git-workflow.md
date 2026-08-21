# Code and git workflow

## Repository structure

A repository has to contain a README file which can guide through its usage and contains a reasonable number of sections that reflects the complexity of the work.
In other words...keep it as simple as possible and self-explanatory.

I would structure it in this way:

```
main
 │
 ├── requirements/...
 ├── implementation/...
 ├── experiments/...
 ├── numerical_results/...
 └── plots/...
```

If the numerical result files' size is above the limits of GitHub, you have to save them locally (a backup would be nice to have), to store them later on [Zenodo](https://zenodo.org/) making them public.

I would also suggest to read [this website](https://sebszyller.com/blog/2026/researchrepoin2026) since it is related to how to manage a GitHub research repository.

## Git workflow

Whenever you have finished a task or a part of it, TEST IT. Immediately after, commit the files related to that part. That should concern a specific completed task.

In this way, you are protecting yourself, saving your time and your work in case of a disaster (e.g. your pc has some malfunctions, the hardisk stops working, conflicts when we are working on the same part of code and then one of us has to merge overwriting the work of the other one...).
