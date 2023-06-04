# Nextra Mermaid

Starting today, Nextra supports rendering the Mermaid diagrams.

- The feature request issue: https://github.com/shuding/nextra/issues/1373
- The pull request: https://github.com/shuding/nextra/pull/1930

Prior to this, I have used this amazing plugin to add the support to Nextra:

https://github.com/mariansimecek/remark-mermaid-nextra

I am elated to learn this is now an out of the box feature as I strongly believe
Mermaid support should be everywhere where MarkDown is being processed.

I am running into issues getting this support to work in my work project, though
and I need to find out whether the problem lies in how the work project is set
up (we're using PNPM workspaces and ESM everywhere) or if it is a legit issue
with the Nextra Mermaid support so that I could reproduce it and report it.

In this repository I will create a new Nextra project and see whether the
Mermaid support works as expected.
If yes, I will use this repository to compare with the work repository and see
where are the differences in set up and behavior.
I will bridge the gaps one by one and see where it falls apart if it ever does.

